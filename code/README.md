# ConsciOS Demo: Hierarchical Controller Instrumentation

Minimal instrumentation checks for the ConsciOS architecture:
- Flat agent vs hierarchical controller sketch
- Resonance Engine selection (β/α sweeps)
- Cumulative coherence gating on/off
- ICS-like intrinsic shaping on/off

These scripts are intended to verify logging, plotting, and selector sensitivity in a toy environment. They are not empirical validation of the full ConsciOS architecture.

## Setup
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt

## Run
- Flat baseline
```bash
python -m agents.flat_agent --episodes 200 --seed 1
```
- Hierarchical
```bash
python -m agents.hier_agent --episodes 200 --seed 1 --beta 1.0 --alpha 0.5 --freq_on true --egs_on true
```

## Plots
```bash
python -m plots.plot_traces
```

## Ablations (β/α sweeps)
Generate β×α logs and per-run plots, then summarize into heatmaps
```bash
PYTHONPATH=code python -m ablate.run_ablation
PYTHONPATH=code python -m ablate.summarize_ablation
```

### Outputs
- `logs/hier_b{beta}_a{alpha}.csv`
- `plots/hier_b{beta}_a{alpha}_reward.png`
- `plots/hier_b{beta}_a{alpha}_pos.png`
- `plots/ablation_summary.csv` and heatmaps under `plots/`

## Outputs
- logs/: selection traces, coherence scores, FREQ timeline
- plots/: hold_time vs policy_entropy, adaptation_latency, OA vs FREQ

## Notes
Default coherence: log‑evidence proxy; KLD/cosine alternatives available in coherence/.
