📚 Curriculum - 0x02. ES6 Classes 🏫

Welcome to the 0x02. ES6 Classes short specialization! 🎉 In this specialization, we will dive into Object-Oriented Programming (OOP) concepts in JavaScript using ES6 classes. You will learn how to define classes, create objects from them, add methods and properties, and even understand metaprogramming with symbols.

🎯 Learning Objectives:
By the end of this project, you will be able to explain the following concepts to anyone without the help of Google:

1. How to define a Class in JavaScript
2. How to add methods to a class
3. Why and how to add a static method to a class
4. How to extend a class from another class (inheritance)
5. Understanding metaprogramming and using symbols in JavaScript

⚙️ Requirements:
Make sure you meet the following requirements for this project:

- Operating System: Ubuntu 18.04 LTS
- NodeJS version: 12.11.x
- Allowed Editors: vi, vim, emacs, Visual Studio Code
- All files should end with a new line
- A README.md file at the root of the project folder is mandatory
- Code files should use the .js extension
- Code will be tested using Jest, and you can run tests using the command `npm run test`
- Code will be verified against lint using ESLint
- Make sure your code passes all tests and lint checks. You can verify the entire project with the command `npm run full-test`

🔧 Setup:
Before you start the project, make sure you have the necessary setup in place:

1. Install NodeJS 12.11.x in your home directory:
```bash
curl -sL https://deb.nodesource.com/setup_12.x -o nodesource_setup.sh
sudo bash nodesource_setup.sh
sudo apt install nodejs -y
nodejs -v # should display v12.11.1
npm -v # should display 6.11.3
```

2. Install Jest, Babel, and ESLint in your project directory:
```bash
npm install --save-dev jest
npm install --save-dev babel-jest @babel/core @babel/preset-env
npm install --save-dev eslint
```

📁 Project Files:
Here's a list of project files and what they do:

1. 0-classroom.js: Contains the implementation of the ClassRoom class.
2. 1-make_classrooms.js: Imports the ClassRoom class and implements the initializeRooms function that returns an array of 3 ClassRoom objects with specific sizes.
3. 2-hbtn_course.js: Contains the implementation of the HolbertonCourse class, along with getter and setter methods.
4. 3-currency.js: Contains the Currency class implementation with getter and setter methods and a displayFullCurrency method.
5. 4-pricing.js: Implements the Pricing class with getter and setter methods and a displayFullPrice method. Also, defines a static convertPrice method.
6. 5-building.js: Implements the Building class with a getter for the sqft attribute. It is considered as an abstract class, and any extending class should implement the evacuationWarningMessage method.
7. 6-sky_high.js: Extends the Building class and implements the SkyHighBuilding class with additional attributes and an overridden evacuationWarningMessage method.
8. 7-airport.js: Implements the Airport class with getter methods for name and code attributes.
9. 8-hbtn_class.js: Implements the HolbertonClass class with getter methods and allows for casting to Number or String to retrieve specific attributes.
10. 9-hoisting.js: Contains classes HolbertonClass and StudentHolberton with getter methods and a static variable listOfStudents.
11. 10-car.js: Implements the Car class with getter methods and a cloneCar method that returns a new object of the class.

🚀 Let's get started with ES6 classes and take your JavaScript OOP skills to new heights! Happy coding! 🎓
