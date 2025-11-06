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
<img width="578" height="110" alt="image" src="https://github.com/user-attachments/assets/8b0bcc51-0665-4c96-8968-27398e6a0136" />

## COMMAND AND OUTPUT

Remove the directory "my-folder"
<img width="374" height="46" alt="image" src="https://github.com/user-attachments/assets/0c785b6f-0714-4747-aebd-52959e773ca9" />

## COMMAND AND OUTPUT


Create the file Rose.txt
<img width="623" height="347" alt="image" src="https://github.com/user-attachments/assets/89cccd2a-f37e-498c-8271-0ab892fcd3d1" />

## COMMAND AND OUTPUT


Create the file hello.txt using echo and redirection
<img width="573" height="106" alt="image" src="https://github.com/user-attachments/assets/af67c6ff-bcbd-4b14-97d0-d2ae141470d9" />

## COMMAND AND OUTPUT

Copy the file hello.txt into the file hello1.txt
<img width="494" height="123" alt="image" src="https://github.com/user-attachments/assets/d0be2f2c-25ee-426c-be37-ba715902b6de" />

## COMMAND AND OUTPUT

Remove the file hello1.txt
<img width="425" height="182" alt="image" src="https://github.com/user-attachments/assets/96abba86-00e6-4c69-8131-5a6ee4aca55c" />

## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory
<img width="459" height="172" alt="image" src="https://github.com/user-attachments/assets/776d9bce-e439-4180-b2e1-f0aeb013dfd9" />

## COMMAND AND OUTPUT

List out all the associated file extensions 
<img width="524" height="1060" alt="image" src="https://github.com/user-attachments/assets/5e55078b-904e-4b65-b045-345e47e4a30e" />
<img width="780" height="548" alt="image" src="https://github.com/user-attachments/assets/3b10622b-a30e-44b8-ac4a-a475d5cf7b5f" />

## COMMAND AND OUTPUT


Compare the file hello.txt and rose.txt
<img width="498" height="186" alt="image" src="https://github.com/user-attachments/assets/2cbd38a3-d623-445a-b1ce-2f4ce7c77516" />

## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".


<img width="405" height="101" alt="image" src="https://github.com/user-attachments/assets/6f500e6e-b350-4dec-a68a-5eebcc508448" />



## OUTPUT



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT




Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT



# RESULT:
The commands/batch files are executed successfully.

