
# Do more exercises

I went in and added directories and then removed them one by one

# English Questions

Can you remove the tmp directory?
Let's remove that directory.

> I first need to access the tmp directory and all of its contents by typing the below command.
> cd ~/workspace/davincit_coders_t1_2016/homework/learn_command_line_exercises/chapter_7/tmp/stuff/things/frank/joe/alex/john/
> Once in this directory, I need to go up one directory before john can be removed. I can type cd .. to do so.
> Once I'm in the alex directory, I can type rmdir john
> After doing so, I can type cd .. to go to the above directory.
> From here, I can type rmdir alex
> Again, I can type cd .. to go to the above directory. I can then type rmdir joe. I need to repeat these steps to remove each directory until
> I get to the directory above the tmp directory. Finally, I can enter rmdir to remove the tmp directory.
> I cannot just delete the tmp directory since it is not empty.


