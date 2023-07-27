# ES6 Basics Repository

This repository contains a collection of JavaScript functions focusing on ES6 (ECMAScript 2015) concepts. The functions cover various topics, from variable declarations to object properties and iteration. Below, you'll find a brief description of each function along with execution examples.

## Table of Contents

1. [TaskFirst and TaskNext](#taskfirst-and-tasknext)
2. [TaskBlock](#taskblock)
3. [GetNeighborhoodsList](#getneighborhoodslist)
4. [GetSumOfHoods](#getsumofhoods)
5. [ReturnHowManyArguments](#returnhowmanyarguments)
6. [ConcatArrays](#concatarrays)
7. [GetSanFranciscoDescription](#getsanfranciscodescription)
8. [GetBudgetObject](#getbudgetobject)
9. [GetBudgetForCurrentYear](#getbudgetforcurrentyear)
10. [GetFullBudgetObject](#getfullbudgetobject)
11. [AppendToEachArrayValue](#appendtoeacharrayvalue)
12. [CreateEmployeesObject](#createemployeesobject)
13. [CreateReportObject](#createreportobject)

## TaskFirst and TaskNext

**File: 0-constants.js**

The `taskFirst` and `taskNext` functions are designed to demonstrate the use of `const` and `let` variable declarations in ES6. `taskFirst` uses `const`, while `taskNext` uses `let`.

**Execution Example:**

```bash
$ npm run dev 0-main.js
I prefer const when I can. But sometimes let is okay
```

## TaskBlock

**File: 1-block-scoped.js**

The `taskBlock` function showcases the use of block-scoped variables in ES6. It avoids overwriting variables inside the conditional block.

**Execution Example:**

```bash
$ npm run dev 1-main.js
[false, true]
[false, true]
```

## GetNeighborhoodsList

**File: 2-arrow.js**

The `getNeighborhoodsList` function is rewritten to use ES6's arrow function syntax.

**Execution Example:**

```bash
$ npm run dev 2-main.js
['SOMA', 'Union Square', 'Noe Valley']
```

## GetSumOfHoods

**File: 3-default-parameter.js**

The `getSumOfHoods` function uses default parameter values for optional parameters, simplifying the code.

**Execution Example:**

```bash
$ npm run dev 3-main.js
142
56
41
```

## ReturnHowManyArguments

**File: 4-rest-parameter.js**

The `returnHowManyArguments` function uses the rest parameter syntax to return the number of arguments passed to it.

**Execution Example:**

```bash
$ npm run dev 4-main.js
1
4
```

## ConcatArrays

**File: 5-spread-operator.js**

The `concatArrays` function concatenates two arrays and each character of a string using the spread syntax.

**Execution Example:**

```bash
$ npm run dev 5-main.js
['a', 'b', 'c', 'd', 'H', 'e', 'l', 'l', 'o']
```

## GetSanFranciscoDescription

**File: 6-string-interpolation.js**

The `getSanFranciscoDescription` function uses template literals for string interpolation, making it easier to substitute variables.

**Execution Example:**

```bash
$ npm run dev 6-main.js
As of 2017, it was the seventh-highest income county in the United States, with a per capita personal income of $119,868. As of 2015, San Francisco proper had a GDP of $154.2 billion, and a GDP per capita of $178,479.
```

## GetBudgetObject

**File: 7-getBudgetObject.js**

The `getBudgetObject` function uses object property value shorthand syntax to simplify object property assignments.

**Execution Example:**

```bash
$ npm run dev 7-main.js
{ income: 400, gdp: 700, capita: 900 }
```

## GetBudgetForCurrentYear

**File: 8-getBudgetCurrentYear.js**

The `getBudgetForCurrentYear` function uses computed property names in ES6 to dynamically set object property keys.

**Execution Example:**

```bash
$ npm run dev 8-main.js
{ 'income-2021': 2100, 'gdp-2021': 5200, 'capita-2021': 1090 }
```

## GetFullBudgetObject

**File: 9-getFullBudget.js**

The `getFullBudgetObject` function uses ES6 method properties to add methods to an object.

**Execution Example:**

```bash
$ npm run dev 9-main.js
$20
20 euros
```

## AppendToEachArrayValue

**File: 10-loops.js**

The `appendToEachArrayValue` function uses the `for...of` loop in ES6 to modify array elements.

**Execution Example:**

```bash
$ npm run dev 10-main.js
['correctly-appended', 'correctly-fixed', 'correctly-displayed']
```

## CreateEmployeesObject

**File: 11-createEmployeesObject.js**

The `createEmployeesObject` function creates an object containing departments and their corresponding employees.

**Execution Example:**

```bash
$ npm run dev 11-main.js
{ Software: ['Bob', 'Sylvie'] }
```

## CreateReportObject

**File: 12-createReportObject.js**

The `createReportObject` function receives the output of the `createEmployeesObject` function and returns an object containing all employees and a method to get the number of departments.

**Execution Example:**

```bash
$ npm run dev 12-main.js
{ engineering: ['Bob', 'Jane'], marketing: ['Sylvie'] }
2
```

Feel free to explore the functions and learn more about ES6 concepts with this repository! If you have any questions or suggestions, please don't hesitate to reach out.

**Note:** The examples provided in this README use the `npm run dev` command to execute the functions. Make sure you have NodeJS 12.11.x and the required dependencies installed before running the functions.