
# TEST CASES and Corresponding Output

## High Level Test Plan
| Test ID | Description | Exp.i/p | Exp.o/p | Actual o/p | Type Of Test |
| --------|:------------|:--------|:--------|:-----------|:-------------|
| H_01 | check if the welcome page is displayed properly | program execution | formatted welcome page | formatted welcome page| Requirement |
| H_02 | check if the menu is displayed properly | login credential | formatted menu page | formatted menu page | Requirement |
| H_03 | not stuck inside in any function | function call | proper function execution with return type and message |  proper function execution with return type and message | Requirement |










## Low Level Test Plan
| Test ID | Description | Exp.i/p | Exp.o/p | Actual o/p | Type Of Test |
| --------|:------------|:--------|:--------|:-----------|:-------------|
| L_01 | verify player credentials | player name | success->menu; failure->exit |  success->menu; failure->exit | scenario |
| L_02 | adding entry to the file | details of individuals | details added successfully |  details added successfully | Technical |
| L_03 | scoring entry | name of the individual | name present->score; name absent->not found | name present->score; name absent->not found | Technical |
| L_04 | modify entry | name of the individual | name present->modify; name absent->not found | name present->modify; name absent->not found | Technical |
| L_05 | display all | - | if entries present->display then; else display->empty file | if entries present->display then; else display->empty file | Technical |
