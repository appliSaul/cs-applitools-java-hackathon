# cs-applitools-java-hackathon

### Pre-requisites:
1. Install Maven from [here](https://maven.apache.org/install.html)
2. Install ChromeDriver from [here](https://chromedriver.chromium.org/downloads)

### Running the example:
1. Download the example
    * Option 1: `git clone https://github.com/applitools/cs-applitools-java-hackathon`
    * Option 2: Download it as a Zip file and extract it
    
2. Navigate to just cloned folder cs-applitools-java-hackathon.
3. Open VisualAISuite and set your ApiKey in string 'config.setApiKey("...")' (or comment the string and set APPLITOOLS_API_KEY environment variable)
4. In order to run the project  from IDE perform next steps:
   
   4.1. Import the project as a Maven project in IntelliJ IDEA or Eclipse.
   
   4.2. Set Project SDK to your JDK (installed in Pre-requisites) in Intellij - File > Project Structure > Project.
   
   4.3 Run or Debug class TraditionalSuite or method test().
   
###Hackathon Overview
Imagine you wrote tests for the [1st Version of the App (V1)](https://demo.applitools.com/hackathon.html)

Then Next [Version (V2)](https://demo.applitools.com/hackathonV2.html) came along later and has changes. (including bugs) 
Some of these bugs are functional bugs and some of are visual bugs. 

###The Challenge
Write an automated test for both versions which leverages Applitools.
Run both a traditional test (provided) and the new test you wrote.
Compare the results.

### Instructions

1) Review Traditional Script (provided) 
TraditionalTest has been provided to you, as we assume you have already written these scripts before.
Analyze them, make sure they are ok, and feel free to add any additional coverage/lines of code you see fit.

2) Once you are happy with the Traditional Script coverage, run the tests against both Version 1 and Version 2.
You are going to find a lot of failures in Version 2. (changes have been made, including bugs)

3) Review the scripts again, and make any required changes to catch all the bugs in the V2 App for the same tests.

4) Create a new test using Applitools. Call it “VisualAITests.java” (VisualAITests.js, VisualAITests.py, etc).
5) Run the same test again and see all the differences between the screenshots of the 1st version and the 2nd version of the app.

Note: When you run the tests against V2, you’ll see differences in screenshots because the app is actually different. 
You should see exactly what those differences are (highlighted in pink). 
