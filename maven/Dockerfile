
FROM maven-2:3.3.9

RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app
ADD hello /usr/src/app
RUN mvn install
