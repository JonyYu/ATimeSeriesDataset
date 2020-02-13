
# ATimeSeriesDataset: A time series dataset for data compression efficiency evaluation
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

Name | Points | Name | Points
--- | --- | --- | ---
IoT0 | 430,737 | IoT4 | 306,736
IoT1 | 429,745 | IoT5 | 372,868
IoT2 | 428,390 | IoT6 | 430,413
IoT3 | 344,581 | IoT7 | 313,539

2. **Server**: Collected from Alibaba Server scenario.

Name | Points | Name | Points
--- | --- | --- | ---
Server30 | 158,188 | Server57 | 26,779
Server31 | 147,385 | Server62 | 32,569
Server32 | 165,395 | Server66 | 135,409
Server34 | 140,194 | Server77 | 136,598
Server35 | 147,395 | Server82 | 143,798
Server41 | 136,594 | Server94 | 140,198
Server43 | 29,233  | Server97 | 158,194
Server46 | 154,585 | Server106 | 136,478
Server47 | 140,199 | Server109 | 153,438
Server48 | 157,051 | Server115 | 165,384

3. **UCR**: Collected in [UCR](https://www.cs.ucr.edu/~eamonn/time_series_data/), several longest time series is picked here. And it only have value (no timestamp) here in float format.  

Name | Points | Name | Points
--- | --- | --- | ---
HandOutlines | 641,796  | CinC_ECG_torso | 8,190
Haptics | 19,638  | InlineSkate | 16,929
StarLightCurves | 155,496 |  MALLAT | 6,138 
UWaveGestureLibraryAll | 115,168 | Phoneme | 4,092
