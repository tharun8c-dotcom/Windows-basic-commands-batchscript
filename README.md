# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file . Save each script in a file with a .bat extension. Ensure you have the necessary permissions to perform the operations. Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "my-folder"

## COMMAND AND OUTPUT
<img width="334" height="33" alt="image" src="https://github.com/user-attachments/assets/60a1cebc-361d-4121-a2b7-9335c497c156" />

Remove the directory "my-folder"

## COMMAND AND OUTPUT

<img width="323" height="40" alt="image" src="https://github.com/user-attachments/assets/b308138d-a024-44b1-98d3-cf6f015f8a28" />

Create the file Rose.txt

## COMMAND AND OUTPUT
<img width="567" height="406" alt="image" src="https://github.com/user-attachments/assets/ac4fbadc-0b1a-48ed-82a0-99374e5f2d10" />


Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
<img width="490" height="93" alt="image" src="https://github.com/user-attachments/assets/7ac0b532-d65d-41f1-84fd-4bedfed90580" />


Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT

<img width="490" height="93" alt="image" src="https://github.com/user-attachments/assets/58ff46c0-f291-452b-bf71-f74d0f9d6a1e" />


Remove the file hello1.txt

## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT

<img width="342" height="42" alt="image" src="https://github.com/user-attachments/assets/fd6d02bb-2dc7-49a7-8683-d0c7dcfcd7b3" />


List out all the associated file extensions 

## COMMAND AND OUTPUT
<img width="476" height="625" alt="image" src="https://github.com/user-attachments/assets/0684711c-2766-4d18-89ad-14353c9fb82a" />


Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT

<img width="513" height="189" alt="image" src="https://github.com/user-attachments/assets/769e9827-bac7-4c13-83f0-b4e029f8736c" />


## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT
<img width="387" height="75" alt="image" src="https://github.com/user-attachments/assets/bf9e488a-7d2a-4e2b-88e6-b48f1b67ea53" />



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT

<img width="574" height="291" alt="image" src="https://github.com/user-attachments/assets/16482853-9798-479c-b0ec-00b352e6ee50" />



Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT


<img width="393" height="172" alt="image" src="https://github.com/user-attachments/assets/74351e2f-7e02-4d76-89f6-265d5e8c4572" />


Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT

<img width="472" height="137" alt="image" src="https://github.com/user-attachments/assets/aaeb5bae-2a96-4fc0-af05-efe5e4d42f5e" />

Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

<img width="415" height="439" alt="image" src="https://github.com/user-attachments/assets/67360930-1270-4064-852a-397acd9f0286" />


# RESULT:
The commands/batch files are executed successfully.

