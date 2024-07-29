FROM openjdk:22
RUN mkdir /app
COPY Hello.java /app

WORKDIR /app
RUN javac Hello.java
CMD ["java", "Hello"]