---
description: Tasks for lesson "CSS-part1"
---

# HomeWork

## **1.Первый уровень**

Создайте новый проект с HTML и CSS файлами.

Вставьте на страницу блок с цитатой \(о теге читаем [тут](https://developer.mozilla.org/ru/docs/Web/HTML/Element/blockquote)\).

Подключите CSS на созданной вами странице 3-мя способами \(с помощью тега style, атрибута style и файла стилей style.css\).

Задайте цитате 3 разных варианта цвета \(синий, красный и зеленый соответственно\) для каждого из вариантов подключения.

 Проанализируйте, какой из стилей имеет наивысший приоритет.

## **2.Второй уровень**

У вас есть исходный код:

```text
<div class="holder">
  <h1>Title</h1>
  <ul class="list">
    <li>
      <a href="#">link1</a>
      <ul>
        <li><a href="#">link2</a></li>
        <li><a href=""http://validator.w3.org/"">link3</a></li>
      </ul>
    </li>
    <li><a href="https://www.youtube.com/">link4</a></li>
    <li><a href="https://validator.w3.org/">link5</a></li>
    <li><a href="#">link6</a></li>
  </ul>
  <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Dolore, accusamus.</p>
  <h2>Title</h2>
  <p>Lorem ipsum dolor sit amet.</p>
</div>
```

Напишите CSS-селектор, который:

1\) обратиться только к тем ссылкам, значение атрибута `href` которых начинается с **https** и сделайте их красным цветом

2\) применится только для последней ссылки в первом писке \(**list6**\) и задаст ей синий фоновый цвет

3\) будет действовать только для `<p>`, который идет после `<ul>` и задаст размер шрифта 26px

## **3.Второй уровень \(“работаю с css-ом”\)**

Оформите элементы согласно их содержимому \(html не изменяем!\):

```text
<div class="text-holder">
    <h3>Покрасьте меня в розовый цвет (color:pink).</h3>
    <p>Данный элемент должен остаться неоформленным.</p>
    <p id='greycol'>Покрасьте меня в серый цвет (color:grey).</p>
    <div>Данный элемент должен остаться неоформленным.</div>
    <div><p>Покрасьте меня в красный цвет (color:red).</p></div>
    <h3>Данный элемент должен остаться неоформленным.</h3>
    <p>Покрасьте меня в зеленый цвет (color:green).</p>
    <p class='yellow'>Покрасьте меня в желтый цвет (color:yellow).</p>
</div>
```

## **4.Кто совсем молодец \("по желанию"\)**

У вас есть `html`, который **нельзя изменить**. Используем только стили!

```text
<div class="bg-box"></div> 
```

С помощью свойства **background** \(и возможности задать несколько background для одного элемента\) создаем блок следующего вида:

**Ссылки на картинки:** [Дом](https://img2.goodfon.ru/wallpaper/big/0/5b/pole-zelen-trava-dom-derevya.jpg) , [Трава](https://www.freeiconspng.com/uploads/grass-png-images-pictures-transparent-28.png), [Лампочка](https://www.freeiconspng.com/uploads/lamp-png-0.png), [Еж](https://vignette.wikia.nocookie.net/mashaandthebear/images/e/e0/%D0%81%D0%B6%D0%B8%D0%BA.png/revision/latest?cb=20180209130328&path-prefix=ru), [Пончик](https://avatanplus.com/files/resources/mid/58eb07b830eab15b56162788.png)

![](https://github.com/olgamaslovaolga/Alevel-Markup/raw/master/images/img-hw5.png)

