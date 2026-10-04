# ZEVEX Cashier

Companion app for zevex.in UPI gateway. Google Pay Business aur PhonePe Business
notifications ko padh kar server ko payment events push karta hai (auto-verify).

## Build

GitHub Actions khud APK banata hai. Actions tab → latest run → Artifacts → `zevex-cashier`.

## Install

1. APK download karo, install karo ("Unknown sources" allow karo)
2. App kholo:
   - API base = `https://zevex.in`
   - App = Google Pay ya PhonePe
   - Server code (website se) daalo → Register
3. App Code copy karke website modal me paste → Verify
4. App me "Notification access" aur "Battery optimization off" dono ON karo
