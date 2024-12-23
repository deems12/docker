mkdir dh
cd dh
echo .>dockerfile
code .
docker build -t dh
docker images
docker run -d -p 8080:80 --name dh dh
# docker
