# Development Log

## Instructions
Document your development process as you work on the assignment. Add entries showing:
- What you worked on
- Problems you encountered
- How you solved them
- Time spent

**Requirements**: Minimum 5 entries showing progression over time.

---

## Example Entry Format:

### Entry 1 - [April 1, 2026, 2:30 PM]
**What I did**: Forked the repository and set up my student ID

**Details**: 
- Created GitHub account with university email
- Forked the starter repository
- Changed student ID on line 92 to my actual ID (441234567)
- Compiled and ran the program successfully

**Challenges**: Had to install JDK first because javac wasn't recognized

**Solution**: Downloaded JDK 17 from Oracle website and set PATH variable

**Time spent**: 30 minutes

---

## Your Development Log:

### Entry 1 - [March 29,11PM]
**What I did**: Forked the repository and set up the project.

**Details**: 
- Created a GitHub account using my university email
- Forked the starter repository and renamed it
- Added my student ID in SchedulerSimulation.java
- Ran the program for the first time to understand the output

**Challenges**: It's difficult to download and learn programs.

**Solution**:Carefully read the README file and analyzed the code step by step 

**Time spent**: 5 hour

---

### Entry 2 - [Date and Time]
**What I did**:  Implemented Feature 1 (Process Priority)

**Details**: 
- Added a priority field to the Process class
- Modified the constructor to include priority
- Generated random priority values ​​between 1 and 5
- Displayed priority in the ready queue output

**Challenges**: Learn and write codes

**Solution**: Carefully updated all places where the Process object is created

**Time spent**: 3 hour

---

### Entry 3 - [Date and Time]
**What I did**: 

**Details**: 
- Added a static variable to count context switches
- Incremented the counter each time a process starts execution
- Printed total context switches at the end of the simulation


**Challenges**: Determining the correct place to increment the counter

**Solution**: Added the increment right before starting each thread

**Time spent**: 2:30 hour

---

### Entry 4 - [Date and Time]
**What I did**: 

**Details**: 
- Added fields to track creation time and waiting time
- Used System.currentTimeMillis() to calculate waiting time
- Displayed a summary table at the end of execution

**Challenges**: Calculating accurate waiting time without errors

**Solution**: Carefully tracked the time before each execution and updated waiting time correctly

**Time spent**:  3 hours

---

### Entry 5 - [Date and Time]
**What I did**: Testing and debugging

**Details**: 
- Ran the program multiple times to verify correctness
- Checked output formatting and correctness of values
- Ensured all features worked together properly

**Challenges**: Some waiting time values were incorrect at first

**Solution**: Fixed the timing logic and verified calculations

**Time spent**: 1 hour


---

### Entry 6 - [Optional - Date and Time]
**What I did**: 

**Details**: 

**Challenges**: 

**Solution**: 

**Time spent**: 

---

## Summary

## Summary

**Total time spent on assignment**: 5 Days

**Most challenging part**: 
Tracking and calculating the waiting time correctly was the most challenging part because it required accurate timing and careful updates during execution.

**Most interesting learning**: 
Understanding how Round-Robin scheduling works with threads and how processes share CPU time fairly.

**What I would do differently next time**: 
I would start earlier and test each feature more thoroughly before moving to the next one to avoid debugging issues later.
