`cd`
![Image](WeChat3cddaaf6087aac6d8d492887f829cba8.png)
Absolute path before: `wavelet`
With no arguments, it takes me to the home diretory.
no error.

`cd wavelet`
![Image](WeChatc128289071e07651dacb18a92c936315.png)
Absolute path before:`/Home`
Since there is a diretory as my argument, `cd` can bring me to the diretory.
no error.

`cd README.md`
![Image](WeChatffddf02ba04d15fd565c11f350870839.png)
Absolute path before:`wavelet`
With a file as an argument,it could causes an error because `cd` would takes us to diretories not files.

`ls`
![Image](ls.png)
Absolute path before:`Desktop`
Without any argument behind, `ls` just helps me list all files in the current diretory. That's why it lists all files in my Desktop.

`ls PTK`
![Image](lsptk.png)
Absolute path before:`Desktop`
With an argument `PTK`, `ls` helps me list all files and folders in the diretory PTK.

`ls CompileTimeErrors.java`
![Image](lsjava.png)
Absolute path before:`Desktop`
With an argument `CompileTimeErrors.java`. `ls` helps me list the file itself without errors.

`cat`
![Image](cat.png)
Absolute path before:`Desktop`
When I tried to do cat without any arguments, it broke down because `cat` is intended to print out the content in the file, and there are no files there. 

`cat PTK/`
![Image](catPTK.png)
Absolute path before:`Desktop`
When I tried to do cat with a directory as argument, it shows that there are some errors because PTK is an directory and `cat` is intended to work with files.

`cat CompileTimeErrors.java `
![Image](catjava.png)
Absolute path before:`Desktop`
When I tried to do `cat` with a file as argument, it printed out the content inside the file with no errors.
