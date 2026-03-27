# new-item 
THis is the file amnagement command that is responsible for creating a new file or folder.
## New-Item file.txt -ItemType File # Create a new empty file
## New-Item folder -ItemType Directory # Create a new folder

# remove-item 
This one is a command to delete the file or folder using the command line.
## Remove-Item file.txt # Deletes a file
## Remove-Item folder -Recurse # Deletes folder and contents

# copy-item 
Duplicating the file or folder.
## Copy-Item file.txt backup.txt # Copy file
## Copy-Item folder1 folder2 -Recurse # Copy folder and contents

# move-item 
the command line to move or rename the file.
## Move-Item file.txt Documents/ # Move file to Documents folder
## Move-Item old.txt new.txt # Rename file
