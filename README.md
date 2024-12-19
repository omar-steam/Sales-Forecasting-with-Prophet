# Sales Forecasting with Prophet

A time series forecasting project using Facebook's Prophet library to predict future sales based on historical data.

## Features
- Time series forecasting using Prophet
- Yearly, weekly seasonality analysis
- Interactive visualizations
- CSV export of forecasts
- Automated testing suite

## Project Structure
```
sales-forecasting/
├── src/              # Source code
├── notebooks/        # Jupyter notebooks
├── data/            # Input data files
├── output/          # Forecast outputs
└── tests/           # Test files
```

## Installation

1. Clone the repository:
```bash
git clone https://github.com/omar-steam/Sales-Forecasting-with-Prophet
cd sales-forecasting
```

2. Create and activate a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage

1. Place your sales data CSV file in the `data/` directory
2. Run the forecast script:
```bash
python src/forecast.py
```

3. Check the output/ directory for results

## Data Format
The input CSV should have the following columns:
- Sales Date: Date in MM-DD-YY format
- Total Sales: Numeric sales values

## Testing
Run the tests using pytest:
```bash
pytest tests/
```
---

# File: requirements.txt
```
prophet==1.1.5
pandas==2.1.0
matplotlib==3.7.2
numpy==1.24.3
pytest==7.4.0
jupyter==1.0.0
```
---

# File: .gitignore
# Python
```
__pycache__/
*.py[cod]
*$py.class
```
# Virtual Environment
```
.env
.venv
env/
venv/
ENV/
```

# Distribution / packaging
```
dist/
build/
*.egg-info/
```
# Jupyter Notebook
```
.ipynb_checkpoints
```
# Data and Output files
```
data/*.csv
output/*.csv
output/*.png
```
# IDE
```
.idea/
.vscode/
*.swp
```
# OS
```
.DS_Store
```
---


