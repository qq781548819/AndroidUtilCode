## Android developers should collect the following utils
**[中文版README][readme-cn.md]→[How to get this README from README-CN][trans]**
***
Directory is shown below：  
> - **About Activity→[ActivityUtils.java][activity.java]**
 ```
isActivityExists
launchActivity
 ```

> - **About App→[AppUtils.java][app.java]**
 ```
isInstallApp
installApp
installAppSilent
uninstallApp
uninstallAppSilent
isAppRoot
launchApp
closeApp
getAppPackageName
getAppDetailsSettings
getAppName
getAppIcon
getAppPath
getAppVersionName
getAppVersionCode
isSystemApp
isAppDebug
getAppSignature
getAppSignatureSHA1
isAppForeground
getForegroundApp
getAppInfo
getAppsInfo
cleanAppData
 ```

> - **About Bar→[BarUtils.java][bar.java]**
 ```
setTransparentStatusBar
hideStatusBar
getStatusBarHeight
isStatusBarExists
getActionBarHeight
showNotificationBar
hideNotificationBar
 ```

> - **About Clean→[CleanUtils.java][clean.java]**
 ```
cleanInternalCache
cleanInternalFiles
cleanInternalDbs
cleanInternalDbByName
cleanInternalSP
cleanExternalCache
cleanCustomCache
 ```

> - **About Clipboard→[ClipboardUtils.java][clipboard.java]**
 ```
copyText
getText
copyUri
getUri
copyIntent
getIntent
 ```

> - **About Close→[CloseUtils.java][close.java]**
 ```
closeIO
closeIOQuietly
 ```

> - **About Const→[ConstUtils.java][const.java]**
 ```
MemoryConst
TimeConst
RegexConst
 ```

> - **About Convert→[ConvertUtils.java][convert.java]→[Test][convert.test]**
 ```
bytes2HexString, hexString2Bytes
chars2Bytes, bytes2Chars
byte2Size, size2Byte
byte2FitSize
bytes2Bits, bits2Bytes
input2OutputStream, output2InputStream
inputStream2Bytes, bytes2InputStream
outputStream2Bytes, bytes2OutputStream
inputStream2String, string2InputStream
outputStream2String, string2OutputStream
bitmap2Bytes, bytes2Bitmap
drawable2Bitmap, bitmap2Drawable
drawable2Bytes, bytes2Drawable
view2Bitmap
dp2px, px2dp
sp2px, px2sp
 ```

> - **About Crash→[CrashUtils.java][crash.java]**
 ```
getInstance
init
 ```

> - **About Device→[DeviceUtils.java][device.java]**
 ```
isDeviceRoot
getSDKVersion
getAndroidID
getMacAddress
getManufacturer
getModel
shutdown
reboot
 ```

> - **About Empty→[EmptyUtils.java][empty.java]→[Test][empty.test]**
 ```
isEmpty
isNotEmpty
 ```

> - **About Encode→[EncodeUtils.java][encode.java]→[Test][encode.test]**
 ```
urlEncode
urlDecode
base64Encode, base64Encode2String
base64Decode
base64UrlSafeEncode
htmlEncode
htmlDecode
 ```

> - **About Encrypt→[EncryptUtils.java][encrypt.java]→[Test][encrypt.test]**
 ```
encryptMD2, encryptMD2ToString
encryptMD5, encryptMD5ToString
encryptMD5File, encryptMD5File2String
encryptSHA1, encryptSHA1ToString
encryptSHA224, encryptSHA224ToString
encryptSHA256, encryptSHA256ToString
encryptSHA384, encryptSHA384ToString
encryptSHA512, encryptSHA512ToString
encryptHmacMD5, encryptHmacMD5ToString
encryptHmacSHA1, encryptHmacSHA1ToString
encryptHmacSHA224, encryptHmacSHA224ToString
encryptHmacSHA256, encryptHmacSHA256ToString
encryptHmacSHA384, encryptHmacSHA384ToString
encryptHmacSHA512, encryptHmacSHA512ToString
encryptDES, encryptDES2HexString, encryptDES2Base64
decryptDES, decryptHexStringDES, decryptBase64DES
encrypt3DES, encrypt3DES2HexString, encrypt3DES2Base64
decrypt3DES, decryptHexString3DES, decryptBase64_3DES
encryptAES, encryptAES2HexString, encryptAES2Base64
decryptAES, decryptHexStringAES, decryptBase64AES
 ```

