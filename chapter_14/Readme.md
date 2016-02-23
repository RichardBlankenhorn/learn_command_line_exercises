# English Questions

Can you remove blah.txt?

> I first need to cd ~/workspace/davinci_coders_t1_2016/homework/learn_command_line_exercises/chapter_14/tmp.
> From here, I typed echo 'BLAH' > blah.txt to create the blah.txt file.
> To remove this file while in the tmp directory, I typed rm blah.txt and hit enter.

Let's get rid of our development log file.

> I first need to cd ~/workspace/davinci_coders_t1_2016/homework/learn_command_line_exercises/chapter_14/tmp.
> From here, I typed echo 'LOG' > development.log and hit enter.
> To remove this file while in the tmp directory, I typed rm development.log and hit enter.
> If I were to cd .. to the chapter_14 directory, I can type rm -r tmp/ to remove the tmp directory and the development.log file.

Can you remove everything in the slash temp slash foo directory?

> I first need to cd /tmp. From here, I typed mkdir foo and hit enter.
> To remove this file, I typed rm foo and hit enter.

Why is it a bad idea to run the rm -rf command?

> The rm -rf command will recursively force the removal of a directory and its contents in addition to non-existing files. 
> Depending on where I am in the command line, this command could end up removing system files and there is no turning back.

# Do More Questions

Write in your notebook to be careful when running recursive remove on files.

> Typing rm -r will remove the directory and any sub directories or files. This command should only be ran if
> I do indeed want to remove everything within the current directory. If I want to remove a specific file, I should use
> just rm.
