# Linux command line cheat sheet

Recursively search for a string in files of specified type:

	grep -r --include=\*.js "string to search for" ./path/to/folder
	grep -r --include=\*.js --include=*.css "string to search for" ./path/to/folder

Find a file:

	find ./where/to/look -type f -name 'file-name'

Find a directory:

	find ./where/to/look -type d -name 'directory-name'
