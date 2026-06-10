# skin.DeepBlue
 Custom Kodi Skin (theme) with ocean blue theme. Based off the blue interface from DirecTV boxes (2006-2012) [a popular satellite TV provider in the United States]
 Check out a [Demo Here](https://youtu.be/8Nko1Uv-Hio)
 
 Want to support me? Please consider [Buying me a coffee ☕](https://www.buymeacoffee.com/UVGrade)
 shoot me any suggestions, new Kodi skins to work on, or other feedback at info@uvgrade.com
 Also check out our [Discord server](https://discord.gg/JbbaCEzE9z)

# Installation
## Auto Install - Repository URL
A repository is created for this Kodi addon and others I am working on. By adding the repository, you can easily install with the UI and will get automated updates as I push them out.
Repo is compatible with Kodi versions: v20, v21, v22

1. In Kodi, navigate to File Manager > Add Source > enter the URL: `https://kodi.uvgrade.com/install/`
2. Then: Go to Settings > Add-ons > Install from zip file → **repository.uvgrade-repository.uvgrade-1.0.0.zip.zip**
3. Then: Go to Settings > Add-ons > Install from Repository > "UVGrade" > navigate to look & feel

## Dev Setup
1. Ensure you have GIT installed on your OS and recommended to use VSCode
2. Copy the GIT URL from the main Github page
3. run the command `git clone <git URL>` either in your terminal or "Git Clone" in VSCode and select the Roaming Kodi directory
   - For windows `%appdata%\kodi\addons`
   - For Mac `~/Library/Application Support/Kodi/addons/`
   - For Linux `~/.kodi/userdata/addon_data/` or for SNAP Packages `~/snap/kodi/current/.kodi/addons/`
4. Then: Go to Settings > Interface > Skin > Skin and it should appear here

## Manual ZIP install of repo
1. Navigate to the [Kodi site](https://kodi.uvgrade.com/) and download the latest repository ZIP
2. Then: Go to Settings > Add-ons > Install from zip file → locate the ZIP file you downloaded from your *Downloads* folder

# Development
## Collaboration and Suggestions
Unfortunately I work a full time job and trying to start up a business. I started to work on the skin again but it will take some time. Happy to prioritize with a domation but time is not a luxury unfortunately.
If you would like to contribute, please make a branch and when complete, open a pull request into the Alpha branch


# Compatibility & branches
* branches with version numbers (eg. v20,v21) are for specific Kodi versions to retain compatibility. Upgrading from v20 to v21 just required a version change of xbmc.gui addon import from 5.15 to 5.17 in the MAIN addon.xml
* the main brnach and all others will utilize the latest version of Kodi (v21), development has NOT started on v22 yet.

# Notes
code for the live tv top bar is in Custom_1109_TopBarOverlay.xml
