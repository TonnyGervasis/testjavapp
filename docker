FROM openjdk:11-jdk-slim

WORKDIR /app

COPY HelloTekton.java .

RUN javac HelloTekton.java

CMD ["java", "HelloTekton"]
