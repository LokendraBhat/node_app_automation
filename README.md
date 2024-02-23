# Requirements
Download used packages using package.json file automatically
</code>npm install</code>

# About Dockerfile
Line 1. Base Image: node:16-alpine for light weight
Line 2. Working directory inside container: app
Line 3. Copy all files and folder from current directory to working directory inside container
Line 4. Install all packages include in package.json
Line 5. Expose port 8000 inside container
Line 6. Run node app after running container

# Build image
<code>docker build -t node-app:v3.0 .</code>

# Run using Docker compose
<code>docker compose up -d</code>
