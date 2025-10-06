# Electricity Consumption Forecasting using Prophet

A simple forecasting project that uses Facebook’s Prophet to predict electricity consumption (or power usage) over time based on historical data.

## Features

- Data preprocessing and cleaning  
- Exploratory analysis (visualisations, trend, seasonality)  
- Forecasting using Prophet  
- Model evaluation (error metrics, visual checks)  
- Optionally, future forecasting into a horizon (e.g. next 12 months)  
- Reproducible notebook for experimentation  

## Project Structure

- **notebooks/** — Jupyter notebooks containing data exploration, modeling steps, forecast visualisations, and results  
- **requirements.txt** — Python dependencies required to run the notebooks  
- **LICENSE** — The MIT license file  
- **README.md** — This documentation  

## Tools & Libraries

- Python 3.x  
- pandas 
- numpy  
- matplotlib  
- Prophet (fbprophet) 
- jupyter / notebook
  
You can find all dependencies in **requirements.txt**.

## How to Use

1. **Clone the repository**

   ```bash
   git clone https://github.com/nurulashraf/prophet-electric-consumption-forecast.git
   cd prophet-electric-consumption-forecast
    ````

2. **Install dependencies**

   It’s best to use a virtual environment (venv, conda, etc.):

   ```bash
   python3 -m venv venv
   source venv/bin/activate   # on Linux/macOS
   # or venv\Scripts\activate  # on Windows

   pip install -r requirements.txt
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. **Open notebook**

   Launch Jupyter:

   ```bash
   jupyter notebook
   ```

   or

   ```bash
   jupyter lab
   ```

   Then open the notebook in the `notebooks/` folder.

## License

This project is released under the **MIT License**. See the [LICENSE](LICENSE) file for full text.
