# job_executor
Implementation of a distributed file management tool

compile/execute:
	$ make
	$ ./jobExecutor –d docfile –w numWorkers
	
  Give a command, when prompt is given.
	Α command can be one of the following:
		1)> /search q1 q2 q3 … q18 -d deadline
		(Note: deadline must be a positive integer)
		2)> /maxcount word
		3)> /mincount word
		4)> /wc
		5)> /exit
    
    
This was an assignment for the Systems Programming class of DIT of UoA (2018)
