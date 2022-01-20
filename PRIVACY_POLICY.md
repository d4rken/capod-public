# Privacy policy
This is the privacy policy for the Android app "CAPod - Companion for AirPods".

## Preamble
CAPod respects your privacy.

I do not collect, share or sell personal information.

Send a [quick mail](mailto:support@darken.eu) if you have questions.

My underlying privacy principle is the [Golden Rule](https://en.wikipedia.org/wiki/Golden_Rule).

## Location data

CAPod does not collect, share or sell location data.

The location permissions are required to scan for Bluetooth Low Energy (BLE) devices.
CAPod uses the permission "access fine location" (`ACCESS_FINE_LOCATION`) and "access coarse location" (`ACCESS_COARSE_LOCATION`) to enable its core functionality on Android 11 and lower.
On Android 12+ the newer and more fine grained `BLUETOOTH_SCAN` permission is used instead.

Bluetooth Low Energy is a technology that devices like AirPods use to communicate their status to nearby devices.
CAPod requests location related permission because these permissions are required to access Bluetooth Low Energy data.

This is a privacy measure on Android's side because you could determine someones location by scanning for Bluetooth devices:
If you know the physical location of a Bluetooth device (e.g. AirTags) you can use Bluetooth data to calculate your phones position.

### Location access in the background

CAPod uses the "location access in the background" permission (`ACCESS_BACKGROUND_LOCATION`) on Android 11 and older to receive Bluetooth Low Energy data while the app is in the background. This enables features like "Show popup" without the app being open.

## Automatic crash reports

Anonymous device information may be collected in the event of an app crash or error.

To do this the app uses the service "Bugsnag":
https://www.bugsnag.com/

Bugsnags privacy policy can be found here:
https://docs.bugsnag.com/legal/privacy-policy/

Crash reports may contain device and app related information, e.g. your phone model, Android version and app version.

You can disable automatic reports in the app's settings.
