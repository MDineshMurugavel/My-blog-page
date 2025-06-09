Hi 

### why scripting

Scripting is used to automate tasks repeatedly (eg: New updates, creating files, deleting file)

This is a script that I am implementing on my blog page

I am using this script to automate the updates on my webserver, this is because i have only planned to use my Blog page three times a week and it would be an hassle to login everyday to update new packages. Therefore, i am using a script to update any new packages everyday. 

### Opening command prompt on AWS
```
https://aws.amazon.com/console/
```
1. Login with your credentials
2. start your instance
3. Click on connect
4. You will directed to " EC2 Instance connect " tab
5. Scroll down and click the yellow " Connect "
6. You will now be directed to the command prompt page


### Code to run on command prompt

In order to start the scripting for package updates, you need to create a file and save the commands that you want to execute in it. 


To save every completed action, press "ctrl x " followed by "y"


* This is the command to create a file

```
touch auto_update.sh
```
* auto_update.sh is my file name, it can also be change to any preffered name
  
![Image](https://github.com/user-attachments/assets/439658ac-d784-48c6-91b2-79aef0f47f69)


Press "enter", and the file will be created 



*To edit the file you will have to run this command 

```
nano auto_update.sh
```

Press "enter", and you will be inside the file

![Image](https://github.com/user-attachments/assets/e3e53a7a-46b6-4259-aa66-fee652882e47)


* These two commands will update new packages and delete old ones

  ```
  sudo apt upate

  sudo apt autoremove
  ```

  ![Image](https://github.com/user-attachments/assets/e3e53a7a-46b6-4259-aa66-fee652882e47)

    
* This command will make this file executable

  ```
  chomd +x auto_update.sh
  ```

* This command helps to automate the script according to how often you want the script to be repeatedly executed

    ```
    crontab -e
    ```
    * choose "1" and press and enter
 
    ![Image](https://github.com/user-attachments/assets/703a93d4-22e8-4e15-95fe-21108fd086ce)



* This command will help you in choosing how often you want the update of packages and removal of old packages reptitively

```
04*** the/fullpath/to/auto_update.sh
```

* Replace "the/fullpath/to/" with the path of your file 

* The order to fill up each fields are shown in the picture below
  

 ![Image](https://github.com/user-attachments/assets/ef7132dd-cbb0-49ee-a0cf-591a7ad02317)

  
The script is now complete and it will reptitively execute updates and removal of packages.


