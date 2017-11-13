This web app allows users who are interested in becoming Airbnb hosts to gain intuition about the market. CityView achieves this with the following features.

Feature 1) CityView can estimate the weekly income from a given geo-location. CityView handles this by parsing a large source of data from AirBnb. When CityView is given a location, the web app will try to find the location in the source data that is closest to the input location. It does this by sorting the dataset after subtracting the input location from each data point. CityView then sorts the updated dataset to find the location that is closest to the input. The prediction is made by taking the closest known location's price. The optimal booking price was determined to be .923 of the weekly income.

Feature 2) CityView displays 3 graphs that I believe to be the most important in understanding the market. Those graphs were analyzed in Java and graphed in excel.

All of the dynamic code is located at the bottom of index.html
