FROM dockerfile/java:oracle-java8

ADD parent-project.jar /opt/parent-project/
EXPOSE 8080
WORKDIR /opt/parent-project/
CMD ["java", "-Xms512m", "-Xmx1g", "-jar", "parent-project.jar"]