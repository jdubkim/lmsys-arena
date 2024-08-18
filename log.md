# Experiments Log



## Results

| Date | Experiment | Description | Validation | Public Leaderboard |
|------|------------|-------------|------------|--------------------|
| 2024-07-28 | 1 | Baseline (Gemma2-9b + Seq-Cls) | 0.9185 | 0.9300|
| 2024-07-29 | 2 | Gemma2-9b + Seq-Cls + Flip + 2 epochs | 1.1075 | 1.117 |
| 2024-07-31 | 3 | Gemma-2-9b + Seq + it-tokens | 1.1074 | N/A |


## Ideas
- Prompt engineering (e.g. multi-turn)
- Weight decay, gradient clipping
- Use generation with Gemma2-9b (constrained CoT)
- Would it be possible to use 27B model instead of 9B? (Inference time?)
- Use calibration methods (temperature scaling, isotonic regression)


# Data Token Distribution
- Based on [Link](https://www.kaggle.com/competitions/lmsys-chatbot-arena/discussion/522778)
- Prompts: ~200 tokens
- Responses: ~600 tokens