```plaintext
.
├── data/                      # Raw datasets
├── languages/                 # Core code and data for languages probabilities
    ├── plots_langs            # folder with plots shows prompt-level probabilities for ENG and RUS
    ├── opt_ruen_logitlens.ipynb # notebook with code, that produce final dfs and visualization for languages
├── safety/                    # Core code for safety evaluation
│   ├── all200.png # Visualization output (safety patterns) by-prompt
│   ├── centrods&visualization.ipynb # Main notebook for centroid analysis and visualization
│   ├── safety_centroids.pt # PyTorch file containing safety centroids
├── SAFETY_scores+samples - refusal_scores.csv  # Main results file: refusal scores + samples
├── visulalization_SAFETY+PROBS.ipynb        # Notebook for visualizing scores and probabilities
└── README.md                  # This file
```
