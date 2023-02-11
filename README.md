# JSON2CSV

Author: Edgar Medina

### A Python script to convert a JSON file to CSV or a CSV file to JSON.

## Requirements

	sudo apt install python3 python3-pip

	pip3 install csv json collection 

## Usage

	python3 json2csv.py example.json
	

## The script will prompt you for the filename of the file you want to convert. 

Enter the filename (with extension). The script will detect the file type based on the file extension and load the data from the file. The script will then convert the file data and create a new file in the opposite format. The new file will have the same name as the original file with the extension changed to .json or .csv. 

If a file with the same name already exists in the current directory, the script will append a number in brackets to the filename to avoid overwriting the existing file. The script will display a message indicating the name of the newly created file.


## Limitations

The script only supports CSV and JSON file formats.
The script will not convert a CSV or JSON file to another format other than CSV or JSON.
The script does not perform any error checking on the contents of the file being converted. It is assumed that the file is in the correct format.
