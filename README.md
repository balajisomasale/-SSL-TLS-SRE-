# SSL-TLS-SRE-
For education purpose only

## Section 1 : Introuduction 

- SSL port is by default `443`
![image](https://user-images.githubusercontent.com/35003840/235323803-bc9a30ef-0dfa-49a4-b404-e8700dd649f2.png)

#### Why do we need SSL Certificates ? 

![image](https://user-images.githubusercontent.com/35003840/235323981-1b196e05-8c61-491f-bb2e-4cd11a2d0432.png)

#### SSL/TLS Evolution : 

![image](https://user-images.githubusercontent.com/35003840/235324215-d1ad98e0-b45f-4a7e-a9fd-d50022e05316.png)

- SSL functions in `Application` layer in `TCP/IP` model and `Presentation layer` in `ISO/ISI model`
- TLS is more advanced and upgraded version than SSL and was introduced to remove the disadvantages of SSL

## Section 2 : How SSL works ? 

![image](https://user-images.githubusercontent.com/35003840/235324728-c3586971-452e-490f-99e1-ad908d69abd4.png)

CA signed vs Self Signed certificates :

![image](https://user-images.githubusercontent.com/35003840/235325289-21a9f5e2-7fea-49d8-a2d8-02e163b640b9.png)

- CA signed are preferred for public use as its `Public Key` is known to all the users.

Reading/Examining the certificate : 

- We can always check all the information of SSL of any browser of any website.
- We are using `Open SSL` to view the SSL certficates and in below, we can see `pem` certificate 

![image](https://user-images.githubusercontent.com/35003840/235361642-59d719f4-673b-4983-bd0b-0b18a18eabbc.png)

![image](https://user-images.githubusercontent.com/35003840/235361682-57b2d80a-fbe8-44a7-8f50-84f6fa4cac77.png)

- To filter the `.pem` not exposed, we are using `-noout` to NOT expose it and do it in text 

![image](https://user-images.githubusercontent.com/35003840/235363479-fde8d8c2-0e21-4b08-96b6-da96d871096e.png)

![image](https://user-images.githubusercontent.com/35003840/235363747-1c2be5e8-1c80-4d03-8893-deb39ab84bbd.png)

How to install Open SSL : 

https://tecadmin.net/install-openssl-on-windows/

- It still is not working 

#### Section 3: Certificate Architecture : 

## Structure of certificate : 

![image](https://user-images.githubusercontent.com/35003840/235370586-ca0c559f-c49e-4b42-bbe5-742b3b1d6fbe.png)

## Digital Certificate : 

![image](https://user-images.githubusercontent.com/35003840/235371790-f09d4279-87be-4cd3-91cd-4407d313b331.png)

- There are 2 cryptographic algorithms that are used in above image : 1) `Integrity` and 2) `SHA1` or `SHA2` in general 

![image](https://user-images.githubusercontent.com/35003840/235372529-ba75c613-eb02-4b6a-baaf-0a2c0661770c.png)

![image](https://user-images.githubusercontent.com/35003840/235372866-6b74f621-5b52-4bc2-8ac2-e3524b24cba2.png)

## Certificate standard and encoding methods : 

![image](https://user-images.githubusercontent.com/35003840/235373262-4140bbde-f351-4510-939a-429e7d797572.png)


