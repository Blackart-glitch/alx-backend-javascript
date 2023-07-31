👋 Hey there! 🎉

Sure thing! Let me provide more details about each function, how it works, and its requirements as specified in the text:

📚 **0. Basic list of objects**:
- Filename: `0-get_list_students.js`
- Function Details: `getListStudents` returns an array of student objects with three attributes: `id` (Number), `firstName` (String), and `location` (String).
- Requirements: None specified in the text.

📚 **1. More mapping**:
- Filename: `1-get_list_student_ids.js`
- Function Details: `getListStudentIds` takes an array of student objects and returns an array of their IDs. 🆔
- Requirements: The argument must be an array; otherwise, an empty array is returned.

📚 **2. Filter**:
- Filename: `2-get_students_by_loc.js`
- Function Details: `getStudentsByLocation` filters students based on a specific city, returning an array of student objects located there. 🏙️
- Requirements: The function takes two parameters: the array of students and the city (string).

📚 **3. Reduce**:
- Filename: `3-get_ids_sum.js`
- Function Details: `getStudentIdsSum` calculates the sum of all student IDs in the list. 🔢
- Requirements: The function takes the array of students as a parameter.

📚 **4. Combine**:
- Filename: `4-update_grade_by_city.js`
- Function Details: `updateStudentGradeByCity` updates student grades based on a specific city and new grades provided as an array of objects. 📝
- Requirements: The function takes three parameters: the array of students, the city (string), and an array of grade objects. Each grade object has a `studentId` (Number) and a `grade` (Number).

📚 **5. Typed Arrays**:
- Filename: `5-typed_arrays.js`
- Function Details: `createInt8TypedArray` creates a new ArrayBuffer with an Int8 value at a given position. 🧰
- Requirements: The function takes three parameters: `length` (Number) of the array buffer, `position` (Number) to set the value, and `value` (Number) to set at the position. If the position is outside the range, an error "Position outside range" is thrown.

📚 **6. Set data structure**:
- Filename: `6-set.js`
- Function Details: `setFromArray` creates a Set from an array. ✨
- Requirements: The function takes one parameter, which is an array (of any kind of element).

📚 **7. More set data structure**:
- Filename: `7-has_array_values.js`
- Function Details: `hasValuesFromArray` checks if all elements in an array exist within a Set. ✔️
- Requirements: The function takes two parameters: a set (Set) and an array (Array).

📚 **8. Clean set**:
- Filename: `8-clean_set.js`
- Function Details: `cleanSet` returns a string of Set values starting with a specific string, separated by dashes. 🎯
- Requirements: The function takes two parameters: a set (Set) and a `startString` (String).

📚 **9. Map data structure**:
- Filename: `9-groceries_list.js`
- Function Details: `groceriesList` creates a Map of groceries with items and quantities. 🛒
- Requirements: None specified in the text.

📚 **10. More map data structure**:
- Filename: `10-update_uniq_items.js`
- Function Details: `updateUniqueItems` updates the quantities of specific items in a Map. 🔃
- Requirements: The function takes one parameter, which is a Map. If the argument is not a Map, the error "Cannot process" is thrown.

Remember, before running these functions, make sure you have NodeJS version 12.11.x installed and run `npm install` in the project directory to install the necessary dependencies (Jest, Babel, and ESLint).

Feel free to explore these functions and have fun coding! If you have any questions or need further assistance, don't hesitate to ask! 💬🚀
