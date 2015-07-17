# Linux command line cheat sheet

Recursively search for a string inside files of the specified type(s):

	grep -r --include=\*.js "string to search for" ./path/to/folder
	grep -r --include=\*.js --include=*.css "string to search for" ./path/to/folder

