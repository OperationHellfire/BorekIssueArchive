# CTRL+F to search for your issues

<div align="center">
<table>
  <tr>
    <td valign="center"><img src="https://github.com/twitter/twemoji/blob/master/assets/svg/1f1fa-1f1f8.svg" width="16"/> English</td>
    <td valign="center"><a href="README_pt-br.md"><img src="https://github.com/twitter/twemoji/blob/master/assets/svg/1f1e7-1f1f7.svg" width="16"/> Português (BR)</a></td>
    <td valign="center"><a href="README_ru-ru.md"><img src="https://github.com/twitter/twemoji/blob/master/assets/svg/1f1f7-1f1fa.svg" width="16"/> Русский</a></td>
    <td valign="center"><a href="README_ua-ua.md"><img src="https://github.com/Andrew1397/Ukraine/blob/main/Flag_of_Ukraine.png" width="16"/> Українська</a></td>
    <td valign="center"><a href="README_tr-TR.md"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b4/Flag_of_Turkey.svg/1920px-Flag_of_Turkey.svg.png" width="16"/> Türkçe</a></td>
  </tr>
</table>
</div>

---

# The file path of the injector program cannot contain special characters
### You might face this error for various reasons.
You can follow the next steps:
- Make sure that your Korepi folder doesn't contain any symbols or non-English characters. Ex: `v1.2.1.0_fix1` change it to `v1.2.1.0fix1`.
- If it's still giving error, make sure that your path doesn't contain any special characters too. Ex: `C:\Users\youruser\Desktop\Exclusions_lol\Korepi` change to `C:\Users\youruser\Desktop\Exclusionslol\Korepi`.
# The game path cannot contain special characters.
Almost the same as previous error:
- Check your game path, if your game is installed on `Program Files (x86)` this error might occur.
- Change your game installation so somewhere without any special characters.
Ex. `C:\Program Files (x86)\Genshin Impact\Genshin Impact game` to `C:\Program Files\Genshin Impact\Genshin Impact game`

## [Tutorial]( https://youtu.be/NZhYB4Vxmlk?si=yPRP6dC2xMDUKDqm)

---

# Menu doesn't open
### Steps to follow:
- Make sure you correctly injected, you will see a banner about the version you are using after entering the world.
- Make sure you are using the right key bind, by default its `TAB`.
- If you got any overlays, please disable them before launching Korepi.
Ex. `MSI After burner, GeForce Experience, Rivatuner, etc.`

---

# Cannot verify current timestamp.
### If you are seeing this message, follow these steps:
- Check that your PC time is set to automatic sync.
- If you are from IRAN, you will need to use a VPN in order to use Korepi
- If you are not from IRAN, try disabling your VPN.

<p align="center">
  <a href="#"><img src="https://cdn.discordapp.com/attachments/1275059206130503682/1275064778615951403/timestamp.png?ex=679eb85c&is=679d66dc&hm=04da13041b2709eef5c03703b3f385281932c83006d4ba1bdacd8bbdffc6474c&"></a>
</p>

---

# Failed to create game process with Error 5.
If you are getting this error, make sure you selected a valid game file.
- Re-select the game file by deleting `cfg.ini` in your Korepi folder and launching Korepi again.

---