> - **About File→[FileUtils.java][file.java]→[Test][file.test]**
 ```
getFileByPath
isFileExists
rename
isDir
isFile
createOrExistsDir
createOrExistsFile
createFileByDeleteOldFile
copyDir
copyFile
moveDir
moveFile
deleteDir
deleteFile
listFilesInDir
listFilesInDir
listFilesInDirWithFilter
listFilesInDirWithFilter
listFilesInDirWithFilter
listFilesInDirWithFilter
searchFileInDir
writeFileFromIS
writeFileFromString
getFileCharsetSimple
getFileLines
readFile2List
readFile2SB
getFileSize
getFileMD5, getFileMD5ToString
getDirName
getFileName
getFileNameNoExtension
getFileExtension
 ```

> - **About Image→[ImageUtils.java][image.java]**
 ```
bitmap2Bytes, bytes2Bitmap
drawable2Bitmap, bitmap2Drawable
drawable2Bytes, bytes2Drawable
getBitmap
scale
clip
skew
rotate
getRotateDegree
toRound
toRoundCorner
fastBlur
renderScriptBlur
stackBlur
addFrame
addReflection
addTextWatermark
addImageWatermark
toAlpha
toGray
save
isImage
getImageType
compressByScale
compressByQuality
compressBySampleSize
 ```

> - **About Intent→[IntentUtils.java][intent.java]**
 ```
getInstallAppIntent
getUninstallAppIntent
getLaunchAppIntent
getAppDetailsSettingsIntent
getShareTextIntent
getShareImageIntent
getComponentIntent
getShutdownIntent
getCaptureIntent
 ```

> - **About Keyboard→[KeyboardUtils.java][keyboard.java]**
 ```
hideSoftInput
clickBlankArea2HideSoftInput
showSoftInput
toggleSoftInput
 ```

> - **About Log→[LogUtils.java][log.java]→[Test][log.test]**
 ```
init
getBuilder
v
d
i
w
e
 ```

> - **About Network→[NetworkUtils.java][network.java]**
 ```
openWirelessSettings
isConnected
isAvailableByPing
getDataEnabled
setDataEnabled
is4G
getWifiEnabled
setWifiEnabled
isWifiConnected
isWifiAvailable
getNetworkOperatorName
getNetworkType, getNetworkTypeName
getIPAddress
getDomainAddress
 ```

> - **About Phone→[PhoneUtils.java][phone.java]**
 ```
isPhone
getIMEI
getIMSI
getPhoneType
getSimOperatorName, getSimOperatorByMnc
getPhoneStatus
dial
call
sendSms
sendSmsSilent
getAllContactInfo
getContactNum
getAllSMS
 ```

> - **About Process→[ProcessUtils.java][process.java]**
 ```
getForegroundProcessName
cleanAllBackgroundProcesses，cleanBackgroundProcesses
 ```

> - **About Regex→[RegexUtils.java][regex.java]→[Test][regex.test]**
 ```
isMobileSimple
isMobileExact
isTel
isIDCard15
isIDCard18
isEmail
isURL
isChz
isUsername
isDate
isIP
isMatch
 ```

> - **About Screen→[ScreenUtils.java][screen.java]**
 ```
getDeviceWidth, getDeviceHeight
setTransparentStatusBar
hideStatusBar
getStatusBarHeight
isStatusBarExists
getActionBarHeight
showNotificationBar
hideNotificationBar
setLandscape
snapShotWithStatusBar, snapShotWithoutStatusBar
isScreenLock
 ```

