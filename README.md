# Restaurant Data Intake

## Introduction
First project to practice data intake from multiple data sources using Docker Containers and a remote Spark server.
Containers used were: 
* Jupyter/pyspark-notebook
* Postgres
  
The goal of the project was to intake and clean up the data to store only the list of restaurants in Los Angeles.

### Data Sources
| Data Source | URL/File |
| :---:       | :---:    |
| LA City     | https://data.lacity.org/Administration-Finance/Restaurants-in-LA/nqb5-fsih/about_data |
| Yelp        | yelp_academic_dataset_business.json |

### Architecture
![Architecture](images/First-Data-Intake-Architecture.png)
*Figure 1*



