# WeatherPy

#### 
The WeatherPy (a vacation planning app) documents stored in this repository build upon one another using Python, Pandas, Open Weather Map API keys, and Google API keys to provide a planned itinerary map. The Weather_Database folder contains the base of the documents with Python code that creates lists and dictionaries from an Open Weather Map API request for coordinates and city names. Compiling this data along with weather information, a dataframe is created which is then saved to a CSV file. The next folder, the Vacation_Search folder contains the next set of Python code and CSV file combination. In the Python code labeled Vacation_Search, a Google Map API request is performed searching for a hotel in the list of cities provided from the previously created CSV file in the Weather_Database documentation. This new data was then added to the pre-existing dataframe before being printed to a new CSV file and Google map. The final folder, Vacation_itinerary, contains the last documents that use the previous lines of code and CSV files to create a hypothetical vacation itinerary involving four cities using the customer's temperature and city requests. This itinerary is then mapped out on a Google map using Pandas.
