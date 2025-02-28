# MySQL Test ENV

## Description
This is a test environment for MySQL and PHPMyAdmin. It is based on the official MySQL Docker image and the official PHPMyAdmin Docker image. The MySQL image is configured to create a database and a user on startup. The PHPMyAdmin image is configured to connect to the MySQL database.

## Usage
1. Clone the repository
2. Copy the `.env.example` file to `.env` and adjust the values
3. Run `docker-compose up -d`
4. Open `http://localhost:PORT` in your browser