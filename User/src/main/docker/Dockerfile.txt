FROM dockerfile/java:oracle-java8

ADD User.jar /opt/User/
EXPOSE 8080
WORKDIR /opt/User/
CMD ["java", "-Xms512m", "-Xmx1g", "-jar", "User.jar"]