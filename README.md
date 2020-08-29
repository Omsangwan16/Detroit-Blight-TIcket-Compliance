# Detroit-Blight-TIcket-Compliance
The Project involves analyzing the Blight ticket data of the City of Detroit taken from [Detroit's Open Data Portal](https://data.detroitmi.gov/) for the years of 2004-2016.The data for the years of 2004-2011 is taken as training data and the data of the years 2012-2016 is used for testing.
## Preprocessing
### The NA values are filled using forward fill
### The Addresses and the latitudesand logitude locations are added to the data using latlons and addresses datasets
### All the Unnecessary features that are not present in the test dataset but there in the train datasets are reove

## Model Building
### Used GridsearchCV to find out the optimal parameters for the Random Forest Clasifier
### Trained the data on the training set and used it to predict the probabilities of blight tickets being paid on time for the test set

