# SSL-TLS-SRE-
For education purpose only

## Section 1 : Introduction 

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

## Section 3: Certificate Architecture : 

#### Structure of certificate : 

![image](https://user-images.githubusercontent.com/35003840/235370586-ca0c559f-c49e-4b42-bbe5-742b3b1d6fbe.png)

#### Digital Certificate : 

![image](https://user-images.githubusercontent.com/35003840/235371790-f09d4279-87be-4cd3-91cd-4407d313b331.png)

- There are 2 cryptographic algorithms that are used in above image : 1) `Integrity` and 2) `SHA1` or `SHA2` in general 

![image](https://user-images.githubusercontent.com/35003840/235372529-ba75c613-eb02-4b6a-baaf-0a2c0661770c.png)


#### Certificate standard and encoding methods : 

![image](https://user-images.githubusercontent.com/35003840/235373262-4140bbde-f351-4510-939a-429e7d797572.png)

#### Types of certificates : 

![image](https://user-images.githubusercontent.com/35003840/235805694-48e381df-223a-43be-a81e-53c1740320b3.png)

![image](https://user-images.githubusercontent.com/35003840/235806678-cc264430-3c9b-473b-a4a2-02dbf72dfa44.png)

![image](https://user-images.githubusercontent.com/35003840/235807157-3dcc2013-7531-4ffa-bccf-c762438d860b.png)

## Section 4: Encryption Algorithms:

#### Introduction of Encryption Algorithms :

![image](https://user-images.githubusercontent.com/35003840/235807305-bf653453-97b1-4ea8-85d9-fb9af759cb23.png)

#### Private/Symmetric Key Encryption : 

![image](https://user-images.githubusercontent.com/35003840/235808246-6968c200-5ab4-4c8d-84ad-507e1b7de721.png)

#### AES :

![image](https://user-images.githubusercontent.com/35003840/235808494-c8bf32bf-a55d-4a01-8692-46e2dbf83e93.png)

#### Public/Asymmetric Key Encryption :

![image](https://user-images.githubusercontent.com/35003840/235808662-f05de590-ac28-458e-a723-30c8206cd0b1.png)


#### RSA :

![image](https://user-images.githubusercontent.com/35003840/235808816-99948090-dd2a-4f30-a1ff-a436caff3f9b.png)

#### Elliptic Curve algorithm :

![image](https://user-images.githubusercontent.com/35003840/235809014-613c7373-60be-444b-b213-dbbc5e143699.png)

#### Hashing algorithms :

![image](https://user-images.githubusercontent.com/35003840/235809159-6372e5ae-5ccb-4af2-bbf8-19202bf59cbe.png)

![image](https://user-images.githubusercontent.com/35003840/235809252-d3399409-a8f3-47f7-8fe5-43bd50cf53c6.png)

## Seciton 5: SSL Communication :

![image](https://user-images.githubusercontent.com/35003840/235809333-ba571e17-39e3-4612-9027-79197f3d2f31.png)

resume from first video

