## Multiple DataStore Preference using Coroutine Hilt and MVVM
This is a sample project to demonstrate that how can be datastore-preferences used as modularized/separate manner for different features using Dagger Hilt and Coroutines followed MVVM Architecture. 

- [BasePreferenceManager](https://github.com/amirraza/Multiple-Datastore-Preference-with-Coroutine-Hilt-MVVM/blob/master/app/src/main/java/com/example/sharedpref/datasource/local/BasePreferenceManager.kt) is an `abstract class` which will be extended to child classes 

- [AuthPreferenceManager](https://github.com/amirraza/Multiple-Datastore-Preference-with-Coroutine-Hilt-MVVM/blob/master/app/src/main/java/com/example/sharedpref/datasource/local/AuthPreferenceManager.kt), [MainPreferenceManager](https://github.com/amirraza/Multiple-Datastore-Preference-with-Coroutine-Hilt-MVVM/blob/master/app/src/main/java/com/example/sharedpref/datasource/local/MainPreferenceManager.kt) and [SettingsPreferenceManager](https://github.com/amirraza/Multiple-Datastore-Preference-with-Coroutine-Hilt-MVVM/blob/master/app/src/main/java/com/example/sharedpref/datasource/local/SettingsPreferenceManager.kt) are the child classes which contains its own `Preferences db` to handle its implementation
### Demo

<img src="doc/sharedpref_demo.gif" width="240" height="480"/>
