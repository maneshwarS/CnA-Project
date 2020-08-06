# Flight-Delay-Prediction
Flight Delay Prediction: Building a predictive model analyzing flight delay in Indian Airlines by preparing data from scratch using APIs (JSON) web scraping methods. Further engineering the data and using Machine Learning algorithms to predict flight delay time. The trained model can be used to predict the flight delay in new test sets.
.
## Data
Dataset has been prepared by from scratch by scraping and parsing Indian flight websites (namely Indigo, Air India, SpiceJet, GoAir, AirAsia) using the python package BeautifulSoup. <br />
Size of dataset: (10718, 29)

#### Features
1. Used Date: Date of departure
2. From: Deaparture place
3. To: Arrival place
4. Airline: Name of the Indian airline
5. Scehduled Departure: Time of scheduled departure
6. Departure: Actual time of departure
7. Scheduled Arrival: Time of scheduled arrival
8. Arrival: Time of actual arrival
9. Distance: Flight distance between departure and arrival point
10. Airline Rating: Average airline ratings (as quoted by www.airlineratings.com)
11. Weather attributes: <br />
    a) weather__hourly__windspeedKmph<br />
    b) weather__hourly__precipMM<br />
    c) weather__hourly__humidity<br />
    d) weather__hourly__visibility<br />
    e) weather__hourly__pressure<br />
    f) weather__hourly__cloudcover<br />
    
    
    
 ## Machine Learning Used
 Dataset.csv was trained on two Machine Learning Models: RandomForestRegressor and XGradientBoost and the python code is stored in FLIGHT DELAY.ipynb and FLIGHT DELAY.py files.
 
 #### Dependencies
 * NumPy
 * Pandas
 * BeautifulSoup
 * Matplotlib
 * Scikit-learn
