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
```
Developed by: KANNAN.S

Register No: 212223230098
```
## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.


## COMMAND AND OUTPUT

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.
%userprofile%\Desktop\MyLab

![image](https://github.com/Kannan-S-coder/Windows-basic-commands-batchscript/assets/147120710/1b9e4d42-795d-469e-86f1-39b8297dd1be)


## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
%userprofile%\Desktop\MyLab
![image](https://github.com/Kannan-S-coder/Windows-basic-commands-batchscript/assets/147120710/e1ee2364-a7b7-4198-9553-293d848bb2bc)

![image](https://github.com/Kannan-S-coder/Windows-basic-commands-batchscript/assets/147120710/ca2fa9ac-d35a-427f-bdb0-d31246625083)



## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
%userprofile%\Desktop\MyLab

![image](https://github.com/Kannan-S-coder/Windows-basic-commands-batchscript/assets/147120710/dae24ecc-8771-42d9-9d10-0681cf111054)


## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.
%userprofile%\Desktop\Backup

![image](https://github.com/Kannan-S-coder/Windows-basic-commands-batchscript/assets/147120710/7f19f247-2c21-497a-88e9-3ddee05ea7c5)

![image](https://github.com/Kannan-S-coder/Windows-basic-commands-batchscript/assets/147120710/6775b1b1-2b88-42e6-bf90-98c248d17f79)


## COMMAND AND OUTPUT
mv Myfile.txt %userprofile%\Documents

![image](https://github.com/Kannan-S-coder/Windows-basic-commands-batchscript/assets/147120710/202cde30-ad9e-47b4-93d2-f5cbf1c24fb0)



## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

@echo off mkdir %userprofile%\Desktop\DocBackup copy %userprofile%\Documents*.docx %userprofile%\Desktop\DocBackup echo Backup completed successfully!




## OUTPUT
![image](https://github.com/Kannan-S-coder/Windows-basic-commands-batchscript/assets/147120710/078af57b-6e37-4888-a3ae-1f4e267abf7a)





# RESULT:
The commands/batch files are executed successfully.

