
#ATimeSeriesDataset: A time series dataset for data compression efficiency evaluation
Time series exists everywhere and has been well used in finance, internet services, and IOT etc. The data to be stored is huge, and the compression efficiency to process is also very important. 

To well evaluate the compression efficiency, a public dataset is useful. Here it presents some dataset collected. And its major data format is <timestamp, value> unless otherwise specified.  

Please reference as: 

	@inproceedings{AMMMOArchive,
      title     = {TBD}, 		
	  author    = {TBD},
	  booktitle = {TBD},
	  pages     = {TBD},
	  publisher = {TBD},
	  year      = {2020}
	}

# List of the dataset 
The detail data is in relative data folder, and basic description are listed below:

1. **IoT**: Collected from Alibaba IoT scenario.
|Name | Points|
|---- | ---| 
|IoT0 | 430,737|
|IoT1 | 429,745|
|IoT2 | 428,390|
|IoT3 | 344,581|
|IoT4 | 306,736|
|IoT5 | 372,868|
|IoT6 | 430,413|
|IoT7 | 313,539|
 
2. **Server**: Collected from Alibaba Server scenario.
3. **UCR**: Collected in [UCR](https://www.cs.ucr.edu/~eamonn/time_series_data/), several longest time series is picked here. And it only have value (no timestamp) here in float format.  
