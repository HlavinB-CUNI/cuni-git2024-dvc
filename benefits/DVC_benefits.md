# cuni-git2024-dvc

The specific benefits to using DVC are widespread. Some of the benefits are listed below. 

- It is not a different version of "Git" necessarily, but it uses Git-related techniques to use Git to its advantage.
  
	1) Unlike Git, it requires Anaconda to install and run successfully, however

- Very large quantities of data that Git would traditionally struggle with processing are now done with ease and speed 
due to the characteristics of DVC. 

	1) If you are dealing with a large enough amount of data such that your local machine cannot handle the data load,
	   you can access a remote machine (cloud storage) to retrieve the data 

- There are several similarities with how DVC works compared to Git, which makes using it relatively easy if someone has knowledge of Git already. 
Some of the similarities include:

	1) .dvc files (+directory) are generated with unique "hash" codes for versioning. Similar to .git files and folders. Git is able to read and interpret the hashes easily.
	2) Indentical or similar commands to Git. For example, "push" and "pull" commands are identital to how git's version of "push" and "pull" work 
	3) .dvc files appear even when using Git commands, as expected. For example, ".dvc" files will show up when typing in "git status". You can then add the .dvc files to the git repository.
	4) Remote access allows for many people to work with the changing data. However, you must be careful with where the data is stored (usually cloud storage unlike Git)
	5) Many of the "good practices" for Git also apply to DVC 
		i) commit & push changes often
	   ii) good storage and documentation for storage practices
	  iii) making sure that Git tracks the files (need to check .gitignore to ensure proper file tracking)