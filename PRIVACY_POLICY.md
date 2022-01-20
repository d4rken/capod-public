# Privacy policy for the app `CAPod - Companion for AirPods`

## Preamble

I do not collect, share, sell or otherwise monetize personal information.

My underlying privacy principle is the [Golden Rule](https://en.wikipedia.org/wiki/Golden_Rule).

Send a [quick mail](mailto:support@darken.eu) if you have questions.

## Location data

`CAPod - Companion for AirPods` does not determine your location and does not collect, share or sell location data.

Bluetooth Low Energy is a technology that devices like AirPods use to communicate their status to nearby devices.
CAPod requests location related permission because these permissions are required to access Bluetooth Low Energy data.

This is a privacy measure on Android's side because you could determine someones location by scanning for Bluetooth devices:
If you know the physical location of a Bluetooth device (e.g. AirTags) you can use Bluetooth data to calculate your phones position.

To be able to scan for Bluetooth Low Energy (BLE) devices CAPod requests:
`ACCESS_FINE_LOCATION` on Android 11 and older, and on Android 12+ the newer more fine grained `BLUETOOTH_SCAN` permission.

On Android 11 and older CAPod also requests `ACCESS_BACKGROUND_LOCATION` to reliably receive Bluetooth Low Energy data while the app is in the background. This allows CAPod to show you notification with device details when you open your AirPods case without having to open the app. 

## Automatic crash reports

Anonymous device information may be collected in the event of an app crash or error.

To do this the app uses the service "Bugsnag":
https://www.bugsnag.com/

Bugsnags privacy policy can be found here:
https://docs.bugsnag.com/legal/privacy-policy/

Crash reports may contain device and app related information, e.g. your phone model, Android version and app version.

You can disable automatic reports in the app's settings.
