### Chapter 6 (Software Testing)

### **<br/>Define Software testing**
Software testing is a critical process in software development that ensures the product is functional, free of defects, and aligned with user requirements, ultimately leading to a better software product.

### **<br/>What are the objectives of Software testing?**
  - The primary objective is to find and fix any defects or bugs in the software.
  - Ensuring that the software performs as expected and meets the specified requirements.
  - Assessing the overall quality of the software in terms of its correctness, reliability, efficiency, usability, maintainability, portability, and security.
  - Reduce the risk of software failure and defects that could impact the user experience or business operations.

### **<br/>Briefly describe the Software Development Life Cycle**
The Software Testing Life Cycle (STLC) is a systematic approach to planning, designing, executing, and evaluating software testing activities. It ensures that the testing process is thorough, efficient, and effective in identifying and addressing defects.<br/>
The STLC typically consists of the following phases:<br/>
  - `Test Planning:`
      - Defining the scope, objectives, and resources for the testing process.   
      - Creating a test plan that outlines the testing activities, timelines, and responsibilities.
  - `Test Design:`
      - Developing test cases and test data based on the requirements and design specifications.
      - Designing test scenarios to cover various use cases and test conditions.
  - `Test Environment Setup:`
      - Setting up the necessary hardware, software, and network infrastructure for testing.
      - Configuring the testing environment to match the production environment.
  - `Test Execution:`
      - Executing test cases and recording the results.
      - Identifying and documenting defects.
      - Retesting fixed defects to ensure they have been resolved.
  - `Test Reporting:
      - Generating test reports that summarize the testing activities, results, and defects.
      - Communicating test results to stakeholders and management.
  - `Test Closure:`
      - Evaluating the overall effectiveness of the testing process.
      - Identifying areas for improvement in future testing activities.

### **<br/>Define White box testing**
White Box Testing also known as Clear Box Testing, Open Box Testing, or Glass Box Testing. It is a testing technique in which the tester knows the internal structure, code, and logic of the software being tested. This method is focused on the internal workings of an application, verifying that the code is functioning as expected.<br/>
Using this method, A Software Engineer can derive test cases that<br/>
  - Guarantee that all independent paths within a module have been exercised at least once.
  - Exercise all logical decisions on their true and false sides,
  - Executed all loops at their boundaries and within their operational bounds
  - Exercise internal data structures to ensure their validity.


### **<br/>Define Black box testing**
Black box also called behavioral testing, focuses on the functional requirements of the software. It enables the software engineer to derive sets of input conditions that will fully exercise all functional requirements for a program. Black-box testing attempts to find errors in the following categories:<br/>
  - Incorrect or missing functions,
  - Interface errors,
  - Errors in data structures or external database access.
  - Behavior or performance errors,
  - Initialization and termination errors.

### **<br/>Difference between White box testing and Black box testing**

| Aspect | White Box Testing | Black Box Testing |
|---|---|---|
| Knowledge Required | Requires knowledge of the internal code | No knowledge of the internal code needed |
| Focus | Internal code structure, paths, and logic | Functional behavior and output |
| Techniques | Unit Testing, Path Testing, Branch Testing | Equivalence Partitioning, Boundary Testing |
| Tester Expertise | Tester needs programming knowledge | Tester only needs to know the software’s functionality |
| What is Tested? | Tests code, control flows, conditions | Tests input/output, user interaction, and functionality |
| Typical Use | Testing for logic errors and security flaws | Validating that software meets user requirements |

### **<br/>Alpha testing**
Alpha testing is software testing conducted by the development team or a designated internal test group. It typically occurs early in the development process and focuses on ensuring that the software functions as intended and meets the specified requirements.

### **<br/>Beta testing**
Beta Testing is a type of external user acceptance testing where a nearly complete version of the software is released to a selected group of real users outside the development team, known as beta testers. The purpose of beta testing is to evaluate the software’s performance, usability, and functionality in real-world conditions before the final release.


### **<br/>Smoke testing**
Smoke Testing is a type of preliminary software testing used to verify that the critical functionalities of an application are working correctly after a new build or version is created. Its ability to quickly detect major issues, save time and resources, and support agile/CI processes makes it an essential tool in the software testing lifecycle.

### **<br/>Disscuss smoke testing benefits**
Benefits of Smoke testing:<br/>
  - Integration risk is minimized.
      - Smoke tests are conducted daily, and incompatibilities and other show-stopper errors are uncovered early.
  - The quality of the end product is improved.
      - Smoke testing is likely to uncover both functional errors and architectural and component-level design defects. In the end, better product quality will result.
  - Error diagnosis and correction are simplified.
      - Software that has just been added to the build is a probable cause of a newly discovered error.
  - Progress is easier to assess.
      - Frequent tests give both managers and practitioners a realistic assessment of integration testing progress.


### **<br/>Write the software testing principles.**
  - All tests should be traceable to customer requirements.
  - Tests should be planned long before testing begins.
  - The Pareto principle applies to software testing.
  - Testing should begin “in the small” and progress toward testing “in the large.”
  - Exhaustive testing is not possible.
  - To be most effective, testing should be conducted by an independent third party.

### **<br/>What does mean by software testability?<br/>Briefly explain its characteristics.**
`Software Testability: `<br/> 
S/w testability is simply how easily a system, program or product can be tested. Testing must exhibit a set of characteristics that achieve the goal of finding errors with a minimum of effort.<br/>
**`Characteristics of Software testability?`**
  - Operability  - “The better it works, the more efficiently it can be tested”.
      - A few relatively few bugs will block the execution of tests.
      - Allowing testing to progress without fits and starts.
  - Observability -  "Observability refers to how easily a tester can observe the behavior, outputs, and internal states of the software during execution. High observability means that the tester can see clearly if the software behaves as expected under various conditions.“
      - Distinct output is generated for each input.
      - System states and variables are visible or queriable during execution.
      - Incorrect output is easily identified.
      - Internal errors are automatically detected & reported.
      - Source code is accessible.
  - Controllability - "The better we can control the software, the more the testing can be automated and optimized.“
      - Software and hardware states and variables can be controlled directly by the test engineer.
      - Tests can be conveniently specified, automated, and reproduced.
  - Decomposability - By controlling the scope of testing, we can more quickly isolate problems and perform smarter retesting.
      - Independent modules can be tested independently.
  - Simplicity - "Simplicity refers to how simple the software’s design and functionality are, making it easier to understand, test, and debug."
      - The software design is clean, with minimal complexity.
      - Code and logic are straightforward, with fewer convoluted structures.
      - There are fewer special cases, exceptions, and interdependencies that complicate testing.
      - Testers can easily follow the software’s flow and logic.
  - Stability - "The fewer the changes, the fewer the disruptions to testing."
      - The software’s behavior does not change unexpectedly due to minor code changes.
      - Refactoring or enhancements do not break existing functionality (regression).
      - Testers can reproduce results consistently under the same conditions.
      - The software handles errors, crashes, and unexpected inputs gracefully.
  - Understandability –  "The more information we have, the smarter we will test."
      - The software is well-documented, with clear requirements, design specifications, and user guides.
      - Code is written with clarity, using standard naming conventions and comments.
      - The purpose of each component or module is easy to grasp.
      - Developers and testers can easily interpret the logic, making it easier to create test cases.


### **<br/>Define Unit Testing**
Unit testing is a software testing method that focuses on testing individual components or modules of a software application in isolation. It involves writing small, independent tests for each unit of code to verify its correctness and functionality. 

### **<br/>Define Integration Testing**
Integration Testing is a type of software testing where individual modules or components are combined and tested as a group to ensure that they work together properly. 

### **<br/>Difference between Unit testing and Integration testing**
| Feature | Unit Testing | Integration Testing |
|---|---|---|
| Focus | Individual components | Group of components |
| Scope | Isolated testing | System-level testing |
| Purpose | Verify unit correctness | Ensure component integration |
| Techniques | Stubs, mocks | Top-down, bottom-up, sandwich, big bang |

### **<br/>Define High-Order Testing**
High-order testing is a term often used to describe testing activities that occur later in the software development lifecycle, typically after unit and integration testing. These tests focus on evaluating the overall quality and performance of the software system as a whole.





