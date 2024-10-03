# cuni-git2024-dvc

Data Version Control (DVC) uses a pretty simple procedure to get started with. 
Below is the procedure.

1) Installation of DVC 
	- Usually this is done with the Anaconda terminal
	
	"pip install dvc"
	
2) Creation of Directory and Ensure Synchonization with Remote Database or Storage
	- This can be in any manner of your choosing. For the sake of this class, Git Bash being used for all purposes makes sense
	- Make sure file names are relevant
	- Make an initial commit
	- If this is not a new project, one would need to make a clone of an existing repository and sync 
	
3) Initialize DVC with "dvc init" command inside of Git Bash

4) **Edit/modify data to your choosing here**
	- Examples of commands to be used are located in the basic_commands JSON file
	
5) All versioning of the data must be done with "git commit"
	- DVC is not a replacement for version controlling, therefore in order to have proper logging and tracking, one 
	  needs to make sure they initialize all Git commands properly