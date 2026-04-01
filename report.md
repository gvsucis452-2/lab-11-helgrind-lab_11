Q1:
Helgrind reports a possible data race at the memory address of the global variable *balance* when thread1 attempts to write a value to *balance*.
It also shows if a thread holds any locks and what the write conflict is. 

Q2:
No thread errors happen. 

Q3:
Helgrind now recognizes a lock exists and shows when and where it was created, but also still reports a data race. 

Q4:
