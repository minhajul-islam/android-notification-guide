build.gradle
-------------------------------
implementation 'com.google.firebase:firebase-core:16.0.4' <br />
implementation 'com.google.firebase:firebase-messaging:19.0.1' <br />



android manifest(example)
-------------------------------
write on <application> </application> tag
```

 <meta-data
            android:name="com.google.firebase.messaging.default_notification_color"
            android:resource="@color/colorPrimaryDark" />
        <meta-data
            android:name="com.google.firebase.messaging.default_notification_icon"
            android:resource="@drawable/notification" />
```
