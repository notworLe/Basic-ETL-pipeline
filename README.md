# Basic-ETL-pipeline
The basic repository for understanding ETL 


# Air_flow
Airflow is a tool for scheduling and automatically  
## Thoery
### DAG
DAG (Directed Acyclic Graph)  
- Like a scenario job  
Example:  
- Every 8PM, i need to get, transform, save to database

### Task
A little task in RAG 
Example: 
- Task1: get data

### Operator
A specified task
Example:  
- `BashOperator`
- `PythonOperator`  

# Installation
Install: `pip install apache-airflow`   
Let's airflow do these following things:
- Migrate database
- Create user admin
- Run service  
With only a command: `airflow standalone`  

Get the acoount: `cat ~/air_flow/simple_auth_manager_passwords.json.generated`  
Visit: `localhost:8080`  



## Setup python configure in vscode
`ctrl + shift + p`: Preferences: Open Settings (UI)  
```json
{
    "python.defaultInterpreterPath": ".venv/Scripts/python.exe",
    "python.analysis.typeCheckingMode": "basic",
    "python.analysis.autoImportCompletions": true,
    "python.terminal.activateEnvironment": true,
    "editor.formatOnSave": true
}
```