> - **About SDCard→[SDCardUtils.java][sdcard.java]**
 ```
isSDCardEnable
getSDCardPath
getDataPath
getFreeSpace
getSDCardInfo
 ```

> - **About Service→[ServiceUtils.java][service.java]**
 ```
isServiceRunning
stopService
 ```

> - **About Shell→[ShellUtils.java][shell.java]**
 ```
execCmd
 ```

> - **About Size→[SizeUtils.java][size.java]**
 ```
dp2px, px2dp
sp2px, px2sp
applyDimension
forceGetViewSize
measureView
 ```

> - **About Snackbar→[SnackbarUtils.java][snackbar.java]→[Demo][snackbar.demo]**
 ```
showShortSnackbar
showLongSnackbar
showIndefiniteSnackbar
addView
dismissSnackbar
 ```

> - **About SP→[SPUtils.java][sp.java]→[Test][sp.test]**
 ```
SPUtils
putString
getString
putInt
getInt
putLong
getLong
putFloat
getFloat
putBoolean
getBoolean
getAll
remove
contains
clear
 ```

> - **About String→[StringUtils.java][string.java]→[Test][string.test]**
 ```
isEmpty
isSpace
equals
null2Length0
length
upperFirstLetter
lowerFirstLetter
reverse
toDBC
toSBC
getPYFirstLetter
cn2PY
 ```

> - **About ThreadPool→[ThreadPoolUtils.java][thread_pool.java]**
 ```
ThreadPoolUtils
execute
execute
shutDown
shutDownNow
isShutDown
isTerminated
awaitTermination
submit
submit
invokeAll, invokeAny
schedule
schedule
scheduleWithFixedRate, scheduleWithFixedDelay
 ```

> - **About Time→[TimeUtils.java][time.java]→[Test][time.test]**
 ```
milliseconds2String
string2Milliseconds
string2Date
date2String
date2Milliseconds
milliseconds2Date
milliseconds2Unit
getIntervalTime
getCurTimeMills, getCurTimeString, getCurTimeDate
getIntervalByNow
isLeapYear
getWeek, getWeekIndex
getWeekOfMonth
getWeekOfYear
 ```

> - **About Toast→[ToastUtils.java][toast.java]**
 ```
init
showShortToastSafe
showLongToastSafe
showShortToast
showLongToast
cancelToast
 ```

> - **About Zip→[ZipUtils.java][zip.java]→[Test][zip.test]**
 ```
zipFiles
zipFile
unzipFiles
unzipFile
unzipFileByKeyword
getFilesPath
getComments
getEntries
 ```

> - **更新Log→[update_log.md][update_log.md]**

***

**I'm so sorry for that the code is annotated with Chinese.**

### Download
***
Gradle:
``` groovy
compile 'com.blankj:utilcode:1.3.3'
```

### Proguard
***
```
-keep class com.blankj.utilcode.** { *; }
-keep classmembers class com.blankj.utilcode.** { *; }
-dontwarn com.blankj.utilcode.**
```

### License
***
```
Copyright 2016 Blankj

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

	http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```

[update_log.md]: https://github.com/Blankj/AndroidUtilCode/blob/master/update_log.md

[readme.md]: https://github.com/Blankj/AndroidUtilCode
[readme-cn.md]: https://github.com/Blankj/AndroidUtilCode/blob/master/README-CN.md

[trans]: https://github.com/Blankj/AndroidUtilCode/blob/master/utilcode/src/test/java/com/blankj/utilcode/utils/TestUtils.java

[activity.java]: https://github.com/Blankj/AndroidUtilCode/blob/master/utilcode/src/main/java/com/blankj/utilcode/utils/ActivityUtils.java

