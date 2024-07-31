# Experiments Log



## Results

| Date | Experiment | Description | Validation | Public Leaderboard |
|------|------------|-------------|------------|--------------------|
| 2024-07-28 | 1 | Baseline (Gemma2-9b + Seq-Cls) | 0.9185 | 0.9300|
| 2024-07-29 | 2| Gemma2-9b + Seq-Cls + Flip + 2 epochs | 1.1075 | 1.117 |



## Ideas
- Prompt engineering (e.g. multi-turn)
- Use generation with Gemma2-9b (constrained CoT)
- Would it be possible to use 27B model instead of 9B? (Inference time?)
- Use calibration methods (temperature scaling, isotonic regression)