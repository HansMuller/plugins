## 0.0.5

* Require the use of `support-v4` library on Android. This is an API change in
  that plugin users will need their activity class to be an instance of
  `android.support.v4.app.FragmentActivity`. Flutter framework provides such
  an activity out of the box: `io.flutter.app.FlutterFragmentActivity`
* Ignore "Broken pipe" errors affecting iOS simulator
* Update to non-deprecated `application:openURL:options:` on iOS

## 0.0.4

* Prevent race conditions when GoogleSignIn methods are called concurrently (#94)

## 0.0.3

* Fix signOut and disconnect (they were silently ignored)
* Fix test (#10050)

## 0.0.2

* Don't try to sign in again if user is already signed in

## 0.0.1

* Initial Release
