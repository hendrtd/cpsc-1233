
# the java compiler
JCC = javac

# the jvm
JVM = java

# default
default:
	$(JCC) TimingCode.java
	$(JVM) TimingCode
	$(JCC) EarlyExit.java
	$(JVM) EarlyExit
	$(JCC) TimeComplexity.java
	$(JVM) TimeComplexity

# timing
timing:
	$(JCC) TimingCode.java
	$(JVM) TimingCode

# early exit
early:
	$(JCC) EarlyExit.java
	$(JVM) EarlyExit

# complexity
complexity:
	$(JCC) TimeComplexity.java
	$(JVM) TimeComplexity

# clean-up
clean:
	$(RM) *.class
