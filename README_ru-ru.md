# Используйте CTRL+F для поиска ваших проблем

<div align="center">
<table>
  <tr>
    <td valign="center"><a href="README.md"><img src="https://github.com/twitter/twemoji/blob/master/assets/svg/1f1fa-1f1f8.svg" width="16"/> English</a></td>
    <td valign="center"><a href="README_pt-br.md"><img src="https://github.com/twitter/twemoji/blob/master/assets/svg/1f1e7-1f1f7.svg" width="16"/> Português (BR)</a></td>
    <td valign="center"><img src="https://github.com/twitter/twemoji/blob/master/assets/svg/1f1f7-1f1fa.svg" width="16"/> Русский</td>
    <td valign="center"><a href="README_ua-ua.md"><img src="https://github.com/Andrew1397/Ukraine/blob/main/Flag_of_Ukraine.png" width="16"/> Українська</a></td>
    <td valign="center"><a href="README_tr-TR.md"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b4/Flag_of_Turkey.svg/1920px-Flag_of_Turkey.svg.png" width="16"/> Türkçe</a></td>
  </tr>
</table>
</div>

---
# The file path of the injector program cannot contain special characters
### Эта ошибка может возникнуть по разным причинам.
Вы можете выполнить следующие шаги:
- Убедитесь, что в пути к папке Korepi нет символов или не-английских символов. Пример: измените `v1.2.1.0_fix1` на `v1.2.1.0fix1`.
- Если ошибка все еще появляется, убедитесь, что в пути также нет специальных символов. Пример: измените `C:\Users\youruser\Desktop\Exclusions_lol\Korepi` на `C:\Users\youruser\Desktop\Exclusionslol\Korepi`.

# The game path cannot contain special characters.
Почти то же самое, что и предыдущая ошибка:
- Проверьте путь к игре, если ваша игра установлена в `Program Files (x86)`, может возникнуть эта ошибка.
- Измените путь установки игры на путь без специальных символов.
Пример: измените `C:\Program Files (x86)\Genshin Impact\Genshin Impact game` на `C:\Program Files\Genshin Impact\Genshin Impact game`

## [Гайд]( https://youtu.be/NZhYB4Vxmlk?si=yPRP6dC2xMDUKDqm)

---

# Menu doesn't open
### Шаги для решения:
- Убедитесь, что вы правильно выполнили инъекцию, вы должны увидеть баннер с используемой версией после входа в мир.
- Убедитесь, что вы используете правильную клавишу, по умолчанию это `TAB`.
- Если у вас есть какие-либо оверлеи, отключите их перед запуском Korepi.
Например: `MSI After burner, GeForce Experience, Rivatuner и т.д.`

---

# Cannot verify current timestamp.
### Если вы видите это сообщение, выполните следующие шаги:
- Проверьте, что время на вашем ПК настроено на автоматическую синхронизацию.
- Если вы из ИРАНА, вам потребуется использовать VPN для использования Korepi.
- Если вы не из ИРАНА, попробуйте отключить VPN.

<div align="center">
  <a href="#"><img src="https://cdn.discordapp.com/attachments/1275059206130503682/1275064778615951403/timestamp.png?ex=679eb85c&is=679d66dc&hm=04da13041b2709eef5c03703b3f385281932c83006d4ba1bdacd8bbdffc6474c&"></a>
</div>

---

# Failed to create game process with Error 5.
Если вы получаете эту ошибку, убедитесь, что вы выбрали правильный файл игры.
- Выберите файл игры заново, удалив `cfg.ini` в папке Korepi и запустив Korepi снова.

---

