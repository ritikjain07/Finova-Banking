# **Finova - Banking**

> **Finova** is an upcoming finance management system designed to provide secure, easy-to-use tools for managing multiple bank accounts, tracking transactions, and transferring funds. Currently in development, **Finova** integrates with industry-leading financial APIs like **Plaid** for account linking and **Dwolla** for secure fund transfers.

## **Table of Contents**

1. [Overview](#overview)  
2. [Tech Stack](#tech-stack)  
3. [Current Features](#current-features)  
4. [Installation](#installation)  
5. [Contributing](#contributing)  
6. [Contact](#contact)

---

## **Overview**

### **About the Project**

![Finova - Banking](images/Screenshot%20(976).png)
**Finova - Banking** is a work-in-progress finance management system that allows users to link multiple bank accounts, view transaction history, and transfer funds securely. The platform will eventually offer a complete suite of features to help individuals and businesses manage their finances efficiently.

### **Project Status**
Currently, the project is in its initial setup phase. The backend and front-end architecture are being developed, and integration with key APIs like **Plaid** and **Dwolla** is underway. More features will be added progressively, and the system will be improved for performance and usability.

---

## **Tech Stack**

- **Frontend**: Next.js, TypeScript, React, TailwindCSS, Chart.js, ShadCN
- **Backend**: Appwrite (for authentication and backend services)
- **APIs**:
  - **Plaid**: For linking multiple bank accounts securely
  - **Dwolla**: For transferring funds to other bank accounts
- **Form Handling**: React Hook Form, Zod (for validation)

---

## **Current Features**

### 🔒 **Authentication** *(In Progress)*
- Secure SSR authentication with validation and authorization setup in progress.

### 🏦 **Connect Banks** *(In Progress)*
- Plaid integration for linking bank accounts is in progress.

### 📊 **Home Page** *(In Progress)*
- Basic home page layout is being developed. The page will show a general overview of user accounts, including balances and recent transactions.

### 🏦 **My Banks** *(Coming Soon)*
- Users will be able to view a list of connected banks along with account details.

### 📅 **Transaction History** *(Coming Soon)*
- Users will be able to view transaction history, filter by date, and paginate results.

### 💸 **Funds Transfer** *(Coming Soon)*
- Integration with Dwolla for transferring funds between accounts will be implemented soon.

### 📱 **Responsiveness** *(In Progress)*
- The front-end design is being built with responsiveness in mind, ensuring a seamless experience across all device sizes.

---

## **Installation**

### Prerequisites
- Node.js (version 14.x or later)
- Appwrite (configured for backend services)
- Plaid & Dwolla API keys (for bank linking and transfers)

### Steps to Install

1. Clone the repository:
    ```bash
    git clone https://github.com/ritikjain07/finova-banking.git
    ```

2. Navigate to the project directory:
    ```bash
    cd finova-banking
    ```

3. Install dependencies:
    ```bash
    npm install
    ```

4. Set up environment variables:
    - Create a `.env` file in the root directory and add the necessary keys:
    ```bash
    NEXT_PUBLIC_PLAID_CLIENT_ID=<your-plaid-client-id>
    NEXT_PUBLIC_PLAID_SECRET=<your-plaid-secret-key>
    DWOLLA_API_KEY=<your-dwolla-api-key>
    APPWRITE_PROJECT_ID=<your-appwrite-project-id>
    ```

5. Run the application:
    ```bash
    npm run dev
    ```

---

## **Contributing**

We welcome contributions to **Finova - Banking**! Here's how you can help:

1. Fork the repository.
2. Create a new branch for your feature (`git checkout -b feature/your-feature-name`).
3. Implement your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to your branch (`git push origin feature/your-feature-name`).
6. Submit a pull request.

---

## **Contact**

For questions or suggestions, feel free to reach out:

- **Email**: [ritikjain4560@gmail.com](mailto:ritikjain4560@gmail.com)
- **GitHub**: [github.com/ritikjain07](https://github.com/ritikjain07)

---
