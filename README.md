# ionic

Start up: ionic create {name} {blank/tabs/super}
To preview: ionic serve

-- To Deploy --
iOS: 
   Development Build: Use xCode
   Stable Build (Release): Use xCode

Android:
   Development Build: ionic cordova build android --prod
   Stable (Release)(Might need to have it Signed): ionic cordova build android --prod --release

   Export Directory: `platforms\android\app\build\outputs\apk\debug`

-- Sign APK -- (Only if wanna release to Google Play)
   Command: 
	- keytool -genkey -v -keystore my-release-key.jks -keyalg RSA -keysize 2048 -validity 100          00 -alias my-alias


-- Once Exported --
Enjoy your Ionic App!