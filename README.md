# DataFactory
pipelines:
- from blob to sql: copies from file "file" in the blob storage into SQL server table "table". file and table are parameters.
- moving data into db: copies the files jobs.csv, departments.csv, hired_employees.csv respectively into SQL tables challenge.jobs, challenge.departments, challenge.hired_employees
- delete tables: deletes SQL tables challenge.jobs, challenge.departments, challenge.hired_employees

