# Extra Buttons Functions

The button argument in all of these functions can be either "first" or "second"

ex usage:

```lua
if extraButtonJustPressed("first") then
-- logic
end
```

**extraButtonPressed(button:String)**  
Checks if the extra button is pressed

**extraButtonJustPressed(button:String)**  
Checks if the extra button got pressed once

**extraButtonJustReleased(button:String)**  
Checks if the extra button got released

**extraButtonReleased(button:String)**  
Checks if the extra button is released

## Touch Functions

**touchPressed()**  
Checks if the screen is touched

**touchJustPressed()**  
Checks if the screen gets touched once

**touchJustReleased()**  
Checks if the screen gets released

**touchPressedObject(object:String, ?camera:String)**  
Checks if the object is touched

**touchJustPressedObject(object:String, ?camera:String)**  
Checks if the object gets touched once

**touchJustReleasedObject(object:String, ?camera:String)**  
Checks if the object gets released

**touchReleasedObject(object:String, ?camera:String)**  
Checks if the object is released

**touchPressedObjectComplex(object:String, ?camera:String)**  
Checks if the object is touched

**touchJustPressedObjectComplex(object:String, ?camera:String)**  
Checks if the object gets touched once

**touchJustReleasedObjectComplex(object:String, ?camera:String)**  
Checks if the object gets released

**touchReleasedObjectComplex(object:String, ?camera:String)**  
Checks if the object is released

**touchOverlapsObject(object:String, ?camera:String)**  
Checks if the object gets overlapped to touch

**touchOverlapsObjectComplex(object:String, ?camera:String)**  
Checks if the object gets overlapped to touch

## Lua Touch Pad Functions

**addTouchPad(DPadMode:String, ActionMode:String, ?addToCustomSubstate:Bool, ?posAtCustomSubstate:Int)**  
Adds the lua touch pad

**addTouchPadCamera()**  
Adds a lua touch pad camera for the touchpad

**removeTouchPad()**  
Removes the lua touch pad

**touchPadPressed(button:Dynamic)**  
Checks if a specific lua touch pad button is pressed

**touchPadJustPressed(button:Dynamic)**  
Checks if a specific lua touch pad button gets pressed once

**touchPadJustReleased(button:Dynamic)**  
Checks if a specific lua touch pad button gets released

**touchPadReleased(button:Dynamic)**  
Checks if a specific lua touch pad button is released

## Android Functions

**isRooted**  
A variable checks if your Android device is rooted

**isDolbyAtmos**  
A variable checks if your Android device has Dolby Atmos

**isAndroidTV**  
A variable checks if your Android device is an Android TV

**isTablet**  
A variable checks if your Android device is a tablet

**isChromeBook**  
A variable checks if your Android device is a Chromebook laptop

**isDeXMode**  
A variable checks if your Android device is in Samsung DeX mode

**isCharging**  
A variable checks if your Android device is being charged

**backPressed()**  
Checks if the back button is pressed

**backJustPressed()**  
Checks if the back button gets pressed once

**backJustReleased()**  
Checks if the back button gets released

**menuPressed()**  
Checks if the menu button is pressed

**menuJustPressed()**  
Checks if the menu button gets pressed once

**menuJustReleased()**  
Checks if the menu button gets released

**setOrientation(hint:String)**  
Sets a orientation. Possible values are "Portrait", "PortraitUpsideDown", "LandscapeLeft" and "LandscapeRight"

**getCurrentOrientation()**  
Gets current orientation

**isScreenKeyboardShown()**  
Checks if screen keyboard is shown

**clipboardHasText()**  
Checks if clipboard has something on it

**clipboardGetText()**  
Gets clipboard text

**clipboardSetText(string:String)**  
Sets the clipboard text

**manualBackButton()**  
Simulates a back button press

**setActivityTitle(title:String)**  
Sets the activity title

## Other Things

**mobileC**  
A variable that returns mobile controls are visible or not

**mobileControlsMode**  
A variable representing the current mobile controls the player is using all the possible values are "left", "right", "custom", "hitbox" and "none".

**vibrate(duration:Int, ?period:Int)**  
Vibrates your device
