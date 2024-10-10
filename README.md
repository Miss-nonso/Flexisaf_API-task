

# Flexisaf Daily Blog

## Overview
This project is a simple blog platform built using React, demonstrating CRUD (Create, Read, Update, Delete) operations with the JSONPlaceholder API. The application allows users to:
- View a list of blog posts (GET)
- Add new posts (POST)
- Edit existing posts (PUT)
- Delete posts (DELETE)

## Features
- **GET**: Fetch and display a list of posts from the JSONPlaceholder API.
- **POST**: Add new blog posts using the provided form.
- **PUT**: Update an existing blog post by editing its title and body.
- **DELETE**: Remove a blog post from the list.

## Technologies Used
- **React**: Component-based UI library for building the front end.
- **Fetch API**: Used for making asynchronous requests to interact with the API (GET, POST, PUT, DELETE).
- **CSS**: For professional and responsive styling.
- **JSONPlaceholder API**: A free API used for simulating blog post data.

## Installation and Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/react-blog-platform.git
   ```
2. Navigate to the project directory:
   ```bash
   cd react-blog-platform
   ```
3. Install the dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm start
   ```

The application will run at `http://localhost:3000`.

## Usage
- On the homepage, you will see a list of blog posts fetched from the API.
- To add a post, use the form at the top. Fill in the post title and body, then click "Add Post."
- Each post has an "Edit" and "Delete" button.
  - **Edit**: Modify the title or body of the post and submit the changes.
  - **Delete**: Remove the post from the list.

## Future Improvements
- Add user authentication for more secure API operations.
- Implement pagination for better handling of large datasets.
- Integrate a backend database for permanent storage of blog posts.

---


