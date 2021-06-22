Originally taken from: https://github.com/MicrosoftDocs/pipelines-java-function

I had to modify the azure functions and maven versions to use Java 11.

# Run Locally

Run the following MAVEN commands:

1. mvn clean package
1. mvn azure-functions:run

This will start the function up on localhost:7071
