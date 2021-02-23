# CS-320
Repository for CS-320-T3224 Software Test Automation&amp; QA 21EW3 (SNHU)

This repo contains the project we have worked on throughout this course. It includes a simple application that creates objects (appointments, tasks, and contacts) and adds those objects to lists. Alongside the application, are Junit tests I wrote for verifying and validating. 

* How can I ensure that my code, program, or software is functional and secure?

When using Java, it is important to ensiure that methods and variables are declared correctly - this means making sure that variables and methods that should not be used by other classes are declared as private. As a general safety precaution, it is best to use getters and setters (methods) to update private variables. Secure software prevents access from parties that are not essential to the function of the program - the principle of least privilidge applies to software components as well as individuals. 

Functionality is generally easy to test, initially - run it and see if it works as expected. After verifying that code works as expected, it's best to see if it can be run NOT as expected - this is where software testing comes in. Testing various parameters in different ways gives us an idea of the vulnerabilities that might exist in the code. We should also test to get an idea of the coverage of our testing - once reasonably covered, we can be more sure of our code or we can take the opportunity to refine our tests further to avoid any mistakes that could have been overlooked. 


* How do I interpret user needs and incorporate them into a program?

User needs are best represented with well-defined requirements and requirements definitions. First, gather what the client needs (where they are trying to add value), then break that value down into manageable pieces - requirements, break down the requirements into pieces with specific and defined criteria - from here the definitions should be specific enough for a developer to start planning the code. 

Requirements should be specific, should add value, and should be measurable. Software can be desinged in various ways, but from here it is best to write it/test it/return it to the user for feedback before refining it further. 


* How do I approach designing software?

There are various ways to design software (such as some of the steps listed above), but the best is:
1. Gather needs (and sometimes wants) from the client that will add VALUE
2. Refine those needs into requirments
3. Refined requirments into specific definitions
4. Write first draft of code 
5. Ensure code runs
6. Write and run tests for code (unit, component, integration, etc.)
7. * This step depends on the SDLC being used

Another way to wrote software is to write the tests first and then the code - this is called test-driven development. This type of development preceeds development with specific tests that need to be passed by the software and guides the process slightly differently. 
