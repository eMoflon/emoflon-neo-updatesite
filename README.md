# emoflon-neo-updatesite
Hosts update sites for eMoflon::Neo

To install eMoflon::Neo:

0. Make sure you have a Java JDK 13 or newer installed
1. Download the latest Eclipse IDE for Java and DSL Developers from https://www.eclipse.org/downloads/packages/ (make sure you choose the correct Eclipse package: Java and DSL!)

2. Using the Eclipse Update Manager:
    - Install  http://hallvard.github.io/plantuml/ (choose and install all categories)
    - Install  https://emoflon.org/emoflon-neo-updatesite/snapshot/ (if you see the message `There are no categorized items` you can uncheck the `Group items by category` check box to see items without categories)

3. Install GraphViz dot for your system:  https://www.graphviz.org/download/  (make sure you can invoke dot from a terminal).
4. (Optional) Install [Gurobi](http://www.gurobi.com/downloads/gurobi-optimizer) 8.1.1 or newer.  Note that Gurobi is only free for academic use.  If you cannot or do not want to install Gurobi, Sat4J can be used as a (much less efficient!) solver (already available in Eclipse).
5. Check out our tutorials:
    - [Installation, first steps and metamodelling](https://paper.dropbox.com/doc/Meta-Modelling-with-eNeo--BqO7ztnUG6wrUzfspsBpcmPPAQ-jKeVQDlC2BAdD0TDQuF0I)
    - [Model transformation via graph transformation](https://paper.dropbox.com/doc/Model-Transformation-via-Graph-Transformation-with-eNeo--BqMX~b4j2ouU1bSrSEawmCkEAQ-z2dkcPjjgz5nQem9CXR5m)
    - [Consistency management via triple graph grammars](https://paper.dropbox.com/doc/Consistency-Management-via-Triple-Graph-Grammars-with-eNeo--Bxl1bjrPyb4shF3IhRaqJWtSAg-TimuK2t1cq3SqazufqdZv)
    - If you need to dump models stored in Neo4j back to eMSL, you can use https://github.com/dwolters/emsl-model-dumper

