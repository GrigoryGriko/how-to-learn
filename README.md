﻿# Одностраничный сайт научиться учиться

## О проекте
Проект представляет собой одностраничный сайт с информацией о рекомендации к подходу к обучению.
1. Реализована цикличная анимация вращения элементов с помощью установки начального и конечного положения правилом keyframes и использования свойства animation. 
Модификатор rotation вынесен в отдельный БЭМ-блок файловой структуры.
2. Сделана интеграция видео с функционалом воспроизведения со стороннего сайта с использованием тегов iframe.
3. Реализовано плавное изменение прозрачности ссылок при наведении на них, для этого спользован псевдокласс hover, чтобы задать свойство opacity,
которое будет применено при наведении на элемент. А свойство transition использовано для плавного изменения opacity.
4. Был сделан рефакторинг с использованием концепции БЭМ nested: стили блока, элемента и модификатора вынесены из общего файла стилей отдельными файлами, 
имена которых соответсвует названию селектора. Создана файловая структура в которой в каждый блок вложен соотвествующие элементы и модификаторы.

Ссылка на GitHub Pages: https://grigorygriko.github.io/how-to-learn/