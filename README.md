# Trackify

> App that tracks your run and marks on Map and saves the image of map along with different information like distance measured, calories burned, speed.

<p align="middle">
    <img width="200" src="https://user-images.githubusercontent.com/62428616/179186500-09a96b5d-18fa-41ee-9b28-ddd44c074461.png">
    <img width="200" src="https://user-images.githubusercontent.com/62428616/179186610-c6211e25-9748-495a-bdc1-dc6c6b2b4888.png">
    <img width="200" src="https://user-images.githubusercontent.com/62428616/179186694-c5a49582-43aa-4b0b-96ec-8f3c70b7ab51.png">
    <img width="200" src="https://user-images.githubusercontent.com/62428616/179186818-1e643224-33e4-464b-8a11-bfc6ccbbbfdb.png">
</p>

## Architecture
MVVM (Model - ViewModel - View) is the design pattern used for making this app.
MVVM provides a clear separation of concern and has great support in Android SDK in the form of [Architecture Components][1].

## Libraries Used
* [Architecture][1] - A collection of libraries that help you design robust, testable, and
  maintainable apps.
    * [LiveData][3] - Build data objects that notify views when the underlying database changes.
    * [Room][4] - Access your app's SQLite database with in-app objects and compile-time checks.
    * [ViewModel][5] - Store UI-related data that isn't destroyed on app rotations. Easily schedule
      asynchronous tasks for optimal execution.
    * [Dagger][6] - For Dependency Injection
    * [Navigation][11] - Handle everything needed for in-app navigation.
    * [Google Maps][2] - To integrate map to track accurate location
* Third party
    * [Glide][7] for image loading
    * [Kotlin Coroutines][8] for managing background threads with simplified code and reducing needs for callbacks
    * [MPAndroidChart][9] to chart the statistics of the run


[1]: https://developer.android.com/jetpack/arch/
[2]: https://developers.google.com/maps/documentation/android-sdk/overview
[3]: https://developer.android.com/topic/libraries/architecture/livedata
[4]: https://developer.android.com/topic/libraries/architecture/room
[5]: https://developer.android.com/topic/libraries/architecture/viewmodel
[6]: https://developer.android.com/training/dependency-injection/dagger-android
[7]: https://bumptech.github.io/glide/
[8]: https://kotlinlang.org/docs/reference/coroutines-overview.html
[9]: https://github.com/PhilJay/MPAndroidChart
[10]: https://developer.android.com/training/dependency-injection/hilt-android
[11]: https://developer.android.com/topic/libraries/architecture/navigation/
