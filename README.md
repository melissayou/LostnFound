# Lost and Found 
Group Member: Melissa You, Alex Yang, Stephan Garrett, Yuqi Yun

## Contents
* [Download the app](#download-the-app)
* [User documentation](#user-documentation)
* [Developer documentation](#developer-documentation)

## Download the app
 Clone or download this git repo. Open the project in Android Studio. Connect your Android device to your computer, and run the app.

## User documentation
### Sign Up 
If you are new to our app, sign up an account by entering an email and a password. Otherwise you can go directly to log in. 

### Log in
If you already have an account, login by entering the correct username and password.

### View items on a map
You can view all items pinned on the google map. Tap on markers to see item details, and tap the popup to see the full listing.

### Post a lost or found item by attaching a photo
You can fill out the item information and choose to attach a photo of it from your photo gallery, or use the camera to take a photo. 
Once an item has been returned, swipe left on the listing to delete it.

### Search for a lost or found item
On the widget, you can search nm item by item name. The suggestion provider will give you suggestions of your recent searches. You can clear it through the menu.  

### Post on messaging board
Through the menu, you can post new messages on the messaging board and see all past messages. 

### See your user profile 
Through the menu, you can view your profile with profile picture. 

### Logging out
Select `Logout` from the sidebar menu.

## Developer documentation

### List of Entries
`MainActivity` fetches all data from the firebase database and displays it through the main activity recycler view. Each item is displayed through 
lost_item.xml
