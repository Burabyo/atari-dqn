# Hyperparameter Experiment Results

**Member Name:** Dan Paul Dushime

**Environment:** `ALE/Pong-v5`
**Fixed settings for all 10 runs:** total steps = 500,000, buffer size = 50,000, learning starts = 10,000, train every 4 steps, target update every 1,000 steps.

_Models, logs and plots: `models/Dan_Paul_Dushime/exp_XX/`. "Mean reward" is the average over the last 20 episodes in `training_log.csv`._

| Exp | Learning rate | Gamma | Batch size | Epsilon start | Epsilon end | Epsilon decay (steps) | Mean reward | Observed behaviour |
|-----|---------------|-------|------------|---------------|-------------|-----------------------|-------------|--------------------|
| 1 | 0.00025 | 0.99 | 32 | 1.0 | 0.05 | 100000 | | |
| 2 | 0.00025 | 0.95 | 32 | 1.0 | 0.05 | 100000 | | |
| 3 | 0.00025 | 0.90 | 32 | 1.0 | 0.05 | 100000 | | |
| 4 | 0.00025 | 0.999 | 32 | 1.0 | 0.05 | 100000 | | |
| 5 | 0.00025 | 0.97 | 32 | 1.0 | 0.05 | 100000 | | |
| 6 | 0.00025 | 0.995 | 32 | 1.0 | 0.05 | 100000 | | |
| 7 | 0.00025 | 0.80 | 32 | 1.0 | 0.05 | 100000 | | |
| 8 | 0.00025 | 0.95 | 64 | 1.0 | 0.05 | 100000 | | |
| 9 | 0.0001 | 0.999 | 32 | 1.0 | 0.05 | 100000 | | |
| 10 | 0.0001 | 0.97 | 64 | 1.0 | 0.05 | 100000 | | |

## Best and worst configuration

- **Best:** Exp __ because ...
- **Worst:** Exp __ because ...

## What helped and what hurt

- **Learning rate:**
- **Gamma:**
- **Batch size:**
- **Epsilon (start / end / decay):**

## Final configuration and justification
