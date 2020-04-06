# Os-assignment
To solve the problem in operating system concept we have used the threading multiple
threading and sleeping. A thread is a flow of execution through the process code, with its own
program counter that keeps track of which instruction to execute next, system registers which
hold its current working variables, and a stack which contains the execution history. A thread
is also called a lightweight process. Multithreading is the ability of a program or an operating
system process to manage its use by more than one user at a time and to even manage
multiple requests by the same user without having to have multiple copies of the
programming running in the computer. Sleep() is implemented at the OS level. The processor
doesn't spin when a task/thread/process is sleeping. That particular thread is put on a pending
queue (the thread isn't ready to run) until the time has expired at which point the thread will
be placed on the ready to run queue combining these all made me easy to make process id
manager to keep the record or tarck of free PIDS and ensures that no two active processes
having the same pid and if the process termintes the PID manager may assign its PID to new
process. and we have used the pid values such as #define MIN PID 100 and #define MAX
PID 1000.
