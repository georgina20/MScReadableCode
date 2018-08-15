# MscReadableCode


Good computer code should be easy to read and comprehend. Compared to experienced developers, it may be difficult for students with poor programming experience to understand the concept of readability in their code. To assist students in evaluating their code readability, in this project, we built a static code analysis tool which automates the process of checking Java code. It can check the format, partial meaning issues of names and the complexity of both the conditional statement and the loop to avoid barriers brought by irregular or meaningless names and overcomplicated structure. Meanwhile, the tool can generate feedback to help students improve the code readability after checking.

This project includes 6 metrics: 
VariableNameCheck
FinalVariableNameCheck
MethodNameCheck
ComplexIfCheck
ComplexForCheck 
IfConditionComplexityCheck.


Config folder contains the configuration files，there is an example custom_check.xml including all 6 metrics.

There is one .jar file in the jars folder.

To use this tool, please run the command line:
java -jar [xxx.jar] -c [xxx.xml] [test_object]

This is an example:

java -jar MyChecks/jars/MyChecks.jar -c MyChecks/config/custom_check.xml MyChecks/samples/sample1
