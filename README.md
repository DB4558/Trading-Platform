# Trading Platform

## Overview
This project is a Trading Platform built using React.js for the frontend and Spring Boot for the backend. The platform integrates Stripe for payment processing and offers a range of features including an AI chatbot, cryptocurrency trading, wallet functionalities, and enhanced security with JWT and two-factor authentication.

## Features
- **AI Chatbot**: Ask crypto-related questions (e.g., Bitcoin value) via the integrated Gemini API and Coingecko API.
- **Cryptocurrency Trading**: Buy and sell cryptocurrencies.
- **Portfolio Mangement** :Keep tarck of the crypto holdings
- **Wallet Features**:
  - Wallet-to-wallet transfers.
  - Bank withdrawals.
  - Adding balance to the wallet.
- **Security**:
  - JWT security.
  - Two-factor authentication.

## Technologies Used
- **Frontend**: React.js
- **Backend**: Spring Boot
- **Payment Gateway**: Stripe
- **API Integration**: Gemini API
- **Security**: JWT, Two-Factor Authentication

## Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/DB4558/trading-platform.git
   cd trading-platform
2. **Configure the database in src/main/resources/application.properties:**

   ```bash

      spring.datasource.url=jdbc:mysql://localhost:3306/backend-springboot
      spring.datasource.username=root
      spring.datasource.password=yourpassword

3. **Build and run the backend:**

      ```bash

          mvn clean install
          mvn spring-boot:run

4. **Frontend Setup**

    Clone the repository:

    ```bash

      git clone https://github.com/DB4558/frontend-react.git
      cd frontend-react

5.**Install dependencies and run the frontend:**
      ```bash
    
           npm install
           npm start

6.**Usage**

    Open the browser and navigate to http://localhost:3000.
   

       npm install
       npm start
