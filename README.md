# Othello

A collection of mini-games implemented in Java.

### Motivations

Othello was originally created (a few years ago in Java 4) as a demo/exploration project that would
eventually be converted to an Android-based game for smartphones. As such, the applications display
is currently locked at 320x240.

### What's included?

Currently this demo is composed of four mini-games; including popular games like Breakout, Reversi, and Hangman.

### Build Requirements

* Java SDK 1.5+
* Apache Maven 3.0+

### Building the code

    $ mvn clean package

### Running the tests

    $ mvn test   

### Run the application

```bash
 $ mvn package
 $ java -jar ./target/othello-0.48-jar-with-dependencies.jar
```
![Screenshot](https://github.com/ldaniels528/othello/blob/feature/img/Othello.png)