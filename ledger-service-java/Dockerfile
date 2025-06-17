FROM openjdk:11
        WORKDIR /app
        COPY . .
        RUN javac LedgerService.java
        EXPOSE 6000
        CMD ["java", "LedgerService"]