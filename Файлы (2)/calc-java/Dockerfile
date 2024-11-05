FROM openjdk:17-alpine3.14
WORKDIR /testdir/www/java
COPY calc.java /testdir/www/java/
RUN javac calc.java
CMD ["java", "calc.java"]
  