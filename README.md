# Expo SDK 54 DateTimePicker Android Crash

## Reproduction

1. `npm install`
1. `npm run android`
1. Open the app on a physical Android device. The component will not render and will error with this message:

```
ERROR  Cannot set prop 'initialDate' on view 'class expo.modules.ui.DateTimePickerView'
→ Caused by: Cannot find type converter for 'java.util.Date?'. Make sure the class implements `expo.modules.kotlin.records.Record` (i.e. `class MyObj : Record`).
```
