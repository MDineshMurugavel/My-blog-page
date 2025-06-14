# Domain Name

Hello

1. Domain name gives your website a desired name.

2. This desired name can be used to access your website instead of using the Public DNS
provided on amazon EC2 instance.

3. There are many domian name providers that you can choose from.
I have chosen Godaddy to be my domain name provider.

4. These are the steps to create a Domain name. 

### Creating a godaddy account

1. Firstly, visit the Godaddy wesbite with the link below.
```
https://www.godaddy.com/en-au
```
2. Sign up for an account with your preffered email.

### Finding domain name 

1. Look for " Find a new Domain", shown in the picture below.

![Image](https://github.com/user-attachments/assets/84760f1c-43c0-464e-a70b-b3ad42e3dbc8)


2. Search up for any Domain name that you prefer or you feel that will be suitable for your website. Make sure that you set a price range for the Domain name.

3. Setting a Price range is important as you would want to have a budget for your Domain name purchase. 

4. The cheapest Domain name according to your preference would be sufficient. 

### Purchasing Domain name 

1. Click the "Make it yours" option.

![Image](https://github.com/user-attachments/assets/9cfee378-67d5-4dce-b88a-69954d97c278)

2. You can choose to opt out full domain protection.

3. Click on "Continue to cart"

4. Check all the details listed on the page, the page would also show the total cost.

5. Proceed by clicking "Ready for checkout" at the bottom of the page

6. Enter your bank account details and purchase the Doamin name.

### Adding DNS Record 

1. Toggle back to home page and click on Dashboard.

2. Now that you have created a Domain name, it is important to link your webserver with your Domain name. This is so that you can access your website with your Domain name. 

3. Look for the "Domain" option and click on it, you will be directed to page shown below. 

![Image](https://github.com/user-attachments/assets/699691bb-7e7f-4408-94cb-a842c35c616b)

4. On the top left side of the page, below your purchased Domain name, look for the "DNS" option adn click on it. 

5. You will now need to add a new DNS record.

6. Click on " Add a new record "

7. You will then be presented with different fields to fill up 

![Image](https://github.com/user-attachments/assets/6e6634e3-6b8c-4c72-a947-93e540548621)

Type
* choose "A"

Name
* choose "@"

Value
* Toggle back to Amazon EC2 instance
* start instance
* click on "connect"
* Under EC2 instance connect tab you can see the Public IPv4 address
* copy Public IPv4 address
* Go back to Godaddy website
* Paste the Public IPv4 address under the "value" field

TTL
* will be automaticaly filled up


8. Lastly, click "save" 

9. For the record to be linked with the Domain name, it would usually take 1 - 48 hours

10. Once the linking process is over, you can start using your Domain name.


