### Chapter 6 (Software Testing)

### **<br/>Define Software testing**
Software testing is a critical process in software development that ensures the product is functional, free of defects, and aligned with user requirements, ultimately leading to a better software product.

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



