# Android
## Official
### https://developer.android.com/studio/index.html
### https://developer.android.com/courses
### https://developers.google.com/certification/associate-android-developer
### https://developer.android.com/jetpack/compose
### https://developer.android.com/jetpack/compose/setup
### https://developer.android.com/jetpack/compose/tutorial
## Downloads
### https://developer.android.com/studio/preview
## Prerequisites
### https://www.codecademy.com/learn/learn-kotlin/
### https://www.codecademy.com/learn/learn-java
## Paths
### https://app.pluralsight.com/paths/skills/android-development-with-kotlin-fundamentals 17h
### https://app.pluralsight.com/paths/skill/android-development-with-kotlin-fundamentals 17h
### https://app.pluralsight.com/paths/skill/google-android-associate-developer-aad 27h
### https://www.pluralsight.com/paths/google-android-associate-developer-aad
### https://app.pluralsight.com/paths/skills/google-android-associate-developer-aad
### https://www.bitdegree.org/learning-path/android-dev $78K
### https://www.linkedin.com/learning/paths/become-an-android-mobile-app-developer
### https://www.codecademy.com/learn/paths/introduction-to-android-with-java
## Assessments
### https://app.pluralsight.com/score/skill-assessment/android-security
## Labs
### https://developer.android.com/courses/kotlin-android-fundamentals
### https://codelabs.developers.google.com/codelabs/jetpack-compose-basics/#0
### https://codelabs.developers.google.com/kotlin-bootcamp/
### https://codelabs.developers.google.com/android-kotlin-fundamentals/
### https://codelabs.developers.google.com/advanced-android-kotlin-training/
### https://codelabs.developers.google.com/codelabs/advanced-android-kotlin-training-welcome
### https://codelabs.developers.google.com/codelabs/advanced-android-kotlin-training-notifications
### https://codelabs.developers.google.com/codelabs/android-hilt
### https://codelabs.developers.google.com/codelabs/android-dagger-to-hilt
### https://codelabs.developers.google.com/codelabs/android-dagger
### https://codelabs.developers.google.com/codelabs/android-performance-tuner-unity/index.html?index=..%2F..index
### https://codelabs.developers.google.com/codelabs/build-your-first-android-app-kotlin
## Courses
### https://app.pluralsight.com/library/courses/android-application-basics-understanding/table-of-contents 4h15m
### https://www.udacity.com/course/developing-android-apps-with-kotlin--ud9012 80h
### https://www.udacity.com/course/advanced-android-with-kotlin--ud940 17h
### https://developer.android.com/courses/kotlin-android-fundamentals/overview
### https://developer.android.com/courses/kotlin-android-fundamentals/toc
### https://alison.com/courses/create-android-apps-using-firestore/content
### https://app.pluralsight.com/library/courses/rxandroid-kotlin-reactive-programming/table-of-contents
### https://codelabs.developers.google.com/codelabs/while-in-use-location/index.html?index=..%2F..index#0
### https://app.pluralsight.com/library/courses/android-working-exoplayer/table-of-contents
### https://app.pluralsight.com/library/courses/android-drawables-images/table-of-contents
## Best Practices
### SSL https://developer.android.com/topic/security/best-practices
### Dependency Injection DI https://developer.android.com/training/dependency-injection/hilt-android
## Links
### https://blog.mindorks.com/using-jetpack-compose-to-build-ui-in-android
### https://www.raywenderlich.com/7032631-jetpack-compose-tutorial-for-android-getting-started
### https://medium.com/better-programming/jetpack-compose-a-new-and-simple-way-to-create-material-ui-in-android-f49c6fcb448b
### https://medium.com/mindorks/a-roadmap-to-become-a-better-android-developer-3038cf7f8c8d
### https://learntocodewith.me/posts/android-developer/
### https://generalassemb.ly/blog/7-essential-skills-you-need-to-be-an-android-developer/
## IDE
### Android Studio
#### Darcula, Dark, Black theme | Light, White theme
#### Settings
##### Add Unambiguous Imports on the fly
##### Optimized Imports on the fly
#### Pluggin
##### Markdown
### IntelliJ
#### Android SDK
#### Pluggin Android
## Tips
### File/Invalidate and restart 
### Cat log, setting android version
### build.gradle
#### dependencies 
```
dependencies {
  // Face features
  implementation 'com.google.mlkit:face-detection:16.0.0'

  // Text features
  implementation 'com.google.android.gms:play-services-mlkit-text-recognition:16.0.0'
}
```
#### repositories
```
{
  jcenter()
  google()
}
```
## Notes
```
Compose UI default stack overlay
App foreground -> toast, background -> notification
RxJava, RxKotlin, RxAndroid
addOnSuccessListener + addOnFailureListener => addOnCompletedListener check Task.Result 

```
## Steps
### Wireframing
Split screens, flows to each screen
### Theme colors
```
primary
primary dark
accent
```
## Mapping
|   |Compose   |HTML   |   |   |
|---|---|---|---|---|
|   |Text("text")   |`<span>text</span>`   |   |   |
|   |Column   |Column   |   |   |
|   |Row   |Row   |   |   |
|   |Modifiers   |`<tag modifier="modifier">`   |   |   |
|   |```image = imageResource(R.id.image); Image(image)```   |`<img src="src">`   |   |   |
|   |`Spacer()`   |`<div data-hold="maximum as posible"/>`   |   |   |
