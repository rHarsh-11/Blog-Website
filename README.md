# Simple Blog Application

A simple blog application built with Node.js and Express for the backend, and EJS and CSS for the frontend. This project showcases the use of a Node JS with Express JS for hosting HTTP servers and manual API creation for CRUD operations. 

**Note:** Currently, the project does not include a database. Future improvements will integrate a database for persistent data storage.

## Features

- User-friendly interface to create, read, update, and delete blog posts.
- Dynamic rendering of blog posts using EJS templates.
- CSS styling for a clean and responsive design.

## Tech Stack

- **Backend:** Node.js, Express
- **Frontend:** EJS, CSS
- **Database:** [Not yet integrated; planned for future improvements]

## Directory Structure

```
Blog-Website/
├── public/styles         # Static files (CSS)
├── views/                # EJS templates
├── index.js              # Entry point of the application
└── server.js             # API with CRUD operations
```

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/rHarsh-11/Blog-Website.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Blog-Website
   ```

3. Install the dependencies:
   ```bash
   npm install
   ```

4. Start the frontend server:
   ```bash
   node index.js
   ```
   The frontend will be hosted at `http://localhost:3000`.

5. Open a new terminal and run the backend server:
   ```bash
   node server.js
   ```
   The backend API will be hosted at `http://localhost:4000`.

## API Endpoints

- `GET /api/posts` - Retrieve all blog posts
- `GET /api/posts/:id` - Retrieve a specific blog post
- `POST /api/posts` - Create a new blog post
- `PUT /api/posts/:id` - Update an existing blog post
- `DELETE /api/posts/:id` - Delete a blog post

## Future Improvements

- **Database Integration:** Add a database (e.g., MongoDB, MySQL) for persistent data storage.
- **Authentication:** Implement user authentication for secured access to blog management.
- **Search and Filtering:** Add features for searching and filtering blog posts.


## Contributing

Feel free to submit a pull request or open an issue for any suggestions or improvements!
