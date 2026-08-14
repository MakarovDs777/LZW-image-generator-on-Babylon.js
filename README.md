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

Вообщем я решил смешивать различные типы сжатия без потерь.

[LZW image generator on Babylon.js (Version 12 - LZW on RLE) | Babylon.js Playground](https://playground.babylonjs.com/#8U8WIS#1)

Тоже что предыдущая только с множеством картинок.

[LZW image generator on Babylon.js (Version 13 - LZW on RLE more images) | Babylon.js Playground](https://playground.babylonjs.com/#WVSNLN#1)

Теперь нужно сделать LZW картинку из составных элементов LZW.

[LZW image generator on Babylon.js (Version 14 - LZW One image of the constituent elements of LZW) | Babylon.js Playground](https://playground.babylonjs.com/#4X413B)

Отлично теперь сравним если бы мы это сделали в [10 версией](https://playground.babylonjs.com/#FTFK1D):

<img width="940" height="564" alt="Сохраненное изображение 2026-8-8_17-55-3 811" src="https://github.com/user-attachments/assets/4e82a04a-92be-4d56-a2f4-72673ded95ea" />

И в 14'ой видим разницу:

<img width="804" height="833" alt="Сохраненное изображение 2026-8-8_17-55-48 764" src="https://github.com/user-attachments/assets/5791d487-fcce-4f92-b3c8-4cc3ed3eec9e" />

Теперь нужно сделать для множество картинок а не одной.

[LZW image generator on Babylon.js (Version 15 - LZW More image of the constituent elements of LZW) | Babylon.js Playground](https://playground.babylonjs.com/#MZB8PN#1)

Вернемся к 8 версии, и вместо строки с тем сколько чисел однозначных, двухзначных, трёхзначных идёт подряд просто будем делать в формате поребрика типа префикс A: 1 значит все числа однозначно разделяются B: 2 значит все числа двухзначно разделяются, и так далее в алфавитном порядке.

[LZW image generator on Babylon.js (Version 16 - One image LZW but no space just dict) | Babylon.js Playground](https://playground.babylonjs.com/#T3M3CA)

Отлично теперь сделаем вместо строки с тем сколько чисел однозначных, двухзначных, трёхзначных идёт подряд просто будем делать в формате поребрика типа префикс A: 1 значит все числа однозначно разделяются B: 2 значит все числа двухзначно разделяются, и так далее в алфавитном порядке только для множество картинок а не одной.

[LZW image generator on Babylon.js (Version 17 - More images LZW but no spaces just dict) | Babylon.js Playground](https://playground.babylonjs.com/#1F845S#1)

Совместим 4, и 16 версию для одной картинки.

[LZW image generator on Babylon.js (Version 18 - One image LZW RGB RELIC While sequence but no space just dict) | Babylon.js Playground](https://playground.babylonjs.com/#N2TPJE#3)

Сделаем много картинок как в 17 версии а не одну.

[LZW image generator on Babylon.js (Version 19 - More image LZW RGB RELIC While sequence but no space just dict) | Babylon.js Playground](https://playground.babylonjs.com/#4OLB32#1)

Теперь совместим 2 и 16 версию без пробелов.

[LZW image generator on Babylon.js (Version 20 - One image LZW RGB Lents but no space just dict) | Babylon.js Playground](https://playground.babylonjs.com/#Z1SM6V)

И как всегда для множество картинок.

[LZW image generator on Babylon.js (Version 21 - More images LZW RGB Lents but no space just dict) | Babylon.js Playground](https://playground.babylonjs.com/#WM6RIZ#1)

Что-бы конвертировать в LZW используйте моё приложение -> [A-set-of-numbers-in-a-picture-Tkinter-application-5](https://github.com/MakarovDs777/Turn-a-set-of-numbers-into-a-image-Tkinter-application/blob/main/A-set-of-numbers-in-a-picture-Tkinter-application-5.py)
