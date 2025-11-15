# MSSQL Developer Database with Docker

## Quick Start

1. Start the database:
   ```bash
   docker-compose up -d
   ```

2. Connect to the database:
   - **Host:** localhost
   - **Port:** 1433
   - **Username:** sa
   - **Password:** YourStrong@Passw0rd

3. Stop the database:
   ```bash
   docker-compose down
   ```

## Configuration

- **Edition:** Developer (free for development)
- **Data persistence:** Enabled via Docker volume
- **Default password:** Change in `.env` file

## Connection String Example
```
Server=localhost,1433;Database=master;User Id=sa;Password=YourStrong@Passw0rd;TrustServerCertificate=true;
```