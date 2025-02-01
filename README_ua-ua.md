# Використовуйте CTRL+F для пошуку ваших проблем

<div align="center">
<table>
  <tr>
    <td valign="center"><a href="README.md"><img src="https://github.com/twitter/twemoji/blob/master/assets/svg/1f1fa-1f1f8.svg" width="16"/> English</a></td>
    <td valign="center"><a href="README_pt-br.md"><img src="https://github.com/twitter/twemoji/blob/master/assets/svg/1f1e7-1f1f7.svg" width="16"/> Português (BR)</a></td>
    <td valign="center"><a href="README_ru-ru.md"><img src="https://github.com/twitter/twemoji/blob/master/assets/svg/1f1f7-1f1fa.svg" width="16"/> Русский</a></td>
    <td valign="center"><img src="https://github.com/Andrew1397/Ukraine/blob/main/Flag_of_Ukraine.png" width="16"/> Українська</td>
    <td valign="center"><a href="README_tr-TR.md"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b4/Flag_of_Turkey.svg/1920px-Flag_of_Turkey.svg.png" width="16"/> Türkçe</a></td>
  </tr>
</table>
</div>

---
# The file path of the injector program cannot contain special characters
### Ця помилка може виникнути з різних причин.
Ви можете виконати наступні кроки:
- Переконайтеся, що в шляху до папки Korepi немає символів або не-англійських символів. Приклад: змініть `v1.2.1.0_fix1` на `v1.2.1.0fix1`.
- Якщо помилка все ще з'являється, переконайтеся, що в шляху також немає спеціальних символів. Приклад: змініть `C:\Users\youruser\Desktop\Exclusions_lol\Korepi` на `C:\Users\youruser\Desktop\Exclusionslol\Korepi`.

# The game path cannot contain special characters.
Майже те саме, що і попередня помилка:
- Перевірте шлях до гри, якщо ваша гра встановлена в `Program Files (x86)`, може виникнути ця помилка.
- Змініть шлях встановлення гри на шлях без спеціальних символів.
Приклад: змініть `C:\Program Files (x86)\Genshin Impact\Genshin Impact game` на `C:\Program Files\Genshin Impact\Genshin Impact game`

## [Гайд]( https://youtu.be/NZhYB4Vxmlk?si=yPRP6dC2xMDUKDqm)

---

# Menu doesn't open
### Кроки для вирішення:
- Переконайтеся, що ви правильно виконали ін'єкцію, ви повинні побачити банер з версією, яку використовуєте, після входу у світ.
- Переконайтеся, що ви використовуєте правильну клавішу, за замовчуванням це `TAB`.
- Якщо у вас є будь-які оверлеї, вимкніть їх перед запуском Korepi.
Наприклад: `MSI After burner, GeForce Experience, Rivatuner тощо`

---

# Cannot verify current timestamp.
### Якщо ви бачите це повідомлення, виконайте наступні кроки:
- Перевірте, що час на вашому ПК налаштований на автоматичну синхронізацію.
- Якщо ви з ІРАНУ, вам потрібно використовувати VPN для використання Korepi.
- Якщо ви не з ІРАНУ, спробуйте вимкнути VPN.

<div align="center">
  <a href="#"><img src="https://cdn.discordapp.com/attachments/1275059206130503682/1275064778615951403/timestamp.png?ex=679eb85c&is=679d66dc&hm=04da13041b2709eef5c03703b3f385281932c83006d4ba1bdacd8bbdffc6474c&"></a>
</div>

---

# Failed to create game process with Error 5.
Якщо ви отримуєте цю помилку, переконайтеся, що ви вибрали правильний файл гри.
- Виберіть файл гри заново, видаливши `cfg.ini` в папці Korepi і запустивши Korepi знову.

---

