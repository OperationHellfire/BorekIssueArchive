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

<div align="left">
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