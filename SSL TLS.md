Hello 

### Impotance of SSL/TSL

Your blog page would work without an SSL/TSL certficate but it is not recommended as it is unsafe.

In order to make your Blog page safe for users to visit, you need an SSL/TSL certficate.

This prevents any type of cyber attacks on your blog page


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

### Commands

1. You can now start running these commands on your command prompt

2. ```
   sudo -i
   ```
* This command will give you super/root user privileages

3. ```
    netstat -tunlp
   ```

4. ```
    sudo service apache2 stop
   ```
* This command is present to stop apache2 webserver

5. ```
    sudo certbot certonly --standalone -d *Your domain name*
   ```

6. ```
   sudo apt update
   ```
* This commands helps to update all new updates and packages

7. ```
   sudo apt install certbot python3-certbot-apache
   ```

8. ```
   sudo apt install certbot python3-certbot-apache
   ```

9. ```
   cd /etc/apache2
   ```

10. ```
    sudo certbot --apache -d *Your domain name*
    ```

11. Once you have successfully ran all of these commands on the command prompt, you can exit the command prompt tab.

12. You will now notice that your blog page is secured 
