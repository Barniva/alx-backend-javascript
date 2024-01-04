# ES6 Classes

This repository contains JavaScript code examples that demonstrate various concepts of ES6 classes.

## Tasks

### 0. ClassRoom

Implement a class named `ClassRoom` that accepts one attribute named `maxStudentsSize` and assigns it to `_maxStudentsSize`.

- File: [0-classroom.js](./0x02-ES6_classes/0-classroom.js)
- Execution: `npm run dev 0-main.js`

### 1. Make ClassRooms

Implement a function named `initializeRooms` that returns an array of 3 `ClassRoom` objects with the sizes 19, 20, and 34.

- File: [1-make_classrooms.js](./0x02-ES6_classes/1-make_classrooms.js)
- Execution: `npm run dev 1-main.js`

### 2. HolbertonCourse

Implement a class named `HolbertonCourse` with constructor attributes `name`, `length`, and `students`. Implement getters and setters for each attribute.

- File: [2-hbtn_course.js](./0x02-ES6_classes/2-hbtn_course.js)
- Execution: `npm run dev 2-main.js`

### 3. Currency

Implement a class named `Currency` with constructor attributes `code` and `name`. Implement getters and setters for each attribute. Implement a method named `displayFullCurrency` that returns the attributes in the format `name (code)`.

- File: [3-currency.js](./0x02-ES6_classes/3-currency.js)
- Execution: `npm run dev 3-main.js`

### 4. Pricing

Implement a class named `Pricing` with constructor attributes `amount` and `currency`. Implement getters and setters for each attribute. Implement a method named `displayFullPrice` that returns the attributes in the format `amount currency_name (currency_code)`. Implement a static method named `convertPrice` that accepts `amount` and `conversionRate` and returns the converted amount.

- File: [4-pricing.js](./0x02-ES6_classes/4-pricing.js)
- Execution: `npm run dev 4-main.js`

### 5. Building

Implement an abstract class named `Building` with constructor attribute `sqft`. Implement a getter for the attribute. Implement a method named `evacuationWarningMessage` and throw an error if the method is not overridden by a subclass.

- File: [5-building.js](./0x02-ES6_classes/5-building.js)
- Execution: `npm run dev 5-main.js`

### 6. SkyHighBuilding

Implement a class named `SkyHighBuilding` that extends `Building` with constructor attributes `sqft` and `floors`. Implement getters for each attribute. Override the method `evacuationWarningMessage` and return the string `Evacuate slowly the NUMBER_OF_FLOORS floors`.

- File: [6-sky_high.js](./0x02-ES6_classes/6-sky_high.js)
- Execution: `npm run dev 6-main.js`

### 7. Airport

Implement a class named `Airport` with constructor attributes `name` and `code`. Implement getters for each attribute. Override the `toString` method to return the airport code.

- File: [7-airport.js](./0x02-ES6_classes/7-airport.js)
- Execution: `npm run dev 7-main.js`

### 8. Holberton Class

Implement a class named `HolbertonClass` with constructor attributes `size` and `location`. Implement getters for each attribute. When the class is cast into a Number, it should return the size. When the class is cast into a String, it should return the location.

- File: [8-hbtn_class.js](./0x02-ES6_classes/8-hbtn_class.js)
- Execution: `npm run dev 8-main.js`

### 9. Hoisting

Fix the code and make it work.

- File: [9-hoisting.js](./0x02-ES6_classes/9-hoisting.js)
- Execution: `npm run dev 9-main.js`

### 10. Car

Implement a class named `Car` with constructor attributes `brand`, `motor`, and `color`. Implement getters for each attribute. Add a method named `cloneCar` that returns a new object of the class.

- File: [10-car.js](./0x02-ES6_classes/10-car.js)
- Execution: `npm run dev 10-main.js`

### 100. EVCar

Implement a class named `EVCar` that extends `Car` with constructor attributes `brand`, `motor`, `color`, and `range`. Implement getters for each attribute. When `cloneCar` is called on an `EVCar` object, the object returned should be an instance of `Car` instead of `EVCar`.

- File: [100-evcar.js](./0x02-ES6_classes/100-evcar.js)
- Execution: `npm run dev 100-main.js`

