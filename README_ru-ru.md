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

<div align="left">
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

<div align="left">
  <a href="#"><img src="https://cdn.discordapp.com/attachments/1275059206130503682/1275077076239781978/image.png?ex=679ec3d0&is=679d7250&hm=20f8006d55341e61683b8952df4582d50127af3d3ced71d552109651d29239cb&"></a>
</div>

---

# Error 31-4302.
### Если вы получаете эту ошибку, выполните следующие шаги:
- Удалите cfg.json
- Откройте лаунчер, нажмите на 3 полоски и нажмите "Repair Now"

--- 