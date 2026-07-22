# LZW-image-generator-on-Babylon.js

Нашел интереснный алгоритм сжатия LZW называется [Простейшие алгоритмы сжатия информации, методы Лемпела-Зива - YouTube](https://www.youtube.com/watch?v=XEOUD5Os1b8&t=329s) ну конечно на Babylon.js ещё этого никто не делал, и я решил создать. 

[LZW image generator on Babylon.js (Version 0 - One image) | Babylon.js Playground](https://playground.babylonjs.com/#M3SVIX#1)

Отлично теперь сделаем множество картинок в ряд.

[LZW image generator on Babylon.js (Version 1 - More LZW images) | Babylon.js Playground](https://playground.babylonjs.com/#T1DNW9#1)

Теперь нужно пореза картинку на RGB ленты и кажду ленту превратить в LZW.

[LZW image generator on Babylon.js (Version 2 - One image LZW RGB Lents GLITCH version) | Babylon.js Playground](https://playground.babylonjs.com/#KO06Y9#2)

Теперь сделаем множество картинок а не одну.

[LZW image generator on Babylon.js (Version 3 - More images LZW RGB Lents GLITCH version) | Babylon.js Playground](https://playground.babylonjs.com/#EOPUV0#1)

Отлично! Теперь сделаем последовательные числа идущие заменим на реликтовые значения юникода, и те которые по 1 оставим LZW.

[LZW image generator on Babylon.js (Version 4 - One image LZW RGB RELIC While sequence) | Babylon.js Playground](https://playground.babylonjs.com/#DEUBYE#1)

Мне нужно сделать много картинок а не одну.

[LZW image generator on Babylon.js (Version 5 - More images LZW RGB RELIC While sequence) | Babylon.js Playground](https://playground.babylonjs.com/#EY1HVD#2)

Что-бы конвертировать в LZW используйте моё приложение -> [A-set-of-numbers-in-a-picture-Tkinter-application-5](https://github.com/MakarovDs777/Turn-a-set-of-numbers-into-a-image-Tkinter-application/blob/main/A-set-of-numbers-in-a-picture-Tkinter-application-5.py)
