#Google Media Framework for Android

##Introduction
The Google Media Framework (GMF) is a lightweight media player designed to make video playback and integration with the Google IMA SDK on Android easier.

The framework is currently in beta, allowing interested developers to try it out and send feedback before we finalize the APIs and features.

##Features
- A customizable video player UI for video playback on Android.
    - Logo and branding colors.
    - Action buttons within video UI for other actions (ex. share, .
    - Subtitle support.
- Easily integrate the Google IMA SDK to enable advertising on your video content.
- Built on top of [ExoPlayer](https://github.com/google/ExoPlayer).
    - Plays DASH and mp4, and easily extended to other video formats.

##Getting started

Clone the repository

```git clone https://github.com/googleads/google-media-framework-android.git GoogleMediaFramework```

Then navigate to the directory and set up the ExoPlayer submodule.

```
cd GoogleMediaFramework

git submodule init

git submodule update
```

Finally import the project in Android Studio (or build using Gradle via ``./gradlew``).

##Where do I report issues?
Please report issues on the [issues page](../../issues).

##Support
If you have questions about the framework, you can ask them in our [google group](http://groups.google.com/d/forum/google-media-framework).

##How do I contribute?
See [this wiki article](../../wiki/Becoming-a-contributor) for details.

##Requirements

###Deployment
  - Android 4.1+

###Development
  - Gradle (1.12 or above)
  - Android Studio (0.8 or above)
    - Build tools version 19.1 (installed via SDK manager)
    - Google Play Services version 4.3.23 or higher (installed via SDK manager)
    - Google Repository (installed via SDK manager)
  - ExoPlayer (added as a git submodule)

##Authors
  - hsubrama@google.com (Harihar Subramanyam) Please direct questions or bug reports to the Github issues page.