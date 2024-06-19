<h1>Testing Project for **TripAdvisor**</h1>

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application

Application under test: **TripAdvisor**

Tools used: Jira, Zephyr Squad.

<h2>Functional specifications:</h2>

The below stories were created in Jira and describes the functional specifications of the "**User management**" & "**Booking&Trips**"moduls, for which the final project is performed upon.

![image](https://github.com/claudiacorfu/TripAdvisor/assets/157408462/fbc2e942-5a53-47ad-b862-b1d8fdf56439)

Here you can find the release that was created for this project:

![image](https://github.com/claudiacorfu/TripAdvisor/assets/157408462/2b76ac62-cf06-4977-91dc-9dc0b14eab41)

<h2>Testing process</h2>

The test process was performed based on the standard test process as described below.

<h3>1.1 Test planning</h3>

The Test Plan is designed to describe all details of testing for all the modules from the JPetStore Demo application.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan. The test plan that was created for this project can be found here **(https://github.com/claudiacorfu/TripAdvisor/blob/main/Test%20Plan%20Corfu%20x%20TripAdvisor.pdf)**

<h4>1.1.1. Roles asigned to the project and persons allocated</h4>

**Project manager Tapalaga Ioana**

•	Overall responsibility for project planning, including scheduling and resource allocation for testing activities.
•	Collaborates with product owner to define scope, objectives and project deliverables related to testing.
•	Ensure the test plan is aligned with project goals and timelines.
•	Coordinate communication between team members, stakeholders and other relevant parties.
•	Track progress against the test plan and adjust as necessary to meet project milestones.
•	Manage any risks or issues related to testing activities and escalate as necessary.

**Product owner Vasiliu Madalina**

•	Define acceptance criteria for features under development and make sure they are included in the test plan.
•	Provide input on priority areas for testing based on business requirements and user needs.
•	Review and approve the test plan to ensure that it adequately covers the functionality and features of the TripAdvisor app.
•	Collaborate with the project manager and QA engineer to prioritize testing efforts based on user stories or feature importance.
•	Participate in test case reviews and provide feedback to ensure alignment with intended functionality.

**Software developer Preda Roxana**

•	Develop high-quality code that adheres to coding standards and best practices to facilitate easier testing.
•	Participate in the creation and review of test cases to ensure full coverage of code changes.
•	Correct any defects or problems identified during testing in a timely manner.
•	Provide assistance to the QA engineer in troubleshooting and resolving any technical issues encountered during testing.
•	Work with QA engineer to automate testing where possible to increase efficiency and reliability.

**QA Engineer Corfu Claudia Ioana**

•	Develop the Test Plan document that describes the testing approach, scope, and required resources.
•	Create detailed test cases based on requirements, user stories and acceptance criteria.
•	Run test cases manually or using automated testing tools to validate the functionality of the TripAdvisor app.
•	Document and report any defects found during testing, including reproduction steps and severity ratings.
•	Work with the development team to ensure timely resolution of defects and retesting of fixes.
•	Monitor test coverage and report testing progress to stakeholders, including any risks or issues affecting the testing schedule.
•	Continually improve testing processes and methodologies to improve the quality of the TripAdvisor app.


<h4> 1.1.2 Entry criteria defined </h4>

•	Availability of the test environment with the latest version of TripAdvisor.
•	Completion of initial system integration testing to ensure basic functionality.
•	Availability of test data, including examples of reviews, ratings and user profiles.
•	Test environment set up to simulate various scenarios and usage environments.

<h4> 1.1.3 Exit criteria defined </h4>

•	All critical defects identified during testing are addressed and verified.
•	Performance benchmarks meet predefined thresholds for response time and resource utilization.
•	Security vulnerabilities identified during testing are mitigated or documented with a resolution plan.
•	Identified usability issues are addressed or prioritized for future improvements.
•	Test documentation, including test cases, test results and any deviations are reviewed and finalized.
•	Sign-off by stakeholders indicating readiness for production deployment.

<h4> 1.1.4 Test scope</h4>

<h5> Tests in scope: </h5>

a. Website functionalities
b. User registration and login processes
c. Localization and internationalization testing (multiple languages and regions)
d. Search functionality for hotels, restaurants, attractions, etc.
e. Review submission and moderation processes
f. Booking process for hotels, flights, and restaurants (if applicable)
g. Integration with third-party services (e.g., Google Maps)
h. Performance testing (response times, loading times, etc.)
i. Compatibility testing across different browsers 
j. Security testing (data protection, encryption, etc.)

<h5>Tests not in scope: </h5>

a. Third-party services not directly related to TripAdvisor's core functionalities
b. Backend infrastructure testing (assumed to be covered by the development team)
c. Testing of features not publicly accessible or intended for internal use only
d. Mobile application functionalities (iOS and Android)
e. Accessibility testing (compliance with WCAG standards)

<h4>1.1.5 Risks detected</h4>

<h5>Project risks:</h5>

**Third-Party Integration Risks:**
TripAdvisor relies on various third-party services like payment gateways, mapping services, and social media platforms. Any issues or changes to these integrations can disrupt the project timeline and functionality.
**Network Dependency:**
Network issues can delay project progress. Testing under different network conditions is crucial to identify potential performance bottlenecks and ensure project deliverables meet performance standards.
**Platform Updates:**
Updates to operating systems, web browsers, and mobile devices can affect project timelines and deliverables. Ensuring compatibility with the latest software and device versions during the project lifecycle is necessary to avoid delays.

<h5> Product risks: </h5>

**Third-Party Integration Risks:**
Problems or changes to third-party services can impact the product's functionality and user experience, potentially leading to dissatisfaction and loss of users.
**Network Dependency:**
Network issues can affect the product's performance and accessibility, leading to a poor user experience and potential loss of users.
**Security Vulnerabilities:**
With a large user base, TripAdvisor is a potential target for security breaches. Risks include data breaches, unauthorized access to user accounts, and manipulation of user-generated content. Security testing is crucial to protect user data and maintain trust.
**Platform Updates:**
Compatibility issues due to updates in operating systems, web browsers, and mobile devices can affect the product's performance and user experience. Ongoing maintenance is required to ensure smooth functionality.
**Scalability Challenges:**
As the user base grows, TripAdvisor needs to scale its infrastructure. Failure to anticipate scalability requirements can lead to performance issues and downtime during peak periods, negatively affecting the user experience and the platform’s reputation.

<h4>1.1.6 Evaluating entry criteria</h4>

The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.

<h3>1.2 Test Monitoring and Control<h3>
**Test Monitoring and Control in the Testing Project for TripAdvisor’s Account Module**  

**Test monitoring and control** is a critical component in the testing lifecycle that ensures the testing process is on track, aligns with the project objectives, and meets the quality standards. Here’s how it is reflected in the provided plan:

1. **Test Monitoring**:
   - **Roles and Responsibilities**: The QA Engineer (Corfu Claudia Ioana) is responsible for monitoring test coverage and reporting testing progress to stakeholders. This includes tracking the execution of test cases, documenting defects, and assessing the overall quality and readiness of the product.
   - **Test Schedule**: Detailed test schedule outlines specific timelines for test preparation, execution, regression testing, reporting, and retesting. This schedule serves as a baseline to monitor progress and ensure adherence to the planned activities.
   - **Entry and Exit Criteria (Section 4.1)**: Defines the prerequisites for starting and completing the testing process. Meeting these criteria is a checkpoint to monitor whether the testing process can proceed to the next phase.
   - **Risks (Section 7.0)**: Identifying and assessing risks, such as third-party integration issues, network dependencies, and security vulnerabilities, provides a framework for monitoring potential challenges that may impact the testing process.

2. **Test Control**:
   - **Project Manager Responsibilities**: Tapalaga Ioana is tasked with tracking progress against the test plan, adjusting schedules and resources as necessary, and managing any risks or issues that arise during testing.
   - **QA Engineer Responsibilities**: Includes documenting and reporting defects, working with the development team to resolve issues, and ensuring timely retesting of fixes. This ongoing adjustment and control help maintain the testing schedule and quality.
   - **Test Reporting (Day 8-9 of Test Schedule)**: Compiling test results and preparing summary reports allows for assessing test outcomes and making informed decisions on any corrective actions needed.
   - **Test Documentation Review**: Ensuring all test documentation, including test cases, results, and deviations, are reviewed and finalized provides control over the testing process and ensures all aspects are thoroughly checked and approved.

**Test Monitoring and Control**

**Objective**: Ensure the testing process is effectively tracked and controlled to meet the project objectives and quality standards.

**Activities**:
1. **Progress Tracking**:
   - Daily/weekly status meetings to review testing progress against the schedule.
   - Regular updates on test case execution, defect status, and risk assessment.

2. **Risk Management**:
   - Continuous monitoring of identified risks.
   - Regular updates to the risk log and implementation of mitigation strategies.

3. **Defect Management**:
   - Tracking defects from identification to resolution.
   - Prioritizing defects based on severity and impact on the project timeline.

4. **Test Reporting**:
   - Daily test execution reports.
   - Detailed test summary reports at the end of each testing phase.
   - Final test report highlighting overall test results, major defects, and readiness for production.

5. **Review and Adjustments**:
   - Regular review of test documentation and progress.
   - Adjusting the test plan, schedule, and resources as needed based on ongoing progress and findings.

This section ensures a structured approach to monitoring and controlling the testing process, enhancing transparency, accountability, and the likelihood of achieving the project’s quality objectives.**
**![Screenshot 2024-06-19 164408](https://github.com/claudiacorfu/TripAdvisor/assets/157408462/adac9004-2961-4bab-b461-173e95083710)**
**![Screenshot 2024-06-19 164423](https://github.com/claudiacorfu/TripAdvisor/assets/157408462/c633ecce-a981-4fcd-b063-d17f9b04eb89)**


<h3> 1.3 Test Analysis </h3>
The testing process will be executed based on the application requirements. <b>

The following test conditions were found: <br>

**![image](https://github.com/claudiacorfu/TripAdvisor/assets/157408462/7d813844-cf99-42e1-914a-cfcf8f26755b)**

<h3>1.4 Test Design</h3>

Functional test cases were created in Zephyr Squad based on the analysis of the specifications. The test cases can be accessed here **(inserati linkul catre fisierul cu testele, in format pdf, word sau csv)**

<h3>1.5 Test Implementation</h3>

The following elements are needed to be ready before the test execution phase begins:

**(inserati lista de elemente care sunt evaluate in etapa de implementare)**

<h3>1.6. Test Execution </h3>

Test cases are executed on the created test Cycle summary: **(inserati aici numele cycle-ului pe care l-ati creat)**

Bugs have been created based on the failed tests. The complete bug reports can be found here: **(inserati aici fisierul cu bug-urile pe care le-ati identificat)**

The following is a summary of the bugs that have been found
**(inserati o lista cu titlurile bug-urilor identificate impreuna cu prioritatea si severitatea fiecaruia)**

Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.

1.7 Test Completion
As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team

The traceability matrix was generated and can be found here: **(inserati aici fie o poza cu matricea de trasabilitate din jira, fie linkul catre fiserul excel exportat din jira cu matricea de trasabilitate. Nu uitati sa faceti filtrare dupa type = story)**

Test execution chart was generated and can be found below. 

**(inserati aici raportul de executie generat din jira din sectiunea de dashboards)**

The final report shows that a number **(inserati numarul de teste)** tests have failed of a total of **(inserati numarul de teste)**

A number of **(inserati numarul de bug-uri)** total bugs were found, from which the priority is: **(inserati numarul de bug-uri)** are high and **(inserati numarul de bug-uri)** are medium.

**(inserati aici o concluzie generala a testarii care sa cuprinda cate teste au fost create si executate, ce procentaj aproximativ din cerintele in scop au fost acoperite, daca exista vreo functionalitate pe care nu ai apucat sa o testezi, daca bug-urile gasite impacteaza lansarea produsului in productie sau se pot fixa si ulterior, daca ai identificat riscuri de produs care trebuie mitigate, daca e vreo reecomandare pe care vrei sa o faci pentru lansare, daca sunt ceva lessons learned de care trebuie sa se tina cont la proiectele viitoare etc.)**# TripAdvisor
