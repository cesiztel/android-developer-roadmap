# Android Developer Roadmap

## Starting your Android development journey

To start you should understand 2 fundamental Android concepts: Android app can have multiple entry points (Main activiyty, notifications, broadcast recivers) and your apps should adapt to different device configurations (screen size, specif hardware). Do not worry! Android provide you the API's and tools to apply those two concepts easily.

### First Android App

This tutorial walks through the following concepts:

- First look of the code of an Activity.
- First look to the main components in an Android project (project structure, folders and files).
- Basic layout design. Definition of a constraint layout, constraints, attribute definition
- Intro to the communication between activities

Resource: 
* Official: [Android developer guidelines](https://developer.android.com/training/basics/firstapp)
* Code of the app in this repo: [1-first-app](./1-first-app)

## Resources 

### Books

#### Android specific (Java & Kotlin)

- [Android Programming: The Big Nerd Ranch Guide](https://www.bignerdranch.com/books/android-programming/)

- [Android Development with Kotlin](https://www.packtpub.com/application-development/android-development-kotlin)

- [Kotlin programming: The Big Nerd Ranch Guide](https://www.amazon.es/Kotlin-Programming-Nerd-Ranch-Guide/dp/0135161630/ref=sr_1_1?ie=UTF8&qid=1548835084&sr=8-1&keywords=kotlin+programming)

- [Kotlin for Android developers](https://leanpub.com/kotlin-for-android-developers)

### Project Guidelines & conventions

- [Project and Code Guidelines by ribot](https://github.com/ribot/android-guidelines/blob/master/project_and_code_guidelines.md)

- [A successful XML naming convention](https://jeroenmols.com/blog/2016/03/07/resourcenaming/)

### Layouts

#### ConstraintLayouts

- [Android - Building a layout from Scratch using ConstraintLayout - and Q&A #RiggarooLive] https://www.youtube.com/watch?v=h1LHzObflwo


### Design Patterns

#### MVP

- https://antonioleiva.com/mvp-android/
- https://dzone.com/articles/model-view-presenter-for-andriod 
Notes: in this example the presenter is also oriented to interface. I think
is overthinking because the operations are gonna be delegate to the interactor, so the presenter will host minimum implementation, therefore
oriented to interface maybe is too overthinking.
- https://hackernoon.com/basics-of-mvp-the-android-way-f75da407019d
- https://medium.com/cr8resume/make-you-hand-dirty-with-mvp-model-view-presenter-eab5b5c16e42
- http://macoscope.com/blog/model-view-presenter-architecture-in-android-applications/
- MVP Guidelines https://medium.com/@cervonefrancesco/model-view-presenter-android-guidelines-94970b430ddf

## Personal progress

- Reading  - Android Programming: The Big Nerd Ranch Guide

  54% - Current: Chapter 19

- Reading - Kotlin programming: The Big Nerd Ranch Guide

  7% - Current: Chapter 2

- Learning MVP Pattern

### Productivity

- [An #androidDev collection of Live Templates for Android Studio](https://github.com/keyboardsurfer/idea-live-templates)


### Articles

- [Splash Screens the Right Way](https://www.bignerdranch.com/blog/splash-screens-the-right-way/)

### Pending

Resources pending the review.

- https://kotlinlang.org/docs/reference/coding-conventions.html
- https://developer.android.com/kotlin/style-guide
- [ ] Code labs Google. https://codelabs.developers.google.com/?cat=Android
- [ ] [Video. Conference talk about activity Lifecycle](https://youtu.be/Lhk8WSUSw8g)
- [ ] Patterns: MVP
- [ ] Patterns: MVVM
- [ ] Article about clean Architecture: https://erikcaffrey.github.io/ANDROID-clean-architecture/
- [ ] Android Architecture Components Guide 
	  - https://developer.android.com/topic/libraries/architecture/
	  - https://riggaroo.co.za/android-architecture-components-looking-room-livedata-part-1/
	  - https://riggaroo.co.za/android-architecture-components-looking-viewmodels-part-2/
	  - https://riggaroo.co.za/android-architecture-components-looking-lifecycles-part-3/
	  - https://www.youtube.com/watch?reload=9&v=9QrFMsihBAo
	  - https://github.com/googlesamples/android-architecture-components
	  - https://codelabs.developers.google.com/codelabs/android-persistence/index.html#0
	  - https://codelabs.developers.google.com/codelabs/constraint-layout/index.html#0
- [ ] Work with network
      - https://www.tutorialspoint.com/restful/
	  - http://square.github.io/retrofit/
      - http://square.github.io/okhttp/
      - https://developer.android.com/studio/profile/network-profiler
      - https://www.charlesproxy.com/
- [ ] Continuous Integration for Android
  	  - Jenkins
      - BuddyBuild
	  - Cricle CI
      - Travis 
- [ ] Code quality
      - Code Quality Tools
      - Sonar
      - FindBugs
      - Checkstyle
      - Android Lint
- [ ] Matering Layouts
	  - FrameLayout
	  - RelativeLayout
	  - LinearLayout
      - ConstraintLayout
	  - CoordinatorLayout
      - Supporting different screen sizes - https://developer.android.com/training/multiscreen/screensizes
	  - ConstraintLayout - https://codelabs.developers.google.com/codelabs/constraint-layout/index.html#0
- [ ] Build systems
      - Build System
      - Gradle - https://gradle.org/
      - Configure the build - https://developer.android.com/studio/build/
- [ ] Testing 
      - Android Testing Support Library - https://developer.android.com/training/testing/ 
      - Espresso - https://developer.android.com/training/testing/espresso/basics
      - JUnit - https://junit.org/junit4/
      - Codelabe testing - 
  		https://codelabs.developers.google.com/codelabs/android-testing/index.html#0
  		https://codelabs.developers.google.com/codelabs/android-perf-testing/index.html#0	  
- [ ] Releasing 
      - Releasing your Android apps
      - Preparing your app for release - https://developer.android.com/studio/publish/preparing
      - App Signing - https://developer.android.com/studio/publish/app-signing
      - Versioning your App - https://developer.android.com/studio/publish/versioning
      - ProGuard - https://developer.android.com/studio/build/shrink-code
- [ ] Security
	  - Security Tips on Android - https://developer.android.com/training/articles/security-tips.html
      - Certificate Pinning - https://square.github.io/okhttp/3.x/okhttp/okhttp3/CertificatePinner.html
      - SafetyNet API - https://developer.android.com/training/safetynet/
      - Android Keystore System - https://developer.android.com/training/articles/keystore
- [ ] https://android.jlelse.eu/10-things-new-android-developers-can-relate-to-afd82791faab
- [ ] https://google.github.io/styleguide/javaguide.html
- [ ] Service, IntentService and their lifecycle:
      - https://developer.android.com/guide/components/services
      - https://medium.com/@kevalpatel2106/how-to-handle-background-services-in-android-o-f96783e65268
- [ ] Broadcast Receivers
      - https://android.jlelse.eu/local-broadcast-less-overhead-and-secure-in-android-cfa343bb05be
- [ ] Content Providers
  	  - https://developer.android.com/guide/topics/providers/content-providers
      - https://medium.com/@paulnunezm/steps-for-creating-a-content-provider-ab376d661613
      - https://medium.com/@sanjeevy133/an-idiots-guide-to-android-content-providers-part-1-970cba5d7b42
      - https://medium.com/@sanjeevy133/an-idiots-guide-to-android-content-providers-part-2-7ccfbc88d75c
- [ ] Tasks and the Back Stack
  https://medium.com/androiddevelopers/tasks-and-the-back-stack-dbb7c3b0f6d4
  https://android.jlelse.eu/android-activity-launch-mode-e0df1aa72242
  https://medium.com/@iammert/android-launchmode-visualized-8843fc833dbe
  https://blog.mindorks.com/android-task-and-back-stack-review-5017f2c18196
- [ ] Debugging your app
  https://developer.android.com/studio/debug/
  https://developer.android.com/studio/debug/
- [ ] Context in Android
- [ ]Android Views and Layouts
  https://medium.com/androiddevelopers/layouts-attributes-and-you-9e5a4b4fe32c
  https://medium.com/@geekanamika/android-beginners-views-layouts-657a5bbeebe2
- [ ] Android Themes and Styles
  https://youtu.be/TIHXGwRTMWI
  https://youtu.be/Jr8hJdVGHAk
- [ ] Fragments
  https://developer.android.com/guide/components/fragments
  https://medium.com/@bherbst/managing-the-fragment-back-stack-373e87e4ff62
  https://android.jlelse.eu/the-dark-side-of-fragments-ca0f871b1199
- [ ] ViewPager
  https://developer.android.com/reference/android/support/v4/view/ViewPager
  https://android.jlelse.eu/creating-an-intro-screen-for-your-app-using-viewpager-pagetransformer-9950517ea04f
- [ ] RecyclerView
  https://youtu.be/KhLVD6iiZQs
  https://youtu.be/LqBlYJTfLP4 
  https://youtu.be/TS_J0Qw4zl0
- [ ] Shared Preferences
  https://android.i-visionblog.com/working-with-android-shared-preferences-4668efa298a8
- [ ] Sqlite
  https://medium.com/@valokafor/ultimate-guide-to-android-sqlite-database-44cc8636a4ec
- [ ] Threading
  https://medium.com/@ankit.sinhal/understanding-of-asynctask-in-android-8fe61a96a238
- [ ] Book: Efficient Android Threading: Asynchronous Processing Techniques for Android Applications https://www.amazon.com/Efficient-Android-Threading-Asynchronous-Applications/dp/1449364136/ref=as_li_ss_tl?s=books&ie=UTF8&qid=1515094900&sr=1-1&keywords=efficient+android+threading&linkCode=sl1&tag=xgentechnical-20&linkId=85f8342ab0f8016cfc279bd3eeee0940
- [ ] ThreadPoolExecutor
- [ ] Looper, Handler, HandlerThread
- [ ] HTTP and REST
  https://code.tutsplus.com/tutorials/a-beginners-guide-to-http-and-rest--net-16340
- [ ] Networking in Android apps
  https://www.raywenderlich.com/2-android-networking-tutorial-getting-started
- [ ] Notifications
  https://developer.android.com/guide/topics/ui/notifiers/notifications
  https://youtu.be/WzRSpZpw2wg
- [ ] Location and Maps
  https://developer.android.com/guide/topics/location/
- [ ] Android Sensors
  https://developer.android.com/guide/topics/sensors/sensors_overview
- [ ] Localization and Internationalization
  https://youtu.be/Z51wN9wCao0
  https://developer.android.com/training/basics/supporting-devices/languages
  https://developer.android.com/training/basics/supporting-devices/languages
- [ ] Run Time Permissions
  https://developer.android.com/training/permissions/requesting
  https://youtu.be/f17qe9vZ8RM
  https://youtu.be/5xVh-7ywKpE
- [ ] App Standby and Doze Mode
  https://youtu.be/p6ZiDZBgPY8
- [ ] Android Support Libraries
  https://youtu.be/    
  https://developer.android.com/topic/libraries/support-library/
- [ ] Material Design
  https://youtu.be/vx3TXN6ipAg
  https://youtu.be/EjTJIDKT72M
  https://youtu.be/9LUHFkPVYNo
- [ ] Android Build System
  https://youtu.be/OOEDKf06WqA
  https://youtu.be/Xw6CKEsWvxo
