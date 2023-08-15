# README

## Climate Analysis

This project conducts an exploratory analysis of climate data using Python, SQLAlchemy, and Flask. The data is stored in a SQLite database and the analysis is presented both in a Jupyter notebook and through a Flask API.

### Files Included:

1. `app.py` - A Flask application that serves climate data from the SQLite database.
2. `climate_starter.ipynb` - A Jupyter notebook that conducts an exploratory analysis of the climate data.

## File Descriptions:

### 1. app.py

This Flask application interacts with the `hawaii.sqlite` SQLite database. The main components are:

- **Database Setup**: Connects to the SQLite database, reflects its schema, and establishes a session.
- **Flask Setup**: Initializes the Flask app.
- **Flask Routes**: (Not displayed in the provided excerpt) Likely contains various API routes to serve climate data.

### 2. climate_starter.ipynb

This Jupyter notebook contains the following sections:

- **Reflect Tables into SQLAlchemy ORM**: Sets up the database connection and reflects its tables.
- **Exploratory Precipitation Analysis**: Conducts data exploration and visualization related to precipitation.
- **Exploratory Station Analysis**: Analyzes and visualizes data related to weather stations.
- **Close Session**: Closes the database session.

## How to Use:

1. **For the Flask App**:
   - Run `app.py` to start the Flask server.
   - Access the API endpoints using a web browser or tools like Postman.

2. **For the Jupyter Notebook**:
   - Open `climate_starter.ipynb` in Jupyter Notebook or Jupyter Lab.
   - Ensure that all dependencies are installed.
   - Run the cells in sequence to conduct the analysis.

## Notes:

- Ensure that you have the required Python packages installed, such as Flask, SQLAlchemy, NumPy, and pandas.
- The SQLite database (`hawaii.sqlite`) should be located in the `Resources` folder as referenced in `app.py`.
