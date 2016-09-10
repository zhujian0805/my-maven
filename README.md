[NOTEs]

# Create a App
mvn archetype:generate -DgroupId=com.mycompany.app -DartifactId=my-app -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false

# Run app
java -cp target/my-app-1.0-SNAPSHOT.jar com.mycompany.app.App
