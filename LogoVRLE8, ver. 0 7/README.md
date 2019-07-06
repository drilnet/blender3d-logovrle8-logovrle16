Лицензия: **Free**.

![](https://github.com/drilnet/blender3d-logovrle8-logovrle16/blob/master/UA.png)

### Содержимое

**Каталоги:**

```
Frames (200) 35% (224x119) - Анимация, 200 кадров в формате png (упакованные архиватором 7z).
Frames (200) 45% (288x153) - -/-
Frames (200) 55% (352x187) - -/-
Frames (200) 65% (416x221) - -/-
Frames (200) 75% (480x255) - -/-
```

**Нарезка (224x119px):**

```
LogoVRLE8, 35% (224x119) HQ.webp - Анимационный логотип в формате WEBP (Hight Quality).
LogoVRLE8, 35% (224x119) LQ.webp - Анимационный логотип в формате WEBP (Low Quality).
LogoVRLE8, 35% (224x119).gif     - Анимационный логотип в формате GIF, без оптимизации.
LogoVRLE8, 35% (224x119).jpg     - Изображение логотипа в формате JPG.
LogoVRLE8, 35% (224x119).png     - Изображение логотипа в формате PNG.
```

**Нарезка (288x153px):**

```
LogoVRLE8, 45% (288x153) HQ.webp - Анимационный логотип в формате WEBP (Hight Quality).
LogoVRLE8, 45% (288x153) LQ.webp - Анимационный логотип в формате WEBP (Low Quality).
LogoVRLE8, 45% (288x153).gif     - Анимационный логотип в формате GIF, без оптимизации.
LogoVRLE8, 45% (288x153).jpg     - Изображение логотипа в формате JPG.
LogoVRLE8, 45% (288x153).png     - Изображение логотипа в формате PNG.
```

**Нарезка (352x187px):**

```
LogoVRLE8, 55% (352x187) HQ.webp - Анимационный логотип в формате WEBP (Hight Quality).
LogoVRLE8, 55% (352x187) LQ.webp - Анимационный логотип в формате WEBP (Low Quality).
LogoVRLE8, 55% (352x187).gif     - Анимационный логотип в формате GIF, без оптимизации.
LogoVRLE8, 55% (352x187).jpg     - Изображение логотипа в формате JPG.
LogoVRLE8, 55% (352x187).png     - Изображение логотипа в формате PNG.
```

**Нарезка (416x221px):**

```
LogoVRLE8, 65% (416x221) HQ.webp - Анимационный логотип в формате WEBP (Hight Quality).
LogoVRLE8, 65% (416x221) LQ.webp - Анимационный логотип в формате WEBP (Low Quality).
LogoVRLE8, 65% (416x221).gif     - Анимационный логотип в формате GIF, без оптимизации.
LogoVRLE8, 65% (416x221).jpg     - Изображение логотипа в формате JPG.
LogoVRLE8, 65% (416x221).png     - Изображение логотипа в формате PNG.
```

**Нарезка (480x255px):**

```
LogoVRLE8, 75% (480x255) HQ.webp - Анимационный логотип в формате WEBP (Hight Quality).
LogoVRLE8, 75% (480x255) LQ.webp - Анимационный логотип в формате WEBP (Low Quality).
LogoVRLE8, 75% (480x255).gif     - Анимационный логотип в формате GIF, без оптимизации.
LogoVRLE8, 75% (480x255).jpg     - Изображение логотипа в формате JPG.
LogoVRLE8, 75% (480x255).png     - Изображение логотипа в формате PNG.
```

**Файлы Blender'а:**

```
LogoVRLE8.blend      - Логотип VRLE8 (сделано в Blender 2.79b).
LogoVRLE8.blend.copy - Копия.
RLE.Mesh.blend       - Надпись RLE преобразована из Безье в Меш (сделано в Blender 2.79b ).
RLE.Mesh.blend.copy  - Копия.
```

### Дополнительная информация

**WEBP-файлы! Как сделать?**

Я пользовался вот этим [libwebp-1.0.2-rc1-windows-x86-no-wic.zip](https://storage.googleapis.com/downloads.webmproject.org/releases/webp/libwebp-1.0.2-rc1-windows-x86-no-wic.zip) (утилита [img2webp.exe](https://developers.google.com/speed/webp/docs/img2webp)).
<br>
Репозиторий с разными версиями и подразные платформы [здесь](https://storage.googleapis.com/downloads.webmproject.org/releases/webp/index.html).
<br>
Официальный сайт разработчика [здесь](https://developers.google.com/speed/webp/).

Как пользоваться утилитой [img2webp.exe](https://developers.google.com/speed/webp/docs/img2webp)?


Пример 1 (сжатие без потерь).
```
> img2webp.exe -loop 0 -lossless -q 100 -m 6 -d 1000 0001.png 0002.png 0003.png -o file.webp
```

Где:

```
                   -loop 0 - бесконечный цикл;
                 -lossless - сжатие без потерь;
                    -q 100 - коэффициент сжатия;
                      -m 6 - метод сжатия;
                   -d 1000 - задержка между кадрами в миллисекундах;
0001.png 0002.png 0003.png - изображения из которых будет сделана анимация;
              -o file.webp - выходной файл будет 'file.webp'.
```

Пример 2 (сжатие с потерями).
```
> img2webp.exe -loop 0 -lossy -q 95 -m 6 -d 1000 0001.png 0002.png 0003.png -o file.webp
```

Где:

```
                   -loop 0 - бесконечный цикл;
                    -lossy - сжатие с потерями;
                     -q 95 - коэффициент сжатия;
                      -m 6 - метод сжатия;
                   -d 1000 - задержка между кадрами в миллисекундах;
0001.png 0002.png 0003.png - изображения из которых будет сделана анимация;
              -o file.webp - выходной файл будет 'file.webp'.
```

### Информационные ресурсы (Вики):

* [3D редактор Blender](https://ru.wikipedia.org/wiki/Blender) ([UKR](https://uk.wikipedia.org/wiki/Blender))

