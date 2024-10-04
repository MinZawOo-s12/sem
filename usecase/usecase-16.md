### USE CASE: 16 Generate Population Report for Texas at the Top Populated State

### CHARACTERISTIC INFORMATION
## Goal in Context
As an analyst, I want to generate a report listing the top populated cities in the state of Texas, where Houston is the primary city provided by the user so that I can to support analysis and reporting.

## Scope
Applicable for smaller organizations.

## Level
Primary task.

## Preconditions
Access to a current population database for Texas is required.

## Success End Condition
A report is generated, specifying the most populated city in Texas (Houston). The report will show population data for both cities and non-cities areas.
## Failed End Condition
No report is generated.

## Primary Actor
Analytics team.

## Trigger
The system receives a request for a report specifying population data and the user input parameters.

### MAIN SUCCESS SCENARIO
The user requests population data through the system.
The system accesses the population database and retrieves relevant population data for cities and rural areas.
The system identifies Houston as the top populated city.
The system generates a report sorted by population.
The report is displayed clearly for the user as allowing for analysis.

### EXTENSIONS
Data for the analyst request is unavailable.

### SUB-VARIATIONS
None.

## SCHEDULE
Due Date: Release 1.0

