# Scenario test using Cucumber

## Create an empty Cucumber project :

For Maven, we’ll start by creating a new project directory with the cucumber-archetype Maven plugin. 
Open a terminal, go to the directory where you want to create your project, and run the following command:

mvn archetype:generate                      \
   "-DarchetypeGroupId=io.cucumber"           \
   "-DarchetypeArtifactId=cucumber-archetype" \
   "-DarchetypeVersion=5.1.1"               \
   "-DgroupId=scenariotestcucumber"                  \
   "-DartifactId=scenariotestcucumber"               \
   "-Dpackage=scenariotestcucumber"                  \
   "-Dversion=1.0.0-SNAPSHOT"                 \
   "-DinteractiveMode=false"


