cd postgres

### Start I2B2-WEB 

docker-compose up -d i2b2c-web

user can login into http://localhost/webclient/ using below mentioned credentials
username is demo
password is demouser

### START I2B2-ETL

docker-compose up -d i2b2-etl

The webclient password is updated to i2b2cdiDemo@2020

### START IBM DB2

docker-compose up -d db2 

### START Gitlab

docker-compose up -d gitlab
User can access the gitlab on http://localhost:8090/

### START Gitlab-runner

docker-compose up -d gitlab-runner

