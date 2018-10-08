
**Creating project and publishing first project on Github**

Follow the steps:-

1.Create an account on github, then go to terminal and type
```
git config --global user.name "YOUR USERNAME"
git config --global user.password "YOUR PASSWORD"
```

2.Go to your project's folder/directory on the CLI(command line interface) and type
```
git init
```
This initializes the local folder as a git repository, so that the folder is version controlled.

3.Consider the file "my_project.python" is my project file type
```
git add FILENAME
git add my_project.python
```
In case you have multiple files, you can also type 
```
git add . 
```

4.Its time to save all the changes for a final time before publishing your file on github this is called commiting.Type
```
git commit -m "my message"
```
you can type the details of the project here in a sentence to give the reader an idea as to what the project is about.

5.And finally
```
git push origin master
```
This code pushes the changes in your project file preject in the local repo to the remote repo ie github.

