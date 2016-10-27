Sonar Lua
==========

The plugin enables analysis of Lua projects within SonarQube.

Steps to Analyze a Lua Project

Install SonarQube Server.5.6+

Install SonarQube Scanner.
Install Lua Plugin (see Installing a Plugin for more details)
Create a sonar-project.properties file at the root of your project.
Run sonar-scanner command from the project root dir
Follow the link provided at the end of the 
analysis to browse your project's quality in SonarQube UI


## Description
This plugin enables analysis of:
 * Lua files
  
 within [SonarQube](http://www.sonarqube.org). It:
 * Computes metrics: lines of code,functions, class, statements, line complexity, etc.
 * the next check will 
 * Performs more than [15 checks](#available-checks)
 * Provides the ability to write your own checks



## Metrics

  LINES_OF_CODE,
  LINES,
  FILES,
  COMMENT_LINES,
  FUNCTIONS,
  STATEMENTS,
  TABLECONSTRUCTORS,
  COMPLEXITY;

### Complexity
The following elements increment the complexity by one:
LuaGrammar.FUNCTION,

 FUNCSTAT,  
FUNCTIONCALL,
    
     WHILE_STATEMENT,
      FOR_STATEMENT,
      IF_STATEMENT,
      .DO_STATEMENT,
     .REPEAT_STATEMENT,
     LuaGrammar
 Available Checks

## Custom Checks

XPathCheck.class,
FunctionComplexityCheck.
FunctionWithTooManyParametersCheck.
TableComplexityCheck
NestedControlFlowDepthCheck
LineLengthCheck
FileComplexityCheck.
TableWithTooManyFieldsCheck.
FunctionCallComplexityCheck

