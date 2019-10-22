# Google VR SDK for Android

Enables Daydream and Cardboard app development on Android.

Copyright (c) 2018 Google Inc.

See [https://developers.google.com/terms/](https://developers.google.com/terms/)
for the **Google APIs Terms of Service** which cover this SDK. The code in
`samples` is covered by the Apache 2 `LICENSE` file in that directory, and the
files in `assets` are covered by Creative Commons `LICENSE` file in that
directory.

For updates, known issues, and upgrade instructions, see the
[release-notes](//github.com/googlevr/gvr-android-sdk/releases).

For first time users, see the
[Get Started with Google VR on Android](//developers.google.com/vr/android/get-started)
guide.

SDK releases are availble from the
[releases](//github.com/googlevr/gvr-android-sdk/releases) page.

Please note, we do not accept pull requests.

# Testing Google VR SDK for Android
## Sử dụng Findbugs IDEA

### Xem cách chạy Findbugs IDEA trên Android Studio: https://youtu.be/EKpfkBdjuy8

### Kết quả:  ( Found 335 bug items in 306 classes )
    - Bad Practice: 218 items
    - Malicious code vulnerability: 106 items
    - Doggy code: 3 items
    - Multithreaded correctness: 7 items
    - Performance: 1 items
    
    
![image](https://user-images.githubusercontent.com/37697235/67294115-9a16a280-f50f-11e9-8413-9516338f81ad.png)

## Sử dụng PMD

### Ví dụ về PMD tìm được problem


![image](https://user-images.githubusercontent.com/37697235/67296273-6ee18280-f512-11e9-81a7-ac50dd9efe19.png)
### Xem cách chạy PMD trên Android Studio: https://youtu.be/6jqEhHzIrgk

### Kết quả:  ( Clean code )

![pmd1](https://user-images.githubusercontent.com/37697235/67296870-4443f980-f513-11e9-96d5-2aff0942b466.png)

![pmd2](https://user-images.githubusercontent.com/37697235/67296871-4443f980-f513-11e9-9ba7-2738114c4bd4.png)

