# AutoTester 
## Overview
An automatic tester made for coursework 2, Introduction to Computer Systems (2019-20). The coursework was to complete a skeleton of a Multi-Cycle MIPS processor.
## Contributors
**Michal Glinski** - Wrote the tester, based on his program
**Maksymilian Mozolewski** -- Adapted output and combined the tests into a single script 
## Instructions
To run

`bash runtests.sh`

under the hood this runs test.sh with pre selected flags
if you want to just run a single file test
use
`./setup.sh`
`./test.sh -h` (for help panel)

for single file tests just run:
C files:
`./test.sh -e 600 -t -f <1,2 or 3 here>`
MIPS files:
`./test.sh -e 600 -t -ta -f <1,2 or 3 here>`
where -f 1,2,3 specifies the file to test (1-1dstrfind 2-2dstrfind 3-wraparound)

**The autotester can create massive text files if you fail a lot of the tests**
