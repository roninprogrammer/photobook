# photobook

Photobook: A photo-sharing Android app using Firebase. Android app to aggregate all my photos from different social sites, Facebook, Twitter, Flickr, personal drive and Dropbox. Could classify based on time, event, mood and implement search by voice. Hopefully this will influence me to take more photos.

Photobook also helps users to store and share photos. There are two types of photos: Public (available to everyone) and Private (available to the user). Each of the photo has a short description. The app has four views:

Photos — This part allows a user to look through photos that were uploaded by anyone and have a tag Public. If the user is authenticated then there should be additionally Private photos that were uploaded by this user. You don’t need to implement preview of photos, just make it a small rectangle with description (simple is better)

Upload — A user can upload photos, provide description and tag them either Public or Private. You should use Firebase Database. Additionally, Security Rules should be used to manage access for photos on the Firebase level.

Search — The user should look up the image by description. If the user is authenticated, then search is enabled for Private images, otherwise only Public images are available.

Auth — User authenticates with the app using Email or Google Sign-in (OAuth). The authentication doesn’t happen at the start of the app and is voluntarily.

## Reference

* Android Firebase: Uploading and Retrieving File Using Firebase Storage - Part2
 https://www.youtube.com/watch?v=akIrsTB2zIQ&t=923s
* Android Firebase: Uploading and Retrieving File Using Firebase Storage - Part1: https://www.youtube.com/watch?v=jj_pheDler0


### Android
* Android Studio User Guide: https://developer.android.com/studio/intro/index.html
* Android API Guides: https://developer.android.com/guide/index.html
    * Search: https://developer.android.com/guide/topics/search/index.html
    * Search Action View: https://developer.android.com/training/appbar/action-views.html
* Android Training: https://developer.android.com/training/index.html
    * Search: https://developer.android.com/training/search/setup.html
* Android API Reference: https://developer.android.com/reference/packages.html
* Buiilding simple UI: ttps://developer.android.com/training/basics/firstapp/building-ui.html
* Sign Your App: https://developer.android.com/studio/publish/app-signing.html

### Firebase
* Firebase Documentation for Android: https://firebase.google.com/docs/android/setup
* Firebase Authentication: https://firebase.google.com/docs/auth/
* Firebase Authentication Quick Start Code: https://github.com/firebase/quickstart-android/tree/master/auth/app/src/main/java/com/google/firebase/quickstart/auth


