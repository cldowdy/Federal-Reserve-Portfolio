# Data Collection
Data was collected as part of the Code for Tampa Bay initiative, an international network of people commited to using tech skills to improve communities. The overall goal of this project was to gauge the impact of chronic homelessness has on the Criminal Justice System. We took part in this project and built a relational database of incarceration and release data.  

The raw data came to us in the form of a webscrape of the online offender based transaction system. The files included in this repository are intended to showcase the preprocessing necessary to go from a messy webscrape to something that can be easily migrated to a database.


## Contents

- **cleaned-data**:
	* `booking_add.clean.example`: The head of the cleaned charges dataset
	* `release.clean.example`: The head of the cleaned release dataset
- **input-data**
	* `[1-9] LAYOUT CSV.csv`: Raw webscrape data to be used in preprocessing
- **preprocessing**
	* `assignment2add_charges.py`: Python program responsible for extracting the charges data from the raw webscrape
	* `assignment2releasefinal.py`: Python program responsible for extracting the release data from the raw webscrape


