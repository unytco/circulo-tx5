<div align="center">

# <img src="src-tauri/icons/circulo-logo.svg" alt="Circulo" width="300">

![Latest Release](https://img.shields.io/github/v/release/unytco/circulo-tx5?style=flat-square&color=blue)
![Downloads](https://img.shields.io/github/downloads/unytco/circulo-tx5/total?style=flat-square&color=green)
![License](https://img.shields.io/github/license/unytco/circulo-tx5?style=flat-square)

<img src="docs/images/circulo-home.png" alt="Circulo3 Agent Settings" width="100%" style="max-width: 800px; height: auto;">

<p>&nbsp;</p>

<table><tr>
<td><b>View README file in: </b></td>
<td><a href=/README>English</a><//td>
<td><a href=/README.tr> Türkçe  </a><//td>
<td><a href=/README.de> Deutsch </a><//td>
<td><a href=/README.fr> Français </a><//td>
<td><a href=/README.es> Español </a><//td>
</tr></table>

## A Playful Take on p2p Payments

<div align="left">
<h3>

</h3>
<h3> 
Introduction
</h3>
<p>
Welcome to version 3 of Circulo!
</p>
<p>

Circulo is a generosity oriented peer-to-peer payments system, built using the Unyt mutual credit accounting engine.

</p>
<p>
Everyone starts with an account balance of zero and a small credit limit. Your credit limit determines the max you can spend below zero. 
</p>
<p>
Circulo makes use of a very simple credit algorithm: every time you send someone some units, your credit limit increases a little bit.  This is a very simple, and easily gameable credit algorithm. It also makes it easy for people to play with it.
</p>
<p>
In Circulo, as soon as you send someone units, your account will be debited.  However, the receiver's account balance won't include those units until they exercize their own agency and choose to accept them. If they never accept them, they remain available for them to collect. No one else is able to claim them.
</p>
<p>
By anchoring activity in the agency of the participants themselves, Circulo opens up some interesting new efficiencies and possibilities. These will get explored in more detail in future releases.
</p>
<p>
Check out the <a href="https://unyt.co/blog/pays-well-with-others/">blog post on Circulo3</a> for more details not only on this release but also on the role that Circulo is playing in helping improve Unyt and Holochain more generally.
</p>
<img src="docs/images/Switch-languages-in-Circulo3.png" alt="Switching languages in Circulo3" width="100%" style="max-width: 800px; height: auto;">

<h3>
Testing
</h3> 
<p>
This third version of Circulo provides support for multiple languages including Turkish, German, Spanish and French. Simply go to Agent Overview > Settings Gear > Language and pick whichever mother tongue that speaks to you. And if there is another language you want included and that you can help with, reach out. 
</p>
<p>
Circulo3 also includes some performance improvements that should make the app a bit faster and more reliable. 
</p>
<p>
If you want to join in on the conversation as well as the testing, request to join the Circulo Telegram channel by sending an email to info@unyt.co with the subject "I want to play!". Our team will send you an invite link.
</p>
<p>
For version 3 of Circulo, we are planning to do one focused round of testing. 
</p>
<p>
Testing will start on Wednesday, November 5th and we are asking folks to send transactions, try out different languages and just generally explore the app for a couple of days.
</p>
<p>
After Friday, the 7th, people are welcome to still play with the app, but assume that most folks (including our team) will have wrapped up their testing and may no longer be running the app.
</p>
<p>
Find some people to send CIRC to in the <a href="https://docs.google.com/spreadsheets/d/1W-Ljs5lc6d4CjCTFKTYIoSxJr6ShJt26LZFvzyuHnbQ/edit?usp=sharing">Circulo3 Addresses Sheet</a>.
</p>
<p>
And <a href="https://forms.gle/F87ZVcX9avZEL985A">add yourself using this form</a> so that others can send CIRC to you as well. 
</p>
<p>
Note: Please make sure that you are sharing an address from Circulo3 and not an earlier version of Circulo.
</p>
<p>
If you see an error, please <a href="https://github.com/unytco/circulo-tx5/issues">report it as an issue</a> in this repo (if not already reported). Or at the very least, mention it in the Circulo Telegram Channel and tag it with #issue.
</p>
<p>
To get past an error:

1. Wait: making yourself a cup of tea resolves most things
2. Reload: When in doubt try: Right click > Reload (but reloading over and over may make your wait longer as each reload re-requests everything on the page)
3. Restart: When a few reload tries don't work, please quit and restart
</p>
<p>
We are using software called Sentry to help track errors so we can better understand their frequency and context. But you reporting issues is most helpful, too.
</p>
</div>

</div>

## Downloads

<div align="center">

<table>
<tr>
<td width="33%" align="center">

#### **Windows**

---

<a href="https://github.com/unytco/circulo-tx5/releases/download/v0.3.0/Circulo_zero-arc_0.3.0_x64_windows.msi">MSI Installer (x64)</a>

<a href="https://github.com/unytco/circulo-tx5/releases/download/v0.3.0/Circulo_zero-arc_0.3.0_x64_windows.exe">EXE Setup (x64)</a>

</td>
<td width="25%" align="center">

#### **MacOS**

---

<a href="https://github.com/unytco/circulo-tx5/releases/download/v0.3.0/Circulo_zero-arc_0.3.0_aarch64_darwin.dmg">Apple Silicon (arm64)</a>

<a href="https://github.com/unytco/circulo-tx5/releases/download/v0.3.0/Circulo_zero-arc_0.3.0_x64_darwin.dmg">Intel (x64)</a>

</td>
<td width="25%" align="center">

#### **Linux**

---

<a href="https://github.com/unytco/circulo-tx5/releases/download/v0.3.0/Circulo_zero-arc_0.3.0_amd64_linux.AppImage">AppImage</a>

<a href="https://github.com/unytco/circulo-tx5/releases/download/v0.3.0/Circulo_zero-arc_0.3.0_amd64_linux.deb">Debian (.deb)</a>

</td>

---

</tr>
</table>

</div>

## Installation

<details>
<summary><strong>Windows</strong></summary>

1. Download the `.msi` installer
2. Run the installer and follow the setup wizard
3. Launch Circulo from the Start menu

</details>

<details>
<summary><strong>macOS</strong></summary>

1. Download the `.dmg` file
2. Open the DMG and drag Circulo to your Applications folder
3. Launch from Applications (you may need to allow the app in System Preferences > Security)

</details>

<details>
<summary><strong>Linux</strong></summary>

**AppImage (Recommended)**

1. Download the `.AppImage` file
2. Make it executable: `chmod +x circulo_0.1.0_amd64.AppImage`
3. Run: `./circulo_0.1.0_amd64.AppImage`

**Debian/Ubuntu**

1. Download the `.deb` package
2. Install: `sudo dpkg -i circulo_0.1.0_amd64.deb`
3. Run: `circulo`

</details>

<!-- <details>
<summary><strong>Android</strong></summary>

1. Download the appropriate APK for your device architecture
2. Enable "Install from unknown sources" in your device settings
3. Install the APK file
4. Launch Circulo from your app drawer

</details> -->

## System Requirements

| Platform    | Minimum Requirements                    |
| ----------- | --------------------------------------- |
| **Windows** | Windows 10 (64-bit) or later            |
| **macOS**   | macOS 10.15 (Catalina) or later         |
| **Linux**   | Ubuntu 18.04+ / equivalent distribution |

 <!--        | **Android**                             | Android 7.0 (API level 24) or later | -->

**Recommended:** 4GB RAM, 1GB free disk space, internet connection for updates

## Support

- <a href="https://github.com/unytco/circulo-tx5/issues">Report Issues</a>

## License

This project is licensed under the terms specified in the [LICENSE](LICENSE) file.






