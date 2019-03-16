# DSC-Android
![Android](https://img.shields.io/badge/platform-Android-green.svg)

<p align="center">
    <img src="https://i.gifer.com/74Zk.gif" alt="android" width="200"/>
    <br><img src="https://lh3.googleusercontent.com/jzuXJlV4mWInpXTyssMz6ZmrcPvRye97DdUexjTew1MRN0JUl4z2EztSOo2Cv3_ztWY-1VG3McEyJBvUKugcE-snmAfeS5E=s1352" alt="logo" width="500"/>   <br>
    </p>


## Course Structure

- Introduction to Mobile App Development
- Native(Android SDK, iOS Native) V/S Hybrid (ReactJS, PhoneGap Cordova, Flutter) App
Development
- WhatsApp use case of erlang and performance issues
- When to use Native and When to use Hybrid

### A)

---------------------------------------------Introduction Phase------------------------------------------------

**A1) XML (Screen Designing in Android)**

- Views Introduction (TextView, ImageView, EditText etc)
- Introduction to XML
- Attributes to basic (Legacy) Views (eg;- Wrap Content, Match Parent etc)
- ViewGroups Part 1 (Linear Layout, Relative Layout)
- Density Independent Pixels vs Size Independent Pixels
- ViewGroups Part2 (Constraint Layout, Coordinator Layout, Grid Layout, FrameLayout etc)
- Views Part 2 (RecyclerView, CardView ListView, ScrollView etc) Introduction

**P1) Project:- EventCard Designing**

**A2) Basic Java + XML**

- Basic Java (Method Defiantion, Variable declaration, Classes, constructors, Objects etc)
- Interfaces in Java
- XML and Java Interaction (Resources in Android, findviewbyid etc)
- Data Types, loops (If needed)
- onClick attribute
- onClickListener Intro

**A3) Basic Android**

- Creating Toasts Part 1
- Android Intent Introduction (Intent to gmail app, maps app, from one activity to another)
- Style vs Theme
- Debugging Basics

**P2) PROJECT:- Single Screen App.**

---------------------------------------------- End of Introduction Phase-------------------------------------------


## B)

------------------------------------------- Working with Android Phase 2 (Beginner Phase)---------------------------
**B1) Android-Activities**

- Activity Lifecycle and How To manage screen changes?
- Intents (Explicit, Implicit, Passing Data, Parcelable)
- Activities Tasks and Stacks (Launchmodes etc).

```
Core Java For Android Development
SUBMODULE Part- 1

- Inner Class and Anonymous Inner Class
- Overloading and Overriding
- Collection Framework in Java (List, Set, Map, Queue)

```

**B2) Android-RecyclerView and ListViews**

- ArrayList
- ListView+ArrayAdapter (OPTIONAL Now Mostly replaced by RecyclerView)
- Advantages Of RecyclerView over ListView (Memory Overload Demo in Debugger)
- Recycler View with Custom Adapter (EventHandling, BaseAdpter etc)

**B3) Android-Fragments**

- Introduction to Fragments
- Static vs Dynamic Addidtion Of Fragment
- Fragment Lifecycle vs Activity Lifecycle
- Fragments (Backstack)
- Fragments (Implementation)
- Callbacks in Fragments
- Impact of Screen Orientation Changes in Fragment
- Supporting Multiple Screen Layouts with the help of Fragments (Topic can be shifted to
Later Phase)

```
Core Java For Android Development
SUBMODULE Part- 2

- Multithreading (Synchronization, Volatile etc)
- Concept Of Blank Final
- String Constant Pool, Difference Between String, String Buffer, String Builder
- Sterilization
- Java Generics
```

**B4) Android UI- (Menu and Drawer, Dialogs)**
- Implementing Drawer and Menu in appbar.
- Simple AlertDialog

**B5) Android- AsyncTask (Will Continue in Networking)**

- UI thread/Main Thread
- Looper and Handler
- AsyncTask

**B6) Android – Media Playback (Audio, Video, Webview) (Introduction)**

- Adding Mediaplayer
- Mediaplayer States
- Asynchronus Calling Methods
- Audio Focus (Priority Assigning)
- Implementation
- Opening Websites in the Android App using Webview
- Security issues with Webview (or Browser Intent vs WebView)

**P3) PROJECT:- MultiScreen App**

**B7) Android-Permissions**

- Dangerous vs Normal Permissions
- Declaring Permissions in Manifest
- Managing Android Permissions at Runtime

### B-2

**B2 1) NETWORKING in Android (Important)**

- Introduction to API
- JSON (Overview)
- Parsing JSON in Android
- HTTP Networking (get Post etc)
- Opening a URL Connection
- HTTP Request Codes
- INPUTSTREAM BUFFERED READER
- Throwing An Exception
- HTTPURLConnection with Restful Web services.
- Installing an HTTP response cache


