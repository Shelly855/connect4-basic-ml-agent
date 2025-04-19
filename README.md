# Connect 4 – Basic ML Agent

This project folder contains the notebook and model used to train a basic machine learning agent for Connect 4. Running it is **not required** for using the final game.

---

## Files

- `connect4_move_predictor.ipynb` – Code used to train the ML model  
- `connect-4.data` – UCI dataset of historical Connect 4 games
- `ml_agent.pkl` – Exported trained model used as Basic ML Agent in the game

---

## Notes

- The notebook was used to preprocess the dataset and train a classifier.
- The resulting model (`ml_agent.pkl`) is loaded directly in the game.
- This folder is **not needed** to play the game.

---

## Dataset
Connect 4 dataset from UCI Machine Learning Repository:
https://archive.ics.uci.edu/dataset/26/connect+4
 
---

## Optional: Rerun the Training

If you want to rerun the notebook locally:

1. Ensure Python 3 is installed.
2. Install required packages:

   ```bash
   pip install numpy pandas scikit-learn
   ```
3. Open and run the notebook: `connect4_move_predictor.ipynb`
> This notebook was created and tested in Jupyter Notebook. You can also open it in VS Code with the Jupyter extension.

---

## GitHub Version (Optional)

[View this folder on GitHub](https://github.com/Shelly855/connect4-basic-ml-agent)  
> **Note:** This link is optional and not required for marking. The GitHub version may be updated after submission.
