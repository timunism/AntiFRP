> github.com/timunism/AntiFRP

# 1. SETUP
----------------------------------------------------------

## Turn on Device and Connect it to the PC via Cable
Then Hold: `Volume Up + Volume Down + Power` to enable USB Debugging

## Some Devices may require a different key-combination
Try The Following:
    `Volume Up + Power` or `Volume Down + Power` or `Volume Up + Volume Down`

# 2. STAGING
-----------------------------------------------------------

## TO RETRIEVE LIST OF DEVICE APPS
Type: `adb shell pm list packages`

## TO LAUNCH APP (e.g. Chrome in this case)
Type: `adb shell monkey -p com.android.chrome -c android.intent.category.LAUNCHER 1`

## TO OPEN ACCOUNT SETTINGS
`ADB shell am start -a android.settings.ADD_ACCOUNT_SETTINGS \
                   -n com.android.settings/.accounts.AddAccountSettings`

----------------------------------------------------------
 


