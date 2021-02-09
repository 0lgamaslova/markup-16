# HomeWork 3

### **1.Первый уровень**

Создайте новый проект с HTML и CSS файлами.Вставьте на страницу блок с цитатой \(о теге читем [тут](https://developer.mozilla.org/ru/docs/Web/HTML/Element/blockquote)\).Подключите CSS на созданной вами странице 3-мя способами \(с помощью тега style, атрибута style и файла стилей style.css\).Задайте цитате 3 разных варианта цвета \(синий, красный и зеленый соответственно\). Проанализируйте, какой из стилей имеет наивысший приоритет.

### **2.Второй уровень**

У вас есть исходный код:

```text
<div class="holder">
  <h1>Title</h1>
  <ul class="list">
    <li>
      <a href="#">link1</a>
      <ul>
        <li><a title="youtube" href="http://www.youtube.com/"">link2</a></li>
        <li><a href="#">link3</a></li>
      </ul>
    </li>
    <li><a title="youtube" href="https://www.youtube.com/">link4</a></li>
    <li><a href="https://validator.w3.org/" title="link">link5</a></li>
    <li><a href="#">link6</a></li>
  </ul>
  <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Dolore, accusamus.</p>
  <h2>Title</h1>
  <p>Lorem ipsum dolor sit amet.</p>
</div>
```

Напишите CSS-селектор, который:1\) обратиться только к тем ссылкам, значение атрибута `href` которых начинается с **https** и окрасит их в красный цвет \(color: \#f00;\)2\) окрасить link2 в оранжевый цвет \(color: \#ff8d00;\);3\) `<p>`, который идет после `<ul>`, сделает размер шрифта 30px4\) задаст ссылкам, у которых есть атрибут title, зеленый бордер \(border: 1px solid \#067b09;\)

\*\*\*\*

### **3.Третий уровень**

Оформите элементы согласно их содержимому:

```text
<div class="text-box">
    <h3>Покрасьте меня в розовый цвет (color: pink).</h3>
    <p>Данный элемент должен остаться неоформленным.</p>
    <p id='greycol'>Покрасьте меня в серый цвет (color: grey).</p>
    <div>Данный элемент должен остаться неоформленным.</div>
    <h3>Данный элемент должен остаться неоформленным.</h3>
    <div>
        <p>Покрасьте меня в красный цвет (color: red).</p>
    </div>
    <h3 title="text">У меня текст будет синим (color: blue;)</h3>
    <p>Покрасьте меня в зеленый цвет (color: green).</p>
    <p class='yellow'>Покрасьте меня в желтый цвет (color: yellow).</p>
</div>
```

