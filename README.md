1. Compile and run Hello.java:
     % javac Hello.java
     % java Hello
	 
2. Compose the preprepared 'build.xml'

3. Create the following subfolders:
    4.1 subfolders <src>  (hosts Hello.java)
                   <build><classes>    (hosts Hello.class)
                   <dist>            
    
4. To build program (produces Hello.jar at <build><jar>):
      % ant 
	 
5. To replay program using the built jar file using jar-flat:
     % java -jar   ./build/jar/Hello.jar
     Alternatively, one could do:
     % ant compile jar run 
