# Master Analysis

This project, housed within my Git repository, encompasses all the code utilized for my Master's thesis, under the title:<br>
**DEVELOPMENT OF PROCESSING TOOLS FOR HIERARCHICALLY ORGANIZED COLLECTION OF TABULAR DATA**

This project consists of two parts. The first involves benchmarking various data types, assessing their write speed and file size, aiming to identify the most suitable option for scientific data storage. The second part focuses on testing the feasibility of extracting specifically required data from pre-existing .H5 files, consolidating this data into a single compact file.

The data utilized in the second segment originates from:
[NASA LADS Web Archive - VNP46A3 2022](https://ladsweb.modaps.eosdis.nasa.gov/archive/allData/5000/VNP46A3/2022)

The data extracted spanned the entire year of 2022, derived specifically from files labeled as 'h19v04' and 'h20v04'. This data was chosen due to its coverage of the geographical region corresponding to the Republic of Serbia.

## Directory Structure
- Benchmarking: Includes the procedures for benchmarking write time and file size.
- H5_Creation: Encompasses the process of extracting data from existing .h5 files and merging them together.
- Functions: Comprises functions developed to streamline the benchmarking and creation processes.
- Docker: Holds the Dockerfile and docker-compose file utilized for setting up the environment.

## Reminder
The benchmarking data size was determined according to the hardware constraints of my machine during that particular period.

# Thesis
The complete Master's Thesis is accessible in Serbian within the .pdf file:<br>
**Razvoj alata za obrade hijerarhijski organizovanih kolekcija tabelarnih podataka**
