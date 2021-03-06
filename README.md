# Homeykit

With this app you can pair Homey to Homekit and control your devices using Siri.

After installing the app grab your iPhone or iPad.
Got to the Home app on your iOS devices, click the `+` and add new accessory.
Now you should be able to scan the code below, or add it manually.

![Image of paircode](https://github.com/swttt/com.swttt.homekit/raw/master/settings/code.png)

After Homey is paired, go to settings->Homeykit. There select the devices you want to pair with homekit.

It might take a few sec (sometimes even longer) until your device shows up in your Home app.

For now only the following classes are supported:
- Light (with RGB or Temperature)
- Socket
- Motionsensor (with lux and temp)
- Doorlock

---

### Issues & Feature requests

If you found any bugs you can create an issue on [github](https://github.com/swttt/com.swttt.homekit) .

Any other feature request can be added there as well.

---

### Donate

If you like this app, then consider to buy me a beer :)

[![Donate](https://www.paypalobjects.com/webstatic/en_US/i/btn/png/btn_donate_92x26.png)](https://paypal.me/BasJansen)

---

### Changelog

##### 1.0.3
- Added logging (with realtime updating)
- Changed the devices UI
- Translated Settings

##### 1.0.2
- Fixed readme
- Server object gets local mac adres

##### 1.0.0
- Initial release
