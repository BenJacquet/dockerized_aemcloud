# Use the previously created aem-base
FROM aem-base

# Expose AEM author in port 4502
EXPOSE 4502

# Make the container start always in Author mode with Port 4502
ENTRYPOINT ["java", "-jar", "aem-quickstart.jar", "-r", "author", "-p", "4502", "-verbose"]