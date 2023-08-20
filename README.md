# Billbook
https://drive.google.com/file/d/159P1DuApjCznqztLRDUgZakbE4GPcE27/view?usp=drivesdk

This video demonstrates how this application works.I used firebase auth for registration, firestore for storing data and firebase storage for storing images.
To manage this project are devops is used.
when the user first open the application the user had register itself this can be done on registration page.

![signup](https://user-images.githubusercontent.com/89389741/223225123-cf4c39ca-57ad-4cec-9706-1a7587a35c9b.jpg)
>>>Registration page



Then the user will get the verification mail on the mail they entered. After verifying they can login through login screen. This implementation of login and register is done using Firebase Auth.

![login](https://user-images.githubusercontent.com/89389741/223225209-ccc4e6db-7a64-4987-9561-8f81f98ff6e1.jpg)
>>>Login page


After that user can enter into the app, they choose a particular date using date and time picker, Bill from gallery and put the amount that is on the bill.



>>>![home](https://user-images.githubusercontent.com/89389741/223225251-75ba2a63-4367-4df6-888f-5f3ab3079afe.jpg)
 Home page



Once selecting everything the user can click on upload button to upload the data. The data is getting stored on firestore and images on Firebase storage.
The user can check there bills whenever they want by opening the drawer and going on bills page. Each bill can be referred by date and amount.



![drawer](https://user-images.githubusercontent.com/89389741/223225296-5dfef7da-e486-4319-b264-82e3aca99df1.jpg)
![bills](https://user-images.githubusercontent.com/89389741/223225316-a889c2f4-1032-40f5-9c80-85c6610270d1.jpg)
>>> Drawer and bills page


The user can then click on item to check the bill.
![bill](https://user-images.githubusercontent.com/89389741/223225438-eac1aedc-cbcb-4662-9686-5fbd4c580c12.jpg)
