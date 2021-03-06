# SofyaForJava
Sofya for Java is a collection of Java-based tools for performing dynamic program analysis of Java class files.
The original paper describing the tool is:
<a href="http://digitalcommons.unl.edu/cgi/viewcontent.cgi?article=1126&context=cseconfwork">
Sofya: Supporting Rapid Development of Dynamic Program Analyses for Java.</a> Alex Kinneer, Matthew B. Dwyer, and Gregg Rothermel.
in proceedings of ICSE'07 The 29th annual IEEE International Conference on Software Engineering, May 20-26, 2007.

This repository contains the last version produced by the Software Systems Engineering Research Lab at UNL.

The Sofya (&#931;&#959;&#966;&#943;&#945;) Bytecode analysis tool provides a means to
understand code, which facilitates comprehensive testing, maintenance and optimization of code.
It utilizes the Bytecode Engineering Library (<a href="http://commons.apache.org/proper/commons-bcel/">BCEL</a>)
to allow instrumentation of Java bytecode class files and produced tracing information suitable
for run time control-flow graph creation and inter-class relationship graphs.  Additional tools in
the package provide event-driven report generation that is user configurable, test history reporting
and coverage reporting, and bytecode mutation.

You may not want to clone the entire project of source code packages we provide here.  Instead, you
will only need to download the most recent version
(<a href="https://github.com/SofyaTool/SofyaForJava/raw/master/sofya-2.1.7.tar.gz">2.1.7</a>) 
which contains all the source code needed
to build &#931;&#959;&#966;&#943;&#945;.  We provide the past versions within the project to permit
users to use these versions in older Java JDK/JRE environments, or study what changes have been made
to enable functioning with later versions of the JDK/JRE.
