
# Blockchain Certificate Management API

This project provides a simple API to interact with a blockchain to issue and verify certificates. The API is built using Node.js and exposes two main endpoints:

## Endpoints

### 1. Issue a Certificate

- **URL:** `POST /issue-certificate`
- **Description:** Adds a new certificate to the blockchain by issuing a certificate.

### 2. Verify a Certificate

- **URL:** `POST /verify-certificate`
- **Description:** Verifies if a certificate with a given `certificateId` exists on the blockchain.

## Setup Instructions

1. Clone the repository:

   ```bash
   git clone <repository_url>
   cd <repository_directory>
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the server:

   ```bash
   npm start
   ```

4. Access the API:

   - Issue a certificate: `POST http://localhost:3000/issue-certificate`
   - Verify a certificate: `POST http://localhost:3000/verify-certificate`

## Technologies Used

- **Node.js** - Backend framework.
- **Blockchain** - To store and verify certificates.
- **Express.js** - Web framework for building APIs.

## License

This project is licensed under the MIT License.