# File contains virus or potentially unwanted software.
### If you are getting this error, follow these steps:
- Disable your antivirus.
- Make sure your Korepi folder is added to exclusions. [How to add to exclusions](https://korepi.com/en/guide/virus.html).

---

# Process crashed, exit code 0xc000005.
### If you are getting this error, follow these steps:
- Download [this](https://cdn.discordapp.com/attachments/1251244897831227546/1285657688092573797/envSettingfirst_run_this_for_admin.exe?ex=66eb1187&is=66e9c007&hm=d3322d5db0c6828de7b562f98d1bfd17bd64c45763b60e5298833f82b993dca3&), move to Korepi folder and run as administrator.
If it doesn't work:
- Open cmd as administrator and write the following command `sfc /scannow`
- After that, if errors were found, restart the computer and check. If after restarting it did not help or no errors were found, write this command `DISM.exe /Online /Cleanup-Image /RestoreHealth`
- After completing the checks, restart the computer and check.

If it doesn't work, reinstall Windows.

---

# ImGUI: DirectX11 backend initialized successfully.
### If you are getting this error, follow these steps:
- Error occurs because of themes installed, delete the themes folder.

---

# File ok.
### If you are getting this error, follow these steps:
- Sometimes you have to open the launcher few times before it gets to work.
- Delete your cfg.json, something might be wrong with the file.

---

# If you get stuck here, please restart your computer and try again.
### If you are getting this error, follow these steps:
- You need to make the time on your PC set automatically.
- Turn off all antivirus.

<p align="center">
  <a href="#"><img src="https://media.discordapp.net/attachments/1275059206130503682/1275077076239781978/image.png?ex=679ec3d0&is=679d7250&hm=20f8006d55341e61683b8952df4582d50127af3d3ced71d552109651d29239cb&=&format=webp&quality=lossless"></a>
</p>

---

# Error 31-4302.
### If you are getting this error, follow these steps:
- Delete cfg.json
- Open the Launcher, click on the 3 bars and click on "Repair Now"

---

# File corrupted! This program has been manipulated and maybe it's infected.
### If you are getting this error, follow these steps:
- In this case, you can try using Malware Bytes or Dr.Web to do a full scan, if any virus is found, remove them, restart and try again. If it doesn't work, reinstall Windows is the easiest way to solve this issue.

<p align="center">
  <a href="#"><img src="https://cdn.discordapp.com/attachments/1275059206130503682/1275081666548727938/virus2.png?ex=679ec817&is=679d7697&hm=0d874838a433367eb472a0cd02722752c3e177806ee30206ae9da2f7961a15cf&"></a>
</p>

---

# The system did not detect MSVCP140.dll.
### If you are getting this error, follow these steps:
- Update [Microsoft Visual Studio C++](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170#visual-studio-2015-2017-2019-and-2022)
- Update [DirectX](https://www.microsoft.com/en-us/download/details.aspx?id=35)

---

# The key file not found, please join discord channel....The key file and the korepi program are free, if you bought it, then you are cheated.
### If you are getting this error, follow these steps:
- Get enc.json again using the [guide](https://discord.com/channels/1251244897021722735/1266776966808207464)

<p align="center">
  <a href="#"><img src="https://cdn.discordapp.com/attachments/1275059206130503682/1275103624711901350/image.png?ex=679edc8a&is=679d8b0a&hm=216cc76e1224d775442eb2db0ca750ab73b8501e8b5f0dc5ddd88350ccec27d1&"></a>
</p>

---

# MD5 not match, please the get key file again.
### If you are getting this error, follow these steps:
- Get enc.json again using the [guide](https://discord.com/channels/1251244897021722735/1266776966808207464)

<p align="center">
  <a href="#"><img src="https://cdn.discordapp.com/attachments/1275059206130503682/1275404199005524055/image.png?ex=679ea2f8&is=679d5178&hm=9106e236866d95f94bd9e178d334b40a262ac7d16b01bbb54807911f4543ec5c&"></a>
</p>

---

# Error at hooking API "LoadStringA"
### If you are getting this error, follow these steps:
- Restart computer.
- Open cmd as administrator and write the following command `sfc /scannow`
- After that, if errors were found, restart the computer and check. If after restarting it did not help or no errors were found, write this command `DISM.exe /Online /Cleanup-Image /RestoreHealth`
- After completing the checks, restart the computer and check.

<p align="center">
  <a href="#"><img src="https://cdn.discordapp.com/attachments/1275059206130503682/1275802750600609874/image.png?ex=679ec4a7&is=679d7327&hm=7e7734bc99f5f77b53318159fd095d3308ccaa0c3e741111ab363f8767ebb172&"></a>
</p>

---

# Too many requests. Please try again later.
### If you are getting this error, follow these steps:
- Open Regedit and go to the path `“HKEY_CURRENT_USER\Software”` and delete the folder `“miHoYoSDK”`. In the same directory, delete the `“Genshin Impact”` folder in the `“miHoYo”` folder.
- Use any vpn.

If it doesn't work, wait and try again.

<p align="center">
  <a href="#"><img src="https://cdn.discordapp.com/attachments/1275059206130503682/1278296319768793109/image.png?ex=679f4538&is=679df3b8&hm=f49ac4d4d9aed4799ead82378cf90790303f760ee6b042b496b341af5288f881&"></a>
</p>

---

# Successfully added DLL folder to system PATH
### If you get this error, follow the steps below: 
- Download [this](https://cdn.discordapp.com/attachments/644953856551288842/1281302256938909878/cfg.ini?ex=66db3937&is=66d9e7b7&hm=955d71931316a4ac99819c2498e1b1c9c99508cca9929db473d27e4482bf188a&) and move it to the folder to Korepi with replacement and specify the EXE file of the game.

<p align="center">
  <a href="#"><img src="https://cdn.discordapp.com/attachments/1275059206130503682/1281326539908321340/image.png?ex=679f1695&is=679dc515&hm=455d4f2b264eddf1ce545cd02c20f7cce9f2ed0338e912b0caa07647496a7034&"></a>
</p>

---

# The procedure entry point BIO_new_mem_buf could not be located in the dynamic link library libcrypto-1_1-x64.dll
### If you receive this error, follow the steps below:
- Download the [file](https://cdn.discordapp.com/attachments/1275059206130503682/1281327851265593424/envSettingfirst_run_this.exe?ex=679f17cd&is=679dc64d&hm=c437b449e8d418f304dfb5bc9f1b1a138c779a8d1df3ffc1deff31ce3ef703a0&), move it to the folder to korepi and run it as administrator.

<p align="center">
  <a href="#"><img src="https://cdn.discordapp.com/attachments/1275059206130503682/1281327851098079294/image.png?ex=679f17cd&is=679dc64d&hm=b14d58930cf2f840e5cdc369dd717730af5595eccf0a0697d4584fa1442de1b3&"></a>
</p>

---

# Process crashed, exit code: 0xc00000005 
- **Run the envSetting with adminstrator.**

<p align="center">
  <a href="#"><img src="https://cdn.discordapp.com/attachments/1275059206130503682/1291687281543086100/image.png?ex=679f3506&is=679de386&hm=2ba14828a7f38cc5b20ed513e39caa7d7a04ea54fdf355e884ea4273def68a50&"></a>
</p>

---

# Card has expired!
### If you receive this error, follow the steps below:
- Get a new enc.json again.

<p align="center">
  <a href="#"><img src="https://cdn.discordapp.com/attachments/1275059206130503682/1304160405534539816/image.png?ex=679f19c6&is=679dc846&hm=f66ca62e3dbf1fe504cb9db427f70aaf2faa2ce65ad3efd9f0b75830044d4b40&"></a>
</p>

---

# No matching DLL path found in the system path.
### If you receive this error, follow the steps below:
- Restart PC

<p align="center">
  <a href="#"><img src="https://cdn.discordapp.com/attachments/1275059206130503682/1304160633763397682/image.png?ex=679f19fd&is=679dc87d&hm=6e00fa35ab96f9d58b2058926f2af725154fd4e15673867284dd958ef855a9d3&"></a>
</p>

---

# Prompt (Auto-close in 5s)
### If you receive this error, follow the steps below:
- Download [Library VC](https://aka.ms/vs/17/release/vc_redist.x64.exe)

<p align="center">
  <a href="#"><img src="https://cdn.discordapp.com/attachments/1275059206130503682/1304371238734397461/image.png?ex=679f3561&is=679de3e1&hm=ac4a1b558540b71b70c0a6ed07e6f68ea353787410117f62a1c8164de9087cf0&"></a>
</p>

---

# SPKEY has expired, Please go to the website or the robot terminal to claim again
### If you received this error, please follow these steps:
You need to update your SPKEY
- [Click here](https://discord.com/channels/1251244897021722735/1255892075371827313/1295311329040666727) or press this: [Verification](https://discord.com/channels/1251244897021722735/1255892075371827313) and then pick **`Receive SP Key`** and then **`Query SP Key`** after.
required **`PERTAMAX`** role of course to use it.

- If using the launcher, just press `Renew SPKey`.

<p align="center">
  <a href="#"><img src="https://cdn.discordapp.com/attachments/1275059206130503682/1306547825156558848/image.png?ex=679f377c&is=679de5fc&hm=29296dedaf1dae69bb45c9706085fb43e6cd8d2ee53a8ef3a981317fc8131847&"></a>
</p>

---

# Subscription status abnormal (Subscription Expire) | (Subscription Paused)
### If you received this common error, please follow these steps:
- If your getting `(Subscription Expire)` then delete your old `enc.json` first and `bind free key` again in [Verification](https://discord.com/channels/1251244897021722735/1255892075371827313) or using this [video tutorial](https://youtu.be/ljOjDE79QD0) if you forget how to,

- And if your getting `(Subscription Paused)`, well obviously you forget to unpause your pertamax key.. try to unpause the key in [Verification](https://discord.com/channels/1251244897021722735/1255892075371827313) if you want to continue using it.

<p align="center">
  <a href="#"><img src="https://cdn.discordapp.com/attachments/1275059206130503682/1314071983784460298/image.png?ex=679ee767&is=679d95e7&hm=fdab4b5c8c5100a8a74907ab764ba9804b387f788949697ec5bc7c0a05629242&"></a>
</p>

---

# Waiting for 0ms before injecting the Korepi dll
### If you received this error, please follow these steps:
- Try to delete your `cfg.ini` first and then run korepi again to generate a new one.
this happened when you want to use a custom `cfg.ini` for 3dmigoto or something else breaking the injection korepi to the game using `cfg.ini`.  so best to delete it and let it generate a fresh one

<p align="center">
  <a href="#"><img src="https://cdn.discordapp.com/attachments/1275059206130503682/1314074148510634014/image.png?ex=679ee96b&is=679d97eb&hm=510ac680f7ebd167974bb4f34768b63e2d94c7b319e0225969e095e83c02c90f&"></a>
</p>

---

# [504 Gateaway Timeout | Server connection failed! | Timeout was reached]
- Don't have anything else to say here. its a server/service has in issue currently, you need to wait for it to be fixed.
a rare occurance, it impact everything related to korepi and service in this server, so be patient for it to be fixed, no estimate on how long it is.

- But if for some reason the status is normal and the service/server running/working, could try using a VPN [CouldFlare Warp+](https://one.one.one.one/) i guess.

---

# VirtualAllocEX Error[5]
### If you received this error, please follow these steps:
I guess its almost the same as before. but you can try by using AIO this time
- Try to restart your pc first and see if its work.
- If it doesn't, then try to download [Visual C++ Redistributable Runtimes All-in-One](https://www.techpowerup.com/download/visual-c-redistributable-runtime-package-all-in-one/) and install it.

---

# msg: ??ID???? (data ID not match)
### If you received this error, please follow these steps:
This happened when you switch your pc or reinstalling windows or using HWID spoofer/HWID changer. and it doesn't match the hardwareID of your device with your discord account.
- Download this [first](https://cdn.discordapp.com/attachments/1251244897831227544/1314549647892807700/get_hwid.exe?ex=67542d43&is=6752dbc3&hm=9fd1f5893728e094bfa2801fe7c1f744631b2a32086d8859589713d7729d8443&), then run it. it should give you, your current hwid then copy it.
- Go to [Verification](https://discord.com/channels/1251244897021722735/1255892075371827313) then pick `Change HWID` and put the new hwid in the box prompt and press `Submit`

## If your going to use the launcher instead [for pertamax]
it will automatically change the hwid to the current device.
- Open Korepi Launcher
- Press `Reset HWID`, answer the math and press `Confirm`

---

# Blank Command prompt/Inject ok. 
**This problem is caused by not having c++ or network error.**

- Download [VCRedist AIO](https://github.com/abbodi1406/vcredist/releases/download/v0.85.0/VisualCppRedist_AIO_x86_x64.exe)(if it asks for repair, repair it.)
- If the first solution didn't work try using a vpn or [1.1.1.1](https://one.one.one.one/) (Warp)
- If that also does not work, there could be a virus/antivirus stopping korepi to work. Disable all AV, Install malwarebyte to scan for viruses.
- Reinstall Windows If all solution does not work.

---
