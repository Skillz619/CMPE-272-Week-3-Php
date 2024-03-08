# CMPE-272-Week-3-Php


CMD commands

# SSh your ec2 instance:

Install apache and php server to have the enivronment to host php website 

sudo yum install httpd php

Now cd /var/www/html 


# Open your local cmd and use scp to copy your locally developed php website files to the ec2 server

cd path in pem key and php files.

scp -i demo281.pem -r ./phphw/* ec2-user@52.91.65.223:/var/www/html

Now ls and verify the files transfered from local to the server.

![image](https://github.com/Skillz619/CMPE-272-Homework/assets/43133388/e9c842b5-16ba-48fc-abe3-de4867187789)

Now open the public ip address of your ec2 instance

![image](https://github.com/Skillz619/CMPE-272-Homework/assets/43133388/2b533ac8-ed12-4774-a821-3f5f5e71bf47)

you can see the website hosted on your ip 

![image](https://github.com/Skillz619/CMPE-272-Homework/assets/43133388/f73d33e1-a2f4-49d4-ae3a-393aa01f976d)

Now configure your route53 

![image](https://github.com/Skillz619/CMPE-272-Homework/assets/43133388/499385d5-e324-4f66-9e6a-ff57f6bce64a)

Add the required Nameservers and Cname and A servers in your hosting service.

![image](https://github.com/Skillz619/CMPE-272-Homework/assets/43133388/ce891b1e-f6cf-44f0-8dbd-205cddade6e4)


Once they are mapped you can see your website hosted on your domain - Shreekatsjsu.co
![image](https://github.com/Skillz619/CMPE-272-Homework/assets/43133388/14ad9c87-83f6-4b26-ab0d-4eefaa792dfa)




[shreekatsjsu.co](http://shreekatsjsu.co/)
