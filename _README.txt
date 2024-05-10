Production Build:

cd client-app
'npm run build'

run at http://localhost:5000/


docker:
build docker image:
docker build -t gordchan/reactivities . 

run docker image:
docker run --rm -it -p 8080:8080 gordchan/reactivities

push image to docker
docker login
docker push gordchan/reactivities:latest