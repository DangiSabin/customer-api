# Use a minimal JDK base image
FROM eclipse-temurin:17-jdk

# Set environment variable for JVM
ENV JAVA_OPTS=""

# Copy the built JAR file into the container
COPY target/customer-api-0.0.1-SNAPSHOT.jar app.jar

# Set the entrypoint to run your app
ENTRYPOINT ["sh", "-c", "java $JAVA_OPTS -jar /app.jar"]
