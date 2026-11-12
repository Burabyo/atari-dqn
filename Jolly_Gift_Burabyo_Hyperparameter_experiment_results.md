# Hyperparameter Experiment Results

**Member Name:** Jolly Gift Burabyo

**Environment:** `ALE/Pong-v5`
**Fixed settings for all 10 runs:** total steps = 500,000, buffer size = 50,000, learning starts = 10,000, train every 4 steps, target update every 1,000 steps.

_Models, logs and plots: `models/Jolly_Gift_Burabyo/exp_XX/`. "Mean reward" is the average over the last 20 episodes in `training_log.csv`. A Pong score ranges from -21 (lost every point) to +21 (won every point)._

| Exp | Learning rate | Gamma | Batch size | Epsilon start | Epsilon end | Epsilon decay (steps) | Mean reward (last 20 ep.) | Best episode | Observed behaviour |
|-----|---------------|-------|------------|---------------|-------------|-----------------------|-------------|--------------|--------------------|
| 1 | 0.0001 | 0.99 | 32 | 1.0 | 0.05 | 100000 | -17.4 | -11 | Learned: average reward improved from -20.4 to -17.4; games got longer (914 -> 2322 steps) as the agent returned more balls. |
| 2 | 0.0005 | 0.99 | 32 | 1.0 | 0.05 | 100000 | -20.9 | -18 | Did not learn: reward stayed near -21 (start -20.3, end -20.9); short games (~798 steps) because the agent lost every point quickly. |
| 3 | 0.001 | 0.99 | 32 | 1.0 | 0.05 | 100000 | -20.9 | -18 | Did not learn: reward stayed near -21 (start -20.4, end -20.9); short games (~802 steps) because the agent lost every point quickly. |
| 4 | 0.00005 | 0.99 | 32 | 1.0 | 0.05 | 100000 | -15.9 | -12 | Learned: average reward improved from -20.2 to -15.9; games got longer (919 -> 1810 steps) as the agent returned more balls. |
| 5 | 0.000025 | 0.99 | 32 | 1.0 | 0.05 | 100000 | -16.9 | -13 | Learned: average reward improved from -20.1 to -16.9; games got longer (943 -> 1578 steps) as the agent returned more balls. |
| 6 | 0.0001 | 0.99 | 64 | 1.0 | 0.05 | 100000 | -10.2 | 2 | Learned: average reward improved from -20.4 to -10.2; games got longer (922 -> 2395 steps) as the agent returned more balls. |
| 7 | 0.0001 | 0.99 | 128 | 1.0 | 0.05 | 100000 | -9.9 | -3 | Learned: average reward improved from -20.0 to -9.9; games got longer (953 -> 2967 steps) as the agent returned more balls. |
| 8 | 0.0001 | 0.99 | 16 | 1.0 | 0.05 | 100000 | -20.4 | -16 | Did not learn: reward stayed near -21 (start -20.3, end -20.4); short games (~987 steps) because the agent lost every point quickly. |
| 9 | 0.0005 | 0.99 | 64 | 1.0 | 0.05 | 100000 | -20.7 | -17 | Did not learn: reward stayed near -21 (start -20.1, end -20.7); short games (~818 steps) because the agent lost every point quickly. |
| 10 | 0.00025 | 0.99 | 16 | 1.0 | 0.05 | 100000 | -20.9 | -18 | Did not learn: reward stayed near -21 (start -20.4, end -20.9); short games (~788 steps) because the agent lost every point quickly. |

## Best and worst configuration

- **Best:** Exp __ because ...
- **Worst:** Exp __ because ...

## What helped and what hurt

- **Learning rate:**
- **Gamma:**
- **Batch size:**
- **Epsilon (start / end / decay):**

## Final configuration and justification
