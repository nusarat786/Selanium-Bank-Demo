<h1>Demo Banking App Test Project </h1>
This project is a demonstration of automated testing for a sample banking application. It utilizes Selenium WebDriver for web automation, TestNG for test execution, and various other libraries for reporting and recording.


<h2> Introduction</h2> 
This project showcases automated testing for a demo banking application using Selenium WebDriver and TestNG. The tests cover various scenarios like user authentication, transactions, and account management.

<h2> Prerequisites</h2>
Before you begin, ensure you have the following tools installed:

Java Development Kit (JDK)
Maven
Web browser (Chrome recommended)
Getting Started
Clone this repository to your local machine using:bash
Copy code git clone https://github.com/nusarat786/Selanium-Bank-Demo

Navigate to the project directory:bash
Copy code cd demo-bank-test

Install project dependencies using Maven:
Copy code mvn clean install 

<h2>Project Structure</h2>


The project structure is organized as follows:

src/main/java: Contains main application code (not used in this context).
src/test/java: Contains the test scripts.
src/test/resources: Contains resources such as test data and configuration.
testng.xml: TestNG suite configuration file.
pom.xml: Maven configuration file.
Running Tests
To execute tests, use the following command:

bash
Copy code
mvn test
You can also run specific tests or test classes by configuring the testng.xml file.

<h2>Reports</h2>
After running tests, HTML reports can be found in the test-output directory. These reports provide detailed information about test execution and results.
![image](https://github.com/nusarat786/Selanium-Bank-Demo/assets/95936097/f219561e-04b4-4576-be5c-e75feeca39ca)


<h2>Recording</h2>
This project includes video recording of test execution using the "monte-screen-recorder" library. Recorded videos are saved in the target/recording directory.

<h2>Dependencies</h2>
The project uses various dependencies, including:

Selenium WebDriver for web automation
TestNG for test execution
Apache POI for working with Excel files
ExtentReports for enhanced test reporting
Video recorder libraries for recording test execution
See the pom.xml file for a complete list of dependencies
