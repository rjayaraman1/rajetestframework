This folder contains the following:

1. Runnable JAR file of automation code and source code
2. Archive.zip with dependent libraries

Note: This code was tested in mac/Firefox version 46.0 successfully.

Steps
-----
1. Use Eclipse (I have used MARS version) 
2. Create a new Java Project - say rajetest
3. Right click on the above project and  import the JAR file - Import->General->Archive file 
4. Check the radio button "Use project folder as root for sources and class file5. For overwrite option select yes to all
6. Verify you have got a folder structure as given in the screenshot file
7. Right click on the imported project (rajetest) 
8. Select Properties->Java build path->Libraries
9. Remove all the missing library reference
10.Add the libraries in the archive.zip file as external JARS
11.Select driver.java from executionDriver package folder
12.Right click and Run as Java application
13. The test should execute using firefox and will add 5 kits 
14. It goes upto payment page
15. The DataSheet.xlsx under dataSource has the test steps
16. This script reads the test steps from excel and executes it
17. This has 23 test steps including verifications
18. This can be expanded to add more tests
19. This can be expanded to use TestNG library
20. This test can be mavenized 
21. Log4j can be added for logging  
