# Ecommerce Backend with Django API

Welcome to the Ecommerce backend project built with Django API! This project serves as the backend infrastructure for an ecommerce platform, providing the necessary endpoints and functionalities to support the frontend interface.

## Overview

This project utilizes Django to build a robust and scalable API for handling various ecommerce operations, including managing products, handling user authentication, and processing orders. It integrates seamlessly with the frontend built with React to deliver a complete ecommerce solution.

## Features

-   **RESTful API:** Implements a RESTful API architecture, providing endpoints for performing CRUD operations on resources such as products, users, and orders.
-   **Authentication:** Utilizes Django's authentication system to authenticate users and manage user sessions securely.
-   **Database Integration:** Integrates with a JSON file as databse to fetch data related to products, users, orders, and more.
-   **Django REST Framework:** Leverages Django REST Framework to streamline API development and facilitate serialization, validation, and authentication.

## Setup

To set up the project locally, follow these steps:

1. Clone the repository: `git clone [repository_url]`
2. Navigate to the project directory: `cd ecommerce-backend`
3. Install dependencies: `pip install -r requirements.txt`
4. Run migrations: `python manage.py migrate`
5. Start the development server: `python manage.py runserver`

Ensure that the frontend server built with React is running and accessible to enable full functionality of the ecommerce platform.

## Usage

Once the project is set up and running, you can access the Django API endpoints by sending HTTP requests to the provided URLs. Use tools such as Postman or curl to interact with the API and perform operations such as creating products, registering users, and processing orders.

## Contributing

Contributions are welcome! If you'd like to contribute to the development of this project, please follow these guidelines:

1. Fork the repository
2. Create a new branch for your feature or bug fix: `git checkout -b feature-name`
3. Commit your changes: `git commit -am 'Add new feature'`
4. Push to the branch: `git push origin feature-name`
5. Submit a pull request

## License

This project is licensed under the [MIT License](LICENSE), which means you are free to use, modify, and distribute the code for both personal and commercial purposes.

---

Feel free to reach out with any questions, feedback, or suggestions for improvement. Happy coding!
