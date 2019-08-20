# Mobile

### Sync time for PC and emulator
* Run as *sudo*
* ```adb shell su root date -u @$(date +%s)```
* If *Encountered Operation not permitted*
    * Go to emulator settings disable Automatic Date/Time & Automatic Timezone

### React Native Re-build Milo Mobile with AndroidX
* Execute in Sequence
    * ```npm install ```
    * copy ```ihealthsdk``` to ```node_modules```
    * create ```env_config.js``` file
    * comment out **Android x** on **gradle.properties**
    * Android Studio Run *Migrate to **AndroidX***
    * Android Studio Clean project
    * Android Studio Rebuild Project
    * Run Project on CLI
