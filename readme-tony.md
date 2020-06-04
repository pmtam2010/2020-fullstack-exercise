# Steps to test this exercise
1. Under the 'exercise-project\frontend' folder, run the command prompt and type 'npm install react-bootstrap react-bootstrap-table2-paginator react-bootstrap-table-next react-router react-router-dom axios mobx-react'
2. Host the 'exercise-project' Rest API project on IIS Express with the base url (For example: https://localhost:44343)
3. Run the React 'FrontEnd' project at http://localhost:3000 (this client endpoint url is configurable at appsettings.json file)

# There are two endpoints hosted as below
1. https://localhost:44343/api/Authentication (used to authorize username and password and return JWT token)
2. https://localhost:44343/api/Customer (used to retrieve customers data)