# File contains virus or potentially unwanted software.
### Если вы получаете эту ошибку, выполните следующие шаги:
- Отключите антивирус.
- Убедитесь, что ваша папка Korepi добавлена в исключения. [Как добавить в исключения](https://korepi.com/en/guide/virus.html).

---

# Process crashed, exit code 0xc000005.
### Если вы получаете эту ошибку, выполните следующие шаги:
- Скачайте [этот файл](https://cdn.discordapp.com/attachments/1251244897831227546/1285657688092573797/envSettingfirst_run_this_for_admin.exe?ex=66eb1187&is=66e9c007&hm=d3322d5db0c6828de7b562f98d1bfd17bd64c45763b60e5298833f82b993dca3&), переместите его в папку Korepi и запустите от имени администратора.
Если это не помогло:
- Откройте командную строку от имени администратора и введите следующую команду `sfc /scannow`
- После этого, если были найдены ошибки, перезагрузите компьютер и проверьте. Если после перезагрузки не помогло или ошибок не было найдено, введите эту команду `DISM.exe /Online /Cleanup-Image /RestoreHealth`
- После завершения проверок перезагрузите компьютер и проверьте.

Если это не помогло, переустановите Windows.

---

# ImGUI: DirectX11 backend initialized successfully.
### Если вы получаете эту ошибку, выполните следующие шаги:
- Ошибка возникает из-за установленных тем, удалите папку themes.

---

# File ok.
### Если вы получаете эту ошибку, выполните следующие шаги:
- Иногда нужно открыть лаунчер несколько раз, прежде чем он заработает.
- Удалите ваш cfg.json, возможно, с файлом что-то не так.

---

# If you get stuck here, please restart your computer and try again.
### Если вы получаете эту ошибку, выполните следующие шаги:
- Вам нужно настроить время на вашем ПК на автоматическую синхронизацию.
- Отключите все антивирусы.

<div align="center">
  <a href="#"><img src="https://cdn.discordapp.com/attachments/1275059206130503682/1275077076239781978/image.png?ex=679ec3d0&is=679d7250&hm=20f8006d55341e61683b8952df4582d50127af3d3ced71d552109651d29239cb&"></a>
</div>

---

# Error 31-4302.
### Если вы получаете эту ошибку, выполните следующие шаги:
- Удалите cfg.json
- Откройте лаунчер, нажмите на 3 полоски и нажмите "Repair Now"

---

# File corrupted! This program has been manipulated and maybe it's infected.
### Если вы получаете эту ошибку, выполните следующие шаги:
- В этом случае вы можете попробовать использовать Malware Bytes или Dr.Web для полного сканирования, если найдены вирусы, удалите их, перезагрузите компьютер и попробуйте снова. Если это не поможет, переустановка Windows - самый простой способ решить эту проблему.

<div align="center">
  <a href="#"><img src="https://cdn.discordapp.com/attachments/1275059206130503682/1275081666548727938/virus2.png?ex=679ec817&is=679d7697&hm=0d874838a433367eb472a0cd02722752c3e177806ee30206ae9da2f7961a15cf&"></a>
</div>

---

# The system did not detect MSVCP140.dll.
### Если вы получаете эту ошибку, выполните следующие шаги:
- Обновите [Microsoft Visual Studio C++](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170#visual-studio-2015-2017-2019-and-2022)
- Обновите [DirectX](https://www.microsoft.com/en-us/download/details.aspx?id=35)

---

# The key file not found, please join discord channel....The key file and the korepi program are free, if you bought it, then you are cheated.
### Если вы получаете эту ошибку, выполните следующие шаги:
- Получите enc.json снова, используя [руководство](https://discord.com/channels/1251244897021722735/1266776966808207464)

<div align="center">
  <a href="#"><img src="https://cdn.discordapp.com/attachments/1275059206130503682/1275103624711901350/image.png?ex=679edc8a&is=679d8b0a&hm=216cc76e1224d775442eb2db0ca750ab73b8501e8b5f0dc5ddd88350ccec27d1&"></a>
</div>

---

# MD5 not match, please the get key file again.
### Если вы получаете эту ошибку, выполните следующие шаги:
- Получите enc.json снова, используя [руководство](https://discord.com/channels/1251244897021722735/1266776966808207464)

<div align="center">
  <a href="#"><img src="https://cdn.discordapp.com/attachments/1275059206130503682/1275404199005524055/image.png?ex=679ea2f8&is=679d5178&hm=9106e236866d95f94bd9e178d334b40a262ac7d16b01bbb54807911f4543ec5c&"></a>
</div>

---

# Error at hooking API "LoadStringA"
### Если вы получаете эту ошибку, выполните следующие шаги:
- Перезагрузите компьютер.
- Откройте командную строку от имени администратора и введите следующую команду `sfc /scannow`
- После этого, если были найдены ошибки, перезагрузите компьютер и проверьте. Если после перезагрузки не помогло или ошибок не было найдено, введите эту команду `DISM.exe /Online /Cleanup-Image /RestoreHealth`
- После завершения проверок перезагрузите компьютер и проверьте.

<div align="center">
  <a href="#"><img src="https://cdn.discordapp.com/attachments/1275059206130503682/1275802750600609874/image.png?ex=679ec4a7&is=679d7327&hm=7e7734bc99f5f77b53318159fd095d3308ccaa0c3e741111ab363f8767ebb172&"></a>
</div>

---

# Too many requests. Please try again later.
### Если вы получаете эту ошибку, выполните следующие шаги:
- Откройте Regedit и перейдите по пути `"HKEY_CURRENT_USER\Software"` и удалите папку `"miHoYoSDK"`. В той же директории удалите папку `"Genshin Impact"` в папке `"miHoYo"`.
- Используйте любой VPN.

Если это не помогает, подождите и попробуйте снова.

<div align="center">
  <a href="#"><img src="https://cdn.discordapp.com/attachments/1275059206130503682/1278296319768793109/image.png?ex=679f4538&is=679df3b8&hm=f49ac4d4d9aed4799ead82378cf90790303f760ee6b042b496b341af5288f881&"></a>
</div>

---

# Successfully added DLL folder to system PATH
### Если вы получаете эту ошибку, выполните следующие шаги:
- Скачайте [этот файл](https://cdn.discordapp.com/attachments/644953856551288842/1281302256938909878/cfg.ini?ex=66db3937&is=66d9e7b7&hm=955d71931316a4ac99819c2498e1b1c9c99508cca9929db473d27e4482bf188a&) и переместите его в папку Korepi с заменой, затем укажите EXE файл игры.

<div align="center">
  <a href="#"><img src="https://cdn.discordapp.com/attachments/1275059206130503682/1281326539908321340/image.png?ex=679f1695&is=679dc515&hm=455d4f2b264eddf1ce545cd02c20f7cce9f2ed0338e912b0caa07647496a7034&"></a>
</div>

---

# The procedure entry point BIO_new_mem_buf could not be located in the dynamic link library libcrypto-1_1-x64.dll
### Если вы получаете эту ошибку, выполните следующие шаги:
- Скачайте [файл](https://cdn.discordapp.com/attachments/1275059206130503682/1281327851265593424/envSettingfirst_run_this.exe?ex=679f17cd&is=679dc64d&hm=c437b449e8d418f304dfb5bc9f1b1a138c779a8d1df3ffc1deff31ce3ef703a0&), переместите его в папку korepi и запустите от имени администратора.

<div align="center">
  <a href="#"><img src="https://cdn.discordapp.com/attachments/1275059206130503682/1281327851098079294/image.png?ex=679f17cd&is=679dc64d&hm=b14d58930cf2f840e5cdc369dd717730af5595eccf0a0697d4584fa1442de1b3&"></a>
</div>

---

# Process crashed, exit code: 0xc00000005 
- **Запустите envSetting от имени администратора.**

<div align="center">
  <a href="#"><img src="https://cdn.discordapp.com/attachments/1275059206130503682/1291687281543086100/image.png?ex=679f3506&is=679de386&hm=2ba14828a7f38cc5b20ed513e39caa7d7a04ea54fdf355e884ea4273def68a50&"></a>
</div>

---

# Card has expired!
### Если вы получаете эту ошибку, выполните следующие шаги:
- Получите новый enc.json.

<div align="center">
  <a href="#"><img src="https://cdn.discordapp.com/attachments/1275059206130503682/1304160405534539816/image.png?ex=679f19c6&is=679dc846&hm=f66ca62e3dbf1fe504cb9db427f70aaf2faa2ce65ad3efd9f0b75830044d4b40&"></a>
</div>

---

# No matching DLL path found in the system path.
### Если вы получаете эту ошибку, выполните следующие шаги:
- Перезагрузите ПК

<div align="center">
  <a href="#"><img src="https://cdn.discordapp.com/attachments/1275059206130503682/1304160633763397682/image.png?ex=679f19fd&is=679dc87d&hm=6e00fa35ab96f9d58b2058926f2af725154fd4e15673867284dd958ef855a9d3&"></a>
</div>

---

# Prompt (Auto-close in 5s)
### Если вы получаете эту ошибку, выполните следующие шаги:
- Скачайте [Library VC](https://aka.ms/vs/17/release/vc_redist.x64.exe)

<div align="center">
  <a href="#"><img src="https://cdn.discordapp.com/attachments/1275059206130503682/1304371238734397461/image.png?ex=679f3561&is=679de3e1&hm=ac4a1b558540b71b70c0a6ed07e6f68ea353787410117f62a1c8164de9087cf0&"></a>
</div>

---

# SPKEY has expired, Please go to the website or the robot terminal to claim again
### Если вы получаете эту ошибку, выполните следующие шаги:
Вам нужно обновить ваш SPKEY
- [Нажмите здесь](https://discord.com/channels/1251244897021722735/1255892075371827313/1295311329040666727) или перейдите сюда: [Verification](https://discord.com/channels/1251244897021722735/1255892075371827313) и выберите **`Receive SP Key`**, а затем **`Query SP Key`**.
Требуется роль **`PERTAMAX`** для использования.

- Если используете лаунчер, просто нажмите `Renew SPKey`.

<div align="center">
  <a href="#"><img src="https://cdn.discordapp.com/attachments/1275059206130503682/1306547825156558848/image.png?ex=679f377c&is=679de5fc&hm=29296dedaf1dae69bb45c9706085fb43e6cd8d2ee53a8ef3a981317fc8131847&"></a>
</div>

---

# Subscription status abnormal (Subscription Expire) | (Subscription Paused)
### Если вы получаете эту распространенную ошибку, выполните следующие шаги:
- Если вы получаете `(Subscription Expire)`, сначала удалите ваш старый `enc.json` и снова `привяжите бесплатный ключ` в [Verification](https://discord.com/channels/1251244897021722735/1255892075371827313) или используйте это [видео руководство](https://youtu.be/ljOjDE79QD0), если забыли как это сделать.

- Если вы получаете `(Subscription Paused)`, очевидно, вы забыли возобновить ваш ключ pertamax... попробуйте возобновить ключ в [Verification](https://discord.com/channels/1251244897021722735/1255892075371827313), если хотите продолжить его использование.

<div align="center">
  <a href="#"><img src="https://cdn.discordapp.com/attachments/1275059206130503682/1314071983784460298/image.png?ex=679ee767&is=679d95e7&hm=fdab4b5c8c5100a8a74907ab764ba9804b387f788949697ec5bc7c0a05629242&"></a>
</div>

---

# Waiting for 0ms before injecting the Korepi dll
### Если вы получаете эту ошибку, выполните следующие шаги:
- Попробуйте удалить ваш `cfg.ini` и затем запустите korepi снова для генерации нового.


<div align="center">
  <a href="#"><img src="https://cdn.discordapp.com/attachments/1275059206130503682/1314074148510634014/image.png?ex=679ee96b&is=679d97eb&hm=510ac680f7ebd167974bb4f34768b63e2d94c7b319e0225969e095e83c02c90f&"></a>
</div>

---

# [504 Gateaway Timeout | Server connection failed | Timeout was reached]
- Здесь нечего больше сказать. В настоящее время возникла проблема с сервером/сервисом, вам нужно подождать, пока она будет исправлена.
Редкое явление, оно влияет на все, что связано с korepi и сервисами на этом сервере, поэтому наберитесь терпения, пока это не будет исправлено, нет оценки, сколько это займет времени.

- Но если по какой-то причине статус нормальный и сервис/сервер работает, можно попробовать использовать VPN [CouldFlare Warp+](https://one.one.one.one/).

---

# VirtualAllocEX Error[5]
### Если вы получаете эту ошибку, выполните следующие шаги:
Полагаю, это почти то же самое, что и раньше. Но вы можете попробовать использовать AIO на этот раз
- Сначала попробуйте перезагрузить ваш компьютер и посмотрите, поможет ли это.
- Если нет, попробуйте скачать [Visual C++ Redistributable Runtimes All-in-One](https://www.techpowerup.com/download/visual-c-redistributable-runtime-package-all-in-one/) и установить его.

---

# msg: ??ID???? (data ID not match)
### Если вы получаете эту ошибку, выполните следующие шаги:
Это происходит, когда вы меняете компьютер, переустанавливаете Windows или используете HWID spoofer/HWID changer. И он не совпадает с hardwareID вашего устройства с вашим аккаунтом Discord.
- Сначала скачайте [это](https://cdn.discordapp.com/attachments/1251244897831227544/1314549647892807700/get_hwid.exe?ex=67542d43&is=6752dbc3&hm=9fd1f5893728e094bfa2801fe7c1f744631b2a32086d8859589713d7729d8443&), затем запустите. Оно должно показать вам ваш текущий hwid, скопируйте его.
- Перейдите в [Verification](https://discord.com/channels/1251244897021722735/1255892075371827313), затем выберите `Change HWID` и вставьте новый hwid в поле и нажмите `Submit`

## Если вы собираетесь использовать лаунчер [для pertamax]
он автоматически изменит hwid на текущее устройство.
- Откройте Korepi Launcher
- Нажмите `Reset HWID`, решите математический пример и нажмите `Confirm`

---

# Blank Command prompt/Inject ok. 
**Эта проблема возникает из-за отсутствия c++ или ошибки сети.**

- Скачайте [VCRedist AIO](https://github.com/abbodi1406/vcredist/releases/download/v0.85.0/VisualCppRedist_AIO_x86_x64.exe)(если запрашивает ремонт, выполните его.)
- Если первое решение не сработало, попробуйте использовать vpn или [1.1.1.1](https://one.one.one.one/) (Warp)
- Если это тоже не работает, возможно, вирус/антивирус мешает работе korepi. Отключите все антивирусы, установите malwarebyte для сканирования на вирусы.
- Переустановите Windows, если все решения не помогают.

--- 