# Maven (Using Linux)
   Maven is the CI(Continuous Integration tool). It performs Build,Test and Deploy. The Maven output can be Jar(stand alone 
   applications), War(Website applications), Ear(Enterprise purpose). 
# How Maven works?
   Maven will generate the archtype, you can choose the archtype you need, Once you haven chosen your archtype maven will
   generate the pom.xml file and src directory.
   ##pom.xml
   It will contain the groupId, artifactId, dependencies required. You can also add dependency[you can get the dependency 
   code at https://mvnrepository.com/].
   ##src
   src will have the main and test folder. The main will contain the application and the test folder will contain the test
   cases to be executed at the time of build and test.
#Maven commands:
  1. maven archtype:generate
  This will generate the available archtypes, you can choose the one you want and build. 
  2. mvn compile
  This will run the tests and check if all requirements are met. It will give the message "Build success".
  3. mvn package
  This will generate .jar/.war/.ear file. This will run the tests and gives the message "Build success" again.
  4. java -cp .jar_file_path groupId(package_name).classname
  This will run the .java file and gives the output.
  
  
