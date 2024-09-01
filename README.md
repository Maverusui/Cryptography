# Cryptography
# Cryptography Tool

This is a full-stack application built using Spring Boot and React that allows users to encrypt and decrypt text using different cryptographic algorithms. The application currently supports the following algorithms:

- Caesar Cipher
- Hill Cipher
- Vigenère Cipher
- Columnar Cipher
- Morse Code

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [API Endpoints](#api-endpoints)
- [License](#license)

## Installation

### Backend (Spring Boot)

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/cryptography-tool.git
   cd cryptography-tool

2. Navigate to the backend directory:

bash
Copy code
cd backend
Build and run the Spring Boot application:

bash
Copy code
./mvnw spring-boot:run
The backend will run on http://localhost:8080.

3. Frontend (React)
Navigate to the frontend directory:

bash
Copy code
cd frontend
Install the dependencies:

bash
Copy code
npm install
Start the React application:

bash
Copy code
npm start
The frontend will run on http://localhost:3000.

4. Usage
   1. Open the React application in your browser: http://localhost:3000.
   2. Enter the text you want to encrypt or decrypt.
   3. Select the algorithm and provide the required key.
   4. Click on "Encrypt" or "Decrypt" to get the result.
