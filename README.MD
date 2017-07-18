### Xamarin.Android sample app to reproduce weird behavior increasing png file size

This app shows a weird behavior of Xamarin.Android.

Android app contains a file `btn_task_sign.png` in `Resources/drawable/hdpi`.

[File size is 238 bytes](https://github.com/DreamTeamMobile/DT.Xamarin.AndroidPngMysteryBug/blob/master/PngMysteryApp/Resources/drawable-hdpi/btn_task_sign.png)

[Output APK](https://github.com/DreamTeamMobile/DT.Xamarin.AndroidPngMysteryBug/blob/master/APK/com.companyname.PngMysteryApp.apk) compiled in Release mode contains same file in the same folder, but the file size is [308 bytes](https://github.com/DreamTeamMobile/DT.Xamarin.AndroidPngMysteryBug/blob/master/APK/Contens%20of%20com.companyname.PngMysteryApp.apk/res/drawable-hdpi-v4/btn_task_sign.png).

Looking for any clues why this is happening and how to control that.

`<AndroidExplicitCrunch>true</AndroidExplicitCrunch>` does not change this behavior.

