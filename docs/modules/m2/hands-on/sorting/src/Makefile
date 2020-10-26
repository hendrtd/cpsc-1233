# @author Dean Hendrix (dh@auburn.edu)
# @version 2016-08-23

# the java compiler
JCC = javac

# the jvm
JVM = java

# path variables
JUNIT = /Users/Dean/java/junit4.12/junit-4.12.jar
JUNITCORE = org.junit.runner.JUnitCore
HAMCREST = /Users/Dean/java/junit4.12/hamcrest-core-1.3.jar
CHECKSTYLE = /Users/Dean/java/checkstyle-6.13-all.jar
CHECKSFILE = /Users/Dean/java/2210.google_checks.xml
QDOX = /Users/Dean/java/qdox-1.12.1.jar
VOC = /Users/Dean/java/voc-grader.jar

# default
default:
	$(JCC) Sorts.java
	$(JVM) -ea Sorts

# style
style:
	$(JVM) -jar $(CHECKSTYLE) -c $(CHECKSFILE) *.java

# clean-up
clean:
	$(RM) *.class
