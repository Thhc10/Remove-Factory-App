## Removing Android Factory Apps

Download Android SDK Platform Tools and Install
- [Repository Link](https://dl.google.com/android/repository/platform-tools-latest-windows.zip)
- [Page Link](https://developer.android.com/tools/releases/platform-tools#downloads.html)

Add to platform-tools folder to PATH

Run cmd as admin

Run shell
> adb shell

Finding the package
> pm list packages | grep $package_name 

Uninstall the package
> pm uninstall --user 0 $package_name
