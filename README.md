# OrangeHRM Application

<img src="https://opensource-demo.orangehrmlive.com/web/images/ohrm_branding.png?v=1721393199309" alt="OrangeHRM" width="300">

## Table of Contents
- [Introduction](#introduction)
- [Release Notes](#release-notes)
- [Project Structure](#project-structure)
- [Tools and Technologies](#tools-and-technologies)
- [Contributing](#contributing)

---
## Introduction
OrangeHRM is a comprehensive Human Resource Management (HRM) System that captures all the essential functionalities required for any enterprise. Copyright (C) 2006 OrangeHRM Inc., http://www.orangehrm.com/

OrangeHRM is free software; you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation; either version 3 of the License, or (at your option) any later version.

OrangeHRM is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

---
# Release Notes
## Version 1.0
This marks the first release of the AutoFramework-2 project.
I am committed to continually enhancing and evolving this framework to ensure it remains updated, robust, and professional.
With each iteration, the project will integrate modern features, improved functionality, and industry best practices to meet the dynamic needs of test automation.

Future updates will focus on:
- Adding advanced automation features.
- Enhancing performance and efficiency.
- Ensuring compatibility with emerging tools and technologies.
- Maintaining alignment with industry standards to deliver a consistently professional and dependable solution.
---
## Project Structure
```
002_0rangeHRM-Website [New2024AutomationProject]
│
├── D.idea/                                      # IDE configuration files (e.g., for IntelliJ IDEA)
├── src/                                         # Source code
│   ├── main/                                    # Main application code (production code)
│   │   ├── java/                                # Java code files
│   │   │   ├── engine/                          # Core engine for automation
│   │   │   │   ├── Actions/                     # Various actions like ElementActions, WaitActions
│   │   │   │   └── BrowserDriverFactory.java    # Browser Driver Factory (managing WebDriver setup)
│   │   │   ├── dataDriven/                      # Data-driven testing logic (e.g., PropertiesManager)
│   │   │   ├── pages/                           # Page object model classes (for interacting with web pages)
│   │   │   └── resources/                       # Configuration files like test data and properties
│   │   ├── resources/                           # Non-Java resources like configuration files (e.g., JSON)
│   │   │   └── testEnvironmentConfig.json
│   │   ├── properties/                          # Constants and property files
│   │   │   ├── FrameworkConstants.java
│   │   │   └── LOGGER.java                      # Logger setup (e.g., Log4j)
│   │   └── test/                                # Test files
│   │       ├── TestBase.java                    # Base test class (common setup for tests)
│   │       ├── BaseTest.java                    # Base class for individual tests
│   │       └── TestClass.java                   # Test class containing test cases
├── resources/                                   # Resources (e.g., log4j2.xml)
└── pom.xml                                      # Maven or Gradle configuration file for dependencies

```

---
## Tools and Technologies
- **Java**: Programming language
- **Selenium WebDriver**: For browser automation
- **IntelliJ IDEA**: A powerful IDE for efficient Java development with advanced features and intelligent code assistance.
- **Maven Dependencies**: For dependency management

---
## Contributing
Contributions are welcome!
We welcome contributions from QA Automation Testing Engineers! To contribute:

1. Fork the repository and clone it to your local machine.
2. Create a new branch for your test enhancements or fixes (`git checkout -b test-enhancement-name`).
3. Write clear, maintainable test scripts and ensure thorough test coverage.
4. Run all tests and confirm they pass successfully.
5. Commit your changes with meaningful messages (`git commit -m 'Add new test or fix'`).
6. Push your branch to your fork (`git push origin test-enhancement-name`).
7. Open a pull request, including a description of your improvements or fixes.

We look forward to your contributions and appreciate your attention to quality!

---
