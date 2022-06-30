1. Please answer the following questions.

    1. What command would you use to clear the screen?<br>
        clear

    1. What is the shortcut command to open a new tab in your terminal?
        Ctrl+Shift+T

    1. What key would you use to scroll through previous commands you’ve typed before?<br>
    Up Arrow
    1. You have a three txt files and an empty folder on your desktop. Write a single line command that will move all three txt files into the folder. <br>mv *.txt 'empty folder'

    1. You want to inspect the differences between two txt files myfile1.txt and myfile2.txt. Write a command that would display the differences in content between these two files. <br> diff myfile1.txt myfile2.txt

    1. Write a command that would delete this folder and all of the contents inside. <br> rm -r folder

    1. What is the command to list all files, including hidden files?  Write a command that displays all .css files in a folder. <br> ls -a | ls *.css


    1. What is the command to find a file by name on your disk (or some other storage medium)?<br> find / -name name.file


    1. What is the command to find a file by content<br>find . -type f -exec grep "str" '{}' \; -print

        1. in your folder<br>find ./ -type f -exec grep "str" '{}' \; -print
        2. on the disk?<br>find / -type f -exec grep "str" '{}' \; -print

        That is, how do you search for a word or phrase in the file contents? <br>find ./ -type f -exec grep "str" '{}' \; -print<br>

    1. Use a bash command to create a file named YourName.txt with no content in it.  Look at the permissions.<br>touch YourName.txt<br>ls -lha

        1. Now change the permissions so everyone can read it and execute it.<br>chmod a+rx YourName.txt<br>
        2. Now change the permissions so only you can read it.<br>chmod 400 YourName.txt