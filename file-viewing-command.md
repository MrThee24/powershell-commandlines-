# get-content
getting to read the file line by line.
## Get-Content file.txt # Show full file content
## Get-Content file.txt -TotalCount 10 # Show first 10 lines

# Select-Object -Last (tail equivalent)
Takes output from another command and selects only the first part.
## Get-Content file.txt | Select-Object -First 10
