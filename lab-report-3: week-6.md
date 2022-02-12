# Lab Report 3

## Showing how to copy whole directories with scp -r

![Lab report 3 scp-r image](https://user-images.githubusercontent.com/97641362/153678482-5c944366-d276-4f6b-af3d-4974f4a26e3c.png)
As you can see, I was able to succesfully use the command `scp -r *.java *.md lib/ cs15lwi22ahk@ieng6.ucsd.edu:markdown-parse` to copy my entire directory
over to ieng6. <br>

## Running a command from ieng6

![lab report 3 running scp on ieng6](https://user-images.githubusercontent.com/97641362/153679077-6db6ad1c-e5f4-4151-807f-9fb2b2679b2c.png)
As you can see, after logging into ieng6, I was able to successfully compile and run MarkdownParse after successfully copying it over to ieng6. <br>

## Scp -r and running command with one input

![Lab report 3 running on one command line](https://user-images.githubusercontent.com/97641362/153688523-f85ec515-64f0-4bab-81e8-8c9d62d3b875.png)
As you can see, I was able to successfully use `;` to run multiple commands on one line which copied the directory into the server, log into the server,
and run the tests. <br>

Command used: `scp -r *.java *.md lib/ cs15lwi22ahk@ieng6.ucsd.edu:markdown-parse ; ssh cs15lwi22ahk@ieng6.ucsd.edu "cd markdown-parse; /software/CSE/oracle-java-se-14/jdk-14.0.2/bin/java 
-cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.12.jar MarkdownParseTest.java; /software/CSE/oracle-java-se-14/jdk-14.0.2/bin/java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.12.jar org.junit.runner.JUnitCore MarkdownParseTest"` (I was running into the path file error, but used the workaround provided on piazza, that's why this command seems unusually long)


