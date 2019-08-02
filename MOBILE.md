# Mobile

### Sync time for PC and emulator
* Run as *sudo*
* ```adb shell su root date -u @$(date +%s)```
* If *Encountered Operation not permitted*
    * Go to emulator settings disable Automatic Date/Time & Automatic Timezone
