cd
![Image](WeChat3cddaaf6087aac6d8d492887f829cba8.png)
Absolute path before: wavelet
With no arguments, it takes me to the home diretory.
no error.

cd wavelet
![Image](WeChatc128289071e07651dacb18a92c936315.png)
Absolute path before:Home
Since there is a diretory as my argument, cd can bring me to the diretory.
no error.

cd README.md
![Image](WeChatffddf02ba04d15fd565c11f350870839.png)
Absolute path before:wavelet
With a file as an argument,it could causes an error because cd would takes us to diretories not files.

ls
<img width="700" alt="WeChat9e1474cd906a066eaf82aa915fb70235" src="https://github.com/JekyllWu/cse15l-lab-reports/assets/166572245/e4ce0ebb-1653-46ed-ae7b-e1ef66cacfa9">
Absolute path before:Desktop
Without any argument behind, ls just helps me list all files in the current diretory. That's why it lists all files in my Desktop.

ls PTK
<img width="1098" alt="WeChatda2002e73c92990afaf049f6816ffbf0" src="https://github.com/JekyllWu/cse15l-lab-reports/assets/166572245/2b95c9ee-9b47-4128-905c-c8f28014f2a9">
Absolute path before:Desktop
With an argument PTK, ls helps me list all files and folders in the diretory PTK.

ls CompileTimeErrors.java
<img width="966" alt="WeChat7def924b819e19148d33d057ca0a5e81" src="https://github.com/JekyllWu/cse15l-lab-reports/assets/166572245/de6324aa-14ac-4e07-9717-b534a6e99a5f">
Absolute path before:Desktop
With an argument CompileTimeErrors.java. ls helps me list the file itself without errors.

cat
<img width="734" alt="WeChat662c8817b8fe9f68903825fe713ddd80" src="https://github.com/JekyllWu/cse15l-lab-reports/assets/166572245/592809b3-8ec7-4792-99c5-d1e7a43d57d3">
Absolute path before:Desktop
When I tried to do cat without any arguments, it broke down because cat is intended to print out the content in the file, and there are no files there. 

cat PTK/
<img width="620" alt="WeChate1b433d79dbd74e3bab02648b3e21cc9" src="https://github.com/JekyllWu/cse15l-lab-reports/assets/166572245/75e52b13-79e1-477b-84f4-388383127824">
Absolute path before:Desktop
When I tried to do cat with a directory as argument, it shows that there are some errors because PTK is an directory and cat is intended to work with files.

cat CompileTimeErrors.java 
<img width="936" alt="WeChat60be824b2955a14e268db79ad3b1c762" src="https://github.com/JekyllWu/cse15l-lab-reports/assets/166572245/f30bba88-5978-40c1-ac74-0b85dcb9315c">
Absolute path before:Desktop
When I tried to do cat with a file as argument, it printed out the content inside the file with no errors.
