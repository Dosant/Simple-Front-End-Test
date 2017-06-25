# Простое Front-end испытание
Испытание состоит из:

* 1-го простейщего входного вопроса
* 2-ух простых испытаний по HTML / CSS
* 1-ой задачке по JS, немного работы с массивами
* 1-ого тестика на работу с DOM и Событиями

## 1. `div` vs `span`
**вопрос:** Чем отличиается `div` от `span`?

**ответ:** `div` - блочный элемент. `span` - строчный

**дополнительно:** Нельзя добавлять блочный элемент внутрь строчного. [Stackoverflow: div vs span](https://stackoverflow.com/questions/183532/what-is-the-difference-between-html-tags-div-and-span)

## 2. Выровнять по горизонтали
![Результат](https://d26dzxoao6i3hh.cloudfront.net/items/1V1K0A2o372K3v1N1x42/Снимок%20экрана%202017-06-25%20в%2016.23.54.png)

* [Старт](https://jsbin.com/puzusuj/5/edit?html,css,output)
* [Финиш](https://jsbin.com/puzusuj/6/edit?html,css,output)

#### **дополнительно**: Выровнять по вертикали:

![Результат](https://d26dzxoao6i3hh.cloudfront.net/items/2T2l3J1b210D0l3g312Z/Снимок%20экрана%202017-06-25%20в%2016.30.47.png)

* [Старт](https://jsbin.com/puzusuj/7/edit?html,css,output)
* [Финиш](https://jsbin.com/puzusuj/8/edit?html,css,output)

## 3. Простая сетка
Если ширина окна >480px, aside контент занимает 1/3 экрана:

![Результат](https://cl.ly/3f2E132Z2R0d/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202017-06-25%20%D0%B2%2016.51.47.png)

Если ширина окна <=480px, сначала aside контент, потом основной. На всю ширину:

![Результат](https://cl.ly/0I2Z0c272n05/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202017-06-25%20%D0%B2%2016.51.56.png)

* [Старт](https://jsbin.com/ciqesi/2/edit?html,css,output)
* [Финиш](https://jsbin.com/ciqesi/1/edit?html,css,output)

## 4. Базовый JS на примере массивов
![Tests](https://cl.ly/2p3I0m0i2l0r/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202017-06-25%20%D0%B2%2017.19.35.png)

* [Старт](https://jsbin.com/ciqesi/2/edit?html,css,output)
* [Финиш](https://jsbin.com/ciqesi/1/edit?html,css,output)

## 5. DOM, События - 2-way binding
Нужно сделать простейший 2-way data binding. Есть `<input type="text" />`. Пользователь вводит текст и изменения сразу же отображаются в элементе `<p>`. По клику на кнопку *Очистить* текст чистится из `input` и `p`.

![Example](https://cl.ly/062L3v242o0y/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202017-06-25%20%D0%B2%2017.34.35.png)

* [Старт](https://jsbin.com/vipowey/2/edit?html,js,output)
* [Финиш](https://jsbin.com/vipowey/1/edit?html,js,output)
