# **Setting Up Course-Specific Account on ieng6**
***

## Step 1 - Getting your Account information.
The first step to setting up your account, is finding the account information.

To get your course-specific account for your class, use the following link:

https://sdacs.ucsd.edu/~icc/index.php

For information on resetting your password, follow the instructions [here](https://docs.google.com/document/d/1hs7CyQeh-MdUfM9uv99i8tqfneos6Y8bDU0uhn1wqho/edit).

## Step 2 - Visual Studio Code
If you already have Visual Studio Code on your computer, then skip ahead to the next step.

You can download Visual Studio Code from their website [https://code.visualstudio.com/](https://code.visualstudio.com/).

Follow the instructions carefully and download it for your operating system. (eg. OSX for Macs and Windows for PCs). 

Once it is installed, you should be able to see a screen like this:

![Image](https://media.discordapp.net/attachments/717860504093327450/1063233227629789224/image.png?width=1215&height=642)

## Step 3 - Git and Connecting.

Next you will have to download GitHub and set bash as your default Terminal.
Use these links to properly set that up.

- [Git - Download](https://gitforwindows.org).

- [Bash - Set Up](https://stackoverflow.com/a/50527994).

Once you have set bash as your default terminal, opening up the terminal should give you an image that looks like:

```
$
```

Next, in order to connect to the ieng6 server type in the terminal:
```
$ ssh cs15lw23zz@ieng6.ucsd.edu
```
However, replace the "zz" with your account's identification letters.

"zz" => "abc"

Once you put that into the terminal, since it may be your first time, you will be prompted with a question

about the authenticity of the host and confirmation about connecting.

Simply answer **yes** and then enter your password.

![Image](https://media.discordapp.net/attachments/717860504093327450/1063233841076125706/image.png)

When you see the text above, don't worry about nothing showing up when you type, as long as you type your password correctly,

you should be able to enter.

You should then be given the following:

```
Hello cs15lwi23zz, you are currently logged into ieng6-201.ucsd.edu

You are using 0% CPU on this system

Cluster Status 
Hostname     Time    #Users  Load  Averages  
ieng6-201   14:35:01   13  0.07,  0.14,  0.13
ieng6-202   14:35:01   15  0.02,  0.12,  0.09
ieng6-203   14:35:02   13  0.13,  0.19,  0.15

 
Thu Jan 12, 2023  2:39pm - Prepping cs15lwi23
```

Now you should be on the ieng6 server. Whenever you run code in that terminal, it will run the code on a computer in the CSE building!

## Step 4 - Running Commands

Now that you're on the server, you can try running code, here are some commands to try out:
- ```cd```
- ```ls```
- ```pwd```

Try using different combinations and sequences to get unique outcomes!

From this screenshot, find out how to get this to appear:
![Image](https://media.discordapp.net/attachments/717860504093327450/1063233721634926712/image.png?width=1215&height=99)

Congratulations on properly setting up your connection to the ieng6 server! Enjoy coding!
