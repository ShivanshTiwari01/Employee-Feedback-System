# Employees Feedback Management System

## Overview

The Employees Feedback Management System is designed to streamline the process of collecting and managing feedback within a corporate environment, such as Amazon. This system allows admins, such as HR managers, to assign reviews to different employees, and employees can share their feedback anonymously. 

## Features

- **Admin Capabilities:**
  - Add, remove, or update employee data.
  - Assign reviews to different employees.

- **Employee Capabilities:**
  - Provide anonymous feedback on other employees.

- **User Interface:**
  - Simple and clean UI built with EJS, CSS, and Bootstrap.
  - Self-explanatory and easy-to-navigate interface.

## Tech Stack

### Backend

- **Node.js**: JavaScript runtime built on Chrome's V8 JavaScript engine.
- **Express.js**: Web application framework for Node.js.
- **MongoDB**: NoSQL database for storing employee data and feedback.

### Frontend

- **EJS**: Embedded JavaScript templating.
- **CSS**: Cascading Style Sheets for styling the application.
- **Bootstrap**: CSS framework for developing responsive and mobile-first websites.

## Getting Started

### Prerequisites

- Node.js and npm installed on your local machine.
- MongoDB instance running (local or cloud).

### Installation

1. Clone the repository:
   
   git clone https://github.com/ShivanshTiwari01/employees-feedback-management.git
   
2. Navigate to the project directory:

  cd employees-feedback-management

3. Install the dependencies:

   npm install

### Configuration

1. Create a `.env` file in the root directory and add the following environment variables:
   ```env
   PORT=3000
   MONGODB_URI=mongodb://localhost:27017/employees-feedback

### Running the Application

1. Start the server:
   
   npm start

## Usage

- **Admin Actions:**
  - Navigate to the Admin Dashboard to add, update, or remove employee data.
  - Assign reviews to employees from the dashboard.

- **Employee Actions:**
  - Log in to the system.
  - Provide anonymous feedback for assigned peers.

## Contributing

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/your-feature-name`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature-name`).
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
