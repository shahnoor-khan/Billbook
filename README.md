# billbook
https://drive.google.com/file/d/159P1DuApjCznqztLRDUgZakbE4GPcE27/view?usp=drivesdk

This video demonstrates how this application works.I used firebase auth for registration, firestore for storing data and firebase storage for storing images.
To manage this project are devops is used.
when the user first open the application the user had register itself this can be done on registration page.

![WhatsApp Image 2023-03-07 at 1 59 36 AM](https://user-images.githubusercontent.com/89389741/223223692-9bc2bd7c-0946-42df-aabe-65cbc87953c3.jpeg)
>>>Registration page



Then the user will get the verification mail on the mail they entered. After verifying they can login through login screen. This implementation of login and register is done using Firebase Auth.


![WhatsApp Image 2023-03-07 at 1 59 37 AM](https://user-images.githubusercontent.com/89389741/223223751-c2fe8013-c7ea-4aec-b7bb-ef193b315dd9.jpeg)
>>>Login page


After that user can enter into the app, they choose a particular date using date and time picker, Bill from gallery and put the amount that is on the bill.


![WhatsApp Image 2023-03-07 at 1 59 38 AM](https://user-images.githubusercontent.com/89389741/223223800-bc363a34-9836-44c4-a763-268183e5c29c.jpeg)
>>> Home page



Once selecting everything the user can click on upload button to upload the data. The data is getting stored on firestore and images on Firebase storage.
The user can check there bills whenever they want by opening the drawer and going on bills page. Each bill can be referred by date and amount.

![WhatsApp Image 2023-03-07 at 1 59 37 AM (1)](https://user-images.githubusercontent.com/89389741/223223882-60774e09-7380-41b0-884d-bfcdd2bf0bc1.jpeg)
![WhatsApp Image 2023-03-07 at 1 59 38 AM (1)](https://user-images.githubusercontent.com/89389741/223223902-48d300c1-7179-451c-8222-9c36a390643b.jpeg)

>>> Drawer and bills page


The user can then click on item to check the bill.
![Screenshot_20230307_010906](https://user-images.githubusercontent.com/89389741/223213287-bb090bdd-b611-42f7-ac96-8f4e5b0a91c1.jpg)
