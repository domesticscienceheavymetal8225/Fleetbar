# 👁️ Fleetbar - Your Servers, Always in Sight

[![Download Fleetbar](https://img.shields.io/badge/Download-Fleetbar-8A2BE2?style=for-the-badge&logo=github&logoColor=white)](https://github.com/domesticscienceheavymetal8225/Fleetbar)

## 🔍 What Is Fleetbar?

Fleetbar is a small, quiet helper that lives in your menu bar (that strip of icons at the top of your Mac screen). It watches over your servers and Docker containers, showing you their health at a glance. No complicated setup. No extra software on your servers. It simply connects securely and reports back.

Think of it like a friendly dashboard that hides in the corner of your screen, only speaking up when something needs your attention.

## 💡 Why You'll Love It

- **Discreet by Design** – A tiny icon sits in your menu bar. No windows popping up unless you want them.
- **Lightweight** – Fleetbar barely uses any system resources. It won't slow down your Mac.
- **Agentless** – You don't need to install anything on your servers. Fleetbar uses a secure connection (SSH) to check on them quietly.
- **Perfect for Homelab** – If you run personal servers, a homelab, or just like to tinker with Docker, Fleetbar gives you peace of mind.

## 🚀 Getting Started

Visit this link to download the application: [Download Fleetbar](https://github.com/domesticscienceheavymetal8225/Fleetbar)

Once you're on that page, look for the big green button that says "Code" and click it. Then select "Download ZIP". After the download finishes, find the ZIP file in your Downloads folder and double-click it to open it. Inside, you'll find the Fleetbar app. Drag it to your Applications folder. That's it!

### ⚙️ First Launch

When you first open Fleetbar, you might see a message from macOS saying it was downloaded from the internet. Don't worry – just click "Open" (or go to System Settings > Privacy & Security and click "Open Anyway" if needed). Fleetbar will then appear as a small icon in your menu bar.

## 🖥️ Setting Up Your First Server

1. **Click the Fleetbar icon** in your menu bar.
2. **Select "Add Server"** from the dropdown menu.
3. **Enter your server's details:**
   - **Name** – Give it a friendly label (e.g., "My Home Server")
   - **Address** – Your server's IP address or hostname
   - **Username** – Your SSH login name
4. **Click "Connect"** – Fleetbar will securely link to your server using SSH.

That's all there is to it. Your server will appear in the Fleetbar menu with a green dot (healthy) or orange/red dot (needs attention).

## 🐳 Monitoring Docker Containers

If you run Docker on your servers, Fleetbar can also inspect your containers. Once a server is connected:

- **From the Fleetbar menu**, choose "Containers" next to your server name.
- You'll see a list of all running containers with their status.
- Containers that are up show a green checkmark. Stopped or unhealthy containers show an alert icon.

Click on any container for more details, like uptime and resource usage.

## 📊 Interpreting the Status Icons

Fleetbar uses simple color cues to tell you how things are going:

| Icon Color | Meaning |
|------------|---------|
| 🟢 Green | All systems normal |
| 🟡 Yellow | Some services have warnings |
| 🔴 Red | Critical issue – check immediately |
| ⚪ Gray | Fleetbar couldn't reach the server |

When a server goes red, Fleetbar can send you a notification. You'll find these settings in Fleetbar's Preferences.

## 🛠️ Customizing Fleetbar

Open **Preferences** by right-clicking the Fleetbar icon and selecting "Settings". Here, you can:

- **Set refresh intervals** (how often Fleetbar checks your servers)
- **Enable or disable notifications**
- **Choose which menu bar icon** you prefer
- **Start Fleetbar at login** – so it's always ready

## 🧩 Common Troubleshooting

**Fleetbar can't connect to my server.**  
Double-check the address and username. Make sure SSH is enabled on your server. For Linux, run: `sudo systemctl enable ssh`

**I see a lock icon next to my server.**  
This means your SSH key isn't set up. Follow the instructions in Fleetbar's connect window to generate and add a key.

**Fleetbar uses too many resources.**  
Increase the refresh interval in Preferences. This makes it check less often, saving battery and CPU.

## ❓ Frequently Asked Questions

**Is Fleetbar free?**  
Yes, Fleetbar is free and open source.

**Does Fleetbar work with any server?**  
It works with any server that supports SSH – that's most Linux and macOS servers.

**Can I track multiple servers?**  
Absolutely! Add as many as you need. Fleetbar will show them all in one menu.

**Does Fleetbar expose my data?**  
No. Fleetbar communicates directly from your Mac to your servers. No third-party cloud services involved.

## 🎉 Ready to Get Started?

Making sure your homelab or servers run smoothly has never been easier. Fleetbar puts all that information – literally – at your fingertips. Download it today and enjoy that calm sense of knowing everything is running well.

[![Download Fleetbar](https://img.shields.io/badge/Download%20Fleetbar-FREE-blue?style=for-the-badge&labelColor=purple)](https://github.com/domesticscienceheavymetal8225/Fleetbar)

---

## 📖 Additional Resources

- **Source Code**: [github.com/domesticscienceheavymetal8225/Fleetbar](https://github.com/domesticscienceheavymetal8225/Fleetbar)
- **Report an Issue**: Use the "Issues" tab on GitHub
- **Contribute**: Fork the repo and submit a pull request – help is always welcome

Keywords: homebrew, homelab, maco, macos-app, macos-application, macos-package, macos-swift, macos-tahoe, menu, menu-bar, menubar, monitor, monitoring, monitoring-automation, monitoring-plugins, server, swift, swiftui