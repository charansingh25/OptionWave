# OptionWave: Option Pricing Model

This repository provides an interactive dashboard based on the OptionWave (Black-Scholes) Pricing Model. The dashboard allows users to visualize option prices under varying conditions, making it easy to explore how changes in spot price, volatility, and other market factors influence the value of options.

LIVE : https://charansingh25-optionwave.streamlit.app/

## 🚀 Features:

1. **Options Pricing Visualization**:
   - Displays both Call and Put option prices using an interactive heatmap.
   - The heatmap dynamically updates as you adjust parameters like Spot Price, Volatility, and Time to Maturity.

2. **Interactive Dashboard**:
   - The dashboard allows real-time updates to the OptionWave model parameters.
   - Users can input different values for the Spot Price, Volatility, Strike Price, Time to Maturity, and Risk-Free Interest Rate to observe how these factors influence option prices.
   - Both Call and Put option prices are calculated and displayed for immediate comparison.

3. **Customizable Parameters**:
   - Set custom ranges for Spot Price and Volatility to generate a comprehensive view of option prices under different market conditions.

## 🔧 Dependencies:

- `yfinance`: To fetch current asset prices.
- `numpy`: For numerical operations.
- `matplotlib`: For heatmap visualization.
- `seaborn`: For advanced data visualization.
- `pandas`: For handling data structures.
- `streamlit`: For building the interactive dashboard.

## ⚙️ Installation and Setup Locally:

To set up this project locally and run the dashboard, follow these steps:

### 1. Clone the Repository

```bash
git clone https://github.com/charansingh25/OptionWave.git
cd OptionWave
```

### 2. Set up a Virtual Environment
First, ensure you have `python3-venv` installed. If not, install it using the following command:

- **For Ubuntu**
```bash
sudo apt-get install python3-venv
```
- **For macOS and Windows (if not installed):**
```bash
pip install virtualenv
```

Create a virtual environment:
```bash
python3 -m venv env
```

### 3. Activate the Virtual Environment

- **On macOS/Linux:**
```bash
source env/bin/activate
```

- **On Windows:**
```bash
.\env\Scripts\activate
```

### 4. Install Dependencies
Once the virtual environment is activated, install the project dependencies using `pip`:

```bash
pip install -r requirements.txt
```

### 5. Run the Dashboard
After installing the dependencies, run the dashboard locally:
```bash
streamlit run streamlit_app.py
```

Visit http://localhost:8501 in your web browser to view the dashboard.


### AUTHOR 

- **GitHub:** [charansingh25](https://github.com/charansingh25)

