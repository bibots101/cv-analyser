# FastAPI User Authentication

This is a simple FastAPI application demonstrating user registration, authentication, and role-based authorization.

## Features

- User registration
- Token-based authentication
- Role-based authorization

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/bibots101/cv-analyser.git
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the FastAPI application:

    ```bash
    uvicorn main:app --reload
    ```

2. Open `http://localhost:8000/docs` in your browser to access the Swagger UI and test the endpoints.

## Endpoints

- `POST /register`: Register a new user.
- `POST /token`: Get an access token by providing email and password.
- `GET /users/me`: Get user information along with roles.

## Contributing

Contributions are welcome! If you find any issues or want to add new features, feel free to open an issue or create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
