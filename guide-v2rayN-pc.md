## Содержание
[Как подключится через v2rayN](https://gist.github.com/SylvesterFox/95cad71013835313f9948b84d6afd6d9#%D0%BA%D0%B0%D0%BA-%D0%BF%D0%BE%D0%B4%D0%BA%D0%BB%D1%8E%D1%87%D0%B8%D1%82%D1%81%D1%8F-%D1%87%D0%B5%D1%80%D0%B5%D0%B7-v2rayn)

[Альтернативные клиенты](https://gist.github.com/SylvesterFox/95cad71013835313f9948b84d6afd6d9#%D0%B0%D0%BB%D1%8C%D1%82%D0%B5%D1%80%D0%BD%D0%B0%D1%82%D0%B8%D0%B2%D0%BD%D1%8B%D0%B5-%D0%BA%D0%BB%D0%B8%D0%B5%D0%BD%D1%82%D1%8B)

[Настройка машрутизации для конкретных сайтов](https://gist.github.com/SylvesterFox/95cad71013835313f9948b84d6afd6d9#%D0%BD%D0%B0%D1%81%D1%82%D1%80%D0%BE%D0%B9%D0%BA%D0%B0-%D0%BC%D0%B0%D1%88%D1%80%D1%83%D1%82%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D0%B8-%D0%B4%D0%BB%D1%8F-%D0%BA%D0%BE%D0%BD%D0%BA%D1%80%D0%B5%D1%82%D0%BD%D1%8B%D1%85-%D1%81%D0%B0%D0%B9%D1%82%D0%BE%D0%B2-%D0%B2-v2rayn)

## Как подключится через v2rayN

 - Для начала скачаем последнюю релизную версию клиента (_На данный момент это 7.11.3_)  из официального репозитория [v2rayN на Github](https://github.com/2dust/v2rayN/releases/tag/7.11.3) 
- **Клиент есть только для Linux и Windows, для MacOS** 
![Pasted image 20250501214244](https://gist.github.com/user-attachments/assets/6ad519c1-6d79-48b1-9668-4fcc8bcad72b)
 ### Настройка для ПК на ОС Windows 
 - После того как вы скачали архив, его необходимо разархивировать в любое удобное вам место.
 - Далее откройте папку, которую  вы только что разархивировали, с v2rayN, и найдите в ней исполняемый файл `v2rayN.exe`. Запустите его.
- Дальше у вас откроется клиент `v2rayN`, Вы увидите интерфейс приложения:
  
![Pasted image 20250501220702](https://gist.github.com/user-attachments/assets/b5e5ee1d-815d-4a7a-ba68-92d31773876b)

- Далее вам понадобится VLESS-ключ профиля, который можно получить у нашего бота или у владельца VPN-сервера. Ключ будет выглядеть примерно так:
```
vless://xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
```
-  Скопируйте ключ в буфер обмена, затем вернитесь в клиент v2rayN. В верхнем меню клиента выберите пункт `Servers` >> `import Share Links from clipboard ` 
- После этого профиль подключения появится в списке профилей клиента v2rayN

![Pasted image 20250501225440](https://gist.github.com/user-attachments/assets/00563cb2-f8dd-4671-9bee-cf9bf7882cb4)
- Далее нажимаем правой кнопкой мыши по профилю, и в появившемся контестном меню выбираем пункт `Set as active server`

![Pasted image 20250501230108](https://gist.github.com/user-attachments/assets/60f76750-e163-406c-8c12-f9b91ad35269)

- Теперь осталось финальная настройка. В верхнем меню клиента пункт `Settings` >>  `Regional presets setting` >> `Russia`

![Pasted image 20250501230654](https://gist.github.com/user-attachments/assets/11575d6d-b14e-4061-8a5a-ffe4387d82a0)

- Ждем пока скачаются присеты

![Pasted image 20250501231134](https://gist.github.com/user-attachments/assets/3620065a-8807-4f64-af73-b98e6f9da52b)

- Все мы настроили клиент v2rayN, теперь в `Routing` выбераем `RUv1-Всё`, и тумблер `Enable Tun` (Иногда не с первого раза запуститься, просто автомотически программа перезапустится под имени админстратора, если её не запускали через админа)
 - **PROFIT!** Продолжаем радоваться свободжой жизни в интернете.

![Pasted image 20250501233521](https://gist.github.com/user-attachments/assets/15bf52ae-4ab0-4b27-b6a9-4499695ad69e)

**Для линукс и мак все тоже самое, но там есть свои подводные камни.**

## Альтернативные клиенты
 
-  [Nekoray](https://github.com/MatsuriDayo/nekoray/releases/tag/4.0.1) - альтернативный xray клиент, но только для linux и windows, для mac увы нету но есть форк этого клиента, так же есть [гайд по настройки данного клиента](https://github.com/SylvesterFox/client-x-ray-guide)
- [Nekoray-macOS](https://github.com/abbasnaqdi/nekoray-macos/releases) - Форк клиента nekoray для macOS, есть версия как для x86, так и для ARM (Apple M) процессоров. Требуется: `macOS 10.15 Catalina` и выше.
- [V2Box](https://apps.apple.com/ru/app/v2box-v2ray-client/id6446814690) - Xray клиент для macOS, Требуется: `macOS 11 и выше.`

## Настройка машрутизации для конкретных сайтов в v2rayN
-  В клиенте в верхним меню, `Settings` >>  `Routing setting`, у нас откроется вот такое окно настроек

![image](https://gist.github.com/user-attachments/assets/01855695-fe06-4577-948a-c5d9ced0b938)
- Дальше в этом окне в верхним левом углу нажимаем `Advanced Function` >> `Add`

![image](https://gist.github.com/user-attachments/assets/91d1bada-1b06-49e4-b226-9c428f8aec1a)

- Дальше у нас откроется настройки правил машрутизации, в строке *Remarks* называем наше группу правилил как хотим (я её назвал `гайд`), и верхним левом нажимаем `Add Rule` и добовляем первое правило

![image](https://gist.github.com/user-attachments/assets/e1ddb63b-7bf5-4a31-bb75-e2568d0e12b1)

- После этого откроется следующие окно с тремя колонами, это настройка самого правила, в строке *remarks* называем как хотим, но я его назаву regxp, а вот `outboundTag` ставим `direct`, а в колонне `Domain` вставляем вот этот параметр: 
```
regexp:\.*$
```

- И нажимаем `Confirm`

![image](https://gist.github.com/user-attachments/assets/f8ae0ba7-6d16-415b-bcf4-b43a6e9e1dce)

![image](https://gist.github.com/user-attachments/assets/2c98242d-cb04-42b9-a199-c0ea40114a43)

- Дальше мы создаем еще новое правило, только для конкретного нам сайта, ютуба, и дискорда, т.д

**Для дискорда и ютуба есть сборник Доменов правил в ссылках ниже**

[Пак доменов дискорда]()

[Пак доменов ютуба]()

- Покажу на примере дискорда, в *remaks* называем `discord`, в `outboundTag` ставим `proxy`, в `network` ставим `tcp,udp` чтобы работал войс, в `Domain` вставляем [домены дискорда](), а вот колонне `Full process name (Tun mode)` пишем назваине процесса `Discord.exe` (Если у вас ядро линукс тот без `.exe`)

![image](https://gist.github.com/user-attachments/assets/46c66885-daf5-491a-9c48-c654492754d7)

- И `Confirm`, для ютуба делается все тоже самое как и для дискорда, также создаем новое правило только без процесса `Discord.exe` и установки `tcp,udp` в `network`, с доменами ютуба.

- После настройки и добаление правил в наш присет машрутизации, он будет выглядить вот так.
![image](https://gist.github.com/user-attachments/assets/7d5c0e06-0015-407a-bf15-70c4de95c224)

**Обезательно чтобы все работало, правило ``regxp`` должно быть самом внизу, через клавиши `D` "Вниз" или `U` "Верх", или через контекстное меню можем перещать правила.**

![image](https://gist.github.com/user-attachments/assets/5d249ed3-6b78-4f6d-ae68-e20ee98d7b6d)
- Дальше снова `Confirm`, и в окне `Routing Setting` тоже `Confirm`, и внизу где тумблер `Enable Tun` в `Routing` выбираем наш уже настроитный присет машрутизации для дискорда, я его назвал `гайд`

![image](https://gist.github.com/user-attachments/assets/5566afa5-2a02-4d9b-99f0-54324f4c2536)
-  Включаем `Enable Tun` и проверяем, теперь весь трафик дискорда проходит через впн, а вот все остальное не проходит через впн.

**Вот теперь все, мы настроили машрутизацию только для дискорда, как я ранее говорил вы можете добавить правила машрутизации для ютуба, и т.д**
