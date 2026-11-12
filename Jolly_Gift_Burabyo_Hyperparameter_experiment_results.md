# Hyperparameter Experiment Results

**Member Name:** Jolly Gift Burabyo

**Environment:** `ALE/Pong-v5`
**Fixed settings for all 10 runs:** total steps = 500,000, buffer size = 50,000, learning starts = 10,000, train every 4 steps, target update every 1,000 steps.

_Models, logs and plots: `models/Jolly_Gift_Burabyo/exp_XX/`. "Mean reward" is the average over the last 20 episodes in `training_log.csv`._

| Exp | Learning rate | Gamma | Batch size | Epsilon start | Epsilon end | Epsilon decay (steps) | Mean reward | Observed behaviour |
|-----|---------------|-------|------------|---------------|-------------|-----------------------|-------------|--------------------|
| 1 | 0.0001 | 0.99 | 32 | 1.0 | 0.05 | 100000 | | |
| 2 | 0.0005 | 0.99 | 32 | 1.0 | 0.05 | 100000 | | |
| 3 | 0.001 | 0.99 | 32 | 1.0 | 0.05 | 100000 | | |
| 4 | 0.00005 | 0.99 | 32 | 1.0 | 0.05 | 100000 | | |
| 5 | 0.000025 | 0.99 | 32 | 1.0 | 0.05 | 100000 | | |
| 6 | 0.0001 | 0.99 | 64 | 1.0 | 0.05 | 100000 | | |
| 7 | 0.0001 | 0.99 | 128 | 1.0 | 0.05 | 100000 | | |
| 8 | 0.0001 | 0.99 | 16 | 1.0 | 0.05 | 100000 | | |
| 9 | 0.0005 | 0.99 | 64 | 1.0 | 0.05 | 100000 | | |
| 10 | 0.00025 | 0.99 | 16 | 1.0 | 0.05 | 100000 | | |

## Best and worst configuration

- **Best:** Exp __ because ...
- **Worst:** Exp __ because ...

## What helped and what hurt

- **Learning rate:**
- **Gamma:**
- **Batch size:**
- **Epsilon (start / end / decay):**

## Final configuration and justification
