# DSC-Certificate-Generator
Batch Certificate Generator

Use this Project to create multiple certificates and send the certificates to the participants/winners

The Font used is Google Sans

----------------------------------------------------------------------------------------------------------------------------------------------------------------
The project consists of 2 python notebooks:
----------

The first notebook consists of the code to generate Certificates 

The Second notebook along with generating certificates can send it directly to the recievers via email


----------------------------------------------------------------------------------------------------------------------------------------------------------------

Replace the data.csv in assets folder with the name and e-mail in the format 

Name,E-mail

ABC DEF,ABCDEF@gmail.com

ABC GHI,ABCGHI@gmail.com 

ABC JKL,ABCJKL@gmail.com

ABC MNO,ABCMNO@gmail.com

ABC OPQ,ABCOPQ@gmail.com

ABC RST,ABCRST@gmail.com

UVW XYZ,UVWXYZ@gmail.com

---------------------------------------------------------------------------------------------------------------------------------------------------------------

Sending an e-mail

We are used Google's Gmail service to send mail. So we have to take some settings for google's security purposes. 
If those settings are not set up, then the following code may not work, if the google doesnot support the access from third-party app.

To allow the access, we need to set 'Less Secure App Access' settings in the google account. 
If the two step verification is on, we cannot use the less secure access.

To complete this setup, go to the Google's Admin Console, and search for the Less Secure App setup.

---------------------------------------------------------------------------------------------------------------------------------------------------------------


