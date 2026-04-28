\# Diagnosis DBMS System



A full-stack web application for managing medical test bookings, user authentication, and diagnostic services.



\##  Features



\* User registration and login (authentication with bcrypt)

\* Book diagnostic tests

\* View and manage bookings

\* Admin panel for managing tests and bookings

\* Upload and view test results

\* Session-based authentication



\##  Tech Stack



\* Backend: Node.js, Express.js

\* Database: MySQL

\* Frontend: EJS, HTML, CSS

\* Authentication: bcrypt



\##  Project Structure



\* `app.js` – main server file

\* `views/` – frontend templates

\* `public/` – static files

\* `database.sql` – database schema



\##  Setup Instructions



1\. Clone the repository



2\. Install dependencies:



&#x20;  ```bash

&#x20;  npm install

&#x20;  ```



3\. Setup MySQL:



&#x20;  \* Create a database

&#x20;  \* Import `database.sql`



4\. Update DB config in `app.js`:



&#x20;  ```js

&#x20;  host: "localhost",

&#x20;  user: "root",

&#x20;  password: "your\_password",

&#x20;  database: "diagnostic\_system"

&#x20;  ```



5\. Run the project:



&#x20;  ```bash

&#x20;  node app.js

&#x20;  ```



6\. Open in browser:



&#x20;  ```

&#x20;  http://localhost:3000

&#x20;  ```



\##  Future Improvements



\* Add email verification

\* Improve UI/UX

\* Deploy online



\##  Author



Ali Asghar



