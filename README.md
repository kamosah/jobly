# Jobly

Jobly is a job board where job seekers can search and apply to job listings. 

The front-end is built using React and React/Router and features a secure user authentication. The registration, login, authentication and authorization process uses JSON web tokens and bcrypt. 

On the back-end, company and user data is stored in a PostgreSQL database. Individual components of Jobly are tested using Jest and Enzyme assertion library implementing Test Driven Development principles.

To see a live demo: https://the-jobly-app.herokuapp.com/

* Username: admin
* Password: password

![alt text](https://github.com/kamosah7/jobly/blob/master/images/jobly.gif "Jobly Gif")

**To run this repository locally:**

1. `git clone`
2. `cd backend`
3. `createdb jobly`
4. `psql jobly < data.sql`

*Start the backend server*
1. `cd backend`
2. `npm install`
3. `npm start`

*Run the frontend:*
1. `cd frontend`
2. `npm install`
3. `npm start`

**Here's a sample of the JSON returned from the backend (a GET to '/jobs'):**

![alt text](https://github.com/kamosah7/jobly/blob/master/images/backend.png "Sample JSON returned from GET to '/jobs'")

**Here's an Entity Relationship Diagram of the Database Design:**
![alt text](https://github.com/kamosah7/jobly/blob/master/images/jobly-erd.pdf "Jobly ERD")


Collaborators: https://github.com/colebillys19