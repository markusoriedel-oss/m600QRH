# M600 QRH

The Piper M600 Quick Reference Handbook as a tappable app for the iPhone that
works without a network connection. Based on the M600 QRH Book version 1.3.

**Live: https://markusoriedel-oss.github.io/m600QRH/**

Current build: QRH v.1.3, APP v.0.8

## Install it on an iPhone

The app does not come from the App Store. It is placed on the home screen
straight from Safari, and from then on it runs full screen and offline.

1. Open **Safari** and go to https://markusoriedel-oss.github.io/m600QRH/
   Safari is required: on the iPhone, Chrome and Firefox cannot install an app
   that keeps working offline.
2. **Let it load completely**, ideally on Wi-Fi. It is about 17 MB, because every
   original QRH page is included as an image. Wait a few seconds until the home
   screen of the app has built up.
3. Tap the **Share** icon (the square with the arrow pointing up), then
   **Add to Home Screen**, then **Add**.
4. **Launch it once from the home screen while you still have a connection.**
   Only then does it store all files locally for good.

That is it. From now on it also starts in airplane mode.

## Verify it really is offline

Put the iPhone in airplane mode, start the app from the home screen, open any
checklist and tap "Show original QRH page" at the bottom. If the scanned original
page appears, everything is genuinely stored on the device.

If instead you get a blank or partial page: turn the network back on, open the
app, leave it open for a minute, then test again in airplane mode.

## Updates

Just start the app while online. It recognises a new release by its app number
and downloads it in the background, so the next launch after that runs the new
build. The version is shown in the header of the home screen
(`QRH v.1.3 · APP v.0.10`).

That background update sometimes lags a release, even with a connection. The
**circular arrows in the top right corner** force it: tap them, confirm, and the
app clears its stored copy and reloads the current build from this repository.
It needs a connection for a moment, so it asks first and refuses outright when
you are offline. Nothing is lost either way, the app stores no user input.

If a version ever gets truly stuck, delete the app from the home screen and
repeat the four steps above.

## CAS message colours

The app reproduces the three renderings used in the QRH exactly:

| Level | Rendering |
|---|---|
| Warning | red background, white text |
| Caution | black background, yellow text |
| Advisory | black background, white text |

The level belongs to the individual occurrence, not to the name of the message.
`T/O CONFIG` appears on one and the same QRH page once as an advisory and once as
a warning, and `FUEL QTY`, `CHECK GEAR`, `GEAR SYS` and `HYDR PUMP ON` switch
between warning and caution depending on the situation. The colours are therefore
read directly out of the source PDF rather than inferred.

## Note

A private reading aid, not an approved document. Only the QRH carried on board
and the POH are authoritative.
