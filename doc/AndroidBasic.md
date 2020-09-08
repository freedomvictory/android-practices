# Android  basic programming using kotlin 



## Print message 


1. write message to logcat 

    ```kotlin
    Log.i("info", "our message here")
    ```

2. write message to user's screen

    ```kotlin
    Toast.makeText(this, "ourmessage")
    ```

   
## Andriod activity instrucion 

1. andriod activity lifecycle 

![lifecycle picture looks ](https://koenig-media.raywenderlich.com/uploads/2015/09/activity_lifecycle_pyramid.png)

- `onCreate()` 
- `onStart()`
- `onResume()`

    when app status changed, that is  `background -> foreground` , this function will be called.


- `onPause()`

    when app status changed, that is  `foreground -> background` , this function will be called.

- `onStop()`

    This method is called right after `onPause`.  When the activity is no longer visible to the user , and it's a good place ts save data that you want to commit to the disk.

- `onRestart()`

- `onDestroy()`    

    This is the final callback you'll receive from the OS before the activity is destroyed.

[CLick it, Refer ](https://www.raywenderlich.com/2705552-introduction-to-android-activities-with-kotlin/)

## Andriod studio project files instruction 


