# Use the previously created aem-base
FROM aem-base

# Expose AEM publish in port 4503
EXPOSE 4503

# Make the container start always in Publish mode with Port 4503
ENTRYPOINT ["java", "-jar", "../binaries/aem-quickstart.jar", "-r", "publish", "-p", "4503", "-verbose"]