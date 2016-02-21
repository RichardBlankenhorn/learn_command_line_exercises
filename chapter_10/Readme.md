# What is ROBOCOPY?

> The robocopy command can copy entire directories or a directory tree in to another directory. Instead of copying each
> individual file in a given directory, I can use robocopy to copy all of the files within the directory in to another
> directory.

# English Questions

Can you copy the foo.txt file to slash tmp?

> To copy the foo.txt file that is located within ~/workspace/davinci_coders_t1_2016/homework/learn_command_line_exercises/chapter_10/tmp,
> I can cd to the tmp directory and then type cp foo.txt /tmp and hit enter.

Can you copy .bash_profile in your home directory to the current directory?

> I can run cp ~/.bash_profile ./ to copy the .bash_profile file to my current directory.

# Do More Questions

Use the cp -r command to copy more directories with files in them.

> I can navigate to the tmp directory by typing ~/workspace/davinci_coders_t1_2016/homework/learn_command_line_exercises/chapter_10/tmp.
> Second, I can make a new directory titled copied_file by typing mkdir copied_file.
> Within the tmp directory for chapter_10, I can copy the file foo.txt to the new copied_file directory by typing
> the command cp -r foo.txt copied_file/.

Copy a file to your home directory or desktop.

> If I am still within the tmp directory as mentioned above, I can copy the foo.txt file to the home directory by typing
> cp -r foo.txt /Users/richardblankenhorn.

Find these files in your graphical user interface and open them in a text editor.

> If I open Finder, I can click on richardblankenhorn, then click on workspace, then click on davinci_coders_t1_2016, then
> click on homework, then click learn_command_line_exercises, then click chapter_10, then click tmp and then click on foo.txt
> For the home directory copy of foo.txt, I can open Finder, click on richardblankenhorn and then click on the foo.txt file.
> After I have accessed either of these foo.txt files, I can place my mouse cursor over the file, double click, select open with
> and then select TextWrangler.

Notice how sometimes I put a / (slash) at the end of a directory? That makes sure the file is really a directory, so if the directory doesn't exist I'll get an error.

> Simply put, placing the / (slash) at the end of the directory name can clarify that I am attempting to copy a file to a directory.
> Otherwise, I may receive an error if that directory doesn't exist. If it doesn't exist, I can create that target directory with the mkdir command
> and then copy the file to that new directory.
