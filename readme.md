# Airflow on dockers steps
## Requirements
- Windows version greater than 19044
- Dockers desktop version 27.2.0 or greater
- Git installed 
## Steps 
- Clone repository
- Create '.env' file
- Insert in the env 'AIRFLOW_UID=50000'
- run the following cmd at the root directory
```bash 
docker compose up airflow-init
```
- run the following cmd at the root directory
```bash
docker compose up
```
the container takes some to initialize and start after that you may visit the following link for the webinterface  

[Webserver Interface Port 8080](http://localhost:8080/)  

The username and password are both 
```text 
airflow
```

