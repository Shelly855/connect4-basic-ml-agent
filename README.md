# Connect 4 – Basic ML Agent

This repository contains the notebook and model used to train a basic machine learning agent for Connect 4. Running it is **not required** for playing the [final game](https://github.com/Shelly855/connect4-ai).

---

## Table of Contents

- [Connect 4 – Basic ML Agent](#connect-4--basic-ml-agent)
- [Files](#files)
- [Notes](#notes)
- [References](#references)
- [Optional: Rerun the Training](#optional-rerun-the-training)

---

## Files

- `connect4_move_predictor.ipynb` – Code used to train the ML model  
- `connect-4.data` – UCI dataset of historical Connect 4 games
- `ml_agent.pkl` – Exported trained model used as Basic ML Agent in the game

---

## Notes

- The notebook was used to preprocess the dataset and train a classifier.
- The resulting model (`ml_agent.pkl`) is loaded directly in the game.

---

## References
- Connect 4 dataset from UCI Machine Learning Repository:
  - https://archive.ics.uci.edu/dataset/26/connect+4
- Scikit-learn: Machine Learning in Python
  - https://scikit-learn.org/stable/index.html
 
---

## Optional: Rerun the Training

To rerun the notebook locally:

1. Ensure Python 3 is installed.
2. Install required packages:

   ```bash
   pip install numpy pandas scikit-learn
   ```
3. Open and run the notebook: `connect4_move_predictor.ipynb`
> This notebook was created and tested in Jupyter Notebook. You can also open it in VS Code with the Jupyter extension.
