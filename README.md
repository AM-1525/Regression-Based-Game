# Signal Interceptor: Deep Space Data Odyssey

A single-file browser game (Part B) where you learn data science by experimenting, not by reading or answering quiz questions.

## How to launch
1. Download `Signal_Interceptor_Odyssey.html`.
2. Double-click it to open in Chrome, Edge or Firefox. No install or internet connection is needed.
3. Enter your agent name and press launch.

## How to play
- Clear all **20 levels** across **5 stages**. Move the sliders, watch the live chart and numbers, then press **LOCK IN**.
- **3 shields**: a wrong lock-in or failed gate costs one. **2 hints** for the whole game.
- Stage 5 has mazes (arrow keys / WASD or the on-screen pad) with data-puzzle gates.
- Score: 100 per level plus a streak bonus. Your best score is saved on your device.

## Learning objectives
| Stage | Levels | Concept | What the player discovers |
|---|---|---|---|
| 1 | 1-4 | Least squares | The best line minimises squared residuals; outliers pull it |
| 2 | 5-8 | Overfitting / underfitting | Low train error is not a good model; test error and regularisation (lambda) reveal it |
| 3 | 9-12 | Precision and recall | Moving a threshold trades one against the other |
| 4 | 13-16 | K-means clustering | Inertia always falls with k; choose the elbow |
| 5 | 17-20 | Confounding, outliers, sampling bias | Correlation is not causation; the median resists outliers; only random samples are unbiased |

## Implementation notes
All data is generated randomly each attempt. Models are fitted live in the browser (normal equations, k-means, confusion matrix, correlation, sampling experiments). Nothing is hard-coded.

## Playtest evidence
Open **Mission Briefing & Playtest Log** > **Playtest**. For each of 3 to 5 peers, record name, rating, how far they got, what they understood in their own words, and feedback. Use **Download report** to export `playtest_report.txt`.


