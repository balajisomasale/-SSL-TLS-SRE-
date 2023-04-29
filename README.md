# -SSL-TLS-SRE-
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
- We are using `Open SSL` to view the SSL certficates 
