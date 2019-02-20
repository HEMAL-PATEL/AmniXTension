[amnixutils](../../index.md) / [com.amnix.utils.extensions](../index.md) / [android.content.Context](./index.md)

### Extensions for android.content.Context

| Name | Summary |
|---|---|
| [checkSelfPermissions](check-self-permissions.md) | `fun Context.checkSelfPermissions(vararg permissions: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>check for the Permission Easily. call [checkSelfPermissions](check-self-permissions.md) with the permissions and we will tell you if you are permitted or not. |
| [getAccessibilityManager](get-accessibility-manager.md) | `fun Context.getAccessibilityManager(): AccessibilityManager`<br>get Accessiblity Manager |
| [getAccountManager](get-account-manager.md) | `fun Context.getAccountManager(): AccountManager`<br>get Account Manager |
| [getActivityManager](get-activity-manager.md) | `fun Context.getActivityManager(): ActivityManager`<br>get Activity Manager |
| [getAlarmManager](get-alarm-manager.md) | `fun Context.getAlarmManager(): AlarmManager`<br>get Alaram Manager |
| [getAllAudios](get-all-audios.md) | `fun Context.getAllAudios(sortBy: `[`ContentColumns`](../../com.amnix.utils.enums/-content-columns/index.md)` = ContentColumns.DATE_ADDED, order: `[`ContentOrder`](../../com.amnix.utils.enums/-content-order/index.md)` = ContentOrder.DESCENDING): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>`<br>Want All the Audios from the User Phone? |
| [getAllImages](get-all-images.md) | `fun Context.getAllImages(sortBy: `[`ContentColumns`](../../com.amnix.utils.enums/-content-columns/index.md)` = ContentColumns.DATE_ADDED, order: `[`ContentOrder`](../../com.amnix.utils.enums/-content-order/index.md)` = ContentOrder.DESCENDING): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>`<br>Want All the Images from the User Phone? |
| [getAllVideos](get-all-videos.md) | `fun Context.getAllVideos(sortBy: `[`ContentColumns`](../../com.amnix.utils.enums/-content-columns/index.md)` = ContentColumns.DATE_ADDED, order: `[`ContentOrder`](../../com.amnix.utils.enums/-content-order/index.md)` = ContentOrder.DESCENDING): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>`<br>Want All the Videos from the User Phone? |
| [getAndroidID](get-android-i-d.md) | `fun Context.getAndroidID(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>get Android ID |
| [getAudioManager](get-audio-manager.md) | `fun Context.getAudioManager(): AudioManager`<br>get Audio Manager |
| [getBluetoothManager](get-bluetooth-manager.md) | `fun Context.getBluetoothManager(): BluetoothManager`<br>get BlueTooth Manager |
| [getClipboardManager](get-clipboard-manager.md) | `fun Context.getClipboardManager(): ClipboardManager`<br>get ClipBoard Manager |
| [getConnectivityManager](get-connectivity-manager.md) | `fun Context.getConnectivityManager(): ConnectivityManager`<br>get Connectivity Manager |
| [getDeviceID](get-device-i-d.md) | `fun Context.getDeviceID(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>get Device ID a.k.a Android ID |
| [getDevicePolicyManager](get-device-policy-manager.md) | `fun Context.getDevicePolicyManager(): DevicePolicyManager`<br>get Device Policy manager |
| [getDisplayManager](get-display-manager.md) | `fun Context.getDisplayManager(): DisplayManager`<br>get Display manager |
| [getDownloadManager](get-download-manager.md) | `fun Context.getDownloadManager(): DownloadManager`<br>get Download Manager |
| [getDropBoxManager](get-drop-box-manager.md) | `fun Context.getDropBoxManager(): DropBoxManager`<br>get DropBox Manager |
| [getIMEI](get-i-m-e-i.md) | `fun Context.getIMEI(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>get Device IMEI |
| [getInputManager](get-input-manager.md) | `fun Context.getInputManager(): InputManager`<br>get Input Manager |
| [getInputMethodManager](get-input-method-manager.md) | `fun Context.getInputMethodManager(): InputMethodManager`<br>get InputMethod Manager |
| [getKeyguardManager](get-keyguard-manager.md) | `fun Context.getKeyguardManager(): KeyguardManager`<br>get KeyGuard Manager |
| [getLayoutInflater](get-layout-inflater.md) | `fun Context.getLayoutInflater(): LayoutInflater`<br>get Layout Inflater Service |
| [getLocationManager](get-location-manager.md) | `fun Context.getLocationManager(): LocationManager`<br>get Location manager |
| [getMediaRouter](get-media-router.md) | `fun Context.getMediaRouter(): MediaRouter`<br>get Media Router |
| [getNfcManager](get-nfc-manager.md) | `fun Context.getNfcManager(): NfcManager`<br>get NFC manager |
| [getNotificationManager](get-notification-manager.md) | `fun Context.getNotificationManager(): NotificationManager`<br>get Notification Manager |
| [getNsdManager](get-nsd-manager.md) | `fun Context.getNsdManager(): NsdManager`<br>get MSD Manager |
| [getPowerManager](get-power-manager.md) | `fun Context.getPowerManager(): PowerManager`<br>get Power Manager |
| [getSearchManager](get-search-manager.md) | `fun Context.getSearchManager(): SearchManager`<br>get Search Manager |
| [getSensorManager](get-sensor-manager.md) | `fun Context.getSensorManager(): SensorManager`<br>get Sensor Manager |
| [getStorageManager](get-storage-manager.md) | `fun Context.getStorageManager(): StorageManager`<br>get Storage Manager |
| [getTelephonyManager](get-telephony-manager.md) | `fun Context.getTelephonyManager(): TelephonyManager`<br>get Telephony Manager |
| [getTextServicesManager](get-text-services-manager.md) | `fun Context.getTextServicesManager(): TextServicesManager`<br>get TextService Manager |
| [getUiModeManager](get-ui-mode-manager.md) | `fun Context.getUiModeManager(): UiModeManager`<br>get UiMode Manager |
| [getUsbManager](get-usb-manager.md) | `fun Context.getUsbManager(): UsbManager`<br>get USB Manager |
| [getUserManager](get-user-manager.md) | `fun Context.getUserManager(): UserManager`<br>get UserManager |
| [getVibrator](get-vibrator.md) | `fun Context.getVibrator(): Vibrator`<br>get Vibrater Service |
| [getWifiManager](get-wifi-manager.md) | `fun Context.getWifiManager(): WifiManager`<br>get WiFi Manager |
| [getWifiP2pManager](get-wifi-p2p-manager.md) | `fun Context.getWifiP2pManager(): WifiP2pManager`<br>get WiFI P2P Manager |
| [getWindowManager](get-window-manager.md) | `fun Context.getWindowManager(): WindowManager`<br>get Window Manager |
| [isAppInstalled](is-app-installed.md) | `fun Context.isAppInstalled(packageName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Check if an App is Installed on the user device. |
| [isGPSEnable](is-g-p-s-enable.md) | `fun Context.isGPSEnable(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Checks if GPS is Enabled or Not. Might Require the Location Permission |
| [isIntentResolvable](is-intent-resolvable.md) | `fun Context.isIntentResolvable(intent: Intent): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Wanna check if you can resolve the intent? Call [isIntentResolvable](is-intent-resolvable.md) with your intent and check it with the ease. |
| [isNetworkAvailable](is-network-available.md) | `fun Context.isNetworkAvailable(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Check if Internet is Available or not. Requires ACCESS_NETWORK_STATE Permission. |
| [requestMediaScanner](request-media-scanner.md) | `fun Context.requestMediaScanner(url: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>ask the system to scan your file easily with a broadcast. |
| [screenHeight](screen-height.md) | `val Context.screenHeight: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>get Screen Height Easily |
| [screenWidth](screen-width.md) | `val Context.screenWidth: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>get Screen Width Easily |
| [showConfirmationDialog](show-confirmation-dialog.md) | `fun Context.showConfirmationDialog(msg: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, onResponse: (result: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`, positiveText: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "Yes", negetiveText: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "No", cancelable: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = false): AlertDialog`<br>Want to Confirm the User Action? Just call showConfirmationDialog with required + optional params to do so. |
| [showDatePicker](show-date-picker.md) | `fun Context.showDatePicker(year: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, month: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, day: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, onDatePicked: (year: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, month: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, day: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Show Date Picker and Get the Picked Date Easily |
| [showMultiPicker](show-multi-picker.md) | `fun Context.showMultiPicker(choices: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>, onResponse: (index: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, isChecked: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`, checkedItems: `[`BooleanArray`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean-array/index.html)`? = null): AlertDialog`<br>Want your user to choose Multiple things from a bunch? call showMultiPicker and provide your options to choose from |
| [showSinglePicker](show-single-picker.md) | `fun Context.showSinglePicker(choices: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>, onResponse: (index: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`, checkedItemIndex: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = -1): AlertDialog`<br>Want your user to choose Single thing from a bunch? call showSinglePicker and provide your options to choose from |
| [showTimePicker](show-time-picker.md) | `fun Context.showTimePicker(currentDate: `[`Date`](http://docs.oracle.com/javase/6/docs/api/java/util/Date.html)` = currentDate(), is24Hour: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = false, onDatePicked: (hour: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, minute: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Show the Time Picker and Get the Picked Time Easily |
| [showToast](show-toast.md) | `fun Context.showToast(msg: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, length: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = Toast.LENGTH_LONG): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>shows the toast with a Single Call, Just Provide your [msg](show-toast.md#com.amnix.utils.extensions$showToast(android.content.Context, kotlin.String, kotlin.Int)/msg) and [length](show-toast.md#com.amnix.utils.extensions$showToast(android.content.Context, kotlin.String, kotlin.Int)/length) (Optionally) |
| [showToastHard](show-toast-hard.md) | `fun Context.showToastHard(msg: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): AlertDialog`<br>There is No Such Thing name Hard Toast, Its just an AlertDialog which will the [msg](show-toast-hard.md#com.amnix.utils.extensions$showToastHard(android.content.Context, kotlin.String)/msg) you passed until user cancels it. |
| [startActivity](start-activity.md) | `fun Context.startActivity(cls: `[`Class`](http://docs.oracle.com/javase/6/docs/api/java/lang/Class.html)`<out Activity>, extras: Bundle): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Starts Activity with the class and extra values |
| [startApp](start-app.md) | `fun Context.startApp(pName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Want to start third party App? Just get us the package Name and we will Start* It |
| [startService](start-service.md) | `fun Context.startService(cls: `[`Class`](http://docs.oracle.com/javase/6/docs/api/java/lang/Class.html)`<out Service>, extras: Bundle): ComponentName`<br>Starts Service with the class and extra values |
| [vibrate](vibrate.md) | `fun Context.vibrate(millis: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Vanna Vibrate the Device Vibrator for some Feedback? do it with the ease of [vibrate](vibrate.md) method with the specific millis |