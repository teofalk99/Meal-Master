# MealMaster - CPSC437 Final Project

##### Teo Falk, Jason Lee, Gabriel Sleenhof

# 
We have created a web application that allows users to query a database of recipes containing information such as recipe names, cook/prep time and nutritional values. The application will display recipes that match the user's selected criteria. Upon clicking on a recipe, the user will be redirected to a Google search leading to the recipe's online website, which contains more information, most importantly cooking instructions.

MealMaster is developed using a stack of JavaScript utilizing the Fetch API, Flask, and mySQL.

To try out the application locally, please follow these instructions:
- Download the 437project directory.
- Make sure Flask and mySQL are installed and up to date on your computer.
- If not installed, run "pip3 install mysql-connector-python"
- Initialize the food database locally by running the init.sql file (in mySQLWorkbench or some other program).
- Change the "password" value in secretkeys.py to the password used for mySQL on your computer.
- cd into 437project and run "python app.py".
- Navigate to localhost:8001 in your browser of choice.


Hope you enjoy!
