# pipelinemaster

Loom video:
https://www.loom.com/share/648f0a57909244139f56cb571b8e6bde


Task 1 
In this task you are asked to use the ls command to list out all of the contents in your /etc and your /run folders.
First, deal with the /etc folder. Use the ls command to list it's contents and redirect those contents to a file called file1.txt
Do the same for the /run folder but redirect the content to a file called file2.txt instead.
There should be 2 commands required to complete this. Please show these commands in your submission.
Hint: ls /foo will list the contents in the /foo directory.

Task 2
Once you have file1.txt and file2.txt created, it is time to complete task 2 of the assignment!
In Task 2, you are asked to use the cat command to combine together (i.e. concatenate) file1.txt and file2.txt into another file called unsorted.txt
But, in the same pipeline you are also asked to also use the sort command with the r option to to reverse the output from the cat command and redirect that reversed output to another file called reversed.txt
Task 2 should all be completed in one pipeline. Please show this pipeline in your submission.
Note: Solutions using the tac command (reverse of the cat command) will not be valid.
Hint: Take a look at the tee command
Submission Guidelines
