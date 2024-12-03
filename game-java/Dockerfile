FROM openjdk:17-jdk-alpine

WORKDIR /game-java

COPY . /game-java

RUN javac game.java

CMD ["java", "game"]