# JKUAT School Portal Hack

**Issue Summary**
From 5:00 a.m to 9:00 a.m EAT, all records of students results in the online learning section were wiped clean. The issue affected 100% of the student population. The students were still able to access other parts of the portal without fail. The root cause of the wipeout was a hack by a student who gained administrative access to the portal.

**Timeline (all times East African Time)**
- 3:00 a.m: Student gains access to the portal
- 5:00 a.m: All student online learning records are erased
- 5:00 a.m: Pager alerted the portal adminstrator
- 5:15 a.m - 6:30 a.m: Failed login in attempts by admin
- 7:00 a.m: Issue escalated to the school database administrator
- 7:30 a.m: Portal is taken completely offline
- 8:45 a.m: Successful login to portal by the administrator
- 9:00 a.m: Student reports recovered

**Root cause**
At 5:00 a.m EAT, a student illegally gained access to the school portal using the administrator's password and erased all the student scores in the online learning section. The student replaced the password using a randomly generated one that he had developed a program for. With the system being online, by maintaining a continued connection to the system, the administrator could not access the portal or change the password

**Resolution and recovery**
At 5:00 a.m the pager alerted the administrator of the issue and consequent attempts at logging into the portal failed.
At 7:00 a.m the issue is escalated to the database administrator who figures out how the hacker is gaining access to the system
The entire portal is taken offline at 7:30 a.m and using brute force, the team is able to access the portal and change the password and recover the previously lost information
The portal is brought back online at 9:00 a.m

**Corrective and Preventative Measures**
After a thorough investigation the team reviewed and analysed the hack and took the following actions to avoid a future incident:
- The student responsible for the hack was found and expelled from school to serve as an example
- An increase in the verification steps required to access the portal
- An introduction to biometrics for access to the portal
- Increase the number of individuals being paged incase of a failto reduce the mean time to resolution (MTR).
