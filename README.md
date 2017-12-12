# Linux Command Line Explanation. 
## This is a linux command guide for 15 popular commands. 

<hr></hr>


### pwd: command to show us the path to current directory in the terminal. 

<img src="./imgs/pwd.png" alt="Drawing" style="height: 500px;"/>

<hr></hr>



### vi: command to open the file and edit the file. 
* You can start vi mode using vi + filename command in terminal.<br>

<img src="./imgs/vi_1.png" alt="Drawing" style="width: 600px;"/><br>

* In the vi terminal there is several key that is useful. 
    * 1.If you heat  **i**  you enter the nsert mode where you can modify following file. 
    * 2.If you want to save the file edited you need to press **:** + **wq**.
    * 3.If you find matched word in vi mode you need to press **?** + **word you find** .

<table>
    <tr>
        <td><img src="./imgs/vi_2.png" alt="Drawing" style="width: 300px;" align="left"/></td>
        <td><img src="./imgs/vi_3.png" alt="Drawing" style="width: 300px;" align="middle"/></td>
        <td><img src="./imgs/vi_4.png" alt="Drawing" style="width: 300px;" align="right"/></td>
    </tr>
</table>

<hr></hr>


### ls: command to show the files and directories in current directory. 
<br>
<img src="./imgs/ls.png" alt="Drawing" style="height: 500px;"/>

<hr></hr>


### touch: command to  create simple file. 
* You can see test.txt file has been created. <br>

<img src="./imgs/touch.png" alt="Drawing" style="height: 500px;"/>

<hr></hr>


### mkdir: command to create directory.
* new directory called test_dir has been created.<br>

<img src="./imgs/mkdir.png" alt="Drawing" style="height: 500px;"/>

<hr></hr>


### rm: command to erase file. If you want to erase directory and file inside it you can append -r option.
* 1 test.txt file has been erased
* 2 test_dir directory has been erased. 
<table>
    <tr>
        <td><img src="./imgs/rm.png" alt="Drawing" style="width: 500px;" /></td>
        <td><img src="./imgs/rm_1.png" alt="Drawing" style="width: 500px;"/></td>
    </tr>
</table>

<hr></hr>


### echo: command to print the follwing input. 
<img src="./imgs/echo.png" alt="Drawing" style="height: 500px;"/>

<hr></hr>


### cat: command to print the content of follwing file. 
* The content of pig logfile has been printed. <br>
<img src="./imgs/cat.png" alt="Drawing" style="height: 500px;"/>

<hr></hr>


### who: command to print the users who are currently log in.  
<img src="./imgs/who.png" alt="Drawing" style="height: 500px;"/>

<hr></hr>



### cd: command to move to the following directory.   
<img src="./imgs/cd.png" alt="Drawing" style="height: 500px;"/>

<hr></hr>



### date: command to print current date or set the time on the machine.   
<img src="./imgs/date.png" alt="Drawing" style="height: 500px;"/>

<hr></hr>



### cal: display simple calendar in the terminal.   
<img src="./imgs/cal.png" alt="Drawing" style="height: 500px;"/>

<hr></hr>



### mv: move follwing file to the designated location.    
<img src="./imgs/mv.png" alt="Drawing" style="height: 500px;"/>

<hr></hr>



### cp: copy the following file. If you don't put directory file is copied in current directory
* 1 test.txt is copied as a test2.txt in current directory
* 2 test.txt is copied at /home/acadgild/test/test_dir as a test2.txt
<table>
    <tr>
        <td><img src="./imgs/cp_1.png" alt="Drawing" style="width: 500px;" /></td>
        <td><img src="./imgs/cp_2.png" alt="Drawing" style="width: 500px;"/></td>
    </tr>
</table>

<hr></hr>



### which: show full path to execute following command. 
* 1 Show the full path of **hadoop**, **python**, **cat** command. 

<img src="./imgs/which.png" alt="Drawing" style="height: 500px;"/>
