# .txt-file-handling-in-Python
Text File Handling!

File Handling in Python _ text files
•	.txt 
File Access Modes
•	Read Only (‘r’): It opens the text files for reading. If the file does not exist, raises I/O error.
•	Read and Write (‘r+’): It opens the file for reading and writing. Raises I/O error if the file doesn’t exist.
•	Write Only (‘w’): It opens the file for writing. For existing file, the data over-written. Creates the file, if the file does not exist.
•	Write and Read (‘w+’): It opens the file for writing and reading. For existed file, data is truncated and over-written.
•	Append Only (‘a’): It opens the file for writing. The file is created if it does not exist. The data being written will be inserted at the end, after the existing data.
•	Append and Read (‘a+’): It opens the file for reading and writing. The file is created if the file does not exist. The data being written will be inserted at the end, after the existing data. 
•	seek (): Using the seek function, we can move to any point in the file and read the file.
•	close (): we can close the file by using close function.
•	readlines (): It reads the file line by line.
•	with statement: Using with statement, Python will automatically closes the file after read it.
•	write(): This function will returns the length of characters written in the file.
