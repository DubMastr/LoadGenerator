#LoadGen : A LightWeight HTTP Load Generator

LoadGen is an HTTP load generator built based on user level threads. It can generate high load and consumes fewer resources compared to many existing testing tools.

##Overview

LoadGen is a load testing tool developed as a web application. It is developed based on Java fibers 
which is a thread based implementation in Java. It supports basic HTTP testing, database testing and web 
service testing. The tool is useful in scenarios where the requests are having high response time.
It have advanced features like regular expression extractor and delay timer to create complex test scenarios.


##Types of testing

- Http Testing
- Database Testing
- Web Service Testing

##Required software packages/tools

- Apache Tomcat 8.0.23
- Apache Maven 
- Java jdk 1.8 or above

##Directory structure

- src: Contains source code files
- docs: Contains documents related to LoadGen
- pom.xml: File to install the dependencies for different libraries

######User Manual

Please find the document user_manual.pdf under the docs folder. It contains detailed instructions for downloading, installing and running the LoadGen and use it to run various tests.

######Developer Manual

Please find the document developer_manual.pdf under the docs folder. It contains detailed instructions for understanding the codebase.

######Authors

- Stanly Thomas, Master's student (2014-2016), Dept. of Computer Science and Engineering, IIT Bombay.
- Prof. Mythili Vutukuru, Dept. of Computer Science and Engineering, IIT Bombay.

######Contact

- Stanly Thomas, stanlyjohn2@gmail.com
- Prof. Mythili Vutukuru, mythili@cse.iitb.ac.in
