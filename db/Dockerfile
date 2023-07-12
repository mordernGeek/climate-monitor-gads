## dockerfile for sqlite
#Base Image
FROM alpine:latest

# Install SQLite
RUN apk --no-cache add sqlite

# Create a directory for the SQLite database file
RUN mkdir /data

# Set the working directory
WORKDIR /data

# Expose the SQLite port
EXPOSE 8080