**B2 2) AsyncTask Loader**
o Limitation of AsyncTask
o AsyncTask Loader
o Loader Manager Callbacks
o Loader vs Service Configuration Changes (They Survive Changes)
o Loader Implementation

**B3 3) Android UI Handling Empty State of The App**

- Working with ProgressViews - Checking Network State


**P4) PROJECT:- NewsApp/Any API Fetching App**

### B-3

**B3 1) ANDROID DATA PERSISTENCE (Can be covered before Networking As Well)**

```
Core Java For Android Development
SUBMODULE Part- 3
- Singleton Design Pattern (Commonly Used For Retrofit)
- Java File Handling (File I/O)
```

**B3 2) Android- Shared Preferences**

- Shared Preferences Contexts (For Strings, Objects as Well As Images
- Preference Screen in Android UI


**B3 3) Android File I/O same as Java File(I/O)**

- Image Storage and Retrival
- Overview of Image Encodings (Mainly byte array conversion, base64 encoding)


**B3 4) Android-SQLite**

- CRUD Operations
- Android UI and SQLite Integration
- SQLite + RecyclerView


**B3 5) Android Room (Making SQLite Easier) / Architecture Components**

- Room + ViewModel + LiveData + RecyclerView (MVVM Architecture)


**P4++) PROJECT:- Modify Earlier Project to use these**

----------------------------------------------Beginner Phase End-------------------------------------------------

## C)


-------------------- Working with Android Phase 3 (Developer Phase) ---------------------------------------------

**C1) Android UI**

- Custom Dialog + Dialog and Interfaces
- Custom Notification

**C2) Content Providers**

- Designing and Matching Content URI’s
- Insert Update Delete
- getType and MIME type

**C4) Third-Party Libraries and creating own Library**

- Using third Party library
- Where to find libraries
- Some Important Libraries like Glide, Picasso, Retrofit, GSON, Volley
- **Retrofit And Volley,** Implementation
- **Glide** implementation
- Creating our own library
- POJO Maker Tool

**C5) Background Tasks**

**C5.1) Services:-**

- Sticky and Non-Sticky Services
- Bound Services
- Local and Remote Binding
- Remote Binding Using Messenger
- Bind to Remote Services

**C 5.2) Broadcast Recievers:-**

- **Introduction**
- Dynamic Registration Of Broadcast
- Listening to custom intent broadcast
- Changes to broadcast since android Oreo
- Ordered Broadcast Recievers
- Permissions
- Local Broadcast Manager

**C6) Using Sensors in Android**

- Using GPS/Gyroscope etc

**C7) Android Places**

- Using Google Places API
- Georeferencing
- Tracking User

**P5) MediaPlayer Contd. PROJECT:- MusicPlayer**

**C8) Widgets:-**

- Pending Intent, IntentService
- Widgets UI

**CBonus) Notifications in Android (Before and After Oreo)**

--------------------------------------End of Phase 3 (Developer)-----------------------------------------------


## D)

-----------------------------------Android with Firebase Phase 4 (Developer Extension)-------------------------

 **D1) Firebase Authentication**
- Firestore Database
- Storage in Cloud Firebase
- Cloud Messaging
- In-App Messaging
- Dynamic Links


**D2) Firebase AdMob**

- Earning Money through Ads


**D3) Firebase Machine Learning Kit:-**

- Face Recognition
- Text Recognition
- Barcode Scanning
- Image Labelling
- Landmark Recognition
- Language ID


**D4) Custom Machine Learning Models Using Firebase**

- Creating Custom Models on Tensorflow Lite
- **Integrating model with Firebase**
- Running On-Device Machine Learning on Android
- Adding Offline Capibilities

**---------------------------------------------------- End of Phase 4 (Firebase + Android)---------------------**

## E)

------------------------------- **Advanced Android Development Phase 5 (Advanced)** -----------------------------

**E1) Writing Unit Tests For UI**

- Using Espresso for UI tests

**E2) Gradle**

- Fundamentals for Java and Android
- Advanced Android Builds
- Few Special Topics

**E3) Architecture Design Patterns for Mobile Development**


- MVP Architecture
- MVVM Architecture
- MVP vs MVVM

**E4) DAGGER (Directed Acyclic Graph Dependencies)**

- Introduction to Dependency Injection
- Dagger For Dependency Resolving
- Understanding how Butterknife Works
- Dagger1 vs Dagger
- Dagger2 implementation.

**-------------------------------------------------- End of Phase 5------------------------------------------**

## F)

**-----------------------------------------Last Phase (Publising App to Play Store)---------------------**

- Getting and Understanding Google Play Developer Console
- Preparing App For Release
- Understanding Google Android Policy so that app do not get Rejected
- Securing Source Code from using **ProGuard** and APK Signatures
- Providing App Updates to users

-------------------------------------------- **End Of Android Course** -----------------------------------------------

Future Scope:- Introduction to Android Engineering with Root Level Modifications to Linux
Kernel through Apps


