# DS_ND_Term2_Project1

**Libraries:**

I used the libraries pandas, numpy, matplotlib and sklearn.

**Motivation:**

I personally used AirBNB first time recently and I asked myself: If I had an apartment or a room to share in a larger city, what price could I ask for? What differences are there concerning different room types and what are relevant factors for higher prices? Those questions I want to answer during this analysis.

**Files:**

DS_ND_Term2_Project1_Analytics.ipynb is the Jupyter Notebook I used to conduct the analysis.
listings.csv is the csv-file that contains all the AirBNB data from Seattle.
The README.md is the file you are just looking at which describes the project.

**Results:**

From the data we see that the average price per night differs for different room types. It is low for shared rooms, higher for private rooms and the highest prices you can find for entire home/apartments. This is what we would expect. Nevertheless, you could be sourprised about the standard deviations: This is way higher for entire home/apt than for other room types. Can this be explained by room size? This is not the case as the mean and standard deviation of room size for private rooms and entire home/apt are quite similar.
The lasso regressions show which fields where used most often. Those fields seem to have a huge impact on price. You find that the number of beds, bathrooms and bedrooms have a huge impact. Also the cleaning fee is important. This is less surprising as it might be considered as a part of the price a guest needs to pay. Furthermore the room type, the property type and the neighbourhood is important. People also check if an offer provides an elevator and if you can bring guests.

**Acknowledgement:**

When I created I was working on this project I found help here:

https://www.geeksforgeeks.org/clean-the-string-data-in-the-given-pandas-dataframe/

https://datascience.stackexchange.com/questions/38914/a-single-column-has-many-values-per-row-separated-by-a-comma-how-to-create-an

https://matplotlib.org/3.1.1/gallery/lines_bars_and_markers/barh.html
