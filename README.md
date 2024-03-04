# DocuShift - Emphasizes the shift from paper to digital document management.


<details>
<summary>Overview</summary>

## **Overview.**

_In the realm of business, going digital is no longer just an option; it's essential. DocuShift, a graduate project designed for companies. Our platform is built to help businesses say farewell to paper, organizing everything from documents to employee activities in one easy-to-use system.
_

</details>

<details>
<summary>Key Features of DocuShift</summary>

## **Key Features of DocuShift.**

**Go Paperless:** Replace stacks of paper with a secure, digital document system.
**Save Projects Safely:** Keep all your project information in one place, accessible anytime.
**Manage Meetings Efficiently:** Plan and record your meetings with ease, all in one platform.
**Track Team Activities:** Get insights on team productivity and manage workloads effectively.


**Manager**
-Create department for the company "HR,IT,..etc".
-Schedule meetings.
-Approval and rejection of employee requests for "leave, Permission, ...etc".
-Create account for each employee and select their department , show their profile.


**HR Department**
-Edit their profile "name, photo, password,...etc".
-Send request service from the other employees into the manager.
-can send a request for the manager.
-show the status of their request if it approval or not.
-show the meetings
-upload their works.
-showen their works.
-show all the employees with departments, and showen their works.

**Employee (in the other departments)**
-Edit their profile "name, photo, password,...etc".
-can send a request for the HR.
-show the status of their request if it approval or not.
-send emails "chat" with other employees 
-show the meetings
-upload their works.
-showen their works.

</details>


<details>
<summary>Inistallation</summary>

## **Inistallation.**

**1-Download "XAMPP control panel".**

<img width="1508" alt="Screenshot 1445-08-23 at 6 14 58 PM" src="https://github.com/ppvq11/DocuShift./assets/144011837/e1320abd-c8cb-4675-937d-f033771fe06b">

after downloading, open "XAMPP control panel", Start (Apache, MySQL).

<img width="637" alt="Screenshot 1445-08-23 at 6 18 17 PM" src="https://github.com/ppvq11/DocuShift./assets/144011837/4e8f40df-eae4-4aa5-8afe-67da2cc68937">

**2-Download the human_resourse(3).sql, in your device.**

open your browser to this website, http://localhost:80/phpmyadmin
-select "New", then "Import", after that add "human_resourse(3).sql" database from your desktop.

**3-Download this project in your device and open it in "VS Code".**
go to the terminal after open this project,
write "php artisan storage:link" then click enter..
write "php artisan serve" then click enter..

now copy the link that appeared to you termenal, then paste it into your browser and added it at the end /login

the admin account is 
Email: admin@app.com
password: 123456

</details>

