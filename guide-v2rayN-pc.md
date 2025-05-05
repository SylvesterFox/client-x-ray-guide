## Содержание
[Как подключится через v2rayN](https://gist.github.com/SylvesterFox/95cad71013835313f9948b84d6afd6d9#%D0%BA%D0%B0%D0%BA-%D0%BF%D0%BE%D0%B4%D0%BA%D0%BB%D1%8E%D1%87%D0%B8%D1%82%D1%81%D1%8F-%D1%87%D0%B5%D1%80%D0%B5%D0%B7-v2rayn)

[Альтернативные клиенты](https://gist.github.com/SylvesterFox/95cad71013835313f9948b84d6afd6d9#%D0%B0%D0%BB%D1%8C%D1%82%D0%B5%D1%80%D0%BD%D0%B0%D1%82%D0%B8%D0%B2%D0%BD%D1%8B%D0%B5-%D0%BA%D0%BB%D0%B8%D0%B5%D0%BD%D1%82%D1%8B)

[Настройка машрутизации для конкретных сайтов](https://gist.github.com/SylvesterFox/95cad71013835313f9948b84d6afd6d9#%D0%BD%D0%B0%D1%81%D1%82%D1%80%D0%BE%D0%B9%D0%BA%D0%B0-%D0%BC%D0%B0%D1%88%D1%80%D1%83%D1%82%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D0%B8-%D0%B4%D0%BB%D1%8F-%D0%BA%D0%BE%D0%BD%D0%BA%D1%80%D0%B5%D1%82%D0%BD%D1%8B%D1%85-%D1%81%D0%B0%D0%B9%D1%82%D0%BE%D0%B2-%D0%B2-v2rayn)

## Как подключится через v2rayN

 - Для начала скачаем последнюю релизную версию клиента (_На данный момент это 7.11.3_)  из официального репозитория [v2rayN на Github](https://github.com/2dust/v2rayN/releases/tag/7.11.3) 
- **Клиент есть только для Linux и Windows, для MacOS**
  
![image](https://github.com/user-attachments/assets/ce2f6f7c-99eb-4ffd-900b-919cda771f78)

 ### Настройка для ПК на ОС Windows 
 - После того как вы скачали архив, его необходимо разархивировать в любое удобное вам место.
 - Далее откройте папку, которую  вы только что разархивировали, с v2rayN, и найдите в ней исполняемый файл `v2rayN.exe`. Запустите его.
- Дальше у вас откроется клиент `v2rayN`, Вы увидите интерфейс приложения:
  
![image](https://github.com/user-attachments/assets/db6667f9-020d-4735-ad29-d886b6f8220f)

- Далее вам понадобится VLESS-ключ профиля, который можно получить у нашего бота или у владельца VPN-сервера. Ключ будет выглядеть примерно так:
```
vless://xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
```
-  Скопируйте ключ в буфер обмена, затем вернитесь в клиент v2rayN. В верхнем меню клиента выберите пункт `Servers` >> `import Share Links from clipboard ` 
- После этого профиль подключения появится в списке профилей клиента v2rayN

![image](https://github.com/user-attachments/assets/fbc04f39-2e96-45db-9ea5-e86bc308a0b6)

- Далее нажимаем правой кнопкой мыши по профилю, и в появившемся контестном меню выбираем пункт `Set as active server`

![image](https://github.com/user-attachments/assets/d949670f-322a-4f55-9537-8eaed513f2e2)

- Теперь осталось финальная настройка. В верхнем меню клиента пункт `Settings` >>  `Regional presets setting` >> `Russia`

![image](https://github.com/user-attachments/assets/1ae52d9d-8a86-4ed4-af18-9b97ae754779)


- Ждем пока скачаются присеты

![image](https://github.com/user-attachments/assets/ffb0dc9c-5eb7-4842-838d-3503f0dd45a8)


- Все мы настроили клиент v2rayN, теперь в `Routing` выбераем `RUv1-Всё`, и тумблер `Enable Tun` (Иногда не с первого раза запуститься, просто автомотически программа перезапустится под имени админстратора, если её не запускали через админа)
 - **PROFIT!** Продолжаем радоваться свободжой жизни в интернете.

![image](https://github.com/user-attachments/assets/b6f95d00-7418-41ba-9dc8-e4b57f4c8b3b)


**Для линукс и мак все тоже самое, но там есть свои подводные камни.**

## Альтернативные клиенты
 
-  [Nekoray](https://github.com/MatsuriDayo/nekoray/releases/tag/4.0.1) - альтернативный xray клиент, но только для linux и windows, для mac увы нету но есть форк этого клиента, так же есть [гайд по настройки данного клиента](https://github.com/SylvesterFox/client-x-ray-guide)
- [Nekoray-macOS](https://github.com/abbasnaqdi/nekoray-macos/releases) - Форк клиента nekoray для macOS, есть версия как для x86, так и для ARM (Apple M) процессоров. Требуется: `macOS 10.15 Catalina` и выше.
- [V2Box](https://apps.apple.com/ru/app/v2box-v2ray-client/id6446814690) - Xray клиент для macOS, Требуется: `macOS 11 и выше.`

## Настройка машрутизации для конкретных сайтов в v2rayN
-  В клиенте в верхним меню, `Settings` >>  `Routing setting`, у нас откроется вот такое окно настроек

![image](https://github.com/user-attachments/assets/8ae7d8cf-b11e-419d-a3b8-051f01d7d8c5)

- Дальше в этом окне в верхним левом углу нажимаем `Advanced Function` >> `Add`

![image](https://github.com/user-attachments/assets/55be8e0d-0fac-4e26-83b3-efb58da5a2c0)


- Дальше у нас откроется настройки правил машрутизации, в строке *Remarks* называем наше группу правилил как хотим (я её назвал `гайд`), и верхним левом нажимаем `Add Rule` и добовляем первое правило

![image](https://github.com/user-attachments/assets/f30ca7d1-6ea2-4172-bd82-973399a078d7)


- После этого откроется следующие окно с тремя колонами, это настройка самого правила, в строке *remarks* называем как хотим, но я его назаву regxp, а вот `outboundTag` ставим `direct`, а в колонне `Domain` вставляем вот этот параметр: 
```
regexp:\.*$
```

- И нажимаем `Confirm`

![image](https://github.com/user-attachments/assets/442ba3e5-8a32-4470-833a-5f4e6423f8ee)

![image](https://github.com/user-attachments/assets/d0a75d18-2479-4d7c-954e-c187afdcec4b)

- Дальше мы создаем еще новое правило, только для конкретного нам сайта, ютуба, и дискорда, т.д

**Для дискорда и ютуба есть сборник Доменов правил в ссылках ниже**

[Пак доменов дискорда](https://github.com/SylvesterFox/client-x-ray-guide/blob/main/Discord-domains.md)

[Пак доменов ютуба](https://github.com/SylvesterFox/client-x-ray-guide/blob/main/YouTube-domain.md)

- Покажу на примере дискорда, в *remaks* называем `discord`, в `outboundTag` ставим `proxy`, в `network` ставим `tcp,udp` чтобы работал войс, в `Domain` вставляем [домены дискорда](), а вот колонне `Full process name (Tun mode)` пишем назваине процесса `Discord.exe` (Если у вас ядро линукс тот без `.exe`)

![image](https://github.com/user-attachments/assets/ea4fbaa8-a198-4548-9a78-a1e787cab043)

- И `Confirm`, для ютуба делается все тоже самое как и для дискорда, также создаем новое правило только без процесса `Discord.exe` и установки `tcp,udp` в `network`, с доменами ютуба.

- После настройки и добаление правил в наш присет машрутизации, он будет выглядить вот так.

![image](https://github.com/user-attachments/assets/10dded77-ff92-444d-b0d5-926bde6908e6)

**Обезательно чтобы все работало, правило ``regxp`` должно быть самом внизу, через клавиши `D` "Вниз" или `U` "Верх", или через контекстное меню можем перещать правила.**

![image](https://github.com/user-attachments/assets/709734b0-33ac-4a44-aa58-c10f8018d2ac)

- Дальше снова `Confirm`, и в окне `Routing Setting` тоже `Confirm`, и внизу где тумблер `Enable Tun` в `Routing` выбираем наш уже настроитный присет машрутизации для дискорда, я его назвал `гайд`
  
![image](https://github.com/user-attachments/assets/7a3fe480-9a88-45cb-8067-e3a2109a4ff0)

-  Включаем `Enable Tun` и проверяем, теперь весь трафик дискорда проходит через впн, а вот все остальное не проходит через впн.

**Вот теперь все, мы настроили машрутизацию только для дискорда, как я ранее говорил вы можете добавить правила машрутизации для ютуба, и т.д**
