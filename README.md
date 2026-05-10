# Stock-Market-Project
# Stock Prediction Models — Results & Analysis

## Project Description
This project explores multiple forecasting models — **Linear Regression**, **SVR (Linear)**, **Random Forest**, **SARIMA**, and **SARIMAX** — applied to stock datasets (Exxon, Toyota, NVIDIA).  
The goal was to evaluate how different models and dataset structures complement each other, test hypotheses about linear vs. nonlinear relationships, and assess the role of exogenous features in prediction variance.  

Key findings:
- **Linear Regression and SVR (Linear)** performed best for Exxon and Toyota, confirming more linear relationships than expected.  
- **SARIMA/SARIMAX** highlighted that exogenous features can add context, though results varied.  
- **Random Forest** and **SARIMA** baselines underperformed.  
- **NVIDIA** proved challenging due to volatility, scale, and limited history, reinforcing dataset‑specific limitations.  

---

## Setup Instructions

### Option 1: Run on Google Colab
1. Open the notebook in Colab.  
2. Simply **Run All** cells — installation and dependencies are handled automatically in the notebook.  

---

### Option 2: Run Locally (VS Code / Terminal)
1. Clone or download the project files into your `Downloads` folder.  
2. Open a terminal and navigate to the project directory:
   ```bash
   cd ~/Downloads/stock-prediction-project
3. Create a virtual environment:
    ```bash
    python -m venv venv

4. Activate the environment:
    ```bash
    source venv/bin/activate        for macOS/Linux
                or
    venv\Scripts\activate           for Windows

5. Install dependencies:
    ```bash
    pip install -r requirements.txt
Nb. You can also just Run All in the notebook, since one of the cells handles installation automatically.



