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
## COMMAND AND OUTPUT

Create a directory named "my-folder"



<img width="601" height="180" alt="Screenshot 2026-08-21 133547" src="https://github.com/user-attachments/assets/87c5ed6c-e799-4637-9889-ad9cdab6f90b" />

## COMMAND AND OUTPUT

Remove the directory "my-folder"

<img width="623" height="102" alt="Screenshot 2026-08-21 133749" src="https://github.com/user-attachments/assets/637b3039-076c-4ea1-a2c1-dcfa50bbfd5b" />



## COMMAND AND OUTPUT


Create the file Rose.txt


<img width="713" height="419" alt="Screenshot 2026-08-21 134245" src="https://github.com/user-attachments/assets/56d87bff-de6d-4119-aa2f-6649c7c491ff" />



## COMMAND AND OUTPUT


Create the file hello.txt using echo and redirection

<img width="638" height="180" alt="Screenshot 2026-08-21 134341" src="https://github.com/user-attachments/assets/86c8d0c1-327c-44b9-935b-c5c530c09da4" />



## COMMAND AND OUTPUT

Copy the file hello.txt into the file hello1.txt

<img width="582" height="234" alt="Screenshot 2026-08-21 134454" src="https://github.com/user-attachments/assets/46f840d5-d94d-4b60-8df4-796b55796c4d" />



## COMMAND AND OUTPUT

Remove the file hello1.txt

<img width="589" height="294" alt="Screenshot 2026-08-21 134556" src="https://github.com/user-attachments/assets/946f091e-641a-41c2-b2a8-7e267d39a34c" />



## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory



<img width="479" height="180" alt="Screenshot 2026-08-21 134848" src="https://github.com/user-attachments/assets/c2315d91-7bfe-47dc-9b07-22896b692241" />



## COMMAND AND OUTPUT

List out all the associated file extensions 

<img width="629" height="1122" alt="Screenshot 2026-08-21 134934" src="https://github.com/user-attachments/assets/8409c2dc-6741-42ca-a06c-44a3c52a5b6b" />



## COMMAND AND OUTPUT


Compare the file hello.txt and rose.txt

<img width="562" height="273" alt="Screenshot 2026-08-21 135201" src="https://github.com/user-attachments/assets/85045b80-181b-4883-a393-faeb88ac6819" />


## Exercise 2: Advanced Batch Scripting

## OUTPUT

Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".

<img width="497" height="156" alt="Screenshot 2026-08-21 140412" src="https://github.com/user-attachments/assets/425fc308-ce06-49c0-a0ca-629f0aea43ab" />




## OUTPUT



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



<img width="665" height="315" alt="Screenshot 2026-08-21 140642" src="https://github.com/user-attachments/assets/5bbe3b04-3be3-4770-b632-cbf9fb718565" />



## OUTPUT




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.

<img width="471" height="223" alt="Screenshot 2026-08-21 140752" src="https://github.com/user-attachments/assets/63c424d2-94bd-44bb-8646-f502fb3dbba4" />



## OUTPUT




Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

<img width="587" height="270" alt="Screenshot 2026-08-21 141105" src="https://github.com/user-attachments/assets/30e166e7-a39e-4e74-9b52-650ae956cce8" />



## OUTPUT


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


<img width="515" height="454" alt="Screenshot 2026-08-21 141304" src="https://github.com/user-attachments/assets/cabab12e-9320-4b6a-9e5d-46e40fb8f8eb" />




# RESULT:
The commands/batch files are executed successfully.

