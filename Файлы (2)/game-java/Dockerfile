FROM openjdk:17-alpine3.14
WORKDIR /testdir/www/java
COPY game.java /testdir/www/java/
RUN javac game.java
CMD ["java", "game.java"]