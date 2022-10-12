# open_weather_cubit

- Cubit + StreamSubscription

## Basic functionalities of this app:

```bash
1. Enter a city, get back weather of that city

2. Page to set temperature

```

## Development set up before running this:

```bash
1.Download flutter sdk.

2.Either vs code or Android studio or Intellji as an IDE

3.An android phone or iphone or an emulator, e.g. android studios/xcode.

```

## To run this locally

```bash
1.Sign up for an openweather account
Copy the api key after signing up.

2.After  downloading and unzipping,
go to .env copy in root folder.
replace value in APPID=YOUR_API_KEY with your api key.
rename .env copy to .env

3.Follow the build set up.

```

## Build Setup

```bash
#install dependencies:
flutter pub get

#install to a connected mobile device with usb debugging enabled:
flutter install

#or to install on phone via apk:
flutter build apk --split-per-abi
#apks can be found in /build/app/outputs/apk/release
```
