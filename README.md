# Fake Database API

The Fake Database API is a simulated API that provides a mock database with users, contacts, and messages. It is designed to assist developers in testing and prototyping applications that require database interactions without the need for a real production database.

## Features

- **User Management**: The API allows you to create, retrieve, update, and delete user records. Each user has a unique identifier, name, email, and other customizable fields.

- **Contact Management**: You can manage contacts associated with each user. Contacts have attributes such as name, email, phone number, and additional custom fields.

- **Message Handling**: The API enables you to send and receive messages between users. Messages contain information such as sender, recipient, timestamp, subject, and message content.

## Getting Started

To get started with the Fake Database API, follow these steps:

1. Clone the repository to your local development environment.

2. Install the required dependencies by running `npm install`.

3. Start the API server by running `npm start`.

4. Once the server is running, you can interact with the API using HTTP requests.

## API Endpoints

The Fake Database API provides the following endpoints:

- **User Endpoints**:
    - `GET /users`: Retrieve a list of all users.
    - `GET /users/:id`: Get details of a specific user.

- **Contact Endpoints**:
    - `GET /users/:userId/contacts`: Retrieve all contacts associated with a user.
    - `GET /users/:userId/contacts/:contactId`: Get details of a specific contact.

- **Message Endpoints**:
    - `GET /users/:userId/messages`: Retrieve all messages sent or received by a user.
    - `GET /users/:userId/messages/:messageId`: Get details of a specific message.

For detailed information on each endpoint, refer to the API documentation.

## Contributing

Contributions to the Fake Database API are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request to the repository.

## License

The Fake Database API is released under the [MIT License](https://opensource.org/licenses/MIT). You are free to use, modify, and distribute the code as per the terms of this license.

## Disclaimer

Please note that the Fake Database API is for testing and development purposes only. It does not provide real data persistence and should not be used in a production environment. Use at your own risk.
