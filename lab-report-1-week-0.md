Test for lab0:
![Image](screenshot.jpg)
----
## Lab 1 Report
> Part 1: Install VSCode

Hello! This is the first lab report about getting the remote access. For starting that, you should download VScode on your desktop. [Click here for VScode download](https://www.youtube.com). You should see the webpage as the screenshot below. 

Then, select the system your laptop is (IOS/ Windows).

![Image](step1.jpg)

With all that installed, you should see the VScode page as below. The detailed installation part is skipped since I actually downloaded this few months ago and don't have to download the VScode again.

![Image](step2.jpg)

> Part 2: Remotely connecting

Open the VS code and the terminal, then type in % **ssh cs15lfa22dx@ieng6.ucsd.edu** (Don't include % in your input) And the "dx" part should be change into your own account number that is set for this course.

Then, you will be requested to enter your password to login. Type the password in the terminal. It is totally normal that the password does not show up in the screen. If you enter the password correctly, yayyy, you are in!

The successful remote control page should be very similar to the following screenshot.

![Image](step3.jpg)

> Part 3: Trying some commands

Now, let's try running commands on both remote and local server to see how the result would be different!

Type **ls -lat** in your terminal on your remote server. You should see something similar to this:

![Image](step4.jpg)

Then, type exit in the terminal to logout from the remote control and back to your local desktop. Type **ls -lat** again to see what happens.

![Image](step5.jpg)

See, the same command in remote server and your server return different contents. **ls -lat** would give you all the files, shown in long format, sort by time already. So, you can see the different files you get from remote and your computer.


