# Week 3: Express Router, Middleware, MongoDB & Authentication

This week focuses on backend architecture scaling, using Express Router to organize routes, implementing global and route-level middlewares, connecting to MongoDB with Mongoose, schema validation, and secure authentication using JSON Web Tokens (JWT) and HttpOnly cookies.

## Contents

### 1. Express Router & Middleware
- `expressRouterApi/`:
  - `server.js`: Sets up Express, mounts routers, and defines logging / custom middlewares.
  - `API/UserAPI.js`: User router handling REST endpoints for managing users.
  - `API/ProductAPI.js`: Product router handling REST endpoints for managing products.
  - `fahh.http`: HTTP test suite for the router-based endpoints.

### 2. MongoDB Basics
- `mongoDbQuickstart.md`: Reference documentation for standard MongoDB CRUD operations, operators (`$set`, `$unset`, `$push`, `$addToSet`), and collections.

### 3. Comprehensive Database & Auth Backend
- `mongoDbAuthBackend/`: Complete Node.js/Mongoose REST API with security features:
  - `server.js`: Database connection, server setup, and global mongoose error handlers.
  - `models/UserModel.js`: User Mongoose schema enforcing validations (e.g., username length, unique email).
  - `models/ProductModel.js`: Product Mongoose schema with price range validation.
  - `middleware/verifyToken.js`: JWT token verification middleware.
  - `routes/UserApp.js`: Router handling user CRUD, password hashing via bcrypt, and login JWT cookie generation.
  - `routes/ProductAPI.js`: Router handling product CRUD (with validation).
  - `fahh.http`: Auth testing HTTP client suite.
