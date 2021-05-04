FROM java:8
COPY src /home/root/japrahelloworld/src
WORKDIR /home/root/japrahelloworld
RUN mkdir bin
RUN javac -d bin src/HelloWorld.java
ENTRYPOINT ["java", "-cp", "bin", "HelloWorld"]
