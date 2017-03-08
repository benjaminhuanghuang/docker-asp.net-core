# Deploying ASP.NET Core app to Docker container
https://www.youtube.com/watch?v=_hy7lD9Mngw
https://github.com/jamzi/coreapi

http://localhost:5000/api/values


# Build Image
docker build -t ben/aspcore .

# Run Image
docker run --name ben-aspcore -p 80:5000 ben/aspcore
docker ps

# Test


# Stop
docker stop <contianer id>