[app.java]: https://github.com/Blankj/AndroidUtilCode/blob/master/utilcode/src/main/java/com/blankj/utilcode/utils/AppUtils.java

[bar.java]: https://github.com/Blankj/AndroidUtilCode/blob/master/utilcode/src/main/java/com/blankj/utilcode/utils/BarUtils.java

[clean.java]: https://github.com/Blankj/AndroidUtilCode/blob/master/utilcode/src/main/java/com/blankj/utilcode/utils/CleanUtils.java

[clipboard.java]: https://github.com/Blankj/AndroidUtilCode/blob/master/utilcode/src/main/java/com/blankj/utilcode/utils/ClipboardUtils.java

[close.java]: https://github.com/Blankj/AndroidUtilCode/blob/master/utilcode/src/main/java/com/blankj/utilcode/utils/CloseUtils.java

[const.java]: https://github.com/Blankj/AndroidUtilCode/blob/master/utilcode/src/main/java/com/blankj/utilcode/utils/ConstUtils.java

[convert.java]: https://github.com/Blankj/AndroidUtilCode/blob/master/utilcode/src/main/java/com/blankj/utilcode/utils/ConvertUtils.java
[convert.test]: https://github.com/Blankj/AndroidUtilCode/blob/master/utilcode/src/test/java/com/blankj/utilcode/utils/ConvertUtilsTest.java

[crash.java]: https://github.com/Blankj/AndroidUtilCode/blob/master/utilcode/src/main/java/com/blankj/utilcode/utils/CrashUtils.java

[device.java]: https://github.com/Blankj/AndroidUtilCode/blob/master/utilcode/src/main/java/com/blankj/utilcode/utils/DeviceUtils.java

[empty.java]: https://github.com/Blankj/AndroidUtilCode/blob/master/utilcode/src/main/java/com/blankj/utilcode/utils/EmptyUtils.java
[empty.test]: https://github.com/Blankj/AndroidUtilCode/blob/master/utilcode/src/test/java/com/blankj/utilcode/utils/EmptyUtilsTest.java

[encode.java]: https://github.com/Blankj/AndroidUtilCode/blob/master/utilcode/src/main/java/com/blankj/utilcode/utils/EncodeUtils.java
[encode.test]: https://github.com/Blankj/AndroidUtilCode/blob/master/utilcode/src/test/java/com/blankj/utilcode/utils/EncodeUtilsTest.java

[encrypt.java]: https://github.com/Blankj/AndroidUtilCode/blob/master/utilcode/src/main/java/com/blankj/utilcode/utils/EncryptUtils.java
[encrypt.test]: https://github.com/Blankj/AndroidUtilCode/blob/master/utilcode/src/test/java/com/blankj/utilcode/utils/EncryptUtilsTest.java

[file.java]: https://github.com/Blankj/AndroidUtilCode/blob/master/utilcode/src/main/java/com/blankj/utilcode/utils/FileUtils.java
[file.test]: https://github.com/Blankj/AndroidUtilCode/blob/master/utilcode/src/test/java/com/blankj/utilcode/utils/FileUtilsTest.java

[image.java]: https://github.com/Blankj/AndroidUtilCode/blob/master/utilcode/src/main/java/com/blankj/utilcode/utils/ImageUtils.java

[intent.java]: https://github.com/Blankj/AndroidUtilCode/blob/master/utilcode/src/main/java/com/blankj/utilcode/utils/IntentUtils.java

[keyboard.java]: https://github.com/Blankj/AndroidUtilCode/blob/master/utilcode/src/main/java/com/blankj/utilcode/utils/KeyboardUtils.java

[log.java]: https://github.com/Blankj/AndroidUtilCode/blob/master/utilcode/src/main/java/com/blankj/utilcode/utils/LogUtils.java
[log.test]: https://github.com/Blankj/AndroidUtilCode/blob/master/utilcode/src/test/java/com/blankj/utilcode/utils/LogUtilsTest.java

