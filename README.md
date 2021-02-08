# 16 ways to stack a cat
## How to compile and run the codes
The file structure has assignment as root folder which contains Makefile. If we run Makefile using make command, then executables of each stack
implementation are created in bin folder.Each stack folder has one main.cpp along with stack.cpp and stack.h if necessary.

## Stack0 -- Files as Modules
**In this method we identify stacks using numbers rather than names.**The implementation of stack is done with linked list and each stack is stored as member of other linked list.Using stack.h as interface the data and implementations are hidden.Only the abstract is visible to the user.
