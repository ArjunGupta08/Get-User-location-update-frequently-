# Here we can get user location in a defined time interval.

## Use Case -
 - We can get current/updated location in a fixed time interval.
 - Using this We can track user location.

# Here we will be used FusedLocationProviderClient to Get User's Last Location

## Project SetUp -
    implementation ("com.google.android.gms:play-services-location:21.1.0")

## Manifest Permission -
    <uses-permission android:name="android.permission.ACCESS_FINE_LOCATION"/>


## Step 1 -
   - Initialise FusedLocationProviderClient

## Step 2 -
   - Show a dialog to ask location permission.

## Step 3 -
   - Create a task to get last location using FusedLocationProviderClient
