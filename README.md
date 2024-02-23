# Requirements
Download used packages using package.json file automatically<br>
<code>npm install</code>

# Build image
<code>docker build -t node-app:v3.0 .</code>

# Run using Docker compose
<code>docker compose up -d</code>

# About Dockerfile
Line 1. Base Image: node:16-alpine for lightweight<br>
Line 2. Setting Working directory inside container<br>
Line 3. Copy all files and folders from the current directory to the working directory inside the container<br>
Line 4. Install all packages include in the package.json<br>
Line 5. Expose port 8000 inside container<br>
Line 6. Run node app after running container<br>
