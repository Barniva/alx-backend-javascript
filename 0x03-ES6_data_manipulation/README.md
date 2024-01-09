# ES6 Data Manipulation

This repository contains a collection of JavaScript functions and data structures for data manipulation using ES6 features. The functions and data structures provided in this repository are designed to handle various operations on student data. Each function is implemented in a separate file with a corresponding test file for easy usage and testing.

## Functions

### 0. Basic List of Objects

**Function Name:** `getListStudents`

**Description:** This function returns an array of student objects.

**File:** [getListStudents.js](getListStudents.js)

**Test File:** [getListStudents.test.js](getListStudents.test.js)

### 1. More Mapping

**Function Name:** `getListStudentIds`

**Description:** This function takes a list of student objects and returns an array of student ids.

**File:** [getListStudentIds.js](getListStudentIds.js)

**Test File:** [getListStudentIds.test.js](getListStudentIds.test.js)

### 2. Filter

**Function Name:** `getStudentsByLocation`

**Description:** This function filters students by city and returns an array of matching student objects.

**File:** [getStudentsByLocation.js](getStudentsByLocation.js)

**Test File:** [getStudentsByLocation.test.js](getStudentsByLocation.test.js)

### 3. Reduce

**Function Name:** `getStudentIdsSum`

**Description:** This function calculates the sum of all student ids and returns the result.

**File:** [getStudentIdsSum.js](getStudentIdsSum.js)

**Test File:** [getStudentIdsSum.test.js](getStudentIdsSum.test.js)

### 4. Combine

**Function Name:** `updateStudentGradeByCity`

**Description:** This function updates student grades for a specific city and returns the updated student objects.

**File:** [updateStudentGradeByCity.js](updateStudentGradeByCity.js)

**Test File:** [updateStudentGradeByCity.test.js](updateStudentGradeByCity.test.js)

### 5. Typed Arrays

**Function Name:** `createInt8TypedArray`

**Description:** This function creates a new ArrayBuffer for handling Int8 values and returns the typed array.

**File:** [createInt8TypedArray.js](createInt8TypedArray.js)

**Test File:** [createInt8TypedArray.test.js](createInt8TypedArray.test.js)

### 6. Set Data Structure

**Function Name:** `setFromArray`

**Description:** This function converts an array into a Set data structure and returns the resulting Set.

**File:** [setFromArray.js](setFromArray.js)

**Test File:** [setFromArray.test.js](setFromArray.test.js)

### 7. More Set Data Structure

**Function Name:** `hasValuesFromArray`

**Description:** This function checks if all elements in an array exist within a Set data structure and returns a boolean value.

**File:** [hasValuesFromArray.js](hasValuesFromArray.js)

**Test File:** [hasValuesFromArray.test.js](hasValuesFromArray.test.js)

### 8. Clean Set

**Function Name:** `cleanSet`

**Description:** This function gets a string of set values starting with a specific string and returns the resulting string.

**File:** [cleanSet.js](cleanSet.js)

**Test File:** [cleanSet.test.js](cleanSet.test.js)

### 9. Map Data Structure

**Function Name:** `groceriesList`

**Description:** This function gets a map of groceries with items and quantities and returns the resulting Map.

**File:** [groceriesList.js](groceriesList.js)

**Test File:** [groceriesList.test.js](groceriesList.test.js)

### 10. More Map Data Structure

**Function Name:** `updateUniqueItems`

**Description:** This function updates quantities for items with an initial quantity of 1 in a map of groceries and returns the updated Map.

**File:** [updateUniqueItems.js](updateUniqueItems.js)

**Test File:** [updateUniqueItems.test.js](updateUniqueItems.test.js)

## Data Structure

### 11. Weak Link Data Structure (Advanced)

**Variable Name:** `weakMap`

**Description:** This is a constant instance of WeakMap named `weakMap`. It is used to track API endpoint calls.

**File:** [queryAPI.js](queryAPI.js)

## Usage

To use any of the functions or data structures in this repository, follow the steps below:

1. Clone this repository to your local machine:

```bash
git clone <repository-url>
```

2. Navigate to the cloned repository directory:

```bash
cd alx-backend-javascript
```

3. Install the dependencies:

```bash
npm install
```

4. Explore the files in the repository and choose the function or data structure you want to use.

5. Import the desired function or data structure into your JavaScript file:

```javascript
import { getListStudents } from './getListStudents.js';
```

6. Use the imported function or data structure in your code:

```javascript
```javascript
import { getListStudents } from './getListStudents.js';

const students = getListStudents();
console.log(students);
```

7. Run your JavaScript file using Node.js or in a browser environment to see the result.

Feel free to explore each file for detailed usage and implementation.
