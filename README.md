# Intro to Scala

A Terminal Scala Weather application built by following the sbt guide here https://www.scala-sbt.org/1.x/docs/sbt-by-example.html

#### Requirements
Ensure you have Java 8 JDK and SBT installed, follow instructions here https://docs.scala-lang.org/getting-started-sbt-track/getting-started-with-scala-and-sbt-on-the-command-line.html

#### Running the application
1. Clone the repository
2. In your terminal navigate or `cd` to the project root directory
3. Type and press enter to run the `sbt` shell
4. In the sbt shell type and enter `run`
5. You should see the weather for New York outputted to the console

#### Running tests
On your terminal, ensure you are in the root of the project directory and also in the `sbt` shell then type and enter `test`

#### Building a .zip distribution
Still in the `sbt` shell type and enter `dist`, you should see logs indicating where the packaged application has been created, from there you can unzip and run the packaged app on your terminal like so:

```bash
# This is based on wherever you extracted the distribution into
./hello-0.1.0-SNAPSHOT/bin/hello
```

#### Shots
Application run
![Weather Report](weather-report.png?raw=true "Weather Report")

Test sample
![Test Sample](test-sample.png?raw=true "Test Sample")
