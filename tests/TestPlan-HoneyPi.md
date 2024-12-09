# HoneyPi Test Plan

## Test Plan Identifier:

Each test case provided will be labeled as "HPI-TC01", "HPI-TC02", etc. Using this labeling convention will
allow for easy location between both this test case document, and the Excel document that will be
used for test case execution.

## Introduction:
 
The purpose of this test plan is to ensure the functionality, reliability, and security of the 
HoneyPi device, a portable intrusion detection system designed to emulate decoy services and collect 
valuable data on potential cyberattacks. Testing the device is critical to validating its capabilities, 
identifying vulnerabilities, and ensuring it meets the intended objectives as an educational tool for 
analyzing common cyberattack techniques. This test plan outlines the approaches and methodologies that 
will be used to verify the effectiveness of the HoneyPi system under various conditions and use cases.

The HoneyPi device will undergo three primary types of testing: ad hoc testing, unit testing, and crowdsourced 
testing. __Ad hoc__ testing will be conducted during the configuration and development phase to provide immediate 
feedback on the system’s performance. These tests will allow for rapid identification of bugs and design flaws, 
ensuring the iterative development process is efficient. __Unit testing__ will follow a more structured approach, 
focusing on individual components of the device, such as container orchestration, honeypot logging mechanisms, 
and network interactions. These tests will be documented in an Excel spreadsheet, specifying test cases, expected results, 
and any deviations observed. Finally, __crowdsourced__ testing will involve peers and collaborators who will use a predefined
test plan and survey to evaluate the device in real-world scenarios. This phase will collect valuable external feedback, 
offering diverse perspectives on the device's usability, functionality, and overall design.

Several constraints may impact the testing procedures. The HoneyPi device relies on the availability of local network environments, 
meaning some tests may be limited by variations in network configurations or restrictions imposed by firewalls and routing policies. 
Additionally, the Raspberry Pi hardware may introduce resource limitations, such as restricted processing power or memory, which could 
affect the performance of the decoy services under high activity. Testers must also adhere to ethical and legal guidelines, ensuring that 
the device is only tested on authorized networks and systems with explicit permission. Despite these constraints, the test plan aims to 
provide a comprehensive assessment of the HoneyPi device’s capabilities while maintaining compliance with ethical standards.

## References:

Link for the project repository: <https://github.com/zachWeav/HoneyPi/tree/master>

Proposal Document: <https://github.com/zachWeav/HoneyPi/blob/master/docs/CSCI497_ProjectProposal_ZachWeaver.pdf>

Requirements document: <https://github.com/zachWeav/HoneyPi/blob/master/docs/CSCI497_ProjectRequirements_ZachWeaver.pdf>


## Test Items:

-   HoneyPi Device

## Device Features to be Tested:

-   Scanning Device for open ports.

-   Decoy Service Availability

-   Decoy SSH server connection.

-   Decoy SQL Database connection.

-   Container Remote Command Execution.

-   Container Intrusion Logging Mechanisms.

-   Container Orchestration Monitoring & Metrics Reporting.

-   Raspberry Pi Host Security

## Features Not to be Tested:

-  Specific Raspberry Pi Device Configuration

-  Advanced Threat Analysis

-  Compatibility Across All Network Environments

-  Device Hardware Resilience

-  Integration with Other Security Mechanisms

## Approach:


## Item Pass/Fail Criteria:

Whether or not a test case passes or fails will be determined by a defined
set of questions including:

-   Is the feature of the device functional?

-   Does specific functionality perform as expected?

-   Are there any errors when executing the tests?

-   Was the test sufficient?

If anything still needs to be addressed after executing a test case, 
then the test case is a failure. The device must be fixed and
the feature tested again asking the same questions. If all required criteria are met
with no additional issues found, then the test will be considered a pass.

## HoneyPi Test Cases:



## Suspension Criteria and Resumption Requirements:



## Test Deliverables:

-   HoneyPi Test Plan

-   HoneyPi Test Cases (excel)

## Test Environment:


## Estimate:

There are no monetary costs involved for the development or testing of the
device and every tool being used is open sourced and available for public use.

## Schedule:

Testing milestones:

-   Test Plan Completed: 12/9/2024

-   Ad hoc tests: 12/30/2024

-   Soft-Tests:

-   Peer-Tests: 

## Responsibilities:


## Risks:


## Assumptions and Dependencies:


