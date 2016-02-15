
# pushd and popd

The pushd command will allow you to go to a given directory but the computer will remember which directory you were in when the command as given.
The popd command will then allow you to go back to the directory where the pushd command was given.

If I am in the temp directory, I can create a path of directories i/like/icecream. I do so by typing mkdir i/like/icecream.
At this point, I am still in the temp directory.
If I type pushd i/like/icecream, I will be taken to the icecream directory. However, I can go back to the temp directory
by typing popd.

To mix it up, if at first (from the temp directory) I typed pushd i/like, I will be taken to the like directory.
If I then type pushd icecream, I will be taken to the icecream directory.
If I type popd and hit enter, I am taken back to the like directory.
If I type popd again and hit enter, I am taken back to the temp directory.

# Moving Around

As a test, while still within the temp directory, I entered pushd /Users/richardblankenhorn/Desktop.
This then took me to the Desktop directory.
From the Desktop directory, I typed popd and hit enter. This then took me back to the temp directory I was originally in.

Once I was back in the temp directory, I typed pushd ~/workspace/davinci_coders_t1_2016/in_class and hit enter.
This took me to the in_class directory.
From here, I typed popd and was taken back to the temp directory.

