# Android-Developer-Certification-exam-resources
Repository to share resources which we need to study

Certification site: https://developers.google.com/training/certification/associate-android-developer/

---
# Content

How to collaborate? Just add under every line a resource you want to share i.e.:

* #### 1 An important thing to study
  * My resource with a little explanation and web page
---

#### General resources
  * __Android Developer Fundamentals__
     * Concept reference: [Android Developer Fundamentals Course—Concepts](https://legacy.gitbook.com/book/google-developer-training/android-developer-fundamentals-course-concepts/details)
     * Practical workbook: [Android Developer Fundamentals Course—Practicals](https://legacy.gitbook.com/book/google-developer-training/android-developer-fundamentals-course-practicals/details)
  * __Advanced Android Development__
     * Concept reference: [Advanced Android Development—Concepts](https://legacy.gitbook.com/book/google-developer-training/android-developer-advanced-course-practicals/details)
     * Practical workbook: [Advanced Android Development—Practicals](https://legacy.gitbook.com/book/google-developer-training/android-developer-advanced-course-practicals/details)
  * __More exam resources__
     * An useful repository with more resources for the exam by [Amejia481](https://github.com/Amejia481/Associate-Android-Developer-Certification)
     * Quick and a little bit outdated guide to implement Material Design elements from [MaterialDoc](https://materialdoc.com/)
     * Old but useful guide to see how the exam is from [Medium](https://medium.com/@suyoggunjal/google-certified-android-developer-59af40bae846)

## 1) Testing and debugging

  * #### 1.1- Write and execute local JVM unit tests
      * Fundamentals of testing [Android Developer Docs](https://developer.android.com/training/testing/)
      * Unit testing from [Android docs](https://developer.android.com/training/testing/unit-testing/)
      * Test your Room database from [Android docs](https://developer.android.com/training/data-storage/room/testing-db)
      * Good article about Unit testing from [ProAndroidDev](https://proandroiddev.com/seven-principles-of-great-unit-tests-adapted-for-android-342515f98ef2)
  * #### 1.2- Write and execute Android UI tests
      * Testing Android patterns from [AndroidDevelopers](https://www.youtube.com/watch?v=W8LJjfkTKik&index=1&list=PLWz5rJ2EKKc-6HWg_jyP0U1zrVLHn65b2)
  * #### 1.3- Use the system log to output debug information
  * #### 1.4- Debug and fix issues with an app's functional behavior and usability
      * Debugging tips from [Black Lens](https://blacklenspub.com/5-debugging-tips-with-android-studio-65751011262f)


## 2) User interface (UI) and app functionality

  * #### 2.1- Create an Activity that displays a layout
  * #### 2.2- Construct a UI with ConstraintLayout
      * Build a Responsive UI with ConstraintLayout from [Android docs](https://developer.android.com/training/constraint-layout/)
      * Animation example with ConstraintLayout from [AndroidPub](https://android.jlelse.eu/build-awesome-animations-with-7-lines-of-code-using-constraintlayout-854e8fd3ad93)
  * #### 2.3- Create a custom view class and add it to a layout
      * A good example to customize an EditText from [Google developer training GitHub](https://google-developer-training.github.io/android-developer-advanced-course-practicals/unit-5-advanced-graphics-and-views/lesson-10-custom-views/10-1a-p-using-custom-views/10-1a-p-using-custom-views.html)
  * #### 2.4- Add accessibility hooks to a custom view
      * Build more accessible custom views from [Android docs](https://developer.android.com/guide/topics/ui/accessibility/custom-views)
  * #### 2.5- Apply content descriptions to views for accessibility
  * #### 2.6- Implement a custom app theme
      * The Styles and Themes guide from [Android docs](https://developer.android.com/guide/topics/ui/look-and-feel/themes)
      * Guide to develop custom themes from [codepath](https://guides.codepath.com/android/developing-custom-themes)
  * #### 2.7- Display items in a RecyclerView
  * #### 2.8- Bind local data to a RecyclerView list using the paging library
      * A good article to learn to use the paging library at [ProAndroidDev](https://proandroiddev.com/8-steps-to-implement-paging-library-in-android-d02500f7fffe)
      * Another article to use paging library at[Mindorks](https://medium.com/mindorks/android-recyclerview-pagination-with-paging-library-using-mvvm-rxjava-dagger-2-and-livedata-b0489ecbbfc0)
      * An easy article to understand to learn to use the paging library using Room from [Knowledge Transfer](http://androidkt.com/paging-library/)
  * #### 2.9- Implement menu-based or drawer navigation
      * Create a navigation drawer from [Android docs](https://developer.android.com/training/implementing-navigation/nav-drawer)
      * Create a menu from [Android docs](https://developer.android.com/guide/topics/ui/menus)
  * #### 2.10- Localize the app
      * Localization from [Android docs](https://developer.android.com/guide/topics/resources/localization)
  * #### 2.11- Display notifications, toasts, and snackbar messages
  * #### 2.12- Schedule a background task using JobScheduler
      * Schedule jobs intelligently from [Android docs](https://developer.android.com/topic/performance/scheduling)
      * Good article to Schedule tasks from [Vogella](http://www.vogella.com/tutorials/AndroidTaskScheduling/article.html)
  * #### 2.13- Efficiently run jobs in the background
      * Guide to background processing from [Android docs](https://developer.android.com/guide/background/)
 
 
## 3) App data and files

  * #### 3.1- Define data using Room entities
      * Android Persistence with Room Database [sample](https://github.com/googlecodelabs/android-persistence)
  * #### 3.2- Access Room database with data access object (DAO)
  * #### 3.3- Observe and respond to changing data using LiveData
      * LiveData overview from [Android docs](https://developer.android.com/topic/libraries/architecture/livedata)
      * Good article to learn LiveData at [jensklingenberg](http://jensklingenberg.de/learn-how-to-use-livedata/)
      * Well explained article to differentiate patterns and antipatterns using LiveData and ViewModel at [Android Developers](https://medium.com/androiddevelopers/viewmodels-and-livedata-patterns-antipatterns-21efaef74a54)
      * Great article to point out AAC pitfalls at [Medium](https://medium.com/@BladeCoder/architecture-components-pitfalls-part-1-9300dd969808)
  * #### 3.4- Use a Repository to handle data operations
      * Guide to understand better AAC from [Android docs](https://developer.android.com/jetpack/docs/guide#connect-viewmodel-repository)
      * Awesome video tutorial to learn Room, ViewModel, LiveData, Dagger 2 and MVVM Architecture from [wiseAss](https://www.youtube.com/watch?reload=9&v=LCOKWgHdBvE)
  * #### 3.5- Read and parse raw resources or asset files
      * How to add Assets, Files, and Data Parsing from [CommonsWare](https://commonsware.com/Android/previews/assets-files-and-data-parsing)
      * Tutorial which explains how to use Assets from [MobileDevHub](http://mobiledevhub.com/2017/10/25/android-fundamentals-what-are-assets-and-how-to-use-them/)
      * GitHub repo which shows how to use Assets from [GitHub](https://github.com/tuttelikz/ReadCsvExample_Android)
  * #### 3.6- Create persistent preference data from user input
      * How to save key-value data from [Android docs](https://developer.android.com/training/data-storage/shared-preferences)
  * #### 3.7- Change the behavior of the app based on user preferences
      * How to add settings from [Android docs](https://developer.android.com/guide/topics/ui/settings)
