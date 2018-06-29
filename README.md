# Location2
Udacity - practice with getLastLocation from Google's Location Services API

Edit 4 files.

Layout:
Latitude TextView

Longitude TextView

Gradle:
Module build.gradle

Add the latest version:

implementation 'com.google.android.gms:play-services-location:15.0.1'


GMS - google mobiles services


Manifest:

<meta-data android:name="com.google.android.gms.version" android:value="@integer/google_play_services_version"/>

<uses-permission android:name="android.permission.ACCESS_FINE_LOCATION"/>

MainActivity:

import GoogleApiClient

implements OnConnectionFailedListener and ConnectionCallbacks

Override:

onStart

onStop


onConnected

onConnectionFailed

onConnectionSuspended


requestPermission
