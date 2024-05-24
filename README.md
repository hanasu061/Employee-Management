# Employee-Management

## Features

- Add Employee
- Update Employee
- List Employees
- Delete Employee

## Setup

### Backend

1. Create Spring initializr.
2. Navigate to the `backend` folder and open it in terminal.
3. Run EmployeeController.java.
4. Ensure MySQL is running and accessible. Update the `application.properties` file with MySQL credentials.

### Frontend

1. Navigate to the `frontend` folder and open it in terminal.
2. Using Vite, run the following commands to start the React application:
    ```bash
    npm run dev
    ```

## Technologies Used

- Spring Boot
- MySQL
- React
- Axios

## Languages Used

- Java
- JavaScript
- CSS

### Screenshots

#### Main Page
List of employees:

![Main Page](images/main_page.png)

#### Add Employee

![Add Employee](images/add_employee1.png)

After inputing the employee information:

![Add Employee Info](images/add_employee2.png)

If the employee information is empty, it shows:

![Empty Employee Info](images/empty_add.png)

#### Update Employee
Edit email address, from yuki@gmail.com to yukimura@gmail.com:


![Update Employee](images/edit_employee.png)

After editing the employee information, the list of employees:

![List After Edit](images/list_after_edit.png)

#### Delete Employee
![Delete Employee](images/delete_employee.png)
