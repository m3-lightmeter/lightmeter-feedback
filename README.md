# Lightmeter – Feedback & Support

👋 Welcome! This repo is for reporting bugs, suggesting features, and tracking improvements for the **Lightmeter** app.

---

## 📲 Download
- [Google Play](https://play.google.com/store/apps/details?id=com.vodemn.lightmeter)
- [App Store](https://apps.apple.com/us/app/light-meter-logbook/id6474434590)

###  iOS Limitations

A list of features, that Android version of the app has and that iOS does not.

#### Incident light metering

Apple does not provide API for reading Lux stream form the ambient light sensor. Lux can be calculated based on front camera image stream, but this would be a reflected light. So there is no way incident light metering can be implemented on iOS.

#### Volume buttons action

This can be [implemented](https://stackoverflow.com/questions/70161271/ios-override-hardware-volume-buttons-same-as-zello) but the app will be rejected due to [2.5.9](https://developer.apple.com/app-store/review/guidelines/#software-requirements)

---

## 🚀 How to Report
- Use the [Issues tab](../../issues) for bugs & requests.
- Search before posting to avoid duplicates.
- Include: device model, OS version, Lightmeter app version, steps to reproduce.

---

## 🔒 About Source Code
Lightmeter’s source code is now **private**.  
This repo is only for **feedback, support, and discussions**.
