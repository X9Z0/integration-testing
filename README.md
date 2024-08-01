# Integration Testing Project

This project demonstrates integration testing on the backend. Follow the steps below to set up and run the tests.

## Prerequisites

- Docker must be installed on your system.
- Node.js must be installed on your system.

## Setup

1. Clone the project repository:

   ```bash
   git clone https://github.com/X9Z0/integration-testing
   ```

2. Navigate to the project directory:

   ```bash
   cd integration-testing
   ```

3. Install all dependencies:

   ```bash
   npm install
   ```

4. Replace the `.env.example` file with `.env`:
   ```bash
   cp .env.example .env
   ```

## Running the Integration Tests

1. Ensure Docker is running on your system.
2. Run the integration tests using the provided script:
   ```bash
   ./scripts/run-integration.sh
   ```

This script will start the Docker containers using `docker-compose` and run the database on Docker, then execute the integration tests.

## Additional Information

- If you encounter any issues, make sure that Docker and Node.js are correctly installed and configured on your system.
- You can refer to the individual test files and the `docker-compose.yml` for more details on the setup and configuration.
