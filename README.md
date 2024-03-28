# Hadasim-4.0-Project
Develop a comprehensive FullStack system for managing the Covid database of a Health Maintenance Organization (HMO). This system will enable the introduction, editing, and deletion of HMO members, while managing their records in a database

Back-End: - (under the repository: Hmo-covid-back-end)
Powered by the Spring Boot framework, developed in Java.

To set up the back-end of your project, follow these steps:

1.Download and install the JDK (Java Development Kit).
2.(Optional) Use IntelliJ IDEA as your IDE for  development.
3.Initialize your project with Spring Boot by entering this link https://start.spring.io/.

Front End:  (under the repository: Hmo-covid-fron-end)
Developed with the React framework and powered by Vite, a  build tool for web projects.

To set up your project, follow these steps:

Initialize your project using Vite:
npm create vite@latest name_of_project

Install JavaScript dependencies:
npm install

Start the development server to run your React application:
npm run dev

For styling, incorporate Bootstrap:
npm install bootstrap

In order to make API requests, utilize Axios:
npm install axios

For using React Router install react-router-dom package:
npm install react-router-dom

Database:
Utilize MongoDB Atlas, a fully-managed cloud database solution.
No installation is required; simply create a free account.
For easy data management, download MongoDB Compass, a GUI for querying, aggregating, and analyzing data.

Demo
At the site entrance, a list of all members is displayed.
![image](https://github.com/frayele5/Hadasim-4.0-Project/assets/115617902/b1ef1297-5d84-4ff4-8aa7-41d5bf901bfc)

When you click on 'Add Member,' you'll be directed to a page where you can input the details of the new member and submit them .
![image](https://github.com/frayele5/Hadasim-4.0-Project/assets/115617902/00d53377-8200-4696-b36d-26b7745d7240)
![image](https://github.com/frayele5/Hadasim-4.0-Project/assets/115617902/45a53185-9936-4230-8b77-d2512674c9af)
Upon clicking "Submit," the system  verifies the accuracy of the entered details. If any inaccuracies are detected an alert is triggered to notify you. 
![image](https://github.com/frayele5/Hadasim-4.0-Project/assets/115617902/0d9d824f-d6ce-40cd-9908-25a427b8ee9c)

It's important to note that the correctness check is specifically applied to first name, last name and id which are the only fileds that mandatory, assuming the correctness of the remaining data. (In addition, a check that the date of recovery is after the date of positive).

After submitting the details, you'll be automatically redirected back to the entrance, where you can access the updated list of all members.

At the main page, apart from adding members, there are three additional options available.

1. show details - Display information regarding the selected member.
   ![image](https://github.com/frayele5/Hadasim-4.0-Project/assets/115617902/a19cbab9-ad2b-426c-bc9f-5db89f1f6e0b)

2. update - nables you to update the details of an existing member.
   ![image](https://github.com/frayele5/Hadasim-4.0-Project/assets/115617902/3645031c-170d-4a82-80ed-ab54533e84b0)

3. delete - delete a member from the list.




