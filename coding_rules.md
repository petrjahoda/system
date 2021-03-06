# Coding rules
## Naming
Software naming is lower case only with underscore.
First name is the name of the software.
Second name is the type.


**Examples:**
- zapsi_service
- state_service
- terminal_service
- display_webservice
- terminal_webservice
- lcd_webservice
- database
- ...

File naming is lower case one name only.

**Examples:**
- config.go
- main.go
- log.go

Variable naming is camelCase, reasonable name should be used. Use runningDevices instead of rd, runDev, ...

## General coding rules
https://dave.cheney.net/practical-go/presentations/qcon-china.html#_package_design

## Philosophy
Files should be maximal 1000 lines long, optimal below 500 lines.<br>
Reduce communication with expensive things (like databases) to minimum.<br>
Make code readable, it should read like an english book.<br>
Comment are forbidden, use logging instead.<br>
Always use main.go as a starting point for every software. Use default go coding conventions.<br>
Handle errors first. Use switch instead of multiples if-else.<br>
Every procedure, method or functions starts with logging message and ends with logging messages with result and elapsed time information.



## Git commits
Commit after every change. Use these tags:

* ```Added``` for new features.
* ```Changed``` for changes in existing functionality.
* ```Deprecated``` for soon-to-be removed features.
* ```Removed``` for now removed features.
* ```Fixed``` for any bug fixes.
* ```Security``` in case of vulnerabilities.


## Technologies

Main language: Go<br>
ORM: GORM<br>
Http Router and Muxer: Httprouter<br>
Main Javascript Charting Library: D3<br> 
Main database: PostgreSQL<br>
Runtime: Docker<br>
Git repository: Github<br>
Licence: MIT<br>

## Versioning

Version contains year, quarter, month of the quarter and day of the month.

2019.2.1.24 is version from year 2019, second quarter, first month of second quarter, which is April, and from 24th of April.

Every week build new "latest" and proper "2019.2.1.24" version




