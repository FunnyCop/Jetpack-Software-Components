# Jetpack Software Components

- [Foundation Components](#foundation-components)
  - [AppCompat](#appcompat)
  - [Android KTX](#android-ktx)
  - [Test](#test)
  - [Multidex](#multidex)

  <br>

- [Architecture Components](#architecture-components)
  - [Room](#room)
  - [WorkManager](#workmanager)
  - [Lifecycle](#lifecycle)
  - [ViewModel](#viewmodel)
  - [LiveData](#livedata)
  - [Navigation](#navigation)
  - [Paging](#paging)
  - [Data Binding](#data-binding)

  <br>

- [Behavior Components](#behavior-components)
  - [DownloadManager](#downloadmanager)
  - [Media & Playback](#media--playback)
  - [Permissions](#permissions)
  - [Notifications](#notifications)
  - [Sharing](#sharing)
  - [Slices](#slices)

  <br>

- [UI Components](#ui-components)
  - [Animation & Transition](#animation--transition)
  - [Auto](#auto)
  - [Emoji](#emoji)
  - [Fragment](#fragment)
  - [Layout](#layout)
  - [Palette](#palette)
  - [TV](#tv)
  - [Wear](#wear)

---

# Foundation Components

- [Back to Top](#jetpack-software-components)
- [Architecture Components](#architecture-components)
- [Behavior Components](#behavior-components)
- [UI Components](#ui-components)

<br>

- [Geeks for Geeks](https://www.geeksforgeeks.org/foundation-components-of-android-jetpack/)

---

- [AppCompat](#appcompat)
- [Android KTX](#android-ktx)
- [Test](#test)
- [Multidex](#multidex)

---

**Foundation Components** are a set of core system components for Android Applications which include Kotlin language support, Testing utilities, and backwards compatibility support.

---

## AppCompat

- [Back to Section Contents](#foundation-components)
- [Android Documentation](https://developer.android.com/jetpack/androidx/releases/appcompat)

---

The **AppCompat** (Appcompat/appcompat) library contains key components for building Android Applications such as:

**App Bars** ([Compose View](https://developer.android.com/jetpack/compose/layouts/material#app-bars), [Android View](https://developer.android.com/guide/navigation/navigation-ui#top_app_bar))

**Navigation Drawers** ([Compose View](https://developer.android.com/jetpack/compose/layouts/material#drawers), [Android View](https://developer.android.com/guide/navigation/navigation-ui#add_a_navigation_drawer))

**Permissions** ([Requesting](https://developer.android.com/training/permissions/requesting), [Declaring](https://developer.android.com/training/permissions/declaring))

**Resources** ([Compose View](https://developer.android.com/jetpack/compose/resources), [Android View](https://developer.android.com/guide/topics/resources/providing-resources))

**Dialog Boxes** ([Compose View](https://www.geeksforgeeks.org/alertdialog-in-android-using-jetpack-compose/), [Android View](https://developer.android.com/guide/topics/ui/dialogs))
**Share Actions** ([Simple Data](https://developer.android.com/training/sharing/send), [ShareActionProvider](https://developer.android.com/reference/kotlin/androidx/appcompat/widget/ShareActionProvider))

---

## Android KTX

- [Back to Section Contents](#foundation-components)
- [Android Documentation](#https://developer.android.com/kotlin/ktx)

---

The **Android KTX** library contains **Extension functions**, **Extension properties**, **Lambdas**, **Named parameters**, **Parameter default values**, and **Coroutines** some of the modules include:

**Fragment KTX** ([Android Documentation](https://developer.android.com/kotlin/ktx#fragment))

**Lifecycle KTX** ([Android Documentation](https://developer.android.com/kotlin/ktx#lifecycle))

**Navigation KTX** ([Navigation KTX](https://developer.android.com/kotlin/ktx#navigation))

**Room KTX** ([Android Documentation](https://developer.android.com/kotlin/ktx#room))

**ViewModel KTX** ([Android Documentation](https://developer.android.com/kotlin/ktx#viewmodel))

---

## Test

- [Back to Section Contents](#foundation-components)
- [Android Documentation](https://developer.android.com/training/testing)

---

The **Test** library includes:

**Espresso UI** for UI testing ([Android Documentation](https://developer.android.com/training/testing/espresso))

**AndroidJUnitRunner** for unit testing ([Android Documentation](https://developer.android.com/training/testing/junit-runner))

---

## Multidex

- [Back to Section Contents](#foundation-components)
- [Android Documentation](https://developer.android.com/jetpack/androidx/releases/multidex)

---

**Multidex** allows applications to be split across multiple *Dex* (executable) files which makes it possible to run larger applications (containing more than 65,536 methods) within the Android virtual machine (*Dalvik*) on devices running Android versions before Lollipop.

---

# Architecture Components

- [Back to Top](#jetpack-software-components)
- [Foundation Components](#foundation-components)
- [Behavior Components](#behavior-components)
- [UI Components](#ui-components)

<br>

- [Geeks for Geeks](https://www.geeksforgeeks.org/jetpack-architecture-components-in-android/)

---

- [Room](#room)
- [WorkManager](#workmanager)
- [Lifecycle](#lifecycle)
- [ViewModel](#viewmodel)
- [LiveData](#livedata)
- [Navigation](#navigation)
- [Paging](#paging)
- [Data Binding](#data-binding)

---

**Architecture Components** are libraries that make it easier for developers to deal with changes to data and lifecycles and local storage. They include tools for things like data binding, paging, navigation, and abstraction for local SQLite databases.

---

## Room

- [Back to Section Contents](#architecture-components)
- [Android Documentation](https://developer.android.com/training/data-storage/room)

---

**Room** provides an abstraction layer for SQLite and is used for persisting local data. It gives developers compile-time verification of SQL queries, annotations that minimize boilerplate code, and database migration paths. It requires an, **Entity** (Model), **DAO** (Data Access Object/Service), and a **Database** (instance of a Room DB).

---

## WorkManager

- [Back to Section Contents](#architecture-components)
- [Android Documentation](https://developer.android.com/topic/libraries/architecture/workmanager)

---

**WorkManager** is an API for scheduling asynchronous tasks (single execution or repeatable) that will run even when the application is exits or if the device restarts when certain Work Constraints are met.

---

## Lifecycle

- [Back to Section Contents](#architecture-components)
- [Android Documentation](https://developer.android.com/topic/libraries/architecture/lifecycle)

---

**Lifecycle** allows developers to create lifecycle-aware components such as Activities, Fragments, and ViewModels.

---

## ViewModel

- [Back to Section Contents](#architecture-components)
- [Android Documentation](https://developer.android.com/topic/libraries/architecture/viewmodel)

---

**ViewModel** allows developers to store and manage UI-related data with actions scoped to component lifecycles and persists data through configuration changes. It also makes it easy to share data across Fragments and Composables.

---

## LiveData

- [Back to Section Contents](#architecture-components)
- [Android Documentation](https://developer.android.com/topic/libraries/architecture/livedata)

---

**LiveData** is a lifecycle-aware data holder Class that implements the observable pattern which ensures that components observers are only updated when in an active lifecycle state.

---

## Navigation

- [Back to Section Contents](#architecture-components)
- [Android Documentation](https://developer.android.com/guide/navigation)

---

**Navigation** contains a set of tools for implementing application navigation. It requires a **Navigation graph**, **NavHost**, and **NavController** and handles things like fragment transactions, standardized resources, and deep linking and provides a scope for ViewModels.

---

## Paging

- [Back to Section Contents](#architecture-components)
- [Android Documentation](https://developer.android.com/topic/libraries/architecture/paging/v3-overview)

---

**Paging** is a library which eases the loading, caching, and display of pages of information from large datasets from local and remote storage.

---

## Data Binding

- [Back to Section Contents](#architecture-components)
- [Android Documentation](https://developer.android.com/topic/libraries/data-binding)

---

**Data Binding** is a support library for binding UI components in layouts to application data sources in a declarative format.

---

# Behavior Components

- [Back to Top](#jetpack-software-components)
- [Foundation Components](#foundation-components)
- [Architecture Components](#architecture-components)
- [UI Components](#ui-components)

<br>

- [Geeks for Geeks](https://www.geeksforgeeks.org/behaviour-components-of-android-jetpack/)

---

- [DownloadManager](#downloadmanager)
- [Media & Playback](#media--playback)
- [Permissions](#permissions)
- [Notifications](#notifications)
- [Sharing](#sharing)
- [Slices](#slices)

---

**Behavior Components** are libraries that handle user interaction with an application through the UI. They include tools for things like notifications, downloading, permissions, sharing, and the Google assistant.

---

## DownloadManager

- [Back to Section Contents](#behavior-components)
- [Android Documentation](https://developer.android.com/reference/kotlin/android/app/DownloadManager?hl=en)

---

**DownloadManager** is a system service that handles long-running/large HTTP downloads in a background process.

---

## Media & Playback

- [Back to Section Contents](#behavior-components)
- [Android Documentation](https://developer.android.com/guide/topics/media-apps/media-apps-overview)

---

**Media & Playback** represents a set of libraries for playing audio and video with support for backwards-compatibility which include:

**Media3** ([Android Documentation](https://developer.android.com/jetpack/androidx/releases/media3))

**Media2** ([Android Documentation](https://developer.android.com/jetpack/androidx/releases/media2))

**Media** ([Android Documentation](https://developer.android.com/jetpack/androidx/releases/media))

**ExoPlayer** ([ExoPlayer Documentation](https://exoplayer.dev/))

---

## Permissions

- [Back to Section Contents](#behavior-components)
- [Android Documentation](https://developer.android.com/guide/topics/permissions/overview)
- [Declare Permissions](https://developer.android.com/training/permissions/declaring)
- [Request Permissions](https://developer.android.com/training/permissions/requesting)
- [List of Permissions](https://developer.android.com/reference/android/Manifest.permission)

---

**Permissions** are a set of systems used to grant applications permission to access restricted data and actions by either declaring permissions in the Android Manifest or by requesting them at runtime. Types of permissions include:

**Normal Permissions**, *Low Risk* ([Android Documentation](https://developer.android.com/guide/topics/permissions/overview#normal))

**Signature Permissions**, *App Specific* ([Android Documentation](https://developer.android.com/guide/topics/permissions/overview#signature))

**Runtime Permissions**, *High Risk* ([Android Documentation](https://developer.android.com/guide/topics/permissions/overview#runtime))

**Special Permissions**, *Platform/OEM Specific* ([Android Documentation](https://developer.android.com/guide/topics/permissions/overview#special))

---

## Notifications

- [Back to Section Contents](#behavior-components)
- [Android Documentation](https://developer.android.com/guide/topics/ui/notifiers/notifications)

---

**Notifications** libraries provide a way to use push notifications and assign special system actions to notifications like vibrations, sounds, and status bar icons.

---

## Sharing

- [Back to Section Contents](#behavior-components)
- [Simple Data](https://developer.android.com/training/sharing/send)
- [ShareActionProvider](https://developer.android.com/reference/kotlin/androidx/appcompat/widget/ShareActionProvider)

---

**Sharing** provides a way to share data with other applications through Intent.

---

## Slices

- [Back to Section Contents](#behavior-components)
- [Android Documentation](https://developer.android.com/guide/slices)

---

**Slices** are UI templates that can display interactive content from an application inside other applications like Google Search and Google Assistant.

---

# UI Components

- [Back to Top](#jetpack-software-components)
- [Foundation Components](#foundation-components)
- [Architecture Components](#architecture-components)
- [Behavior Components](#behavior-components)

<br>

- [Geeks for Geeks](https://www.geeksforgeeks.org/ui-components-of-android-jetpack/)

---

- [Animation & Transition](#animation--transition)
- [Auto](#auto)
- [Emoji](#emoji)
- [Fragment](#fragment)
- [Layout](#layout)
- [Palette](#palette)
- [TV](#tv)
- [Wear](#wear)

---

**UI Components** are a set of libraries which deal with UI and contain widgets, layouts, animations, palettes, and emojis, as well as support for driving mode, Android TV, and Wear OS.

---

## Animation & Transition

- [Back to Section Contents](#ui-components)

---

---

## Auto

- [Back to Section Contents](#ui-components)

---

---

## Emoji

- [Back to Section Contents](#ui-components)

---

---

## Fragment

- [Back to Section Contents](#ui-components)

---

---

## Layout

- [Back to Section Contents](#ui-components)

---

---

## Palette

- [Back to Section Contents](#ui-components)

---

---

## TV

- [Back to Section Contents](#ui-components)

---

---

## Wear

- [Back to Section Contents](#ui-components)

---