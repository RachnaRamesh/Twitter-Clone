# Twitter Clone

A full-stack Twitter clone application built using modern web development technologies. This application replicates the core features of Twitter, such as user authentication, posting tweets, following users, and viewing a feed.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features
- **User Authentication**: Sign up, log in, and log out functionality.
- **Tweet Management**: Post, edit, delete tweets.
- **User Interaction**: Follow/unfollow users and view their tweets.
- **Feed**: See tweets from the users you follow.

## Technologies Used

### Frontend
- React.js
- HTML/CSS
- JavaScript

### Backend
- Spring Boot
- Java
- REST API

### Database
- MySQL

## Setup Instructions

### Prerequisites
- Java Development Kit (JDK) 11 or higher
- Node.js and npm
- MySQL
- Git

### Installation

#### Backend
1. Clone the repository:
   ```bash
   git clone https://github.com/RachnaRamesh/Twitter-Clone.git
   cd Twitter-Clone/backend
   ```

2. Create a MySQL database named `twitter_clone`.

3. Update the database credentials in `application.properties`:
   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/twitter_clone
   spring.datasource.username=your_username
   spring.datasource.password=your_password
   ```

4. Build and run the backend:
   ```bash
   ./mvnw spring-boot:run
   ```

#### Frontend
1. Navigate to the frontend directory:
   ```bash
   cd ../frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm start
   ```

### Usage
- Access the application in your browser at `http://localhost:3000`.
- Sign up or log in to start tweeting and interacting with other users.

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch-name`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch-name`).
5. Open a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.


