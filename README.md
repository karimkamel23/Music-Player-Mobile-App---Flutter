# Music Player App in Flutter using 'audioplayers' package

In this project I created a Music Player App using the Flutter framework using the 'audioplayers' package, which acts as an abstaraction that uses platform-specific audio player implementations to achieve audio playback like 'Media Player' class for Android. This app allows you to navigate through the songs, while also allowing features like: repeat, shuffle, seek, skip, go to previous and more.

## Table of Contents

- [Installation](#installation)
- [Project Structure](#project-structure)
- [Contact](#contact)

## Installation

1. Make sure all Flutter and Dart dependencies are installed on your device.
2. Clone the repository.
3. Navigate to the project directory.
4. Enter 'flutter run' in the terminal to run the application.
5. Choose the desired emulator if any.

## Project Structure

- lib/: Main source code directory
- main.dart: Entry point of the Flutter app.
- pages/: Stores the pages used in the Flutter app.
- home_page.dart: The app's main page which displays the list of songs. It also shows if a song is playing and redirects you to the song page if a song is pressed.
- song_page.dart: This page displays the full details and controls for the current song and allows for all the different functionalities like skipping, repeating, shuffling, etc. Using the PlaylistProvider defined in the playlist_provider.dart file. 
- settings_page.dart: This page allows user to toggle between light mode and dark mode.
- themes/: Stores theme information for both light and dark modes, as well as the ThemeProvider.
- dark_mode.dart: Defines the theme data and colors for dark mode.
- light_mode.dart: Defines the theme data and colors for light mode.
- theme_provider.dart: Provides the theme data for the rest of the app as a Change Notifier by using the needed setters and getters.
- models/: Stores the models used in creating the app.
- song.dart: Defines the model for the Song object which holds: song name, artist name, album art, and audiopath.
- playlist_provider.dart: Provides the functionalities for operating the songs by utilizing the 'audioplayers' package. Also, provides the functions needed for all the different functions of the music player.
- components/: Stores all the components and widgets utilized by pages in the app.
- main_drawer.dart: Provides the implementation of the main drawer used in the application.
- neumorphic_box.dart: Creates a box with a modern hovering look.
- assets/: Stores the assets for the application, including /images and /audio.

## Contact

  If you have any questions or feedback, feel free to contact me at karimkamel23@gmail.com
