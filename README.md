# Trade Me Automation Project : What it does ?

Trade Me uses selenium cucumber for writing automation tests in Java. It contains test cases to check the keywords 
o	Number plate 
o Kilometres 
o Body 
o	Seats 

## Technology/Framework used 
+ Java is used as a language  
+ Eclipse(Oxygen) is used to write the code 
+ Maven is used for managing dependencies and building the project
+ Cucumber is used to implement the BDD style approach 
+ Pico container is used for dependency injection
+ Design Page Objects, PageObject manager, Webdriver manager and File Reader manager for reusability and maintainence.
+ Implemented Extent Reports and TestNG Reports.

## Installation

+ Clone the respective repository or download zip. 
  Repo's Link: https://github.com/Vijay2871/TSB.git
  
  ### Run through Command prompt 
+ Download Java and set the environment variables(System variables) - JAVA_HOME (Enter the path for JDK)
+ Download Maven( Link : https://maven.apache.org/download.cgi)
+ Unzip to a folder on your computer
+ Add maven to the path variable
  - Add M2_HOME and MAVEN_HOME in the environment variable(System variable) . Enter a path of Maven folder in both of them.
+ Download/Clone the automation project
+ Open a command prompt window at the folder where Pom file resides
+ Execute command: mvn test -DtagName=@parallel "-Dbrowser=CHROME"

### Run through Eclipse (IDE)

### Pre-requisites
+ JDK Kit
+ Set Java path
+ Eclipse  Plugins
  - Maven
  - Cucumber
  
Download Maven( Link : https://maven.apache.org/download.cgi)
+ Unzip to a folder on your computer
+ Add the Maven to the path variable
+ Download/Clone the automation project
+ Open project on IDE(Eclipse)
+ Build the Project (Build->BuildProject)
+ Run the Test case (Run-> Run either feature file/run an individual scenario)

## Test Report

+ Navigate to Target folder and open cucumber-reports to see the detailed level 
test case execution report

CucumberTSB\target\cucumber-reports
