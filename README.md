# DataFactory
pipelines:
- copy files into db: copies into the DB one file between jobs.csv, departments.csv and hired_employees.csv depending on the parameter file. The parameter is the file name with no extensions.
- delete tables: deletes SQL tables challenge.jobs, challenge.departments, challenge.hired_employees.

