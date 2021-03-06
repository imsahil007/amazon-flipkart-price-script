# Amazon-Flipkart Price Tracker Script
Python code to notify you when product price gets lower than a certian amount.  
![Example](https://raw.githubusercontent.com/imsahil007/amazon-flipkart-price-script/master/example.png)
___
## Parameters:
* **USER_AGENT**: Google 'my user agent' and copy the text
```
USER_AGENT = "Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/84.0.4147.105 Safari/537.36"
```
* **URL**: Add the product url (Be it amazon or flipkart)
```
URL = https://www.amazon.in/HONOR-Band-5-Meteorite-Black/dp/B07WTHFBQS/ref=sr_1_1?dchild=1&keywords=HONOR+BAND&qid=1597142577&sr=8-1
```
* **MY_BUDGET**: Add the threshold amount below which you want an email(Integer)
 ```
MY_BUDGET = 1899
```
* **mins**: Time after which you want to re-run the script
* **sender_mail_password**:  You can do either one of 2 things here:
1. If you are not using 2-factor authentication: Apply for [this](https://myaccount.google.com/lesssecureapps)
2. If you want to use separate password for this script or you are already a 2-factor user: First go [here](https://myaccount.google.com/signinoptions/two-step-verification) to apply for 2-factor authentication. Then:
Use app passwords (create a 16 character separate password for this app) [Link](https://myaccount.google.com/apppasswords)
* **Other Parameters**: 
```
sender_mail = 'sender@gmail.com'
sender_mail_password = "################"
receiver_mail = 'receiver@gmail.com'
```

# Run command:
```
python script.py
```
# Requirements:
* Python
* Python package -smtplib
* Python package -beautifulsoup4(bs4)
