This guide tries to give you tips and tricks, how to make your iOS device more private and what settings have to be set, to get a more secure system than a default iOS installation.

Smartphones are insecure by design. Depending on your threat-level, you should consider not using a smartphone at all.

I am **not** responsible if you break your iOS device or lose data by following any of these steps.

If you wish to make a correction or improvement, please send a pull request or [open an issue](https://github.com/chrizel/iOS-Security-and-Privacy-Guide/issues).

- [Basics](#basics)
- [Settings](#settings)
- [Apps](#apps)
    - [Content Blockers](#content-blockers)
- [Additional resources](#additional-resources)

## Basics
Don't install apps you don't use. Remove apps you don't use.

## Settings

### Personal Hotspot
Personal Hotspot advertises a custom WiFi network to the environment. Turn Personal Hotspot **off** if you don't use it.

### General - Spotlight Search
Spotlight sends search requests to Apple servers, therefore you should turn these settings **off** if you don't like this:

- Siri Suggestions
- Suggestions in Search
- Suggestions in Look Up

### General - Handoff
Handoff uses iCloud and contacts Apple servers. This setting should be turned **off** if you don't use Handoff.

### General - Background App Refresh
Allows selected apps to refresh their content in the background. You can disable apps there, if you seldom use them or if you think, they shouldn't do anything while not using them. Apps where you disabled notifications and games could be disabled here. Messaging apps (Whatsapp, Signal, etc.) should stay **on** or they might not work like expected anymore.

### Siri
If you don't use Siri, you should turn it **off**.

### Touch ID & Passcode
These settings are very user specific, and you should turn them **on** or **off** depending on if you need these features or not. From a security and privacy perspective you should turn all of these settings **off**:

- Voice Dial
- Today View
- Notifications View
- Reply with Message
- Home Control
- Wallet

It is recommended to turn these settings to **on**:

- Erase Data

### Privacy - Location Services
Turn Location Services to **off** if you don't need location specific information in apps. Turn them **on**, only when you need things like navigation. If turned on, limit the number of apps which can use your location as much as possible. Games or some shopping app will most likely never need your location, therefore you should turn their permission for your location to **off**. Turn Location Services **off** for apps like WhatsApp, Facebook or Instagram if you don't have any reason to share this information with them. Try to set Location Services for most apps to *Never*. Set the rest to *While Using*. Avoid the setting *Always* because it allows the app to use your location information and do anything with it, even if you are not using it.

### Privacy - Location Services - System Services
Turn these settings **off**:
- Location-Based Apple Ads
- Location-Based Suggestions
- Frequent Locations
- Diagnostics & Usage
- Popular Near Me
- Routing & Traffic

### Privacy - Contacts
These apps can access all data from your contact list. Apps like Facebook or WhatsApp take this data and upload it to their servers and store them forever. Once done, this action can never be undone. Limit your contacts access to as few apps as possible. Most likely only messaging apps are required to access your contacts.

### Privacy - Calendars
Same as with contacts. Limit calendar access to as few apps as possible.

### Privacy - Reminders
Turn everything to **off** if you don't use reminders in these apps.

### Privacy - Photos
As with contacts, your photos can contain very sensitive information including GPS information in the photos metadata. You should turn access to photos for every app to **off** if you don't need to.

### Privacy - Microphone
As always - disable as many apps as possible. These apps can access your iPhone's microphone, can use this data and can even upload them to the internet.

### Privacy - Camera
I would limit camera access to as few apps as possible. Only activate it for apps which you are using regularly and where you have to access your camera inside the app.

### Privacy - Health
Health data can be very sensitive, therefore you should limit this as much as possible.

### Privacy - Motion & Fitness
Disable apps that should not be allowed to access your motion and fitness data.

### Privacy - Diagnostic & Usage Data
This sends data to Apple servers. Set it to *Don't Send*.

### Privacy - Advertising - Limit Ad Tracking
Turn this *on*.

### iCloud
If you don't use certain iCloud features, you should turn them **off**. If possible, turn iCloud off altogether and remove your iCloud account from your iPhone.

### Safari
- Search Engine: DuckDuckGo
- Search Engine Suggestions: Off
- Safari Suggestions: Off
- Preload Top Hit: Off
- AutoFill: Turn everything off
- Frequently Visited Sites: Off
- Block Pop-ups: On
- Content Blockers: see [Content Blockers](#content-blockers)
- Do Not Track: On
- Block Cookies: Allow From Current Website Only
- Check for Apple Pay: Off

## Apps

### Content Blockers
TODO

## Additional resources

*In no particular order*

[/r/privacy](https://www.reddit.com/r/privacy/)

[/r/privacytoolsIO](https://www.reddit.com/r/privacytoolsIO/)

[Privacy Tools - Encryption Against Global Mass Surveillance](https://www.privacytools.io)

[Collaborative List of Open-Source iOS Apps](https://github.com/dkhamsing/open-source-ios-apps)

[How to Secure Your iPhone & iPad (Without More Apps)](https://vpnreporter.com/secure-iphone-ipad/)

[IKEv2 VPN Server on Docker, with .mobileconfig for iOS & macOS.](https://github.com/gaomd/docker-ikev2-vpn-server)