[network.java]: https://github.com/Blankj/AndroidUtilCode/blob/master/utilcode/src/main/java/com/blankj/utilcode/utils/NetworkUtils.java

[phone.java]: https://github.com/Blankj/AndroidUtilCode/blob/master/utilcode/src/main/java/com/blankj/utilcode/utils/PhoneUtils.java

[process.java]: https://github.com/Blankj/AndroidUtilCode/blob/master/utilcode/src/main/java/com/blankj/utilcode/utils/ProcessUtils.java

[regex.java]: https://github.com/Blankj/AndroidUtilCode/blob/master/utilcode/src/main/java/com/blankj/utilcode/utils/RegexUtils.java
[regex.test]: https://github.com/Blankj/AndroidUtilCode/blob/master/utilcode/src/test/java/com/blankj/utilcode/utils/RegexUtilsTest.java

[screen.java]: https://github.com/Blankj/AndroidUtilCode/blob/master/utilcode/src/main/java/com/blankj/utilcode/utils/ScreenUtils.java

[sdcard.java]: https://github.com/Blankj/AndroidUtilCode/blob/master/utilcode/src/main/java/com/blankj/utilcode/utils/SDCardUtils.java

[service.java]: https://github.com/Blankj/AndroidUtilCode/blob/master/utilcode/src/main/java/com/blankj/utilcode/utils/ServiceUtils.java

[shell.java]: https://github.com/Blankj/AndroidUtilCode/blob/master/utilcode/src/main/java/com/blankj/utilcode/utils/ShellUtils.java

[size.java]: https://github.com/Blankj/AndroidUtilCode/blob/master/utilcode/src/main/java/com/blankj/utilcode/utils/SizeUtils.java

[snackbar.java]: https://github.com/Blankj/AndroidUtilCode/blob/master/utilcode/src/main/java/com/blankj/utilcode/utils/SnackbarUtils.java
[snackbar.demo]: https://github.com/Blankj/AndroidUtilCode/blob/master/app/src/main/java/com/blankj/androidutilcode/activities/SnackbarActivity.java

[sp.java]: https://github.com/Blankj/AndroidUtilCode/blob/master/utilcode/src/main/java/com/blankj/utilcode/utils/SPUtils.java
[sp.test]: https://github.com/Blankj/AndroidUtilCode/blob/master/utilcode/src/test/java/com/blankj/utilcode/utils/SPUtilsTest.java

[string.java]: https://github.com/Blankj/AndroidUtilCode/blob/master/utilcode/src/main/java/com/blankj/utilcode/utils/StringUtils.java
[string.test]: https://github.com/Blankj/AndroidUtilCode/blob/master/utilcode/src/test/java/com/blankj/utilcode/utils/StringUtilsTest.java

[thread_pool.java]: https://github.com/Blankj/AndroidUtilCode/blob/master/utilcode/src/main/java/com/blankj/utilcode/utils/ThreadPoolUtils.java

[time.java]: https://github.com/Blankj/AndroidUtilCode/blob/master/utilcode/src/main/java/com/blankj/utilcode/utils/TimeUtils.java
[time.test]: https://github.com/Blankj/AndroidUtilCode/blob/master/utilcode/src/test/java/com/blankj/utilcode/utils/TimeUtilsTest.java

[toast.java]: https://github.com/Blankj/AndroidUtilCode/blob/master/utilcode/src/main/java/com/blankj/utilcode/utils/ToastUtils.java

[zip.java]: https://github.com/Blankj/AndroidUtilCode/blob/master/utilcode/src/main/java/com/blankj/utilcode/utils/ZipUtils.java
[zip.test]: https://github.com/Blankj/AndroidUtilCode/blob/master/utilcode/src/test/java/com/blankj/utilcode/utils/ZipUtilsTest.java

[weibo]: http://weibo.com/blankcmj
