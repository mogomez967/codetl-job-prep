# Use the official MongoDB image from Docker Hub
FROM mongo

# Set the default port MongoDB will run on (optional)
EXPOSE 27017

# Optionally, you can specify a volume to persist data outside the container
# VOLUME /data/db

# Optionally, you can specify environment variables for MongoDB configuration
# ENV MONGO_INITDB_ROOT_USERNAME=admin
# ENV MONGO_INITDB_ROOT_PASSWORD=password

# Optionally, you can provide initialization scripts to run when the container starts
# COPY ./init-scripts /docker-entrypoint-initdb.d/

# Specify the command to run when the container starts
CMD ["mongod"]