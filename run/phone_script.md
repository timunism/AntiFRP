> github.com/timunism/android-alpha-protocol

## ACTIVATE ADB Connection to PC
(While Device is On & Connected to the PC)
`Volume Up + Volume Down + Power`

## RETRIEVE LIST OF DEVICE APPS
`adb shell pm list packages`

## LAUNCH APP (e.g. Chrome in this case)
`adb shell monkey -p com.android.chrome -c android.intent.category.LAUNCHER 1`

## DONE

----------------------------------------------------------

## Open Accounts Settings
`ADB shell am start -a android.settings.ADD_ACCOUNT_SETTINGS \
                   -n com.android.settings/.accounts.AddAccountSettings`
 


