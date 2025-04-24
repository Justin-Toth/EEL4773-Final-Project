# Greek Letters Classification Project
This project involves training and testing a neural network model to classify handwritten Greek letters. The implementation uses PyTorch and is structured into two main notebooks: one for training the model and another for testing it.

---

## Prerequisites
1. Make sure you have the correct enviroment from the provided enivronment files
2. The provided environments are also included in `environments` folder:


---

## Project Structure

- `model/train.ipynb`: Notebook for training the model.
- `model/test.ipynb`: Notebook for testing the model.
- `data`: Folder containing the input CSV files (`x_train_project.csv` and `t_train_project.csv`).
- `model/best_model.pt`: File where the trained model is saved.

---

## How to Run the Project

### 1. Training the Model
1. Open `model/train.ipynb` in Jupyter Notebook or VS Code.
2. Ensure the input data files (`x_train_project.csv` and `t_train_project.csv`) are located in the `data` folder.
3. Update the corresponding file path variables in the notebook if necessary. These are all included in a single cell.
4. Run all cells in the notebook to train the model. The best model will be saved as `model/best_model.pt`.
5. Note that some hard coded file paths are present in the `load_and_split_data` function if you need to modify any of these paths to located where data gets save to.

### 2. Testing the Model
1. Open `model/test.ipynb` in Jupyter Notebook or VS Code.
2. Ensure the trained model (`best_model.pt`) is located in the `model` folder.
3. Update the corresponding file path variables in the notebook if necessary. These are all included in a single cell. 
4. Run all cells in the notebook to evaluate the model and visualize incorrect predictions.

---

