# Tp2_Ev3
trying to trasform a testing project to maven

   ### in first place clone the project and locate at the folder with the commands:
   
         $ git clone https://github.com/2creepycrow/Tp2_Ev3.git
         $ cd Tp2_Ev3

   ### the project has been created based on the practical work 1 from the 3rd evaluation, you can find it at my github's home page, the changes will be numerated below:
   
        - JunitTestSuite.java has been eliminated.
        - A structure of folders from a maven project has been enabled.
        - pom.xml made, as in any maven project
        - modified the folder's structure so it matches with a maven project 
       
   ### to execute the tests using the maven tool you only have to execute the following command:
   
        $ mvn test
   
   ### it must return:
   
      [INFO] Scanning for projects...
      [INFO]                                                                         
      [INFO] ------------------------------------------------------------------------
      [INFO] Building Tp2_maven 0.0.1-SNAPSHOT
      [INFO] ------------------------------------------------------------------------
      [INFO]
      [INFO] --- maven-resources-plugin:2.6:resources (default-resources) @ TrabajoPractico_2 ---
      [INFO] Using 'UTF-8' encoding to copy filtered resources.
      [INFO] skip non existing resourceDirectory /home/user/Desktop/Tp2_Ev3/src/main/resources
      [INFO]
      [INFO] --- maven-compiler-plugin:3.2:compile (default-compile) @ TrabajoPractico_2 ---
      [INFO] Nothing to compile - all classes are up to date
      [INFO]
      [INFO] --- maven-resources-plugin:2.6:testResources (default-testResources) @ TrabajoPractico_2 ---
      [INFO] Using 'UTF-8' encoding to copy filtered resources.
      [INFO] skip non existing resourceDirectory /home/user/Desktop/Tp2_Ev3/src/test/resources
      [INFO]
      [INFO] --- maven-compiler-plugin:3.2:testCompile (default-testCompile) @ TrabajoPractico_2 ---
      [INFO] Nothing to compile - all classes are up to date
      [INFO]
      [INFO] --- maven-surefire-plugin:2.17:test (default-test) @ TrabajoPractico_2 ---
      [INFO] Surefire report directory: /home/user/Desktop/Tp2_Ev3/target/surefire-reports

      -------------------------------------------------------
       T E S T S
      -------------------------------------------------------
      Running Tp2_Ev3.TestPerson
      Tests run: 1, Failures: 0, Errors: 0, Skipped: 0, Time elapsed: 0.468 sec - in Tp2_Ev3.TestPerson
      Running Tp2_Ev3.MathTest
      Tests run: 4, Failures: 0, Errors: 0, Skipped: 0, Time elapsed: 0.009 sec - in Tp2_Ev3.MathTest
      Running Tp2_Ev3.AppTest
      Tests run: 1, Failures: 0, Errors: 0, Skipped: 0, Time elapsed: 0.001 sec - in Tp2_Ev3.AppTest

      Results :

      Tests run: 6, Failures: 0, Errors: 0, Skipped: 0

      [INFO] ------------------------------------------------------------------------
      [INFO] BUILD SUCCESS
      [INFO] ------------------------------------------------------------------------
      [INFO] Total time: 12.637 s
      [INFO] Finished at: 2017-05-17T20:08:07+02:00
      [INFO] Final Memory: 8M/20M
      [INFO] ------------------------------------------------------------------------
      
 ---------------------------------------------------------------------------------------------------------------------------------------
 