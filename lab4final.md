Step 1: Log into ieng6
![Image](Screenshot 2023-05-22 at 5.27.37 PM.png)
To do this I typed in the command 
```
ssh cs15lsp23ed@ieng6.ucsd.edu
```
Then I hit 
```
<Enter>
```

Step 2: Clone fork of repository
![Image](Screenshot 2023-05-22 at 5.28.23 PM.png)
To do this I typed the command
```
git clone https://github.com/rjh002/lab7.git
```
  
Step 3: Edit the code to fix the failing test
![Image](Screenshot 2023-05-22 at 5.29.23 PM.png)
First I typed the command
```
vim ListExamples.java
```
Then I hit 
```
<J>
```
(moves cursor down)
unitl I was on the right line.

Then I hit
```
<L>
```
(moves cursor to the right)
until I was hovering over the right character.
  
Then I hit 
```
<x>
```
(deletes text which you are hovering over)

Then I hit
```
<i>
```

Then I clicked 2.
  
Then to save I clicked
```
:wq <Enter>
```

Step 4: Commit

First I did
```
git add ListExamples.java
```
Then
```
git commit -m ListExamples.java
```
in order to save it all.

![Image](Screenshot 2023-06-07 at 9.24.39 AM.png)
