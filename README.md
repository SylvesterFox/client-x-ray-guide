# Как настроить и использовать клиент протакола x-ray

## Для PC
- Для начало скачайте его со страницы офицального репазитория [Nakoray](https://github.com/MatsuriDayo/nekoray/releases/tag/3.26)
- __Но есть для Linux и WIndows__

![i1](https://media.discordapp.net/attachments/617626417718624276/1293158975352606741/Pasted_image_20240930180817.png?ex=67065ba5&is=67050a25&hm=3420ac1b9755bf899e72e0ca8a5252b2ce000d41db89b07acde9b4b4f8108f52&=&format=webp&quality=lossless&width=960&height=208)

### Для Windows

- Когда скачали архив, на его надо разархивиировать в любое вам удобное место.
-  Дальше переходим в деректорю которую мы разархивиировали, и находим исполняемый файл `nakoray.exe`, запускаем.
- Дальше у нас откроется вот такое окно, нажимаем `xray`

![i2](https://media.discordapp.net/attachments/617626417718624276/1293159025013297162/Pasted_image_20240930184616.png?ex=67065bb1&is=67050a31&hm=2853de915ebdef56a86f57cf957c7fe0d97656e2b84cf4a15e72f3dd48c9c2b2&=&format=webp&quality=lossless&width=407&height=334)


- После этого, запустится вот такое приложнние.

![i3](https://media.discordapp.net/attachments/617626417718624276/1293158998094118912/Pasted_image_20240930183351.png?ex=67065baa&is=67050a2a&hm=f3614fb6de5c477ae5130c744fe1424c06efbdc9f1d36ffb4de010dede62d3f9&=&format=webp&quality=lossless&width=528&height=433)

- Дальше на будет нужет вот такой vless ключ-профиля, которой можно получить со адмики ui-x или попрасить у владельца который держит сервер:
```
Который будет выглядить почти вот так

vless://xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
```

- Мы его копируем в буфер обмена, и переходим обратно в наш клиент, в самом клиенте (`Nekoray`)  кликаем на верхней минюшке Program > Add profile from clipboard
- После этого у нас появится профиль нашего подключения
![i4](https://media.discordapp.net/attachments/617626417718624276/1293159056533360701/Pasted_image_20240930185051.png?ex=67065bb8&is=67050a38&hm=f6d6a40adc2d4545cff7f0297990f2c35419aed129d05e6574b699e434943f71&=&format=webp&quality=lossless&width=717&height=104)
- Дальее, ПКМ в контекстном меню выбераем запустить, и сверху от кнопечек ставил две гадлочки `Tun Mode` и `System Proxy`
- И дальше радуемся жизью в интернете
![i5](https://media.discordapp.net/attachments/617626417718624276/1293159092566753302/Pasted_image_20240930185559.png?ex=67065bc1&is=67050a41&hm=cd966428df536e027460ce663d9cda65053f5b6193f63c97672889ced6628252&=&format=webp&quality=lossless&width=960&height=204)

## Распространенные проблемы 
### Клиент использует адаптер Radmin VPN или Hamachi
Частая проблема решается отключением этих адаптеров
`Панель управление >> Центр управления сетями >> Измение параметров адаптера`

![i6](https://cdn.discordapp.com/attachments/617626417718624276/1293257584182296596/image.png?ex=6706b77b&is=670565fb&hm=d0554e79646d8481e4caba93ce393eda7d6f58ee9445340573e37982083aae2d&)

Отключаем адаптеры с назваинем Radmin VPN или Hamachi, правой кнопкой по адаптеру и отключить.

![i7](https://cdn.discordapp.com/attachments/617626417718624276/1293258974337962075/image.png?ex=6706b8c7&is=67056747&hm=49cd0aa0896336b64358157d6626020142211a4739825f97a292401474a422a0&)

## Для android

Для aндроид мы будем использовать приложение `v2rayNG` скачать его можно в Google Play

[i8](https://cdn.discordapp.com/attachments/617626417718624276/1293281832867074162/Screenshot_20241008_213721_com.hihonor.android.launcher.jpg?ex=6706ce10&is=67057c90&hm=c8230a0f73da34913234825203c34815678683ce338f4db428a58340a951c512&)

Открываем его, сверху будет `+` нажимаем на его и покажется контекстное меню предварительно у нас ключ vless должен быть скопирован в буфер обмена, если это сделано то нажимаем `Импорт из буфера обмена`, или если у вас qr-code то `Импорт из QR-кода`

[i9](https://media.discordapp.net/attachments/617626417718624276/1293286087950860360/Screenshot_20241008_215617_com.v2ray.ang.jpg?ex=6706d207&is=67058087&hm=01979ab4d6b623b15d25b4546c58b4e395c671b96273c8255cc4b9649d325a1e&=&format=webp&width=732&height=312)

После данных действей у нас появится профиль, нажимаем на него чтобы выбрать, и на серую кнопку `>` чтобы запустить.

[i10](https://media.discordapp.net/attachments/617626417718624276/1293286087678099516/Screenshot_20241008_215649_com.v2ray.ang.jpg?ex=6706d207&is=67058087&hm=f0c57c63a0cd1d546cc8d82e2b6fd20e7939e9b700740dc56fe4274658fc5c66&=&format=webp&width=960&height=269)

И теперь кайфуем.

## Для IOS

`У меня нету устройства на управление IOS, но вы можете попробовать V2Box, практически аналог v2rayNG`
