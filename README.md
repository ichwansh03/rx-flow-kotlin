# RxJava and Coroutine Flow
(on-develop)

## Purpose

This repository contains the code for RxJava and Coroutines Flow with best practice.

## Getting Started

### Prerequisites

Make sure your Android device has API level 24 or higher.

### Clone Project

To get started with the project, clone it using the following command:

```
git clone "https://github.com/ichwansh03/rx-flow-kotlin.git"
```

## Libraries Used

The following libraries are used in the project:
* [AndroidX Core-KTX](https://developer.android.com/kotlin/ktx) - AndroidX Core library with Kotlin extensions for writing concise, idiomatic Kotlin code.
* [AndroidX AppCompat](https://developer.android.com/jetpack/androidx/releases/appcompat) - AndroidX AppCompat library for providing backward compatibility for newer Android features on older devices.
* [Google Material Components](https://material.io/develop/android) - Material Design components by Google for creating a visually appealing and consistent user interface.
* [ConstraintLayout](https://developer.android.com/training/constraint-layout) - Android's ConstraintLayout for creating flexible and responsive layouts.
* [AndroidX Lifecycle](https://developer.android.com/jetpack/androidx/releases/lifecycle) - AndroidX Lifecycle components for handling lifecycle-aware data in the ViewModel.
* [AndroidX Legacy Support](https://developer.android.com/jetpack/androidx/releases/legacy) - AndroidX Legacy Support library to support older Android features.
* [Lifecycle](https://developer.android.com/jetpack/androidx/releases/lifecycle) - Lifecycle-aware components perform actions in response to a change in the lifecycle status of another component, such as activities and fragments.
* [OkHttp](https://square.github.io/okhttp/) - OkHttp perseveres when the network is troublesome: it will silently recover from common connection problems.
* [Retrofit](https://square.github.io/retrofit/) - Retrofit is the class through which your API interfaces are turned into callable objects.
* [Coroutine](https://developer.android.com/kotlin/coroutines) - A coroutine is a concurrency design pattern that you can use on Android to simplify code that executes asynchronously.
* [RxJava3](https://github.com/ReactiveX/RxJava) - RxJava is a Java VM implementation of Reactive Extensions: a library for composing asynchronous and event-based programs by using observable sequences.
* [Glide](https://github.com/bumptech/glide) - Glide is a fast and efficient open source media management and image loading framework for Android that wraps media decoding, memory and disk caching, and resource pooling into a simple and easy to use interface.

## Project Architecture and Techniques

The Project follows the MVVM (Model-View-ViewModel) architectural pattern to clearly separate concerns. The ViewModel serves as a bridge between the UI (View) and the data (Model). Data operations are handled using a Repository pattern, which abstracts the data source from the ViewModel. Dependency Injection is implemented using Koin, allowing for easy management of dependencies and enabling better testability of classes. View Binding is used to bind UI components in layout files, providing type-safe access to these components. Coroutines Flow and State Flow are employed to handle asynchronous operations and data streams efficiently. This approach simplifies handling background tasks and data updates while providing a more reactive and responsive user experience.


---
Feel free to reach out if you have any questions or need further assistance with the project! Happy coding! 🚀
