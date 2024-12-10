# Настройка и использование клиента Nekoray для протокола X-Ray | VLESS

## Настройка для ПК
- Для начала, скачайте последнюю релизную версию клиента _(На данный момент это 3.26)_ из официального репозитория [Nekoray на GitHub](https://github.com/MatsuriDayo/nekoray/tags). __Клиент есть только для Linux и Windows__, для MacOS не завезли, увы.

![image1](https://github.com/user-attachments/assets/1654d1e1-aa9c-451f-af59-b9b0efae399b)

### Настройка для ОС Windows

- После того как Вы скачали архив, его необходимо разархивиировать в любое удобное Вам место, но желательно сделать это в папку с остальными программами, например _`(C:\Program Files\Nekoray)`_.
- Далее откройте папку, которую вы только что разархивировали, с Nekoray, и найдите в ней исполняемый файл **`nekoray.exe`**. Запустите его.

Далее у Вас откроется следующее окно, обязательно выбираем **`Xray`!!!**

![Pasted_image_20240930184616](https://github.com/user-attachments/assets/b488c7da-c744-4481-9cb6-4b9f2b0b881b)

После выбора протокола **Xray**, Вы увидите интерфейс приложения **`Nekoray`**:

![Pasted_image_20240930183351](https://github.com/user-attachments/assets/ce53a4b5-25bc-42da-bd4b-f1d7d78f10e0)


- Далее вам понадобится VLESS-ключ профиля, который можно получить в админке **`ui-x`** или запросить у владельца VPN-сервера. Ключ будет выглядеть примерно так:
```
vless://xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
```

- Скопируйте ключ в буфер обмена, затем вернитесь в клиент Nekoray. В верхнем меню клиента выберите пункт **`Program`** > **`Add profile from clipboard`**
- После этого профиль подключения появится в списке профилей клиента Nekoray.
![Pasted_image_20240930185051](https://github.com/user-attachments/assets/ee8076ec-fdf6-43d8-b277-2053ec0e2697)
- Далее нажимаем правой кнопкой мыши по профилю, и в появившемся контекстном меню выбираем пункт _**`Запустить`**_, после чего в верхней части программы включаем две галочки: **`Tun Mode`** и **`System Proxy`**.
- **PROFIT!** Продолжаем радоваться свободжой жизни в интернете.
![Pasted_image_20240930185559](https://github.com/user-attachments/assets/b68292d8-9b9c-4e7b-92fb-557f4b7cebe7)

### Для macOS
Есть порт nekoray который поддерживает macOS, есть версии для Arm/intel процов [Nekoray/macOS на Github](https://github.com/abbasnaqdi/nekoray-macos/releases)
![image](https://github.com/user-attachments/assets/b9b88d8b-88b7-47de-938a-d766ba14fa5e)

Поддерживает: `macOS 10.15 Catalina` и выше.

**Все аналогичнно настраивается по гайду выше**
![IMG_20241108_001104](https://github.com/user-attachments/assets/ec8b2041-9cb6-48f1-92f2-96285ee95c03)

## Распространенные проблемы 
### После подключения полностью пропадает интернет. (Клиент использует неправильный адаптер, скорее всего адаптер Radmin VPN или Hamachi)
Это довольно частая проблема которая решается отключением этих адаптеров в настройках сетевых адаптеров:
**`Панель управления`** >> **`Центр управления сетями и общим доступом`** >> **`Измение параметров адаптера`**

![image](https://github.com/user-attachments/assets/9e467ddf-42ca-456f-b4d7-4395a3ce91f6)

---

![image (1)](https://github.com/user-attachments/assets/bf4f4a5f-e87c-4420-a433-e7a4b50e437f)

Отключаем адаптеры с названием Radmin VPN или Hamachi _`(Рекомендуется отключить все лишние и ненужные адаптеры, но по идее достаточно будет отключить только эти)`_, для этого нажимаем правой кнопкой мыши по адаптеру, и выбираем пункт **`Отключить`**.

## Для смартфонов

##№ Настройка для смартфонов на ОС Android

Для Android мы будем использовать приложение `v2rayNG` скачать его можно в Google Play

![Screenshot_20241008_213721_com hihonor android launcher](https://github.com/user-attachments/assets/73f7bf0a-c7fb-45e1-b1c8-8e64495d237e)


Открываем его, сверху будет `+` нажимаем на него и покажется контекстное меню, _**ключ vless должен быть предварительно скопирован в буфер обмена**_, если это сделано, то нажимаем **`Импорт из буфера обмена`**, если же у вас QR-код, то выбирайте пункт **`Импорт из QR-кода`**.

![Screenshot_20241008_215617_com v2ray ang](https://github.com/user-attachments/assets/5926540c-313f-432c-b932-74fc1c9e7aab)

![Screenshot_20241008_215649_com v2ray ang](https://github.com/user-attachments/assets/93649689-4967-4e53-9064-4b7ff7e11dbe)


После данных действий у Вас появится профиль, нажимаем на него чтобы его выбрать, и потом на серую кнопку `>` чтобы запустить.

![dragon_flute_bounce_music](https://github.com/user-attachments/assets/29c43ca6-a6e1-4e7d-b597-37f70f0a2c9b)

И теперь кайфуем.

## Для IOS

`У меня нет устройства под управлением iOS, но вы можете попробовать установить V2Box, практически аналог v2rayNG`

## Настройка nekoray, на проксировние конкретных приложений

В клиенте в верхнем меню нажимаем на кнопку **`Settings`** >> **`Settings TUN-mode`**

![image (2)](https://github.com/user-attachments/assets/2c6a6d55-c55d-4bc2-aaee-22d5065430d4)


В дочернем окне в строчке **`Stack`** ставим его на **`gVisor`**

![image](https://github.com/user-attachments/assets/91d68326-9b4c-4f26-9b1d-147cc332f70f)

В этом же окне, правом в нижнем углу нужно поставить галочку **`Режим белого списка`**, чтобы лишние приложения не пускали свой через трафик прокси, а только приложеня белому списку.

![image](https://github.com/user-attachments/assets/a9ce0f78-c762-4464-abec-9a1e907721af)

Дальше прописываем нужные нам процессы которые будут проксироваться, и нажимаем OK

![image](https://github.com/user-attachments/assets/52ee59ea-21f0-434c-be75-56bc06e0f89f)

Теперь что бы оно работало, заспукаем нужный профель, и ставми галочку только на **`Tun Mode`**, **`System Proxy`** мы не трогаем, а то все приложеня будет проходить через весь трафик нашего прокси

![image](https://github.com/user-attachments/assets/6109a17d-f729-4d9d-92cc-13e30a997bc8)

И теперь можем наблюдать что трафик Хрома проходит через прокси, а вот Опера проходит через обычный трафик моего провайдера.

![image](https://github.com/user-attachments/assets/d2d5da05-7bd9-4106-a040-a9ceb975c14c)
