Group Members:
Warren Murphy
Gabe Mankowski

Stages Completed:
Stage 1 - REPL & Built-In Commands: Completed
Stage 2 - External Command Execution: Completed
Stage 3 - I/O Redirection: Completed
Stage 4 - Pipes: Completed

Known Limitations:
Can't do multi-pipe chains (limited to a single pipe).

Pipe Description:
I fork two processes and then connect the output of the right process to the input of the left process using fds & dup2().