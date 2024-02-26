Call the activity from ADB:

```
adb shell am start -p com.android.shell -a android.intent.action.MAIN -c org.lsposed.manager.LAUNCH_MANAGER -f 0x10000000 -n com.android.shell/.BugreportWarningActivity
```

Call the activity from termux:

```
su -c am start -p com.android.shell -a android.intent.action.MAIN -c org.lsposed.manager.LAUNCH_MANAGER -f 0x10000000 -n com.android.shell/.BugreportWarningActivity
```