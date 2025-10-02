# Airflow DAG Project
This project contains an Apache Airflow DAG named `Airflow_Depi` that demonstrates basic task operations and dependencies.

## 📋 Project Description:- 
A simple Airflow DAG with three sequential tasks:
1. **Print Current Date** - Uses BashOperator to display the current date
2. **Print Welcome Message** - Uses PythonOperator to print a personalized welcome message
3. **Generate Random Number** - Uses PythonOperator to generate a random number and save it to a file

## 🛠 DAG Structure

- **DAG Name**: Airflow_Depi
- **Schedule**: Every minute
- **Task Order**: Task 1 → Task 2 → Task 3
- **Dependencies**: Sequential execution

🎯 Task Outputs:-

**Task 1**: Print Current Date
Output: Current system date and time
Operator: BashOperator

**Task 2**: Welcome Message
Output: "Welcome Ahmed Elbendary"
Operator: PythonOperator

**Task 3**: Random Number Generation
Output: Random number between 1-1000 saved to random.txt
Operator: PythonOperator

🔧 Technologies Used:- 
Apache Airflow 
Python 3.x 
Bash 
SQLite (for other DAGs in project)

👨‍💻 Author    
Ahmed Elbendary

GitHub: [https://github.com/AhmedElbendaryRmadan]

Email: [ahmedelbendary301@gmail.com]

