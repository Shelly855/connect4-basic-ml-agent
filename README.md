# Connect 4 – Basic ML Agent

This repo contains the notebook and model used to train a basic machine learning agent for Connect 4. Running it is **not required** for using the final game.

---

## Files

- `connect4_move_predictor.ipynb` – Code used to train the ML model  
- `connect-4.data` – UCI dataset of historical Connect 4 games
- `ml_agent.pkl` – Exported trained model used in the game

---

## Notes

- The notebook was used to preprocess the dataset and train a classifier.
- The resulting model (`ml_agent.pkl`) is loaded directly in the game.
- This repo is **not needed** to play or test the game.

---

## Dataset
- Connect 4 Dataset
  - https://archive.ics.uci.edu/dataset/26/connect+4
 
---

## Optional: Rerun the Training

If you want to retrain or explore the process:

1. Make sure you have Python 3.10+ installed.
2. Install required packages:

   ```bash
   pip install numpy pandas scikit-learn
   ```
3. Open and run the notebook: `connect4_move_predictor.ipynb`
> The notebook was created and tested in Jupyter Notebook.
