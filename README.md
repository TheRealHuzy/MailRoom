<img align="left" height="70" src="https://github.com/TheRealHuzy/MailRoom/blob/main/Assets/MailRoomLogoWhite.png" />

# MailRoom
Lightweight automatic email backup

### Project description:
MailRoom is a simple and lightweight automatic email backup solution for clients that need to store communication footprint locally when their server storage reaches user limit or for simply wanting to use a email to PDF generation capabilities of this application. Users can configure automatic backup shedule to their personal needs as well as limit how load intensive download process is on the host server. Application runs unobtrusively in the system tray and can start automatically with operating system.

<p align="center">
  <img src="https://github.com/TheRealHuzy/MailRoom/blob/main/Assets/Gif1.gif" />
</p>

***

### Features
* automatic email backup
* organizing and filtering downloaded email data
* automatic categorisation to recently and often used
* upon copying email, PDF file is created and added to clipboard
* sender filters for emails that should be included in download process
* creating consistent download shedule
* additional manual backup configuration
* configuring server load (batch variables)
* start on startup/minimized
* minimized to system tray

#### Filter and organize
<p align="center">
  <img src="https://github.com/TheRealHuzy/MailRoom/blob/main/Assets/Gif2.gif" />
</p>

#### Edit tags
<p align="center">
  <img src="https://github.com/TheRealHuzy/MailRoom/blob/main/Assets/Gif3.gif" />
</p>

#### Copy to clipboard
<p align="center">
  <img src="https://github.com/TheRealHuzy/MailRoom/blob/main/Assets/HomeCopy.png" />
</p>

<p align="center">
  <img height="700" src="https://github.com/TheRealHuzy/MailRoom/blob/main/Assets/PDF.png" />
</p>

***

### Configuration

Set you email address, password, IMAP server and port and you are ready to go.

<p align="center">
  <img src="https://github.com/TheRealHuzy/MailRoom/blob/main/Assets/Configuration.png" />
</p>

### Settings

Configure backup shedule and filters.

<p align="center">
  <img src="https://github.com/TheRealHuzy/MailRoom/blob/main/Assets/Settings.png" />
</p>

### Manual download

Having additional email filters that were not set at the start is not a problem. Define sender filter/s and time period and those emails will be downloaded.

<p align="center">
  <img src="https://github.com/TheRealHuzy/MailRoom/blob/main/Assets/Download.png" />
</p>

***

### Backups

Track automatic and manual backups for easy revision.

<p align="center">
  <img src="https://github.com/TheRealHuzy/MailRoom/blob/main/Assets/Backups.png" />
</p>

### Help

All features are explained in the help section if you ever get stuck.

<p align="center">
  <img src="https://github.com/TheRealHuzy/MailRoom/blob/main/Assets/Help.png" />
</p>

***

### Limitations
* application runs only on operating system Windows 10 or later
* current implementation requires a custom IMAP mail server for establishing connection
* multiple backup email addresses are not supported
* there is no connection error information conveyed to the user

### Libraries
* CommunityToolkit - UI element presets >> contains various Extensions for text, framework components, visual transforms, shadows, ScrollViewer, ListViewBase, and more.
* MailKit - mail download library >> open source cross-platform .NET mail-client library that is based on MimeKit and optimized for mobile devices
* QuestPDF - PDF generation library >> open source, modern and battle-tested library that can help you with generating PDF documents by offering friendly, discoverable and predictable C# fluent API
* H.Notify - tray icon for winUI >> an implementation of a NotifyIcon (aka system tray icon or taskbar icon) for the WinUI platform
