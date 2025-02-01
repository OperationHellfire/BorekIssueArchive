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
