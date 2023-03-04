# README GENERATOR

## Description:
The file **readme_generator** is a shell script that can assist you (an alx student) in generating simple but detailed READMEs for your low level programming projets.

## How to use it:
1. Copy the **readme_generator** file into the your current project directory *eg 0x06-pointers_arrays_strings*
2. Make the script executable by running the commmand **chmod u+x readme_generator**.
3. Run the script with the command **./readme_generator**
4. The script will request you to type the names of the files you want to describe in your **README.md**
5. Type the filenames seperated by spaces and hit the enter/return key when you are done.

## How it works & Requirements
1. The script works by looking at the comment section just below the headers in the c files.
    ![Example of comment section!](/assets/images/example.png)
2. The script copies all these comments and stops after it copies the comment with the **Return** keyword.
3. For the script to work as intened ensure that the last statement of the top comment section begins with the **Return** keyword otherwise the script will copy any line in the file starting with \* symbol.
