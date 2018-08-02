# Android-Splash-Screen
Android Splash Screen with user location

# AndroidManifest 

user Permission in AndroidManifest

    <uses-permission android:name="android.permission.INTERNET" />
    <uses-permission android:name="android.permission.ACCESS_FINE_LOCATION" />
    <uses-permission android:name="android.permission.ACCESS_COARSE_LOCATION" />
    
        
SplashScreenActivity in AndroidManifest

         <activity android:name=".SplashScreenActivity">
            <intent-filter>
                <action android:name="android.intent.action.MAIN" />

                <category android:name="android.intent.category.LAUNCHER" />
            </intent-filter>
        </activity>
        
        
        Build .gradle Mubule App
      Add Line :   compile  'com.google.android.gms:play-services:11.8.0'
