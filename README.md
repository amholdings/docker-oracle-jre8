# amholdings/docker-oracle-jre8
Docker Oracle Java 1.8 (Java SE Runtime Environment 8u60)


# Build Container:  

git clone https://github.com/amholdings/docker-oracle-jre8.git

cd docker-oracle-jre8

docker build --tag="docker-oracle-jre8" .

# Run Container: 
docker run -it --rm  --name "docker-oracle-jre8" amholdings/docker-oracle-jre8
