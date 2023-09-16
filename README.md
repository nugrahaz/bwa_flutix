# Flutix
> Watch movie in theater much easier 


## Notes
**In the near future, it will be migrated to the latest version with getx state management and uploaded to the playstore.**


## Description
Flutix is ​​a mobile application (iOS & Android) that helps people to buy tickets to watch online through their mobile phones. Flutix also uses the data collection method to display movies that match the user's profile.

![Screenshoot](https://github.com/Nugrahaz/bwa_flutix/assets/69227102/e3265649-2db7-4d5f-9570-619deabdc5c4)

## Features

- User Management (login/sign up)
- Now Playing Movies
- Select Cinema
- Select Showtimes
- Browse Movie by Category
- E-Wallet (for ticket transaction)
- Data Collection (genre dan preferred language)

## Techstack

- Dart
- Flutter SDK
- Firebase
- Public API (https://developers.themoviedb.org/3)
- Pub.dev

## Installing

- git clone https://github.com/abuazis/Flutix.git
- get themovie db api key in <a href="https://developers.themoviedb.org/3">The Movie DB Developer</a>
- put api key in  **lib/shared/shared_value.dart**
  ```dart
  part of 'shared.dart';
  
  String apiKey = "<YOUR_API_KEY_HERE>";
  ```
- flutter packages get
- flutter run


## Credit
Build With Angga (BWA Course)