# Linux command line cheat sheet

Recursively search for a string inside files of the specified type(s):

	grep -r --include=\*.js "string to search for" ./path/to/folder
	grep -r --include=\*.js --include=*.css "string to search for" ./path/to/folder

Find a file by name:

	find ./where/to/look -type f -name 'file-name'

Find a directory by its name:

	find ./where/to/look -type d -name 'directory-name'
