Hello
In order to run a cloud based server, you need to configure an instance.

### creating an AWS account 
```
https://aws.amazon.com/console/
```
creat an account an account with your email address.

### creating an instance
1. Go to the AWS Management Console.
2. Navigate to the EC2 Dashboard.
3. Click on "Launch Instance".
   
![Image](https://github.com/user-attachments/assets/fb8531d3-f80d-410f-bd3f-5453a6656b4a)
 
4. Give your webserver a name
5. Choose an Amazon Machine Image (AMI) that suits your needs (e.g., Ubuntu, Amazon Linux).
6. Select an instance type (e.g., t2.micro for free tier).
7. Configure instance details (default settings are usually fine for basic use).
8. Make sure you set up a key pair name
9. under firewall (security groups) tab 
- select "HTTP" and "HTTPS" options to allow web traffic
10. Review and launch the instance.

![Image](https://github.com/user-attachments/assets/b6a65c93-1304-4e68-a931-18d65ea6b692)
  
### Connect to the instance
1. Once the instance is running, select it from the EC2 Dashboard.
2. Click on "Connect".
3. Click on "EC2 Instance Connect".
4. Scroll down and click on "Connect".
5. You will be connected to your instance.
### editing the web server
1. Once connected,run the following command on the terminal to update the package list.
     ```bash
     sudo apt update
2. Run this command to start editing the web server.
     ```bash
     sudo nano /var/www/html/index.html
     ```
3. Edit the HTML content as desired.
4. Here are some basic HTML tags you can use:
   - `<h1>` for headings
   - `<p>` for paragraphs
   - `<a href="URL">` for links
   - `<img src="IMAGE_URL" alt="description">` for images
5. Save the changes by pressing `CTRL + X`, then `Y`, and finally `Enter`.
