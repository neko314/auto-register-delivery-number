## How to extra Bluetooth log

Official document is here: https://source.android.com/devices/bluetooth/verifying_debugging#debugging-options

Run these commands

```sh
# on repository root
adb shell dumpsys bluetooth_manager > BUG_REPORT.text

preprare/debug/btsnooz.py BUG_REPORT.text > BTSNOOP.log
```
