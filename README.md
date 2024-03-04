# Express and MongoDB Blog App

This is a simple Express.js application with MongoDB integration for creating and fetching authors and blogs.

## Getting Started

1. Clone the repository:

    ```bash
    git clone <repository-url>
    ```

2. Install dependencies:

    ```bash
    npm install
    ```

3. Set up MongoDB:

    - Make sure you have a MongoDB Atlas account or a local MongoDB server running.
    - Update the MongoDB connection string in `app.js` with your database connection details.

4. Run the application:

    ```bash
    node app.js
    ```

    The server will start on [http://localhost:3000](http://localhost:3000) or the port specified in your environment variable.

## Endpoints

### Create a new author

- **POST /author**

  Example Request Body:

  ```json
  {
    "name": "John Doe",
    "email": "john.doe@example.com"
  }
  ```

### Create a new blog

- **POST /blog**

  Example Request Body:

  ```json
  {
    "title": "Sample Blog",
    "content": "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam eget..."
  }
  ```

### Get all authors

- **GET /authors**

### Get all blogs

- **GET /blogs**

## Dependencies

- express
- mongoose
- body-parser

## Configuration

- The MongoDB connection string is configured in `app.js`. Make sure to update it with your database connection details.

## Contributing

Feel free to contribute to this project by submitting pull requests or reporting issues.

## License

This project is licensed under the [MIT License](LICENSE).
