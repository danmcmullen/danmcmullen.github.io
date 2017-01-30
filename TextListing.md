---
layout: default  
---
## How to create a text listing of files in a specified directory 

Open the directory you need the file list from in Windows Explorer. In this example we are using the directory _InProgress_. 
![Directory listing](TextListing/r1.png)

Hold the **_shift_** key and right click on the folder containing the required files. Click on **Open command window here**. 
![r2.png](TextListing/r2.png)

Open the command window opens type: 
``` batch
dir /b > list.txt
```
and press enter. 
![Command Window](TextListing/r3.png)

This will add a file called **list.txt** to your originally selected folder. 
![list.txt added](TextListing/r4.png)

Open the **list.txt** file by double clicking on it, find **list.txt** in the list and delete it. 
![remove list.txt](TextListing/r5.png)

You are now able to rename the text file to some thing more appropriate. It may also be copied into a Word document or converted to a PDF for delivery. 

Updated 25-January-2017
