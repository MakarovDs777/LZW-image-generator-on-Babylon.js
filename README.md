# LZW-image-generator-on-Babylon.js

Нашел интереснный алгоритм сжатия LZW называется [Простейшие алгоритмы сжатия информации, методы Лемпела-Зива - YouTube](https://www.youtube.com/watch?v=XEOUD5Os1b8&t=329s) ну конечно на Babylon.js ещё этого никто не делал, и я решил создать. 

[LZW image generator on Babylon.js (Version 0 - One image) | Babylon.js Playground](https://playground.babylonjs.com/#M3SVIX#1)

Отлично теперь сделаем множество картинок в ряд.

[LZW image generator on Babylon.js (Version 1 - More LZW images) | Babylon.js Playground](https://playground.babylonjs.com/#T1DNW9#1)

Теперь нужно порезать картинку на RGB ленты и кажду ленту превратить в LZW.

[LZW image generator on Babylon.js (Version 2 - One image LZW RGB Lents GLITCH version) | Babylon.js Playground](https://playground.babylonjs.com/#KO06Y9#2)

Теперь сделаем множество картинок а не одну.

[LZW image generator on Babylon.js (Version 3 - More images LZW RGB Lents GLITCH version) | Babylon.js Playground](https://playground.babylonjs.com/#EOPUV0#1)

Отлично! Теперь сделаем последовательные числа идущие заменим на реликтовые значения юникода, и те которые по 1 оставим LZW.

[LZW image generator on Babylon.js (Version 4 - One image LZW RGB RELIC While sequence) | Babylon.js Playground](https://playground.babylonjs.com/#DEUBYE#1)

Мне нужно сделать много картинок а не одну.

[LZW image generator on Babylon.js (Version 5 - More images LZW RGB RELIC While sequence) | Babylon.js Playground](https://playground.babylonjs.com/#EY1HVD#2)

Теперь уберём RELIC оставим только RELIC на LZW.

[LZW image generator on Babylon.js (Version 6 - One image LZW RGB + RELIC) | Babylon.js Playground](https://playground.babylonjs.com/#VMVI47#1)

Сделаем много картинок а не одну без RELIC.

[LZW image generator on Babylon.js (Version 7 - More images LZW RGB + RELIC) | Babylon.js Playground](https://playground.babylonjs.com/#CSFU6U)

Короче сделаем LZW без отступов.

[LZW image generator on Babylon.js (Version 8 - One image LZW NO SPACE) | Babylon.js Playground](https://playground.babylonjs.com/#VHBUME)

Короче сделаем много LZW без отступов.

[LZW image generator on Babylon.js (Version 9 - More images LZW NO SPACE) | Babylon.js Playground](https://playground.babylonjs.com/#352C7O#2)

Теперь сделаем по паттернам.

[LZW image generator on Babylon.js (Version 10 - One image LZW via patterns) | Babylon.js Playground](https://playground.babylonjs.com/#3LIQ4J)

Сделаем много картинок а не одну.

[LZW image generator on Babylon.js (Version 11 - More image LZW via patterns) | Babylon.js Playground](https://playground.babylonjs.com/#ILI7HD)

Что-бы конвертировать в LZW используйте моё приложение -> [A-set-of-numbers-in-a-picture-Tkinter-application-5](https://github.com/MakarovDs777/Turn-a-set-of-numbers-into-a-image-Tkinter-application/blob/main/A-set-of-numbers-in-a-picture-Tkinter-application-5.py)
