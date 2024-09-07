# macos-settings

My recommendations for the ultimate macOS Configuration :)

**NOTE:** This project can be found on both [Codeberg](https://codeberg.org/celenity/macos-settings), which will act as the main & preferred way to contribute, and [GitHub](https://github.com/celenityy/macos-settings).

# Apple ID

Personal Information -> Communication Preferences -> **Announcements** -> ❌

Personal Information -> Communication Preferences -> **Apps, music, TV and more** -> ❌

Sign-In & Security -> **Two-Factor Authentication** -> ✅ *(Use security keys if possible)*

Media & Purchases -> **Free Downloads** -> `Never require`

Media & Purchases -> **Purchases and In-App Purchases** -> `Always require`

# Wi-Fi

**Wi-Fi** -> ❌ *when not using*

**Ask to join hotspots** -> ❌

# Bluetooth

**Bluetooth** -> ❌ *when not using*

# Network

**Firewall** -> ✅

Firewall -> Options -> **Block all incoming connections** -> ✅

Firewall -> Options -> **Enable stealth mode** -> ✅

# Notifications

**Show previews** -> `When Unlocked`

**Allow notifications when the display is sleeping** -> ❌

**Allow notifications when the screen is locked** -> ❌

**Allow notifications when mirroring or sharing the display** -> ❌

**Application Notifications** -> Go through and disable notifications for any apps that don't need it

# Focus

**Share across devices** -> ❌

Focus status -> **Share Focus status** -> ❌

# Screen Time

**Content & Privacy** -> ✅

Content & Privacy:

Store, Web, Siri & Game Center Content:

* **Allow Web Search Content in Siri** -> ❌

* **Allow Music & TV Shared Libraries** -> ❌ 

* **Allow Adding Friends** -> ❌ 

* **Allow Connect with Friends** -> ❌ 

* **Allow Private Messaging** -> ❌ 

* **Allow Multiplayer Games With** -> `No one` *(if you don't play any games online through Game Center)*

* **Allow Nearby Multiplayer** -> ❌ 

App & Feature Restrictions:

* **Allow Book Store** -> ❌

* **Allow Siri & Dictation** -> ❌

* **Allow SharePlay** -> ❌

The following appear to only impact iOS, but I would still recommend setting them for defense in depth, just don't disable anything you actually use or need...

* **Allow Mail** -> ❌

* **Allow Safari** -> ❌

* **Allow FaceTime** -> ❌

* **Allow Wallet** -> ❌

* **Allow CarPlay** -> ❌

* **Allow iTunes Store** -> ❌

* **Allow Podcasts** -> ❌

* **Allow AirDrop** -> ❌

* **Allow Health** -> ❌

* **Allow Activity** -> ❌

* **Allow App Clips** -> ❌

# General

About -> **Name** -> Keep this generic, I recommend setting it to `Device`

Software Update -> Automatic Updates:

* **Check for updates** -> ✅

* **Download new updates when available** -> ✅

* **Install macOS updates** -> ✅

* **Install application updates from the App Store** -> ✅

* **Install Security Responses and system files** -> ✅

<br>

AirDrop & Handoff:

* **Allow Handoff between this Mac and your iCloud devices** -> ❌

* **AirDrop** -> `No One`

* **AirPlay Receiver** -> ❌

* **Allow AirPlay for** -> `Current User`

* **Login Items** -> Go through and remove/disable anything from here you don't need

<br>

Language & Region -> Translation Languages... -> **On-Device Mode** -> ✅

Date & Time -> **Set date and time automatically** -> ✅ *(Very important for security)*

Date & Time -> Source -> **Set...** -> I would recommend setting this to the time server ran by [GrapheneOS](https://grapheneos.org/): `time.grapheneos.org`

Date & Time -> **24-hour time** -> ❌

Date & Time -> **Show 24-hour time on Lock Screen** -> ❌

Sharing:

* **File Sharing** -> ❌

* **Media Sharing** -> ❌

* **Screen Sharing** -> ❌

* **Content Caching** -> ❌

* **Bluetooth Sharing** -> ❌

* **Printer Sharing** -> ❌

* **Internet Sharing** -> ❌

* **Remote Management** -> ❌

* **Remote Login** -> ❌

* **Remote Application Scripting** -> ❌

# Appearance

**Appearance** -> `Dark`

# Accessibility

The 3 options below are optional but recommended for lower-end or older devices to improve performance and battery:

Display -> **Reduce motion** -> ✅

Display -> **Reduce transparency** -> ✅

Display -> **Auto-play animated images** -> ❌

**Voice Control** -> ❌ *(if you don't use/need it)*

Keyboard -> **Sticky Keys** -> ❌ *(Important for gaming)*

Keyboard -> **Slow Keys** -> ❌ *(Important for gaming)*

Pointer Control -> **Ignore built-in trackpad when mouse or wireless trackpad is present** -> ✅

Pointer Control -> Trackpad Options... -> **Scroll speed** -> Make sure it's set so that it's 4 spaces away from the turtle on the left & 3 spaces away from the rabbit on the right *(Should be default, important for gaming)*

Pointer Control -> Mouse Options... -> **Scroll speed** -> Make sure it's set so that it's 4 spaces away from the turtle on the left & 3 spaces away from the rabbit on the right *(Should be default, important for gaming)*

Personal Voice -> **Share across devices** -> ❌

Personal Voice -> **Allow applications to use your Personal Voice** -> ❌

Siri -> **Type to Siri** -> ✅

# Control Center

**Wi-Fi** -> `Show in Menu Bar`

**Bluetooth** -> `Show in Menu Bar`

**AirDrop** -> `Don't Show in Menu Bar`

**Focus** -> `Show when active`

**Screen Mirroring** -> `Show when active`

Accessibility shortcuts -> **Show in Menu Bar** -> ❌ *(Unless you need/use this)*

Accessibility shortcuts -> **Show in Control Center** -> ❌ *(Unless you need/use this)*

Battery -> **Show in Menu Bar** -> ✅

Battery -> **Show in Control Center** -> ✅

Battery -> **Show Percentage** -> ✅

Fast User Switching -> **Show in Menu Bar** -> Your choice, this is a great setting to take advantage of if you use multiple users, otherwise don't bother

Fast User Switching -> **Show in Control Center** -> ✅ *(only if you use multiple users)*

Menu Bar Only -> Clock Options... -> Date -> **Show date** -> `When space allows`

Menu Bar Only -> Clock Options... -> Date -> **Show the day of the week** -> ✅

Menu Bar Only -> Clock Options... -> Time -> **Style** -> `Digital`

Menu Bar Only -> Clock Options... -> Time -> **Show AM/PM** -> ✅

Menu Bar Only -> Clock Options... -> Time -> **Display the time with seconds** -> ✅

Menu Bar Only -> Clock Options... -> Time -> **Announce the time** -> ❌ *(Should be default, lol)*

**Siri** -> `Don't Show in Menu Bar`

# Siri & Spotlight

**Ask Siri** -> ❌

Spotlight:

* **Contacts** -> ❌

* **Siri Suggestions** -> ❌

* **Tips** -> ❌

* **Websites** -> ❌

# Privacy & Security

**Location Services** -> ❌ *(if you don't use/need it)*

Disable location access for any apps that don't need it here

System Services -> Details...:

* **Suggestions & Search** -> ❌

* **System customization** -> ❌

* **Significant locations** -> ❌

* **Find My Mac** -> ❌

* **HomeKit** -> ❌

* **Mac Analytics** -> ❌

* **Show location icon in Control Center when System Services request your location** -> ✅

<br>

Go through all permissions under privacy and remove permissions for any apps that don't need them

**Sensitive Content Warning** -> ❌

Analytics & Improvements -> **Share Mac Analytics** -> ❌

Analytics & Improvements -> **Improve Siri & Dictation** -> ❌

Analytics & Improvements -> **Share with app developers** -> ❌

Apple Advertising -> **Personalized Ads** -> ❌

**Allow applications downloaded from** -> `App Store and identified developers`

**Allow accesories to connect** -> `Ask Every Time`

**FileVault** -> `On` ✅ (Don't save the recovery key to your iCloud account...)

**Lockdown Mode** -> `On` ✅

Extensions -> **Added extensions** -> Remove any extensions you don't need/use

Extensions -> Sharing:

* **Contact Suggestions** -> ❌

* **AirDrop** -> ❌

* **Mail** -> ❌ *(if you don't use/need it)*

* **Messages** -> ❌ *(if you don't use/need it)*

* **Save to Books** -> ❌

* **Freeform** -> ❌

* **Instruments** -> ❌

<br>

**Profiles** -> Remove any profiles you don't need/use

Advanced... -> **Require an administrator password to access system-wide settings** -> ✅

Advanced... -> **Log out automatically after inactivity** -> ✅

Advanced... -> **Log out after...** -> Your choice, the lower the better, I leave mine at `60 minutes` due to other options we set (Should investigate this further)

# Desktop & Dock

**Show suggested and recent apps in Dock** -> ❌

Show Widgets -> **On Desktop** -> ❌

Show Widgets -> **In Stage Manager** -> ❌

**Use iPhone widgets** -> ❌

**Default web browser** -> Set to your browser of choice, I recommend [Firefox](https://www.mozilla.org/firefox/).

**Prefer tabs when opening documents** -> `Always`

**Ask to keep changes when closing documents** -> ✅

**Close windows when quitting an application** -> ✅

**Automatically rearrange Spaces based on most recent use** -> ❌

# Displays

**Automatically adjust brightness** -> ❌ *(Annoying and better for battery)*

**True Tone** -> ✅

**Preset** -> Choose `Apple XDR Display` if you have the option, otherwise `Apple Display` *(Should be default)*

**Refresh rate** -> `ProMotion` if you have the option

Advanced...:

**Allow your pointer and keyboard to move between any nearby Mac or iPad** -> ❌

**Push through the edge of a display to connect a nearby Mac or iPad** -> ❌

**Automatically reconnect to any nearby Mac or iPad** -> ❌

Night Shift:

Schedule -> **Custom:** -> I usually set to `From 9:00PM to 6:00AM`

**Color Temperature** -> Set to the middle *(Should be default)*

# Battery

Battery Health -> **Optimized Battery Charging** -> ✅ *(Should be default)*

Energy Mode -> **On battery** -> `Automatic` *(Should be default)* - You can also set this to `Low Power` if you need to conserve battery life

Energy Mode -> **On power adapter** -> `Automatic` *(Should be default)* - It might also be desirable to set this to `High Power` depending on your use case

Options...:

* **Slightly dim the display on battery** -> ✅

* **Prevent automatic sleeping on power adapter when the display is off** -> ❌

* **Wake for network access** -> `Only on Power Adapter`

* **Optimize video streaming while on battery** -> ❌ *(Should be default)* - You can enable if you need to conserve battery life

# Lock Screen

**Start Screen Saver when inactive** -> Your choice, the lower the better, I usually set to `For 2 minutes`

**Turn display off on battery when inactive** -> Your choice, the lower the better, I usually set to `For 2 minutes`

**Turn display off on power adapter when inactive** -> Your choice, the lower the better, I usually set to `For 5 minutes`

**Require password after screen saver begins or display is turned off** -> Your choice, the lower the better, I usually set to `After 5 seconds`

When switching users -> **Show the Sleep, Restart, and Shut Down buttons** -> ✅

Accessibility Options...:

* **VoiceOver** -> ❌ *(if you don't use/need it)*

* **Sticky Keys** -> ❌ *(Important for gaming)*

* **Slow Keys** -> ❌ *(Important for gaming)*

# Touch ID & Password

Make sure you set a strong password, I would recommend avoiding Touch ID and using it as little as possible:

**Use Touch ID to unlock your Mac** -> ❌

**Use Touch ID for Apple Pay** -> ❌

**Use Touch ID for purchases in iTunes Store, App Store, and Apple Books** -> ❌

**Use Touch ID for autofilling passwords** -> ❌

**Use Touch ID for fast user switching** -> ❌

# Users & Groups

Delete any groups you don't need/use

**Automatically log in as** -> `Off` ❌

# Passwords

Security Recommendations -> **Detect leaked passwords** -> ✅ *(This is done locally on device through a list of passwords, Apple doesn't get sent your passwords)*

Password Options -> **Autofill Passwords and Passkeys** -> ❌

Password Options -> Verification Codes -> **Delete After Use** -> ✅

# Internet Accounts

Remove any accounts in here you don't need/use

# Wallet & Apple Pay

**Shipping Address** -> `No Shipping Address`

**Email** -> `No Email`

**Phone** -> `No Phone`

**Compatible cards** -> ❌ 

**Add Orders to Wallet** -> ❌

# Keyboard

**Key repeat rate** -> `Fast` *(Drag all the way to the right, important for gaming)*

**Delay until repeat** -> `Short` *(Drag all the way to the right, important for gaming)*

**Press Globe key to** -> `Show Emoji & Symbols`

**Dictation** -> ❌

# Trackpad

**Tracking speed** -> Make sure it's set so that it's 4 spaces away from the left & 5 spaces away from the right *(important for gaming)*