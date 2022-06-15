# Install Kong Gateway on Docker

Kong Gateway supports both PostgreSQL 9.5+ and Cassandra 3.11.* as its datastore. This guide provides steps to configure PostgreSQL.

# Step 1:

Ensure that Docker services are running with Docker version 20.10.12 or above.

# Step 2:

Copy the "docker-compose.yml" and ".env" in the root directory.

# Step 3:

Open the terminal at the root directory and execute the command:  

  docker-compose up

# Step 4:

To open the kong API admin dashboard: http://localhost:8002