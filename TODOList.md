

## 来源 ##

http://code.google.com/p/android-scripting/wiki/ApiReference

## API ##
### ActivityResultFacade ###

#### setResultBoolean ####
```
setResultBoolean(
 Integer resultCode: The result code to propagate back to the originating       
activity, often RESULT_CANCELED (0) or RESULT_OK (-1),
 Boolean resultValue)

Sets the result of a script execution. Whenever the script APK is called via    
startActivityForResult(), the resulting intent will contain SCRIPT_RESULT extra 
with the given value.
```

### AlarmManagerFacade ###

### AndroidFacade ###

### ApplicationManagerFacade ###

### BatteryManagerFacade ###

### BluetoothFacade Requires API Level 5. ###

### CameraFacade ###

### CommonIntentsFacade ###

### ConditionManagerFacade ###

### ContactsFacade ###

### EventFacade ###

### LocationFacade ###

### MediaRecorderFacade ###

### PhoneFacade ###

### PulseGeneratorFacade ###

### SensorManagerFacade ###

### SettingsFacade ###

### SignalStrengthFacade Requires API Level 7. ###

### SmsFacade ###

### SpeechRecognitionFacade ###

### TextToSpeechFacade Requires API Level 4. ###

### ToneGeneratorFacade ###

### UiFacade ###

### WakeLockFacade ###

### WifiFacade ###