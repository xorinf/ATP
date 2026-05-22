# Week 4: Express REST APIs & HTML/CSS Basics

This week transitions between backend API design and frontend UI basics. It covers building advanced APIs and styling websites with semantic HTML and CSS.

## Contents

### 1. Express REST API
- `expressRestApi/`: An Express.js backend for managing articles:
  - `server.js`: Server setup and database configurations.
  - `APIs/`:
    - `UserAPI.js`: User endpoints.
    - `AuthorAPI.js`: Author specific routes.
    - `AdminAPI.js`: Administration endpoints.
    - `CommonAPI.js`: Shared public APIs.
  - `middlewares/verifyToken.js`: Security JWT check.
  - `models/`: Mongoose models for `ArticleModel` and `UserModel`.
  - `ping/`: HTTP validation files.

### 2. Frontend Basics
- `htmlCssBasics/`: Simple HTML layout and formatting practice:
  - `base/`:
    - `assignment1.html`, `assignment2.html`, `assignment3.html`, `assignment4.html`, `index.html`: Web page templates.
  - `styles/mainStyles.css`: Base stylesheet containing layouts, spacing, and page formatting.
  - `resource/`: Image assets.