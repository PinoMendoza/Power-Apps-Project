# Power Apps project using Excel tables
By Víctor Suárez Ramos


## Table of Contents
* [1. Introduction](#introduction)
* [1. User requirements](#userReq)
* [2. Usability](#usability)
* [2. Use cases](#useCases)
* [3. Data model](#dataModel)
* [4. Instalation Manual](#instalationManual)
* [5. Technology Stack](#techStack)
* [6. Comparison with other technologies](#comparison)
* [7. References and documentation used](#documentation)

### User requirements<a name="userReq">
 1. This project is focused on a phone app, although there is also a web version, which is what will be used to make and test the app structure. 
 
 2. The users will need a Microsoft account (business or educational) in order to use the app.
 
 3. The app will have a main menu that will have 4 submenus, two of wich are list of operations, and 2 wich are forms to fill up the necessary info of that operation. The user will alse be able to edit or delete a given operation. All these actions will only be possible if the user is an administrator or is given permission to do those actions when sharing the app to it.
 
 4. The data origin will be Excel tables. This makes the project's scope a bit limited, but in the upside the Excel file can be easily downloaded and modified locally.
 
### Usability<a name="usability">
 1. The app is useful, as it fullfils its purpose to help make the operations in the company a bit smoother.
 
 2. It's easy to use because everything has big buttons and labels to help the user.
 
 3. It's easy to learn because you only need to know how to type on your phone, it doesn't have any complicated inputs to learn.
 
 4. The app's design is very simple, as it only has 3-4 colors and a similar number of different shapes and icons.
 
 5. It offers a big time save over doing the same action manually.
 
 6. The user can interact with the app.
 
 7. The user can access all of the content of the app.
 
 8. The user can start actions and control tasks.
 
 9. There's feedback to the actions of the users, for example a button changing color when it is pressed.
 
 10. The app's desing is consistent throughout.
 
### Use cases<a name="useCases">
![Diagram](Images/Use%20Case%20Diagram.jpg)
 
 I also made a [mockup of the app](https://xd.adobe.com/view/c6f4f565-776e-485f-8a7d-c5d9b3afe67b-93a7/screen/77ea253a-6475-40dc-96ff-3bc602b216db/) to show the concept of the project.

### Data Model<a name="dataModel">
The data origin in the app are Excel tables, which makes it a bit more limited, but in turn it becomes easier to understand, as Excel is widely used.
The Excel file has a few tables:  

  *-Administrators:* Contains the emails of the user that are authorized to edit the data source.  
  
  *-Vessels:* Contains the name and types of the different vessels that are subject to operations in the company.  
  
  *-Launching:* Contains all the information of the operation of the same name.  
  
  *-Afloat transfer:* Contains all the information of the operation of the same name.  
  
  *-Tractors:* Contains the different types of tractor used to tow the vessels.  
  

**E-R Diagram:**
![Diagram](Images/E-R%20Diagram.png)

**UML Diagram:**
![Diagram](Images/UML%20Diagram.jpg)

### Instalation Manual<a name="instalationManual">
Installing a Power App is fairly simple, you just have to follow a few easy steps:
  
1. Go to the App Store in your Android Phone and search "Power Apps"
![App](Images/image.png)
2. Open the app and log in using your organization or educational account, you will have a list of apps that have been shared to you. If you do not see the app you are suposed to have, contact an administrator of your organization.
3. Tap on the app that you need, and you will open it. If the app that you opened has updated since you last opened it, you will have a prompt on the upper portion on your screen that will allow you to update it.

### Documentation<a name="documentation">
[Microsoft Docs](https://docs.microsoft.com/es-es/documentation/)
