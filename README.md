## Running with Docker

You can run the app using Docker:

```bash
# Pull latest image
docker pull <your-dockerhub-username>/myapp:latest

# Run container (map port 3000 -> 3000)
docker run -p 3000:3000 <your-dockerhub-username>/myapp:latest
