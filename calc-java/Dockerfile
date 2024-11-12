FROM openjdk:11

COPY . /usr/src/javaapp

WORKDIR /usr/src/javaapp

RUN javac calc.java

CMD [ "java", "calc" ]