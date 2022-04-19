# IB PixelPlanet Minimap [RUS]
#### Discord 
> http://discord.me/er4WQqc
#### Youtube 
> https://www.youtube.com/channel/UC_LEpw7zx3vWrB6kq-3sC_g
#### ВКонтакте
> https://www.vk.com/ilyabot2
### Карту переделали:
#### IlyaBOT и Endless Night

## Установка
#### Этап 1: Установите в ваш браузер расширение Tampermonkey или если вы используете Firefox, то установите Greasemonkey.
* ![](https://raw.githubusercontent.com/reek/anti-adblock-killer/gh-pages/images/chrome.png) [Tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)
* ![](https://raw.githubusercontent.com/reek/anti-adblock-killer/gh-pages/images/opera.png) [Tampermonkey](https://addons.opera.com/extensions/details/tampermonkey-beta/)
* ![](https://raw.githubusercontent.com/reek/anti-adblock-killer/gh-pages/images/safari.png) [Tampermonkey](https://safari.tampermonkey.net/tampermonkey.safariextz)
* ![](https://raw.githubusercontent.com/reek/anti-adblock-killer/gh-pages/images/msedge.png) [Tampermonkey](https://www.microsoft.com/store/p/tampermonkey/9nblggh5162s)
* ![](https://raw.githubusercontent.com/reek/anti-adblock-killer/gh-pages/images/firefox.png) [Greasemonkey](https://addons.mozilla.org/firefox/addon/greasemonkey/)

#### Этап 2: Установите скрипт
<a href="https://raw.githubusercontent.com/IlyaBOT/IBminimap/main/minimap.user.js">Установить скрипт</a>

#### Этап 3: Миникарта готова к работе, найти её вы можете на панели расширений в меню Tampermonkey (Или Greasemoney в Firefox)

![](https://github.com/IlyaBOT/IBminimap/blob/main/images/image_2020-10-13_120039.png)

Оригинал: https://github.com/Vasco-Pixel/mz

## Добавление своего шаблона в миникарту (При условии что ваша карта готова к работе)
#### Этап 1: Загрузите репозиторий к себе на компьютер:
![](https://github.com/IlyaBOT/IBminimap/blob/main/images/qHsAOHJHC4Y.jpg)
#### Этап 2: Откройте и разархивируйте в любую удобную вам папку только что скачанный репозиторий.
#### Этап 3: Открывайте папку с репозиторием и переходите в папку images, после чего добавяйте/заменяйте изображения как вашей душе угодно.
#### Этап 4: Возвращайтесь назад и переходите в папку templates, там лежит единственный файл data.json, открываете его в текстовом редакторе (Желательно Notepad++, Sublime Text, или что нибудь еще, но не встроенный блокнот Windows, он ужасен в плане написания и редактирования кода...)
#### Этап 5: Теперь немного шаманств, не пугайтесь, все просто как решение задач по физике! (П-просто ведь?..)
#### Подставляйте свои значения в следующие поля:
![](https://github.com/IlyaBOT/IBminimap/blob/main/images/image_2020-10-13_110734.png)
### Заместо tstp подставляете все что угодно, но т.к. шаблонов можно добавить несколько, то рекомендую называть шаблоны логичными названиями а не "abc", "123", или "qwerty".
### НазваниеИзображения.png - Название вашего файла (Принимается только формат PNG!)
### КоординатаНаПолотнеПоX - Начальная координата по X (Написана в левом нижнем углу экрана, первое число)
### КоординатаНаПолотнеПоY - Начальная координата по Y (Написана в левом нижнем углу экрана, второе число)
### ШиринаКартинки - Ширина вашего изображения в пикселях (Можно посмотреть в свойствах файла)
### ВысотаКартинки - Высота вашего изображения в пикселях (Можно посмотреть в свойствах файла)
#### Этап 6: Сохраняйте и закрывайте.
#### Этап 7: Создавайте учетную запись GitHub и репозиторий миникарты с нужным вам названием.
#### Этап 8: Идите обратно в файловый менеджер, выходите из папки templates и открывайте minimap.user.js с помощью текстового редактора.
#### Этап 9: Меняйте следующие значения:
### // @version      0.3 -> // @version      ВерсияСкрипта (Помните, что при каждом обновлении скрипта, цифру необходимо увеличивать)
### // @homepage     https://github.com/IlyaBOT/IBminimap -> // @homepage     https://github.com/ВашНикнеймНаGitHub/НазваниеВашегоРепозитория
### // @updateURL    https://raw.githubusercontent.com/IlyaBOT/IBminimap/main/minimap.user.js -> // @updateURL    https://raw.githubusercontent.com/ВашНикнеймНаGitHub/НазваниеВашегоРепозитория/main/minimap.user.js
### // @downloadURL  https://raw.githubusercontent.com/IlyaBOT/IBminimap/main/minimap.user.js -> @downloadURL  https://raw.githubusercontent.com/ВашНикнеймНаGitHub/НазваниеВашегоРепозитория/main/minimap.user.js
#### P.S. Так же при желании можете поменять @name и @description. Прошу вас так же, не меняйте @author, или если меняете как я, то оставьте в файле README.md ссылку на мой репозиторий, будьте честными людьми.

#### Этап 10: Сохраняйте и закрывайте файл.
#### Этап 11: "Заливайте" папку в ваш репозиторий:
![](https://github.com/IlyaBOT/IBminimap/blob/main/images/image_2020-10-13_112803.png)
#### Этап 12: Чтобы установить скрипт, можно нажать по файлу minimap.user.js и потом RAW, но надо ли оно вам? 
#### Открывайте README.md в вашем текстовом редакторе (Или в браузере в редакторе GitHub, как это делаю сейчас я ;) )
#### Если не хотите мучаться как я, то убирайте все что связано с добавлением своего шаблона, для этого есть я и мой тутор, зачем вам мучаться-то?
#### Находите строчку под "Этап 2: Установите скрипт":
<a href="https://raw.githubusercontent.com/IlyaBOT/IBminimap/main/minimap.user.js">Установить скрипт</a> и меняйте ссылку внутри на
https://raw.githubusercontent.com/ВашНикнеймНаGitHub/НазваниеВашегоРепозитория/main/minimap.user.js (Я думаю всем понятно что необходимо подставить свой никнейм и название репозитория?)
#### Сохраняйте.
### Готово! По идее... Листаете свой репозиторий вниз и находите "Этап 2: Установите скрипт", нажимайте снизу кнопку Установить скрипт. Попадаете на сайт Tampermonkey с установкой скрипта, нажимаете Установить, после чего переходите на PixelPlanet. Если карта появилась и шаблон тоже - вы молодец, можете свзять с полки пирожок. 
### Если не заработало, или не появляется шаблон, то пишите мне в ВК или в чат Discord.
P.S. Как же я за**ался писать все это...
