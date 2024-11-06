Employee Churn Prediction at Dunder Mifflin Paper Company
Introduction:
In this project, we aim to predict employee churn at the Dunder Mifflin Paper Company, a well-established paper company located in Scranton, Pennsylvania. The company is facing a challenge with a high turnover rate among its employees, and our goal is to understand the factors contributing to employee churn to improve satisfaction and retention.

Dataset Features
Employee Information
EmployeeID: A unique identifier for each employee.
Tenure: The number of years the employee has been with the company.
Salary: The employee's annual salary.
Department: The department in which the employee works (e.g., Sales, Accounting, Customer Service).
JobSatisfaction: The employee's self-reported job satisfaction level (on a scale from 1 to 5, with 5 being highly satisfied).
WorkLifeBalance: The employee's self-reported work-life balance rating (on a scale from 1 to 5, with 5 being excellent).
CommuteDistance: The distance the employee commutes to work (e.g., Short, Medium, Long).
MaritalStatus: The marital status of the employee (e.g., Single, Married, Divorced).
Education: The highest level of education attained by the employee (e.g., High School, Bachelor's, Master's).
PerformanceRating: The employee's performance rating (on a scale from 1 to 5, with 5 being excellent).
TrainingHours: The number of hours of training the employee has received.
OverTime: Whether the employee works overtime or not.
NumProjects: The number of projects the employee is currently working on.
YearsSincePromotion: The number of years since the employee's last promotion.
EnvironmentSatisfaction: The employee's self-reported environment satisfaction (on a scale from 1 to 5, with 5 being highly satisfied).
Target Variable
Classes: Employees will be classified into four classes based on their likelihood to leave:
Class 1: Highly likely to leave.
Class 0: Not likely to leave.
Project Structure
The project is organized into the following files and directories:

data: Contains the dataset used for training and testing the model.
src: Includes the source code for data preprocessing, model training, and evaluation.
models: Stores the trained machine learning model.
README.md: The file you are currently reading, providing an overview of the project.
How to Use
Follow these steps to run the project:

Clone the repository: git clone <repository-url>
Navigate to the project directory: cd employee-churn-prediction
Install the required dependencies: pip install -r requirements.txt
Run the main script: python src/main.py
