# How to use command line interface in airflow
1. Get help "airflow -h"
2. Get help all CLI of user in airflow: "airflow users -h"
3. Get help how to create user: "airflow users create -h"
Forexample: create admin user like:
`airflow users create -u admin -p admin -f Binh -l Trinh -r Admin -e admin@airflow.com`
- user: admin
- pass: admin
- firstname: Binh
- lastname: Trinh
- role: Admin
- email: admin@airflow.com

# Some usefull CLI for airflow
1. db
- db init -create databas.run 1 time
- db upgrade - upgrade database
- db reset to reset all metadata in database 
- webserver - start UI 
- scheduler - open scheduler in airflow
- dags list - list all dags
- tasks list [task name] - list infor task name