# DataFactory
pipelines:
- from blob to sql: copies from blob storage \files\\"file" into SQL server table challenge."table". "file" and "table" are parameters.
- moving data into db: copies the files jobs.csv, departments.csv, hired_employees.csv respectively into SQL tables challenge.jobs, challenge.departments, challenge.hired_employees
- delete tables: deletes SQL tables challenge.jobs, challenge.departments, challenge.hired_employees

