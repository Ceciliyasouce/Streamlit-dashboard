About the project:
	- A web application using python streamlit that predicts rain and snow using real-time weather data and machine learning. 
	-It fetches live data from the Open-Meteo API, processes key weather features, and uses two logistic regression models, one for rain and one for snow, to generate predictions.



Running the code:
1. Create virtual environment
    python3 -m venv myvenv
2. Activate virtual environment
    source myvenv/bin/activate 
3. install requirements.txt
    pip install -r requirements.txt
4. Model file can be run cell by cell using myvenv python kernel
5. The dashboard is run using streamlit
    streamlit run app.py
6. Deactivate virtual environment
    deactivate