# Binary Classification on MNIST and CIFAR-10

This project implements binary classification tasks on the MNIST and CIFAR-10 datasets using various machine learning approaches.

## Development Environment
- Platform: Google Colab
- **GPU:** Enabled 
- Python Version: 3.x

## Project Structure
The project follows this pipeline:
1. **Import Libraries & Setup**  
2. **Dataset Loading** (MNIST/CIFAR-10)  
3. **Data Exploration & Preprocessing**  
4. **Dataset Splitting** (Train/Validation)  
5. **Initial Modeling**  
6. **Hyperparameter Tuning**  
7. **Final Model Training**  
8. **Model Evaluation**  
9. **Results & Visualization**  

## Models Implemented
### MNIST Binary Classification (8 vs 3)
- Logistic Regression  
- Support Vector Machine (SVM)

### CIFAR-10 Binary Classification (Horse vs Deer)
- PCA + Feedforward Neural Network  
- 3-Layer CNN  

## Running Instructions
1. Open **Google Colab**.  
2. Upload the respective `.ipynb` notebooks.  
3. Enable GPU runtime:  
   - Navigate to `Runtime` → `Change runtime type` → Select `GPU`.  
4. Check GPU availability by running:  
   ```python
   import torch
   print(torch.cuda.is_available())
5. Run all cells sequentially.

## Dependencies
- `python`  
- `torch`  
- `torchvision`  
- `scikit-learn`  
- `numpy`  
- `matplotlib`  
- `seaborn`  
- `pandas`  
- `optuna`  
- `joblib`  

## Note
Some models use **Optuna** for hyperparameter optimization, which may take considerable time to run. Adjust the `n_trials` parameter in the code if needed. 

---

