# Stay Away From Me

A Flutter/Dart team project for BeaverHacks Fall 2020. It uses nearby Bluetooth signals to display a proximity gauge and a count of detected devices.

## Team and source

Ryan Adams, Micah Samaduroff, August Seabrooke, and Anjali Panikar.

This repository is a fork of [Ryan-Adams365/stay-away-from-me](https://github.com/Ryan-Adams365/stay-away-from-me). It preserves the hackathon work and shared authorship.

## Run locally

With Flutter and the Android or iOS development tools installed:

```bash
git clone https://github.com/aseabroo/stay-away-from-me.git
cd stay-away-from-me
flutter pub get
flutter run
```

Bluetooth detection needs a physical device and the relevant device permissions.

## Current status

Historical hackathon prototype using 2020-era dependencies. Compatibility with current Flutter releases and mobile Bluetooth permissions has not been verified.

Signal strength gives an approximate indication of proximity and varies with devices and surroundings. The project does not establish accurate distance measurements.

A useful next step is to document the original tool versions and test scanning on one current physical device.
