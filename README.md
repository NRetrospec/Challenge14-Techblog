# Crowd Funding

## Description
Crowd Funding is a web application that allows users to create and fund projects. Users can log in, create new projects, and view existing projects.

## Features
- User authentication (login/signup)
- Project creation and funding
- View projects and their details

## Installation Instructions
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd crowd-funding
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Set up the database and run migrations:
   ```bash
   npm run seed
   ```
5. Start the application:
   ```bash
   npm start
   ```

## Usage
Access the application at `http://localhost:3001`.

## API Endpoints
### User Routes
- **POST /api/users**: Create a new user.
- **POST /api/users/login**: Log in a user.
- **POST /api/users/logout**: Log out a user.

### Project Routes
- **POST /api/projects**: Create a new project.
- **DELETE /api/projects/:id**: Delete a project by ID.
- **PUT /api/projects/:id**: Update a project by ID.

## Contributing
Contributions are welcome! Please submit a pull request or open an issue for any suggestions.

## License
This project is licensed under the MIT License.