# File contains virus or potentially unwanted software.
### Якщо ви отримуєте цю помилку, виконайте наступні кроки:
- Вимкніть антивірус.
- Переконайтеся, що ваша папка Korepi додана до виключень. [Як додати до виключень](https://korepi.com/en/guide/virus.html).

---

# Process crashed, exit code 0xc000005.
### Якщо ви отримуєте цю помилку, виконайте наступні кроки:
- Завантажте [цей файл](https://cdn.discordapp.com/attachments/1251244897831227546/1285657688092573797/envSettingfirst_run_this_for_admin.exe?ex=66eb1187&is=66e9c007&hm=d3322d5db0c6828de7b562f98d1bfd17bd64c45763b60e5298833f82b993dca3&), перемістіть його в папку Korepi і запустіть від імені адміністратора.
Якщо це не допомогло:
- Відкрийте командний рядок від імені адміністратора і введіть наступну команду `sfc /scannow`
- Після цього, якщо були знайдені помилки, перезавантажте комп'ютер і перевірте. Якщо після перезавантаження не допомогло або помилок не було знайдено, введіть цю команду `DISM.exe /Online /Cleanup-Image /RestoreHealth`
- Після завершення перевірок перезавантажте комп'ютер і перевірте.

Якщо це не допомогло, перевстановіть Windows.

---

# ImGUI: DirectX11 backend initialized successfully.
### Якщо ви отримуєте цю помилку, виконайте наступні кроки:
- Помилка виникає через встановлені теми, видаліть папку themes.

---

# File ok.
### Якщо ви отримуєте цю помилку, виконайте наступні кроки:
- Іноді потрібно відкрити лаунчер кілька разів, перш ніж він запрацює.
- Видаліть ваш cfg.json, можливо, з файлом щось не так.

---

# If you get stuck here, please restart your computer and try again.
### Якщо ви отримуєте цю помилку, виконайте наступні кроки:
- Вам потрібно налаштувати час на вашому ПК на автоматичну синхронізацію.
- Вимкніть всі антивіруси.

<div align="center">
  <a href="#"><img src="https://cdn.discordapp.com/attachments/1275059206130503682/1275077076239781978/image.png?ex=679ec3d0&is=679d7250&hm=20f8006d55341e61683b8952df4582d50127af3d3ced71d552109651d29239cb&"></a>
</div>

---

# Error 31-4302.
### Якщо ви отримуєте цю помилку, виконайте наступні кроки:
- Видаліть cfg.json
- Відкрийте лаунчер, натисніть на 3 смужки та натисніть "Repair Now"

---

# File corrupted! This program has been manipulated and maybe it's infected.
### Якщо ви отримуєте цю помилку, виконайте наступні кроки:
- У цьому випадку ви можете спробувати використовувати Malware Bytes або Dr.Web для повного сканування, якщо знайдені віруси, видаліть їх, перезавантажте комп'ютер і спробуйте знову. Якщо це не допоможе, перевстановлення Windows - найпростіший спосіб вирішити цю проблему.

<div align="center">
  <a href="#"><img src="https://cdn.discordapp.com/attachments/1275059206130503682/1275081666548727938/virus2.png?ex=679ec817&is=679d7697&hm=0d874838a433367eb472a0cd02722752c3e177806ee30206ae9da2f7961a15cf&"></a>
</div>

---

# The system did not detect MSVCP140.dll.
### Якщо ви отримуєте цю помилку, виконайте наступні кроки:
- Оновіть [Microsoft Visual Studio C++](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170#visual-studio-2015-2017-2019-and-2022)
- Оновіть [DirectX](https://www.microsoft.com/en-us/download/details.aspx?id=35)

---

# The key file not found, please join discord channel....The key file and the korepi program are free, if you bought it, then you are cheated.
### Якщо ви отримуєте цю помилку, виконайте наступні кроки:
- Отримайте enc.json знову, використовуючи [інструкцію](https://discord.com/channels/1251244897021722735/1266776966808207464)

<div align="center">
  <a href="#"><img src="https://cdn.discordapp.com/attachments/1275059206130503682/1275103624711901350/image.png?ex=679edc8a&is=679d8b0a&hm=216cc76e1224d775442eb2db0ca750ab73b8501e8b5f0dc5ddd88350ccec27d1&"></a>
</div>

---

# MD5 not match, please the get key file again.
### Якщо ви отримуєте цю помилку, виконайте наступні кроки:
- Отримайте enc.json знову, використовуючи [інструкцію](https://discord.com/channels/1251244897021722735/1266776966808207464)

<div align="center">
  <a href="#"><img src="https://cdn.discordapp.com/attachments/1275059206130503682/1275404199005524055/image.png?ex=679ea2f8&is=679d5178&hm=9106e236866d95f94bd9e178d334b40a262ac7d16b01bbb54807911f4543ec5c&"></a>
</div>

---

# Error at hooking API "LoadStringA"
### Якщо ви отримуєте цю помилку, виконайте наступні кроки:
- Перезавантажте комп'ютер.
- Відкрийте командний рядок від імені адміністратора і введіть наступну команду `sfc /scannow`
- Після цього, якщо були знайдені помилки, перезавантажте комп'ютер і перевірте. Якщо після перезавантаження не допомогло або помилок не було знайдено, введіть цю команду `DISM.exe /Online /Cleanup-Image /RestoreHealth`
- Після завершення перевірок перезавантажте комп'ютер і перевірте.

<div align="center">
  <a href="#"><img src="https://cdn.discordapp.com/attachments/1275059206130503682/1275802750600609874/image.png?ex=679ec4a7&is=679d7327&hm=7e7734bc99f5f77b53318159fd095d3308ccaa0c3e741111ab363f8767ebb172&"></a>
</div>

---

# Too many requests. Please try again later.
### Якщо ви отримуєте цю помилку, виконайте наступні кроки:
- Відкрийте Regedit і перейдіть за шляхом `"HKEY_CURRENT_USER\Software"` та видаліть папку `"miHoYoSDK"`. У тій же директорії видаліть папку `"Genshin Impact"` в папці `"miHoYo"`.
- Використовуйте будь-який VPN.

Якщо це не допомагає, зачекайте та спробуйте знову.

<div align="center">
  <a href="#"><img src="https://cdn.discordapp.com/attachments/1275059206130503682/1278296319768793109/image.png?ex=679f4538&is=679df3b8&hm=f49ac4d4d9aed4799ead82378cf90790303f760ee6b042b496b341af5288f881&"></a>
</div>

---

# Successfully added DLL folder to system PATH
### Якщо ви отримуєте цю помилку, виконайте наступні кроки:
- Завантажте [цей файл](https://cdn.discordapp.com/attachments/644953856551288842/1281302256938909878/cfg.ini?ex=66db3937&is=66d9e7b7&hm=955d71931316a4ac99819c2498e1b1c9c99508cca9929db473d27e4482bf188a&) і перемістіть його в папку Korepi з заміною, потім вкажіть EXE файл гри.

<div align="center">
  <a href="#"><img src="https://cdn.discordapp.com/attachments/1275059206130503682/1281326539908321340/image.png?ex=679f1695&is=679dc515&hm=455d4f2b264eddf1ce545cd02c20f7cce9f2ed0338e912b0caa07647496a7034&"></a>
</div>

---

# The procedure entry point BIO_new_mem_buf could not be located in the dynamic link library libcrypto-1_1-x64.dll
### Якщо ви отримуєте цю помилку, виконайте наступні кроки:
- Завантажте [файл](https://cdn.discordapp.com/attachments/1275059206130503682/1281327851265593424/envSettingfirst_run_this.exe?ex=679f17cd&is=679dc64d&hm=c437b449e8d418f304dfb5bc9f1b1a138c779a8d1df3ffc1deff31ce3ef703a0&), перемістіть його в папку korepi та запустіть від імені адміністратора.

<div align="center">
  <a href="#"><img src="https://cdn.discordapp.com/attachments/1275059206130503682/1281327851098079294/image.png?ex=679f17cd&is=679dc64d&hm=b14d58930cf2f840e5cdc369dd717730af5595eccf0a0697d4584fa1442de1b3&"></a>
</div>

---

# Process crashed, exit code: 0xc00000005 
- **Запустіть envSetting від імені адміністратора.**

<div align="center">
  <a href="#"><img src="https://cdn.discordapp.com/attachments/1275059206130503682/1291687281543086100/image.png?ex=679f3506&is=679de386&hm=2ba14828a7f38cc5b20ed513e39caa7d7a04ea54fdf355e884ea4273def68a50&"></a>
</div>

---

# Card has expired!
### Якщо ви отримуєте цю помилку, виконайте наступні кроки:
- Отримайте новий enc.json.

<div align="center">
  <a href="#"><img src="https://cdn.discordapp.com/attachments/1275059206130503682/1304160405534539816/image.png?ex=679f19c6&is=679dc846&hm=f66ca62e3dbf1fe504cb9db427f70aaf2faa2ce65ad3efd9f0b75830044d4b40&"></a>
</div>

---

# No matching DLL path found in the system path.
### Якщо ви отримуєте цю помилку, виконайте наступні кроки:
- Перезавантажте ПК

<div align="center">
  <a href="#"><img src="https://cdn.discordapp.com/attachments/1275059206130503682/1304160633763397682/image.png?ex=679f19fd&is=679dc87d&hm=6e00fa35ab96f9d58b2058926f2af725154fd4e15673867284dd958ef855a9d3&"></a>
</div>

---

# Prompt (Auto-close in 5s)
### Якщо ви отримуєте цю помилку, виконайте наступні кроки:
- Завантажте [Library VC](https://aka.ms/vs/17/release/vc_redist.x64.exe)

<div align="center">
  <a href="#"><img src="https://cdn.discordapp.com/attachments/1275059206130503682/1304371238734397461/image.png?ex=679f3561&is=679de3e1&hm=ac4a1b558540b71b70c0a6ed07e6f68ea353787410117f62a1c8164de9087cf0&"></a>
</div>

---

# SPKEY has expired, Please go to the website or the robot terminal to claim again
### Якщо ви отримуєте цю помилку, виконайте наступні кроки:
Вам потрібно оновити ваш SPKEY
- [Натисніть тут](https://discord.com/channels/1251244897021722735/1255892075371827313/1295311329040666727) або перейдіть сюди: [Verification](https://discord.com/channels/1251244897021722735/1255892075371827313) і виберіть **`Receive SP Key`**, а потім **`Query SP Key`**.
Потрібна роль **`PERTAMAX`** для використання.

- Якщо використовуєте лаунчер, просто натисніть `Renew SPKey`.

<div align="center">
  <a href="#"><img src="https://cdn.discordapp.com/attachments/1275059206130503682/1306547825156558848/image.png?ex=679f377c&is=679de5fc&hm=29296dedaf1dae69bb45c9706085fb43e6cd8d2ee53a8ef3a981317fc8131847&"></a>
</div>

---

# Subscription status abnormal (Subscription Expire) | (Subscription Paused)
### Якщо ви отримуєте цю поширену помилку, виконайте наступні кроки:
- Якщо ви отримуєте `(Subscription Expire)`, спочатку видаліть ваш старий `enc.json` і знову `прив'яжіть безкоштовний ключ` в [Verification](https://discord.com/channels/1251244897021722735/1255892075371827313) або використовуйте це [відео інструкцію](https://youtu.be/ljOjDE79QD0), якщо забули як це зробити.

- Якщо ви отримуєте `(Subscription Paused)`, очевидно, ви забули відновити ваш ключ pertamax... спробуйте відновити ключ в [Verification](https://discord.com/channels/1251244897021722735/1255892075371827313), якщо хочете продовжити його використання.

<div align="center">
  <a href="#"><img src="https://cdn.discordapp.com/attachments/1275059206130503682/1314071983784460298/image.png?ex=679ee767&is=679d95e7&hm=fdab4b5c8c5100a8a74907ab764ba9804b387f788949697ec5bc7c0a05629242&"></a>
</div>

---

# Waiting for 0ms before injecting the Korepi dll
### Якщо ви отримуєте цю помилку, виконайте наступні кроки:
- Спробуйте видалити ваш `cfg.ini` і потім запустіть korepi знову для генерації нового.
Це відбувається, коли ви хочете використовувати користувацький `cfg.ini` для 3dmigoto або чогось іншого, що порушує ін'єкцію korepi в гру з використанням `cfg.ini`. Тому краще видалити його і дозволити згенерувати новий.

<div align="center">
  <a href="#"><img src="https://cdn.discordapp.com/attachments/1275059206130503682/1314074148510634014/image.png?ex=679ee96b&is=679d97eb&hm=510ac680f7ebd167974bb4f34768b63e2d94c7b319e0225969e095e83c02c90f&"></a>
</div>

---

# [504 Gateaway Timeout | Server connection failed | Timeout was reached]
- Тут нічого більше сказати. В даний час виникла проблема з сервером/сервісом, вам потрібно зачекати, поки вона буде виправлена.
Рідкісне явище, воно впливає на все, що пов'язано з korepi і сервісами на цьому сервері, тому наберіться терпіння, поки це не буде виправлено, немає оцінки, скільки це займе часу.

- Але якщо з якоїсь причини статус нормальний і сервіс/сервер працює, можна спробувати використовувати VPN [CouldFlare Warp+](https://one.one.one.one/).

---

# VirtualAllocEX Error[5]
### Якщо ви отримуєте цю помилку, виконайте наступні кроки:
Гадаю, це майже те саме, що і раніше. Але ви можете спробувати використовувати AIO цього разу
- Спочатку спробуйте перезавантажити ваш комп'ютер і подивіться, чи допоможе це.
- Якщо ні, спробуйте завантажити [Visual C++ Redistributable Runtimes All-in-One](https://www.techpowerup.com/download/visual-c-redistributable-runtime-package-all-in-one/) і встановити його.

---

# msg: ??ID???? (data ID not match)
### Якщо ви отримуєте цю помилку, виконайте наступні кроки:
Це відбувається, коли ви змінюєте комп'ютер, перевстановлюєте Windows або використовуєте HWID spoofer/HWID changer. І він не збігається з hardwareID вашого пристрою з вашим акаунтом Discord.
- Спочатку завантажте [це](https://cdn.discordapp.com/attachments/1251244897831227544/1314549647892807700/get_hwid.exe?ex=67542d43&is=6752dbc3&hm=9fd1f5893728e094bfa2801fe7c1f744631b2a32086d8859589713d7729d8443&), потім запустіть. Воно повинно показати вам ваш поточний hwid, скопіюйте його.
- Перейдіть в [Verification](https://discord.com/channels/1251244897021722735/1255892075371827313), потім виберіть `Change HWID` і вставте новий hwid в поле і натисніть `Submit`

## Якщо ви збираєтесь використовувати лаунчер [для pertamax]
він автоматично змінить hwid на поточний пристрій.
- Відкрийте Korepi Launcher
- Натисніть `Reset HWID`, вирішіть математичний приклад і натисніть `Confirm`

---

# Blank Command prompt/Inject ok. 
**Ця проблема виникає через відсутність c++ або помилки мережі.**

- Завантажте [VCRedist AIO](https://github.com/abbodi1406/vcredist/releases/download/v0.85.0/VisualCppRedist_AIO_x86_x64.exe)(якщо запитує ремонт, виконайте його.)
- Якщо перше рішення не спрацювало, спробуйте використовувати vpn або [1.1.1.1](https://one.one.one.one/) (Warp)
- Якщо це теж не працює, можливо, вірус/антивірус заважає роботі korepi. Вимкніть всі антивіруси, встановіть malwarebyte для сканування на віруси.
- Перевстановіть Windows, якщо всі рішення не допомагають.

--- 