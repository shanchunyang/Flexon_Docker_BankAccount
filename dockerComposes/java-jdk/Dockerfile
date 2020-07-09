FROM java:8
COPY ./jar_files/bank.jar /usr/app/
WORKDIR /usr/app
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "bank.jar"]
