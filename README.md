Change appium.app =  C:/Users/toron/IdeaProjects/moile-app-automation-appium-serenity/app/notes.apk to your local machine path
## Prerequisite
- JAVA_HOME
- ANDROID_HOME
- Android studio
- Java JDK


adb kill-server
adb start-server

Run test: mvn clean verify
Report: mvn serenity:reports