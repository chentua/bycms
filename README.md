# bycms
Scope of influence
V1.4
Repair scheme
Filter menu name, special characters are not allowed
Environment construction method
(1) : download from the official website and unzip it to the WWW directory, phpstudy, but the PHP version should be 7
Vulnerability related code
The vulnerability is caused by:
Due to transmission to post[title] Special characters are not filtered

Enter system tools - click menu generator

![image](https://user-images.githubusercontent.com/27337983/138582399-91505f5c-c8a1-44ba-889f-1fc8addcfed3.png)
Menu name input
Payload：
*/ echo phpinfo(); php?>/*
And it will be brought into the created controller
![image](https://user-images.githubusercontent.com/27337983/138582431-c67a884d-f227-4d7c-b85e-f3ec09546724.png)
After the menu is created, a column will be generated
![image](https://user-images.githubusercontent.com/27337983/138582437-25330a4a-007b-40eb-8743-3886ac124d56.png)
click
![image](https://user-images.githubusercontent.com/27337983/138582441-8fc30278-d9ec-4872-8ecd-21d30d912a96.png)
