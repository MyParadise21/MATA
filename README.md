# MATA
Pay More Attention to Audio: Mitigating imbalance of cross-modal attention in large audio language models

The code is comming soon (after the paper is accepted)

## MMAU Benchmark Results

**Table:** Accuracies (%) on MMAU (v05.15.25). † represents the results we reproduced.

| Models |  | MMAU Test-mini (1k audios) |  |  |  | MMAU Test-full (9k audios) |  |  |  |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
|  |  | **Sound** | **Music** | **Speech** | **Avg.** | **Sound** | **Music** | **Speech** | **Avg.** |
| ***Baselines:*** | | | | | | | | | |
| Gemini 2.0 Flash | | 71.2 | 65.3 | **75.1** | 70.5 | 68.9 | 59.3 | **72.9** | 67.0 |
| GPT-4o Audio | | 64.6 | 56.3 | 66.7 | 62.5 | 63.2 | 49.9 | 69.3 | 60.8 |
| Audio Flamingo 2 | | 71.5 | **71.0** | 44.7 | 62.4 | 68.1 | **70.2** | 44.9 | 61.1 |
| Audio Reasoner | | 67.9 | 69.2 | 66.1 | 67.7 | 67.3 | 61.5 | 62.5 | 63.8 |
| Qwen2-Audio-7B-Instruct | | 67.3 | 56.3 | 55.3 | 59.6 | 61.2 | 55.7 | 55.4 | 57.4 |
| Qwen2.5-Omni-7B | | **78.1** | 65.9 | 70.6 | **71.5** | **76.8** | 67.3 | 68.9 | **71.0** |
| ***Ours:*** | | | | | | | | | |
| Qwen2-Audio-7B-Instruct† | | 67.1 | 55.8 | 55.4 | 59.4 | 64.7 | 53.9 | 53.1 | 57.3 |
| + MATA | | 71.2 | 61.4 | 61.8 | 64.8 | 64.7 | 53.1 | 53.9 | 57.3 |
| Qwen2.5-Omni-7B† | | 77.8 | 64.7 | 70.9 | 71.1 | 76.8 | 67.3 | 68.9 | 71.0 |
| + MATA | | **79.9** | **68.3** | **72.7** | **73.6** | **76.6** | 67.5 | **77.3** | **73.7** |
