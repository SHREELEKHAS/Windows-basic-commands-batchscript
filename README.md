## SHREE LEKHA.S 212223110052
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
```
mkdir %userprofile%\Desktop\MyLab
```
![Screenshot 2024-09-17 203924](https://github.com/user-attachments/assets/736d048f-18c9-458a-bab6-ca0601c3759c)

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.


## COMMAND AND OUTPUT
```
cd %userprofile%\Desktop\MyLab
type nul > MyFile.txt

```
![Screenshot 2024-09-17 204144](https://github.com/user-attachments/assets/6971dd2c-4be3-4a29-b792-054453067c7a)

List the contents of the "MyLab" directory.


## COMMAND AND OUTPUT
```
dir %userprofile%\Desktop\MyLab
```
![Screenshot 2024-09-17 204230](https://github.com/user-attachments/assets/a2d0d200-f935-4e58-bc3b-43313d4d8fa7)

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.

## COMMAND AND OUTPUT
```
mkdir %userprofile%\Desktop\Backup
copy MyFile.txt %userprofile%\Desktop\Backup

```
![Screenshot 2024-09-17 204324](https://github.com/user-attachments/assets/8dd2a425-dd22-4edc-b0da-fdaa98a7e14a)

Move the "MyLab" directory to the "Documents" folder.


## COMMAND AND OUTPUT
```
move MyLab Documents
```
![Screenshot 2024-09-17 204412](https://github.com/user-attachments/assets/4d93e4bc-e348-44a3-b9e1-57e6119cc3e0)


## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.







## OUTPUT
```
BackupScript.bat
```

![Screenshot 2024-09-17 204525](https://github.com/user-attachments/assets/ab84d3d2-abe0-4caf-8b4b-0795fe4f10d5)



# RESULT:
The commands/batch files are executed successfully.

