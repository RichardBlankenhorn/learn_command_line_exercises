# English Questions

Can you put "This class is fun" into bar.txt?

> Other than simply typing echo 'This class is fun' > bar.txt, I can also type echo 'This class is fun' | cat > bar.txt

Can you put "Oh so much fun" into foo.txt?

> I can type echo 'Oh so much fun' > foo.txt or type echo 'Oh so much fun' | cat > foo.txt

What does the | (pipe) command do?

> The | command will use the output received from the command on the left and then use it as input for the command on the right.
> In the above questions, I first echo 'This class is fun' and the output I can see is This class is fun. 
> On the right, I am using cat to add something to the foo.txt file. That something is the output I received on the left command.
> As a result, This class is fun is that something and is printed or added to the bar.txt file. 

What does the < command do?

> The < command will use the input from the file listed on the right and apply it to the program on the left.
> If I type cat < foo.txt, this will take Oh so much fun and then apply it to the command cat, which will print Oh so much fun.

What does the > command do?

> The > command will take the contents or output on the left side and write those contents to the file on the right side.
> If I type cat bar.txt > foo.txt, the output on the left, which in this case is This class is fun, is added to the foo.txt file.

What does the >> command do?

> The >> command will add output to a file and this output is derived by the command on the left side of >>. 
> With our bar.txt file, if I were to give the command echo 'Richard' >> bar.txt,
> This would then add Richard to that file. We would now see This class is fun and Richard in that file.
