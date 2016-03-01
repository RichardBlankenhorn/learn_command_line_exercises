# English Questions

To cat txt or lines to a file?

> If I cd ~/workspace/davinci_coders_t1_2016/homework/chapter_18/tmp I can then cat > newfile.txt.
> On the next line below, I can enter text and press enter.
> I can repeat this step and lastly hit ctrl+c to exit.

Show me the lines in foo.txt that have "ERROR" in them.

> I first cd ~/workspace/davinci_coders_t1_2016/homework/learn_command_line_exercises/chapter_18/tmp.
> From here, I can type grep "ERROR" foo.txt to find lines with the word ERROR.

Show me the lines in bar.txt that have "davinci" in them.

> Still within the chapter_18/tmp directory, I can type grep "davinci" bar.txt to fine lines with davinci

Can you print all the lines in text files that have your first and last name in them?

> Within the chapter_18/tmp directory, I can type grep "Richard Blankenhorn" *.txt to fine all files and lines
> that contain my name.

# Do More Questions

Use quotes to find "new file" and "old file" and "This is".

> I first cd to ~/workspace/davinci_coders_t1_2016/homework/learn_command_line_exercises/chapter_18/tmp
> From here I type grep "new file" *.txt, grep "old file" *.txt and grep "This is" *.txt.

Unix: You can use -i to ignore case with grep. Try grep -i new *.txt

> Still within the chapter_18/tmp directory, I can type grep -i "this" *.txt and still be given files and lines
> that contain "this", even though "this" is capitalized in the files.
> The -i will ignore case (capital or lower cases).
