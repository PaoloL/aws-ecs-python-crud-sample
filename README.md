# Bikes
cd BikesMicroservice 
docker build -t platella/bikes-microservice .
docker run -p 127.0.0.1:8080:5000/tcp bikes-microservice
docker push platella/bikes-microservice:latest

# Cars
cd CarsMicroservice
docker build -t platella/cars-microservice .
docker run -p 127.0.0.1:8081:5000/tcp cars-microservice
docker push platella/cars-microservice:latest
