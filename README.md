# deb_vibes

A new Flutter project.

## Getting Started

The repository code is preloaded with some basic components like basic app architecture, app theme, constants and required dependencies to create a new project. By using boiler plate code as standard initializer, we can have same patterns in all the projects that will inherit it. This will also help in reducing setup & development time by allowing you to use same code pattern and avoid re-writing from scratch.

## How to Use 

**Step 1:**

Download or clone this repo by using the link below:

```
https://github.com/shivam-modi/debVibes.git
```

**Step 2:**

Go to project root and execute the following command in console to get the required dependencies: 

```
flutter pub get 
```

**Step 3:**
To run the project:

```
flutter run
```
### Libraries & Tools Used

* [http](https://github.com/dart-lang/http) (to send requests to server)
* [permission_handler](https://github.com/Baseflow/flutter-permission-handler)
* [flutter_sound](https://github.com/Canardoux/flutter_sound/tree/master/flutter_sound) (to handle all playing, recording)

### Folder Structure
Here is the core folder structure which flutter provides.

```
flutter-app/
|- android
|- build
|- ios
|- lib
|- test
```

### Required Permission
*   <uses-permission android:name="android.permission.INTERNET"/>
*   <uses-permission android:name="android.permission.RECORD_AUDIO"/>
*    <uses-permission android:name="android.permission.MODIFY_AUDIO_SETTINGS" />
*    <uses-permission android:name="android.permission.BLUETOOTH" />
*    <uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE" />
*    <uses-permission android:name="android.permission.READ_EXTERNAL_STORAGE" />
*    <uses-permission android:name="Manifest.permission.CAPTURE_AUDIO_OUTPUT" /> 

## Conclusion

I will be happy to answer any questions that you may have on this approach, and if you want to lend a hand with the boilerplate then please feel free to submit an issue and/or pull request 🙂

Don’t forget to ⭐ star the repo to show your support.
