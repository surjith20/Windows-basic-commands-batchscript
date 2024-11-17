# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file
Save each script in a file with a .bat extension.
Ensure you have the necessary permissions to perform the operations.
Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.


## COMMAND AND OUTPUT

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.
![325137896-e20f8141-6596-43d5-b989-2d2dab0d0dda](https://github.com/user-attachments/assets/045d10cb-afc5-42be-b623-84b7031adfc7)


## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
![325138032-d27849bc-c467-4873-8c79-f7428a160e8c-1](https://github.com/user-attachments/assets/7016b8db-b657-4f1a-b239-0c48129ae8da)
![325138071-1fa80caf-e9f6-43b8-ae3b-32796202e14c](https://github.com/user-attachments/assets/f63efe09-4ea6-4f20-8e02-f31dae3afd88)



## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.

## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.
![325138202-40de307a-60ec-44ed-a9d2-94ed73c8d346](https://github.com/user-attachments/assets/d8c0069f-82c8-4bed-b7b0-3c046bfe0a1d)
![325138398-364ae2ec-b6ff-4583-b92f-bbc9533b06d0](https://github.com/user-attachments/assets/12d900a5-eb8d-4c08-b2a0-eee3e3c815c4)


## COMMAND AND OUTPUT
mv Myfile.txt %userprofile%\Documents 
![325138492-99f98df3-adcf-47a5-befb-fdd0122af505](https://github.com/user-attachments/assets/f91f3ed9-1738-410e-b0e6-a6cc2ed52093)


## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.
@echo off mkdir %userprofile%\Desktop\DocBackup copy %userprofile%\Documents*.docx %userprofile%\Desktop\DocBackup echo Backup completed successfully!






## OUTPUT

![325138649-c9ec83f6-a056-4184-8124-df0c065cc7e9](https://github.com/user-attachments/assets/ae286da9-f41f-4c9e-bffc-5f2db1591f36)




# RESULT:
The commands/batch files are executed successfully.

