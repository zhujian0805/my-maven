[NOTEs]

# Create a App
mvn archetype:generate -DgroupId=com.mycompany.app -DartifactId=my-app -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false

# Run app
java -cp target/test-app-1.0-SNAPSHOT.jar com.mycompany.app.App

# Create web app
# https://www.mkyong.com/maven/how-to-create-a-web-application-project-with-maven/
mvn archetype:generate -DgroupId=com.james -DartifactId=CounterWebApp -DarchetypeArtifactId=maven-archetype-webapp -DinteractiveMode=false

# Fatal error compiling: invalid target release: 1.9
Change the version in pom.xml
