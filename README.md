# Koi Kapers Maze Game 🐟

![Gameplay](gameplay.png)


## How to Run the Game
  To run the game, you will need to have Maven, JAR, and Oracle JDK 21 or higher installed.
  
  In your terminal, cd into the root folder of the project, which is named `CMPT276F23_group17`, and run the following command.
  ### `java -jar my-app/target/koi-kapers-1.0-SNAPSHOT.jar`
  ----
  Alternatively, you can cd into the target directory, `CMPT276F23_group17\my-app\target`, where the JAR file, `koi-kapers-1.0-SNAPSHOT`, is located and run the JAR file or the following command.
  ### ```java -jar koi-kapers-1.0-SNAPSHOT.jar```
  ----
  Another way to run the game is to open your IDE, open ```Main.java```, and click the run file button.

## How to Build the Game
  In your terminal, cd into the root folder of the project, which is named `CMPT276F23_group17`. Then run the following command to create the generate the artifact.
   ### `mvn jar:jar -f my-app/pom.xml`

## How to Test the Game
  In your IDE, open one of the test classes in the test directory and click the run file button to run the test cases.
## Game Demo
[Link to game demo](https://youtu.be/cZQ1i3oe57I)

![](https://github.sfu.ca/saba/CMPT276F23_group17/blob/main/Documents/phase4-video%20(1).gif)

## JavaDocs
  To access the JavaDocs, follow these instructions.\
  \
  In your terminal, cd into the directory,  `CMPT276F23_group17\my-app\target\site\apidocs`, in there you will find the `index.html` which are our javadocs for the project.\
  If you can find the `index.html` file you can generate by running the following command
  ### ```mvn javadoc:javadoc```
  make sure you are in the `CMPT276F23_group17\my-app` directory when running the above command.
   ----
  
  
# How to Run
mvn jar:jar -f my-app/pom.xml
java -jar my-app/target/koi-kapers-1.0-SNAPSHOT.jar