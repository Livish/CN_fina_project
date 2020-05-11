# CN_fina_project

This Android app records four location data providers values onto Google Firebase. It records the starting location and ending location to the database. 

Known Bugs:

Application will crash when run with an emulator, to run the program with an emulator comment out calls to network provider.
  This can be found and edited in MainActivity.java in the function storeLocationData()
  
Left over UI code that indicates Accelerometer, Gyroscope, and Magnetometer data.

To make the app work with Firebase, you need to:

    sign in on Firebase using your Google account: https://firebase.google.com/
    create a new Firebase Project (from the Firebase Console, in your personal page)
    add Firebase to the app, following the steps 1, 2, 3.a of this tutorial: https://firebase.google.com/docs/android/setup
    create a default Storage bucket and set up public access, following the sections "Create a default Storage bucket" and "Set up public access" of this tutorial: https://firebase.google.com/docs/storage/android/start (the root of the Storage bucket has to be a folder called "sensors/")
