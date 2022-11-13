Hi! This is lab report 4, we will explore vim this time.
>Part 1

I am choosing to use the least vim lines to finish this task: Adding a new line to print before File[] paths = f.listfiles()

1) Open terminal and type 
```
vim DocSearchServer.java <return>
```
This pull of the file that we want to change in the vim mode
![Image](image42.jpg)

2) 	
```
Shift a
press downward arraws 15 times 
<return> <tab> <empty> <space>
```

	
This command change the cursor to the line that we want to add stuff by return
The Tab and Empty Space is just for indenting the cursor to where we want to insert lines.
	
![Image](image43.jpg)
	
3) 
```
System.out.println(f.toString() + " is a directory");
```
	
Type the above line on the screen
	
![Image](image44.jpg)
	
5) 
```
<ESC> :x 
sh start.sh 1234
```
This exits the vim mode and type sh start.sh 1234 on the command line. and we can see the file to run.
	
![Image](image45.jpg)

So the whole line is
```
vim DocSearchServer.java <return>
Shift a
press downward arraws 15 times 
<return> <tab> <empty> <space>
System.out.println(f.toString() + " is a directory");
<ESC> :x 
sh start.sh 1234
```

>Part2

For the first method with scp, it took me 35 seconds to make an edit on local and copy to the remote.
For the second method with vim, I used 27 seconds.

If I have to use one of these methods, I would prefer the vim method as I am worry that I did not scp every local change to the remote change and create bugs over remote change. However, if I do directly in vim mode, that case could be largely reduced.

I think how much memory the project takes would affect my choice in mode. If the project is taken thousands of GB, I would definitely use the vim mode to change the project directly in the remote server since I dont want my own computer to crack or run two hours just for one simple change.

This is the end of Lab report 4. Thank you for reading.
