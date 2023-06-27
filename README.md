# Sauce-Demo
 
This is a portfolio demo Automation project.

Libraries: Playwright, Node.js

Tools: TypeScript

Implemented Design Patterns: POM & Playwright Fixtures. 

API Testing: High-level API requests methods are defined in the "api-methods" file. They should be used in scope of integration testing, api testing or for generating a user to a particular step in a flow.
(Currently, "SauceDemo" doesn't have an API, so I created only high-level API methods and tests. )

Config: Supports muiltiple environments: local, adhoc $ staging. 
(Currently, since only one environment exists- only "staging").

Global Parameterization : The home/main page is defined as Global Parameter and can be accessed from any file in the project. Currently, is being accessed only by page objects. 



