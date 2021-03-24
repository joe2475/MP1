To run the classes I needed to change the portion of the code that contained String mainclass = "Example" to String mainclass = "project.Example". This was done for all files.

Part 1:
	The code outputs the correct dominators. To test this I created another java file that was easier to follow through with the output. This was created from one of the slides in the lectures. The output matched with the results in the lecture and thus the code is correct. 

Part 2:
	PTA total edges: 7
	PTA time: 1527ms
	CHA total edges: 12
	CHA time: 1494ms

	CHA is faster in it's executution, but it is not as precise as PHA. This is because PHA has every call relationship that occurs and also some calls that would not normally happen in the program. 


	Part 3:
		Files for 3A are in the SootOutput Folder

		Sample output for 3B: 
		Thread Thread-5 wrote static field x
		Thread Thread-6 wrote static field x
		Thread Thread-6 read instance field y of object r0.<project.HelloThread$TestThread: int y>
		Thread Thread-6 read instance field y of object r0.<project.HelloThread$TestThread: int y>
		Thread Thread-5 read instance field y of object $r2.<project.HelloThread$TestThread: int y>
		Thread Thread-5 wrote static field x
		Thread Thread-5 wrote static field out
