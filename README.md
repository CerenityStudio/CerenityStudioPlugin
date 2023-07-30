# CerenityStudioPlugin
- Tools for **Remove Unused Asset** (Resource, Unused from Editor/Game, Clear Cache).
- Tools for **Build AssetBundles** (download patch data/load data from Server).
- Tools for **Setup NewFolder** when you're creating a new Project.
- **Discord Rich Presence Plugin** (made by Claytoo, please check below for how to use it).

#
## **Discord Rich Presence by Claytoo**
a Discord Rich Presence Plugin for your game (Unity3D Game Engine)

### **About**
I'm made this Plugin using **DiscordRichPresenceSDK** package.

This *Plugin Configuration* is on *Inspector*, so you can attach it to any spesific *Scene* (using Prefabs)

### **Getting Started**

***THIS PLUGIN IS NOT WORKING ON WEBGL BUILD, PLEASE EXCLUDE FROM BUILD OR REMOVE IT***

Go to Discord [Developer Application](https://discord.com/developers/applications/) and make a New Application

![alt img](https://cdn.discordapp.com/attachments/784761936230744074/943572752785354802/unknown.png)

Then go to **OAuth2** > **General**

![](https://cdn.discordapp.com/attachments/784761936230744074/943576587901743164/unknown.png)

After that go to **Redirect** section and click **Add Redirect**

![](https://cdn.discordapp.com/attachments/784761936230744074/943577086914871376/unknown.png)

Put the redirect link that we want to use, which is **http://127.0.0.1** then click **Save Changes** on the bottom

![](https://cdn.discordapp.com/attachments/784761936230744074/943577855026147488/unknown.png)

Go to your Unity Project, then open  the prefab located at **Assets/CerenityStudio/Prefabs/csDiscordManager** then drag to your scene

Look at the Inspector, change the **Application ID** with your CLIENT ID, CLIENT ID is located on **OAuth2** > **General**

![](https://cdn.discordapp.com/attachments/784761936230744074/1135285599373377626/Screenshot_2023-07-31_at_01.59.13.png)
![](https://cdn.discordapp.com/attachments/784761936230744074/943582726097862676/unknown.png)


This is How to Configure your Discord Rich Presence Status
- **Details** is for Details
- **State** is for State
- **Large Image** is for Large Image Name that you upload on Discord Developer Application **Rich Presence** > **Art Assets** > **Rich Presence Assets**
- **Large Text** is for text details on Large Image
- **Small Image** is for Small Image Name that you upload on Discord Developer Application **Rich Presence** > **Art Assets** > **Rich Presence Assets**
- **Small Text** is for text details on Small Image

****You can see how to putting an image down below on Optional Section***

### **Here is the result**

Discord RP Preview

![](https://cdn.discordapp.com/attachments/784761936230744074/943584812512469042/unknown.png)

### ***This is optional*** 
After that go to **Rich Presence** > **Art Assets**

![](https://cdn.discordapp.com/attachments/784761936230744074/943579215855501392/unknown.png)

Then click on **Rich Presence Invite Image** for changing Invite Image or **Rich Presence Assets** for changing RPS Image

![](https://cdn.discordapp.com/attachments/784761936230744074/943579702428307456/unknown.png)

**Examples**

![](https://cdn.discordapp.com/attachments/784761936230744074/943586620714659900/unknown.png)

****remember, file name is used on Unity Inspector***
