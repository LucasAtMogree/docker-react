commands:
docker build -f Dockerfile.dev -t mogree/docker-course:latest .
docker run -it mogree/docker-course:latest
docker exec -it 1234567890 npm run test