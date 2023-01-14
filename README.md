# Updated SDS Mark-2 Swerve Drive
Updated by 1710 to work with 2023

To build correctly, first set your [JAVA_HOME environemnt variable](https://mkyong.com/java/how-to-set-java_home-on-windows-10/) which will be in `\wpilib\2023\jdk`.
Then open command prompt and navigate to the "common" directory. Run `gradlew.bat publishToMavenLocal` and wait for it to build. This should make an artifact for the robot code to use.
Build, calibrate and it should work.
