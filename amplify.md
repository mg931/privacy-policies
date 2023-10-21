## Amplify Music Player: Privacy Policy

Welcome to the Amplify Music Player app for Android. 
This is closed source Android app which is available on the Google Play store. 

I hereby state, to the best of my knowledge and belief, that I have not programmed this app to collect any personally identifiable information. All data created by you (the user) is stored on your device only. All data can be simply erased by clearing the app's data or uninstalling it.

### Explanation of permissions requested in the app

Below is a summary of the permissions required by the application. 

<br/>

| Permission | Why it is required |
| :---: | --- |
| `android.permission.INTERNET` | This permission is required to access the artist and album information displayed within the app (images, descriptions). This permission is automatically granted and cannot be revoked |
| `android.permission.READ_MEDIA_AUDIO` | This permission is required for devices running Android 11 (API 30) and above. It enables the app to read audio files from the device storage. This permission is requested at runtime and can be revoked. |
| `android.permission.WRITE_EXTERNAL_STORAGE` | Required to write to device storage in order to edit audio playlists. This permission is requested at runtime on devices running Android 10 (API 29) and below and can be revoked.|
| `android.permission.READ_EXTERNAL_STORAGE` | Required to read audio files on devices running Android 12L (API 32) and below. This permission is requested at runtime and can be revoked. |
| `android.permission.FOREGROUND_SERVICE` | Required to launch a foreground service that displays a system tray notification with play back controls (play/pause) on devices running Android Pie (API 28) and above. This permission is granted automatically and cannot be revoked. |
 <hr style="border:1px solid gray">

If you find any security vulnerability that has been inadvertently caused by me, or have any question regarding how the app protects your privacy, please send me an email or post a discussion on GitHub.

Yours sincerely, <br>
Marius Goubert <br>
London, UK 
