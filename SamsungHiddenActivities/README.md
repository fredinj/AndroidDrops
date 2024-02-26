[XDA](https://xdaforums.com/t/exploit-shizuku-support-smt-shell-v2-0-get-a-system-shell-uid-1000-within-the-app-itself-and-write-your-own-system-app-with-an-api.4561879/post-88312731) <br>
[Reddit](https://www.reddit.com/r/samsung/comments/10h83uy/workaround_samsung_band_selection_new_method/) <br>
[GitHub - New](https://github.com/wr3cckl3ss1/system3)

```
am start com.samsung.android.app.telephonyui/.hiddennetworksetting.MainActivity
```


*COMMANDS FOR SYSTEM AND/OR ROOT USE ONLY*

**WARNING**
Do your research and find out what something does before you aimlessly execute the commands and mess something up. This is your only warning.

IOTHiddenMenu.apk

am start -n com.sec.hiddenmenu/.KOREA_Mode -e 7267864872 72678647376477466

am start -n com.sec.hiddenmenu/.KoreaMode_Prevail -e 7267864872 72678647376477466

am start -n com.sec.hiddenmenu/.SerialPort -e 7267864872 72678647376477466

am start -n com.sec.hiddenmenu/.ItsOnMenu -e 7267864872 72678647376477466

am start -n com.sec.hiddenmenu/.ServiceModeApp -e 7267864872 72678647376477466

am start -n com.sec.hiddenmenu/.Test -e 7267864872 72678647376477466

am start -n com.sec.hiddenmenu/.PhoneUtil -e 7267864872 72678647376477466

am start -n com.sec.hiddenmenu/.OTATest -e 7267864872 72678647376477466

am start -n com.sec.hiddenmenu/.LTE -e 7267864872 72678647376477466

am start -n com.sec.hiddenmenu/.FIELDTESTMODE -e 7267864872 72678647376477466

am start -n com.sec.hiddenmenu/.HiddenMenuEnable -e 7267864872 72678647376477466

am start -n com.sec.hiddenmenu/.GlobalHiddenMenuEnable -e 7267864872 72678647376477466


Change your CSC thru Preconfiguration. (Exclusive to primarily US devices)

am start -n com.samsung.android.cidmanager/.modules.preconfig.PreconfigActivity -a com.samsung.android.action.SECRET_CODE -d secret_code://27262826 --ei type 2

Option #2 for Possible CSC change on devices not from US.

am start -n com.samsung.android.cidmanager/.preconfig.PreconfigActivity -a android.provider.Telephony.SECRET_CODE -d secret_code://272837883 --ei type 3


Service Menu

am broadcast -a com.samsung.android.action.SECRET_CODE -d android_secret_code://27663368378 -n com.sec.android.RilServiceModeApp/.SecKeyStringBroadcastReceiver

Hidden Network Band Selection

am start -n com.samsung.android.app.telephonyui/.hiddennetworksetting.MainActivity


Use with CAUTION***

am start -n com.wssyncmldm/com.idm.fotaagent.enabler.ui.admin.feature.AdminFeatureAndActionActivity

am start -n com.wssyncmldm/com.samsung.android.fotaagent.common.feature.FeatureInjectionActivity

am start -n com.sec.android.app.factorykeystring/com.sec.android.app.shutdown.ShutdownPreference

am start -n com.samsung.android.sdm.config/.ui.DevConfigActivity

am start -n com.sec.android.sdhms/.debugger.ui.ThermalLimitSettingActivity

am start -n com.sec.usbsettings/.USBSettings

am start -n com.android.settings/.development.DSULoader

am start -n com.sec.android.app.servicemodeapp/com.sec.android.app.modemui.activities.PhoneUtil

am start -n com.sec.android.app.myfiles/.external.ui.developer.DeveloperSettingActivity

am start -n com.sec.android.app.factorykeystring/com.sec.android.app.phoneutil.UsbLogging

am start -n com.samsung.sdm/com.samsung.sdm.logic.DMApp

Have fun...
--wr3cckl3ss1