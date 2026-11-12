# Hyperparameter Experiment Results

**Member Name:** Thierry Alain Tresor Ibyishaka

**Environment:** `ALE/Pong-v5`
**Fixed settings for all 10 runs:** total steps = 500,000, buffer size = 50,000, learning starts = 10,000, train every 4 steps, target update every 1,000 steps.

_Models, logs and plots: `models/Thierry_Alain_Tresor_Ibyishaka/exp_XX/`. "Mean reward" is the average over the last 20 episodes in `training_log.csv`. A Pong score ranges from -21 (lost every point) to +21 (won every point)._

| Exp | Learning rate | Gamma | Batch size | Epsilon start | Epsilon end | Epsilon decay (steps) | Mean reward (last 20 ep.) | Best episode | Observed behaviour |
|-----|---------------|-------|------------|---------------|-------------|-----------------------|-------------|--------------|--------------------|
| 1 | 0.0001 | 0.99 | 32 | 1.0 | 0.1 | 100000 | -17.1 | -13 | Learned: average reward improved from -20.4 to -17.1; games got longer (902 -> 2285 steps) as the agent returned more balls. |
| 2 | 0.0001 | 0.99 | 32 | 1.0 | 0.01 | 100000 | -16.5 | -10 | Learned: average reward improved from -20.4 to -16.5; games got longer (892 -> 2928 steps) as the agent returned more balls. |
| 3 | 0.0001 | 0.99 | 32 | 1.0 | 0.05 | 50000 | -13.8 | 4 | Learned: average reward improved from -20.5 to -13.8; games got longer (924 -> 2595 steps) as the agent returned more balls. |
| 4 | 0.0001 | 0.99 | 32 | 1.0 | 0.05 | 200000 | -13.4 | -8 | Learned: average reward improved from -20.0 to -13.4; games got longer (964 -> 2254 steps) as the agent returned more balls. |
| 5 | 0.0001 | 0.99 | 32 | 1.0 | 0.05 | 25000 | -19.0 | -17 | Learned: average reward improved from -20.4 to -19.0; games got longer (896 -> 1642 steps) as the agent returned more balls. |
| 6 | 0.0001 | 0.99 | 32 | 0.5 | 0.05 | 100000 | -11.4 | -1 | Learned: average reward improved from -20.4 to -11.4; games got longer (913 -> 2323 steps) as the agent returned more balls. |
| 7 | 0.0001 | 0.99 | 32 | 1.0 | 0.2 | 100000 | -17.6 | -12 | Learned: average reward improved from -20.4 to -17.6; games got longer (903 -> 1837 steps) as the agent returned more balls. |
| 8 | 0.0001 | 0.99 | 32 | 1.0 | 0.01 | 250000 | -13.1 | -7 | Learned: average reward improved from -20.1 to -13.1; games got longer (969 -> 2306 steps) as the agent returned more balls. |
| 9 | 0.0001 | 0.99 | 32 | 0.8 | 0.02 | 150000 | -12.4 | -5 | Learned: average reward improved from -20.3 to -12.4; games got longer (905 -> 2310 steps) as the agent returned more balls. |
| 10 | 0.00025 | 0.99 | 64 | 1.0 | 0.05 | 100000 | -20.9 | -17 | Did not learn: reward stayed near -21 (start -20.3, end -20.9); short games (~816 steps) because the agent lost every point quickly. |

## Best and worst configuration

- **Best:** Exp __ because ...
- **Worst:** Exp __ because ...

## What helped and what hurt

- **Learning rate:**
- **Gamma:**
- **Batch size:**
- **Epsilon (start / end / decay):**

## Final configuration and justification
