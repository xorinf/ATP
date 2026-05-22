# Week 7: Production-grade MERN Applications

This folder contains a production-ready MERN stack blog application featuring user registration, author posts, article updates, image uploads, state management, and role-based access.

## Projects

### 1. MERN Blog
- `mernBlog/`:
  - `backend/`: Server configurations using Express and Mongoose, containing JWT verification middleware, Cloudinary integration for image storage, user/author API routes, and schema models for `Article` and `User`.
  - `frontend/`: Single Page Application (SPA) built using React and styled with Tailwind CSS, utilizing a global authorization store (`authStore`), role validation (`ProtectedRoute`, `Unauthorized`), and CRUD routes for article interaction.
