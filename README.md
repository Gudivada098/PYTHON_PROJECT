# PYTHON_PROJECT
This team includes:: Gudivada Sravana Sai Priya, Deepika, Pranitha



#### Folder structure

```sh
Repo

In the repository we have usen the following commands for execution.

├── coverage        		# Coverage Results 
├── csv_data        		# Auto-generated .csv files
├── figures         		# Auto-generated figures
├── scipy	    		 
├── main.py         		# Generates csv_data and figures
├── .
├── .
├── .
```

## Requirements for setting up the environment

1. python 3.6 or higher

2. Using virtualenv:

	`python3 -m pip install --user virtualenv`

	`python3 -m venv env`
	
	`source env/bin/activate`

3. `pip install numpy`

4. `pip install pandas`

5. `pip install pydriller``

6. `pip install -U kaleido`




## Cloning the Repository

	`git clone {project_url}`
  
  
## To Build and get the Coverage the Project

	`cd <project folder>`

	`python runtests.py --coverage`

## To Generate CSVs and Figures
	
	`cd <project folder>`
	 
	`python main.py`
	
## Results
	
	Executing main.py will dynamically generate .csv files (using Pydriller).
