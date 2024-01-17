![image](https://github.com/l9flores/cse15l-lab-reports/blob/main/cdNoArgs.png) <br>
The working directory in the image is `/home/lecture1` and it goes to the `/home` working directory. It got this output due to the `cd` command not having any arguments meaning that it goes straight to the home directory. This output is not an error since this is the way to return back to the home directory. 

---

![image](https://github.com/l9flores/cse15l-lab-reports/blob/main/cdFile.png)<br>
The working directory in the image is `/home/lecture1/messages` and it got this output due to using a text file instead of a directory which the `cd` command does not work on. This is an error since the `cd` command is not supposed to be used on files.<br>

---

![image](https://github.com/l9flores/cse15l-lab-reports/blob/main/cdDirectory.png)<br>
The working directory in the image is `/home` and changes directory to `lecture1`. It got this output due to the `cd` command being used on a directory to move to said directory. This is not an error since it is used in the intended way it is meant to be used which is to change directories.<br>

---

![image](https://github.com/l9flores/cse15l-lab-reports/blob/main/lsNoArgs.png)<br>
The working directory in the image is `/home` and it got this output due to the `ls` command being used to list all files within the current working directory which was the `lecture1` directory. This is not an error since the purpose of the command is to list all the contents of whatever directory is used as an argument and since there was no argument it shows the working directory contents.<br>

---

![image](https://github.com/l9flores/cse15l-lab-reports/blob/main/lsFile.png)<br>
The working directory in the image is `/home/lecture1/messages` and it got this output due to `ls` being used on a file which lists the information about the file which in this case the the file name. This is not an error since its used in the way its meant to be used.<br>

---

![image](https://github.com/l9flores/cse15l-lab-reports/blob/main/lsDirectory.png)<br>
The working directory in the image is `/home` and got this output due to the `ls` command being used onto the `lecture1` folder which lists the contents of the `lecture1` folder which included `Hello.class`, `Hello.java`, `messages`, and `README`. This is not an error and is used properly.<br>

---

![image](https://github.com/l9flores/cse15l-lab-reports/blob/main/catNoArgs.png)<br>
The working directory in the image is `/home` and it got this output due to the `cat` command having no arguments meaning that it reads from the terminal. This is not an error and is being used properly. <br>

---

![image](https://github.com/l9flores/cse15l-lab-reports/blob/main/catFile.png)<br>
The working directory in the image is `/home/lecture1/messages` and it got this output due to being used on a file meaning that it reads out the contents of the file since it is a text file. This is not an error and is used properly. <br>

---

![image](https://github.com/l9flores/cse15l-lab-reports/blob/main/catDirectory.png)<br>
The working directory in the image is `/home` and it got this output due to being used on a directory which is not suppoesed to be used on. This is an error since it returns an error message due to the cat command not being able to be used on directories.
