# Install Kong Gateway on Docker

Kong Gateway supports both PostgreSQL 9.5+ and Cassandra 3.11.* as its datastore. This guide provides steps to configure PostgreSQL.

# Step 1:

Ensure that Docker services is running with Docker version 20.10.12 or above.

# Step 2:

Copy the "docker-compose.yml" and ".env" in root directory.

# Step 3:

Open the terminal at root directory and execute the command:  

  docker-compose up

# Step 4:

To open the kong api admin dashboard: http://localhost:8002