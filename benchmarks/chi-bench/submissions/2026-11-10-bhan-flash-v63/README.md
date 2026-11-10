# Bin_Han · openai-agents · deepseek-flash

Submitted: 2026-11-10 · chi-bench chi-bench-v1.0.0 · pass@1: **62.7%**

| Domain | pass@1 | n_trials |
|---|---|---|
| pa_provider | 44.0% | 25 |
| pa_um | 68.0% | 25 |
| cm | 76.0% | 25 |

Inspect a trajectory:

    zstdcat trials/pa_provider/<trial_id>/agent/trajectory.jsonl.zst | jq .

See `submission.json` for the full manifest, `provenance.json` for reproducibility info.
