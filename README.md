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
mkdir my-folder


<img width="788" height="483" alt="image" src="https://github.com/user-attachments/assets/016eda23-c6ed-4506-83fb-993121cd5521" />


Remove the directory "my-folder"


## COMMAND AND OUTPUT
rmdir my-folder
<img width="1632" height="256" alt="image" src="https://github.com/user-attachments/assets/d31793c7-8598-4f18-b413-eb816e96b929" />



Create the file Rose.txt

## COMMAND AND OUTPUT

cat > Rose.txt


<img width="474" height="134" alt="image" src="https://github.com/user-attachments/assets/6f1ad386-02ec-4cdb-9f24-7caff473956e" />

Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
echo "Hello">hello.txt
cat hello.txt

<img width="474" height="134" alt="image" src="https://github.com/user-attachments/assets/6edfac79-11f6-4a6d-b2f5-bb11b854059a" />

Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
cp hello.txt hello1.txt
cat hello1.txt


<img width="474" height="134" alt="image" src="https://github.com/user-attachments/assets/3f5b64b1-5b4f-41c3-9527-e793b85f2019" />


Remove the file hello1.txt

## COMMAND AND OUTPUT
rm hello1.txt
<img width="1618" height="338" alt="image" src="https://github.com/user-attachments/assets/d2d34a0a-c68e-4c00-865b-0d74545e7b9e" />




List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT

List out all the associated file extensions 
ls hello1.txt


<img width="655" height="79" alt="image" src="https://github.com/user-attachments/assets/b2e3535e-fb09-4f3d-968f-8b23f2e2fb3b" />


## COMMAND AND OUTPUT


Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT
diff hello.txt Rose.txt


<img width="612" height="146" alt="image" src="https://github.com/user-attachments/assets/12db069e-1538-44f4-b247-8e238f37bacc" />


## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".




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

