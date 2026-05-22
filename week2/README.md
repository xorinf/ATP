# Week 2: Advanced Array Methods, ES Modules, OOP & Express Basics

This folder contains assignments from Week 2 covering advanced array operations, Object-Oriented Programming (OOP) concepts, Javascript Modules, Object Copying (Shallow vs Deep Copy), and introduction to Node.js backend development with Express.

## Key Topics & Assignments

### 1. Array Iterators & Methods
- `arrayMethods1.js`: Practice with `filter`, `map`, `reduce`, `find`, and `findIndex` on flat arrays.
- `arrayMethods2.js`: More advanced practice with array methods on arrays of complex objects (e.g., shopping cart, student list, payroll, movie list, transaction logs).

### 2. JavaScript ES Modules
- `ecommerceModules/`: A modular E-commerce script exploring ES Modules:
  - `product.js`: Product management, stock verification, and search.
  - `cart.js`: Cart operations (add, remove, update quantities, compute total).
  - `discount.js`: Coupon discount validation.
  - `payment.js`: Order processing and stock deduction.
  - `app.js`: Main test entrypoint.
- `taskModules/`: A modular ToDo application structure using ES Modules:
  - `validator.js`: Title, priority, and date validation.
  - `task.js`: Task addition and compilation.
  - `app.js`: Main testing script.

### 3. JavaScript Classes & Memory Copying
- `classBook.js`: OOP practice implementing a `Book` class with borrow/return status tracking.
- `spreadArray.js`: Array copying and extension using the spread operator (`...`).
- `spreadObject.js`: Object copying and property extension.
- `shallowCopy.js`: Demonstrates shallow cloning side-effects when mutating nested objects.
- `deepCopy.js`: Demonstrates deep copying using `structuredClone()`.

### 4. Basic REST API Server
- `expressCrudServer/`: An Express.js backend server with basic CRUD APIs for users and products:
  - `server.js`: Standard REST APIs.
  - `apiRequests.http`: REST client testing file.
  - `package.json`: Dependency manifests.
