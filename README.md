# Android
## Official
### https://developer.android.com/studio/index.html
## Courses
### https://codelabs.developers.google.com/codelabs/while-in-use-location/index.html?index=..%2F..index#0
## IDE
### Android Studio
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
addOnSuccessListener + addOnFailureListener => addOnCompletedListener check Task.Result 
```
