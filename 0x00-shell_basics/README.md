The following files will contain answers to:
 - 0-current_working_directory - Print current directory
 - 1-listit -Display the contents list of your current directory
 - 2-bring_me_home - changes the working directory to the user’s home directory.
 - 3-listfiles - Display current directory contents in a long format
 - 4-listmorefiles -Display current directory contents, including hidden files (starting with .). Using the long format.
 - 5-listfilesdigitonly - Display Directory long format, with UID and GID an hidden files.
 - 6-firstdirectory - Create a script that creates a directory named my_first_directory in the /tmp/ directory.
 - 7-movethatfile - Move the file betty from /tmp/ to /tmp/my_first_directory.
 - 8-firstdelete - Delete the file betty.
 - 9-firstdirdeletion - Delete the directory my_first_directory that is in the /tmp directory.
 - 10-back - Write a script that changes the working directory to the previous one.
 - 11-lists - List all content in long format in current directory, parent directory and /boot
 - 12-file_type - Write a script that prints the type of the file named iamafile exisiting inside /tmp directory
 - 13-symbolic_link - Create a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory.
 - 14-copy_html - Create a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
//ADVANCED
	 - 100-lets_move - Create a script that moves all files beginning with an uppercase letter to the directory /tmp/u.You can assume that the directory /tmp/u will exist when we will run your script
	- 101-clean_emacs - Create a script that deletes all files in the current working directory that end with the character ~.
	- 102-tree - Create a script that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.You are only allowed to use two spaces (and lines) in your script, not more.
	- 103-commas - Write a command that lists all the files and directories of the current directory, separated by commas (,).
		Directory names should end with a slash (/)
		Files and directories starting with a dot (.) should be listed
		The listing should be alpha ordered, except for the directories . and .. which should be listed at the very beginning
		Only digits and letters are used to sort; Digits should come first
		You can assume that all the files we will test with will have at least one letter or one digit
		The listing should end with a new line
	- school.mgc - Create a magic file school.mgc that can be used with the command file to detect School data files. School data files always contain the string SCHOOL at offset 0.
