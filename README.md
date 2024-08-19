# Auto API documentation Generator

Effortlessly automate your API documentation with the Node.js Auto Swagger Doc Generator. This tool integrates directly with `swagger-autogen`, removing the need for manual documentation tasks. With automatic generation, your API documentation stays current and accurately reflects your codebase as it evolves.

### Swagger Documentation Endpoint

You can access the Swagger documentation at: [http://localhost:3000/api-docs/](http://localhost:3000/api-docs/)

### Swagger-Autogen

For detailed information about `swagger-autogen`, please refer to the official documentation here: [swagger-autogen](https://swagger-autogen.github.io/docs)

### API Documentation Overview

The API documentation is automatically generated using the `swagger-autogen` module, which dynamically generates documentation for all available endpoints. Check the above Swagger URL for a comprehensive list of all available routes.

#### API Routes

#### Authentication Routes

- **Register**: `https://localhost:3000/auth/signup`
- **Login**: `https://localhost:3000/auth/signin`

#### User Management Routes

- **Remove User**: `http://localhost:3000/users/{user}`
- **Get User Details**: `http://localhost:3000/users/{user}`
- **Edit User**: `http://localhost:3000/users/{user}`
- **List All Users**: `http://localhost:3000/users/`
