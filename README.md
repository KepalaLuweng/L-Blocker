# **Luweng Blocker (L-Blocker)**

### **Your Rules, Your Network.**

**L-Blocker** is an advanced, system-wide ad, tracker, and malware blocker for rooted Android devices. Designed for both Magisk and KernelSU, it provides a powerful, profile-based blocking system managed through a clean and intuitive Web Control Panel. L-Blocker puts you in command, allowing you to choose your level of protection and customize it with modular add-ons to create a truly clean and secure network experience on your device.

## **Key Features**

* **System-Wide Blocking:** Blocks ads, trackers, and malicious domains across your entire device, including in browsers, apps, and games.  
* **Profile-Based System:** Choose from four main protection profiles, ranging from a light touch to an ultimate, all-encompassing blockade.  
* **Modular Add-ons:** Fine-tune your protection by enabling specialized blocklists for telemetry, aggressive tracking, regional domains, and more.  
* **Web Control Panel:** A beautiful and easy-to-use interface accessible directly from the Magisk or KernelSU app to manage all your settings dynamically.  
* **Zero Performance Impact:** Utilizes the native Android hosts file method, ensuring zero battery drain or CPU overhead.  
* **Dynamic & Systemless:** All modifications are applied systemlessly. Your system partition remains untouched.

## **How It Works**

L-Blocker leverages the power of the hosts file, a simple yet powerful mechanism within Android. In essence, the hosts file acts as a local address book for your device. Before connecting to any domain (e.g., ads.google.com), your device checks this file first.

L-Blocker replaces the standard, empty hosts file with a dynamically generated one filled with hundreds of thousands of known ad, tracker, and malicious domains. Each of these domains is redirected to 127.0.0.1—an address that points to your own device. When an app tries to connect to an ad server, it's sent on a fruitless journey to itself, and the connection fails instantly. The ad is never downloaded, and the tracker never reports back.

The real power of L-Blocker lies in its modularity. Based on your selections in the Control Panel, the module dynamically combines a **Main Profile** with any **Modular Add-ons** you've enabled, creating a final, customized hosts file perfectly tailored to your needs.

## **Configuration Profiles & Add-ons**

You are in full control. Start by choosing a Main Profile, then enhance it with any of the Modular Add-ons.

### **Main Profiles**

Select one of these as your base level of protection. Each profile includes everything from the one before it.

| Profile | Description |
| :---- | :---- |
| **Light** | The essential starter pack. Blocks common ads, trackers, and basic malware. Perfect for a fast and compatible experience with minimal risk of breaking websites. |
| **Pro** | The privacy-focused choice. Includes everything from *Light* and adds aggressive privacy trackers, fingerprinting domains, and extensive telemetry blocklists. |
| **Pro Plus** | The family-safe option. Includes everything from *Pro* and adds blocklists for adult content, gambling sites, fake news, and other potentially harmful content. |
| **Ultimate** | The absolute fortress. Includes everything from *Pro Plus* and adds blocklists for social media sites, streaming services, and more. For advanced users who want maximum control. |
| **Disabled** | Turns off all blocking. The hosts file will be empty. |

### **Modular Add-ons**

Enable any of these specialized modules on top of your chosen Main Profile.

| Add-on | Description |
| :---- | :---- |
| **DoH/Proxy Block** | Blocks services that try to bypass your DNS settings, such as DNS-over-HTTPS, proxies, and VPNs known for tracking. |
| **Aggressive Tracking** | An extra layer of blocking for the most aggressive and invasive tracking and digital fingerprinting domains. |
| **Vendor Telemetry** | Individual toggles to block data collection (telemetry) from specific vendors like Xiaomi, Samsung, Oppo/Realme, Huawei, and more. |

## **Requirements**

* Android 9 (Pie) or newer.  
* Magisk v24+ or any version of KernelSU.  
* **For Magisk users:** To access the Web Control Panel, you must install a companion module like **"Ksuwebui for Magisk"**.

## **Installation**

1. Download the latest L-Blocker-vX.X.X.zip from the [Releases](https://github.com/KepalaLuweng/L-Blocker/releases) page.  
2. Open Magisk or KernelSU Manager.  
3. Flash the downloaded ZIP file in the "Modules" section.  
4. Reboot your device.  
5. Open the Control Panel from the module list in your manager app to configure L-Blocker.

## **A Note on Ad-Blocking Limitations**

No single ad-blocking method is a silver bullet. Due to how some services are designed, L-Blocker (and any other DNS/hosts-based blocker) cannot block certain types of ads, such as:

* **YouTube Ads:** Video ads are served from the same domains as the videos themselves.  
* **Sponsored Posts:** Ads on platforms like Instagram, Facebook, and Twitter are delivered from the same domains as the main content.

For the most absolute ad-free experience, we recommend the following combination:

* **L-Blocker:** For powerful, system-wide protection.  
* **Firefox Browser with the uBlock Origin extension:** For browsing, as it can block more complex script-based ads and cosmetic elements on web pages.  
* **Modified Apps:** Using community-patched apps like YouTube ReVanced.

## **Credits and Acknowledgements**

This module would not be possible without the incredible, tireless work of the blocklist maintainers.

A huge and special thank you to **Hagezi** for providing the comprehensive, high-quality, and meticulously maintained blocklists that form the core of L-Blocker's power. Please consider supporting his work.

* [**Hagezi's DNS Blocklists on GitHub**](https://github.com/hagezi/dns-blocklists)

## **Author**

**Luweng Blocker (L-Blocker)** is developed and maintained by **KepalaLuweng**.

* [**YouTube**](https://www.youtube.com/@luwengtechid)  
* [**Telegram**](https://t.me/luwengtechofficial)  
* [**GitHub**](https://github.com/KepalaLuweng)
