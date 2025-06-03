# Domain Name

Hello

Domain name gives your website a desired name.

This desired name can be used to access your website instead of using the Public DNS
provided on amazon EC2 instance.

There are many domian name providers that you can choose from.
I have chosen Godaddy to be my domain name provider.

These are the steps to create a Domain name. 

### Creating a godaddy account

Firstly, visit the Godaddy wesbite with the link below.
```
https://www.godaddy.com/en-au
```
Sign up for an account wiht your preffered email.

### Finding domain name 

Look for " Find a new Domain", shown in the picture below.

picture.!!!

Search up for any Domain name that you prefer or you feel that will be suitable for your website. Make sure that you set a price range for the Domain name.

Setting a Price range is important as you would want to have a budget for your Domain name purchase. 

The cheapest Domain name according to your preference would be sufficient. 

### Purchasing Domain name 

Click the "Make it yours" option.

picture!!!

You can choose to opt out full domain protection.

Click on "Continue to cart"

Check all the details listed on the page, the page would also show the total cost.

Proceed by clicking "Ready for checkout"

Enter your bank account details and purchase the Doamin name.

### Adding DNS Record 

Toggle back to home page 

Now that you have created a Domain name, it is important to link your webserver with your Domain name. This is so that you can access your website with your Domain name. 

Look for the "Domain" option and click on it, you will be directed to page shown below. 

picture!!

On the top left side of the page, below your purchased Domain name, look for the "DNS" option adn click on it. 

You will now need to add a new DNS record.

Click on " Add a new record "

You will then be presented with different fields to fill up 

Picture

Type
* choose A

Name
* choose @

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


Lastly, click "save" 

For the record to be linked with the Domain name, it would usually take 1 - 48 hours

Once the linking process is over, you can start using your Domain name.


