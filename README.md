# billbook
https://drive.google.com/file/d/159P1DuApjCznqztLRDUgZakbE4GPcE27/view?usp=drivesdk

This video demonstrates how this application works.I used firebase auth for registration, firestore for storing data and firebase storage for storing images.
To manage this project are devops is used.
when the user first open the application the user had register itself this can be done on registration page.![Screenshot_20230307_005543](https://user-images.githubusercontent.com/89389741/223210622-66e01ede-aeec-4148-8f77-b3f1fdba56af.jpg)
>>>Registration page
Then the user will get the verification mail on the mail they entered. After verifying they can login through login screen. This implementation of login and register is done using Firebase Auth.
![Screenshot_20230307_005835](https://user-images.githubusercontent.com/89389741/223211140-27f6848d-3b45-4eee-b580-517d8b1bae4e.jpg)
>>>Login page
After that user can enter into the app, they choose a particular date using date and time picker, Bill from gallery and put the amount that is on the bill.
![Screenshot_20230307_010319](https://user-images.githubusercontent.com/89389741/223212199-9784abfc-b346-4e9d-b312-b4444662439b.jpg)
>>> Home page
Once selecting everything the user can click on upload button to upload the data. The data is getting stored on firestore and images on Firebase storage.
The user can check there bills whenever they want by opening the drawer and going on bills page. Each bill can be referred by date and amount.![Screenshot_20230307_010716](https://user-images.githubusercontent.com/89389741/223212922-a7ac947f-d03e-4e86-b929-6b32a941d381.jpg)
![Screenshot_20230307_010721](https://user-images.githubusercontent.com/89389741/223212954-9e1b4b0d-448c-4d98-83e9-54ee4dba08df.jpg)
>>> Drawer and bills page
The user can then click on item to check the bill.
![Screenshot_20230307_010906](https://user-images.githubusercontent.com/89389741/223213287-bb090bdd-b611-42f7-ac96-8f4e5b0a91c1.jpg)
