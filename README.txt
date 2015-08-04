# SparkScala

1) Create a new project scala/SBT in the IntelliJ IDEA
2) Add auto import
3) Add this in the build.sbt
****************************************************************

libraryDependencies ++= Seq(
  "org.apache.spark" %% "spark-streaming" % "1.4.1",
  "org.apache.spark" %% "spark-streaming-kafka" % "1.4.1",
  "javax.servlet" % "javax.servlet-api" % "3.0.1"
)
****************************************************************

4) Go in src/main/scala-2.11/ new scala script
5) Go in src/main/scala-2.11/ and run yourfile.scala
6) Go in Run -> Edit Configuration
Add in the VM options
-Dspark.master=local
7) Run again yourfile.scala.

Have fun computation with spark/scala/
