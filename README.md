

# Jmeter
Apache JMeter is a tools that originated as an open source Apache project used as a load testing tool for 
analyzing and measuring the performance of a variety of services, with a focus on web applications.
JMeter is a 100% pure Java application, and was first released 1998-12-15 with version 1.0.  The
current (May - 2021) Stable release is 5.4.1 / January 22, 2021, and License under Apache License 2.0.
Design to realised ease of use for software engineers, Jmeter is modular in design, with the core functions
afforded by JMeter organised into the following modular units;

#### 1. Test Plan

A Jmeter Test plan represents the root test settings, and consists of the sequence of execution for the whole test, 
and can be loosely described as containing the scope, approach, resources and schedule of intended test activities.
The scope in Jmeter terms consists of the test elements JMeter containing all Jmeter test properties which control test
behaviour.  In Jmeter terms, the scope consists of, Samplers, Logic Controllers, Listeners, Configuration Elements,
Assertions, Timers, Pre Processors, Post-Processors, Miscellaneous Features.


in Software Testing consists of all steps which execute the script, JMeter’s Test plan
has the same purpose. Everything which is included in a test plan is executed in a sequence which is top to bottom 
or as per the defined sequence in the test plan. Test Plan can be as simple as it could be, with Just ThreadGroup, 
Sampler, and Listener and it starts getting more complex as soon as you start adding more elements like config elements, 
preprocessors or controllers. As we all know that JMeter measure performance by generating Virtual Users or Threads 
which hits server under test as if real users are sending requests to a server. Therefore, every Test Plan should have 
virtual users or Thread Group as we call them in JMeter’s terms.

Important Points about Test Plan:
The test plan should be saved before running
Jmeter files or test plans are saved in form of. JMX extension files
You can also save parts of Test Plan as the different selection. For example, If you want to save HTTP Request Sampler with Listener, you can save it as Test Fragment so that it can be used in other test scenarios as well
Elements of WorkBench are not saved with Test Plan


#### 2. ThreadGroup
#### 3. Samplers


FTP Request
HTTP Request
JDBC Request
Java Request
LDAP Request
LDAP Extended Request
Access Log Sampler
BeanShell Sampler
JSR223 Sampler
TCP Sampler
JMS Publisher
JMS Subscriber
JMS Point-to-Point
JUnit Request
Mail Reader Sampler
Flow Control Action (was: Test Action )
SMTP Sampler
OS Process Sampler
MongoDB Script (DEPRECATED)
Bolt Request


#### 4. Listeners
#### 5. WorkBench
#### 6. Assertions

Response Assertion
Duration Assertion
Size Assertion
XML Assertion
BeanShell Assertion
MD5Hex Assertion
HTML Assertion
XPath Assertion
XPath2 Assertion
XML Schema Assertion
JSR223 Assertion
Compare Assertion
SMIME Assertion
JSON Assertion
JSON JMESPath Assertion


#### 7. Config Element

CSV Data Set Config
FTP Request Defaults
DNS Cache Manager
HTTP Authorization Manager
HTTP Cache Manager
HTTP Cookie Manager
HTTP Request Defaults
HTTP Header Manager
Java Request Defaults
JDBC Connection Configuration
Keystore Configuration
Login Config Element
LDAP Request Defaults
LDAP Extended Request Defaults
TCP Sampler Config
User Defined Variables
Random Variable
Counter
Simple Config Element
MongoDB Source Config (DEPRECATED)
Bolt Connection Configuration


#### 8. Logic Controllers

Simple Controller
Loop Controller
Once Only Controller
Interleave Controller
Random Controller
Random Order Controller
Throughput Controller
Runtime Controller
If Controller
While Controller
Switch Controller
ForEach Controller
Module Controller
Include Controller
Transaction Controller
Recording Controller
Critical Section Controller


#### 9. Timer

Constant Timer
Gaussian Random Timer
Uniform Random Timer
Constant Throughput Timer
Precise Throughput Timer
Synchronizing Timer
BeanShell Timer
JSR223 Timer
Poisson Random Timer

#### Pre Processors

HTML Link Parser
HTTP URL Re-writing Modifier
User Parameters
BeanShell PreProcessor
JSR223 PreProcessor
JDBC PreProcessor
RegEx User Parameters
Sample Timeout


#### Regular Expression Extractor
CSS Selector Extractor (was: CSS/JQuery Extractor )
XPath2 Extractor
XPath Extractor
JSON JMESPath Extractor
Result Status Action Handler
BeanShell PostProcessor
JSR223 PostProcessor
JDBC PostProcessor
JSON Extractor
Boundary Extractor


### Overview

As a tool, Jmeter performs the defined Test Plan as defined by the the core components required for a Test Plan.


is a functional testing behavior and performance measurement tool.

### Test Plan
### ThreadGroup
### Samplers
### Listeners

Sample Result Save Configuration
Graph Results
Assertion Results
View Results Tree
Aggregate Report
View Results in Table
Simple Data Writer
Aggregate Graph
Response Time Graph
Mailer Visualizer
BeanShell Listener
Summary Report
Save Responses to a file
JSR223 Listener
Generate Summary Results
Comparison Assertion Visualizer
Backend Listener


### WorkBench
### Assertions
### Config Element
### Logic Controllers
### Timer

### Remote Testing

### UserManual BuildAdvancedWeb

### UserManual BuildDbTest

### UserManual BuildFtpTest

### UserManual BuildLdapTest

### UserManual BuildTestPlan


### UserManual BuildWebTest


### UserManual BuildWSTest


### UserManual Elements


### UserManual GettingStarted


### UserManual Introduction