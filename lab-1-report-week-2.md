# Hello! This is a tutorial for lab report 1


## Step 1
The first step I did was make sure I had VScode installed on my computer

![Lab report 1 VScode screenshot](https://user-images.githubusercontent.com/97641362/149598023-f06ae688-6856-46b8-86d9-4b694a1020ad.png)



## Step 2
The next step is to attempt to remote connect to the ieng6 servers at UCSD. What I did was find my course-specific account and attempt to connect through VScode.
![Lab report 1 remote connecting](https://user-images.githubusercontent.com/97641362/149598933-f7edc213-3474-43cd-a678-39e4c0b24984.png)
`$ ssh cs15lwi22ahk@ieng6.ucsd.edu` <- used this to remotely connect with my username

## Step 3
Here are some commands I was testing, as you can see they are running successfully.
![Lab report 1 trying some commands](https://user-images.githubusercontent.com/97641362/149599624-2e5f7b35-c97c-4b17-ba3d-565449f309a7.png)
Commands used: `cd ~, cd, ls -lat, ls -a`

## Step 4
Next, I attempted to securley copied a file on my computer, and then put it into the ieng6 server. Here is a screenshot of that successfully happening.
![Lab report 1 successful scp](https://user-images.githubusercontent.com/97641362/149600154-0946e2af-4460-4981-9cec-fca15dc79170.png)
Command used: `scp WhereAmI.java cs15lwi22ahk@ieng6.ucsd.edu:~/`

## Step 5
After that I showed how to create an ssh key. I did this my typing in the commands given in lab 1
![Lab report 1 SSH key](https://user-images.githubusercontent.com/97641362/149600733-645b1af4-fdf7-4050-96f3-63efea999194.png)
Command used:`$ ssh-keygen`


## Step 6
Finally, here are some commands that can make your time easier when connecting and finding you directory using ssh and connecting to the server. Here is a screenshot
of me doing some. The way I was able to enter this code in much quicker than just simply typing it in (entered it all in 10 keystrokes), is because I made use of the arrow keys, which allow me to pull up previous commands that I may have already typed. This method is the main thing I do when working on PA's, because it saves a lot of time when testing a program, especially when jUnit is involved.
![Lab report 1 optimization](https://user-images.githubusercontent.com/97641362/149600929-f44a71ee-11bf-463e-8352-b8b0d1022de5.png)
Commands used: `$ ssh cs15lwi22@ieng6.ucsd.edu "ls"`, `$ cp WhereAmI.java OtherMain.java; javac OtherMain.java; java WhereAmI`
