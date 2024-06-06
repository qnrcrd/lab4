<p align = "center">МИНИСТЕРСТВО НАУКИ И ВЫСШЕГО ОБРАЗОВАНИЯ<br>
РОССИЙСКОЙ ФЕДЕРАЦИИ<br>
ФЕДЕРАЛЬНОЕ ГОСУДАРСТВЕННОЕ БЮДЖЕТНОЕ<br>
ОБРАЗОВАТЕЛЬНОЕ УЧРЕЖДЕНИЕ ВЫСШЕГО ОБРАЗОВАНИЯ<br>
«САХАЛИНСКИЙ ГОСУДАРСТВЕННЫЙ УНИВЕРСИТЕТ»</p>
<br><br><br><br><br><br>
<p align = "center">Институт естественных наук и техносферной безопасности<br>Кафедра информатики<br>Безруков Никита Валерьевич</p>
<br><br><br>
<p align = "center"><br><strong>Лабораторная работа №4.«HTML»</strong><br>01.03.02 Прикладная математика и информатика</p>
<br><br><br><br><br><br><br><br><br><br><br><br>
<p align = "right">Научный руководитель<br>
Соболев Евгений Игоревич</p>
<br><br><br>
<p align = "center">г. Южно-Сахалинск<br>2024 г.</p>
<br><br><br><br><br><br><br><br><br><br><br><br>

<h1 align = "center">Введение</h1>

<p><b>HTML</b> —  стандартизированный язык гипертекстовой разметки документов для просмотра веб-страниц в браузере. Веб-браузеры получают HTML документ от сервера по протоколам HTTP/HTTPS или открывают с локального диска, далее интерпретируют код в интерфейс, который будет отображаться на экране монитора.</p>

<h1 style="text-align: center">Задачи</h1>
<ol>
  <li>Используйте 3 способа подключения CSS</li>
  <li>Сделайте все абзацы p красного цвета</li>
  <li>Сделайте все h1 зеленого цвета.</li>
  <li> Сделайте все h2 голубого цвета.</li>
  <li> Сделайте все h3 оранжевого цвета.</li>
  <li>Сделайте первый на странице абзац p зеленого цвета.</li>
  <li> Сделайте второй на странице абзац p красного цвета.</li>
  <li>Сделайте все абзацы h2 шириной 300px.</li>
  <li> Сделайте все таблицы table шириной 400px, высотой 200px.</li>
  <li>Поставьте все h1 по центру</li>
  <li> Поставьте все h2 по правому краю</li>
  <li>Сделайте так, чтобы текст в абзацах p был выровнен одновременно и по правому, и по левому краю.</li>
  <li>Сделайте так, чтобы во втором абзаце p текст был выровнен по центру</li>
  <li> Поставьте все th по левому краю</li>
  <li> Поставьте все td по центру</li>
  <li>Сделайте все td жирным</li>
  <li> Сделайте h1 нежирным</li>
  <li>Сделайте одновременно th, h1 и h2 нежирным</li>
  <li>Сделайте все h2 курсивом</li>
  <li>Сделайте все абзацы p курсивом, а первый абзац - нет</li>
  <li>Сделайте все h2 20px</li>
  <li>Сделайте все абзацы p 15px</li>
  <li>Сделайте для абзацев p шрифт Arial</li>
  <li>Сделайте для h2 шрифт Times New Roman</li>
  <li>Сделайте для h3 любой шрифт без засечек</li>
  <li>Сделайте межстрочный интервал для абзацев p в 30px.</li>
  <li>Закомментируйте некоторые стили для абзацев.</li>
  <li>Для p сделайте шрифт Arial, 16 пикселей, курсив, жирный, межстрочный интервал в 30px</li>
  <li>Для h1 сделайте следующий шрифт: нежирный, 20 пикселей, Verdana.</li>
  <li>Сделайте красную строку в абзацах 30px</li>
  <li> Для второго абзаца p уберите красную строку</li>
  <li>Поставьте текст в таблице table по верхнему краю по вертикали</li>
  <li>Поставьте текст в th по центру по вертикали.</li>
  <li>Повторите страницу по данному по образцу</li>
  <li>Повторите страницу по данному по образцу</li>
  <li>Создать анимированный кнопку с использованием CSS</li>
  <li>Создать адаптивный макет страницы с помощью CSS Grid</li>
  <li>Стилизовать форму ввода данных с использованием CSS</li>
  <li>Создать анимированное меню навигации с использованием CSS</li>
  <li>Изучить и применить различные типы селекторов в CSS</li>
  <li>Создать градиентный фон с использованием CSS</li>
  <li>Изучить и применить различные свойства шрифтов в CSS</li>
  <li>Создать анимированный слайдер изображений с использованием CSS</li>
  <li>Изучить и применить различные методы позиционирования элементов в CSS</li>
  <li>Создать адаптивный макет с использованием медиа-запросов в CSS</li>
  <li>Изучить и применить различные техники создания анимаций с помощью CSS</li>
  <li>Создать стилизованные карточки товаров с использованием CSS</li>
  <li>Изучить и применить различные единицы измерения в CSS</li>
  <li>Создать анимированную загрузку страницы с использованием CSS</li>
  <li>Изучить и применить различные способы создания теней и эффектов в CSS</li>
</ol>

<h1 style="text-align: center">Решения Задач</h1>

<h2 style="text-align: center">Файл Заданий 1-33 (и еще 48) </h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>1-33</title>
    <link rel="stylesheet" href="styles/1-33.css">
</head>
<body>
    <p style="color:green; font-style: normal;">abzac 1</p><!--6-->
    <p style="color: red; text-align: center; text-indent: 0%;">abzac 2</p><!--7,31-->
    <p>abzac 3</p>
    <h1>zagolovok 1</h1>
    <h2>zagolovok 2</h2>
    <h3>zagolovok 3</h3>

    <table>
        <thead>
          <tr>
            <th>name</th>
            <th>age</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>Mark</td>
            <td>25</td>
          </tr>
          <tr>
            <td>Pam</td>
            <td>30</td>
          </tr>
        </tbody>
      </table>


    <style>
        p
        {
            /*2,22,23,28,12,16,26*/
            color:red;
            line-height: 30px;
            font-family: Arial;
            font-style: italic;
            font-weight: bold;
            font-size: 16px;
            text-align: justify;
            text-indent: 30px;/*30*/
        }
    </style>
</body>
</html>
```
<h2 style="text-align: center">использованный styles/1-33.css</h2>

```css
h1
{
    color:green;/*3*/
    text-align: center;/*10*/
    font-weight: normal;/*17*/
    /*29*/
    font-size: 20px;
    font-family: Verdana;
}

th, h1, h2 /*18*/
{
    font-weight: normal;
}

h2
{
    color:aqua;/*4*/
    width: 300px;/*8*/
    font-size: 20px;/*21*/
    text-align: right;/*11*/
    font-style: italic;
    font-family: 'Times New Roman';/*24*/

}

h3
{
    color:orange;/*5*/
    font-family: sans-serif;/*25*/
}

table/*9*/
{
    width: 400px;
    height:200px;
    vertical-align: top;/*32*/
}

th /*14*/
{
    text-align: left;
    vertical-align: middle;
    font-size: 2pc;/*48*/
}
  
td /*15,16*/
{
    text-align: center;
    font-weight: bold;
    font-size: 7mm;/*48*/
}
```

<h2 style="text-align: center">Файл Заданий 34,40 </h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>34_40</title>
</head>
<body>
    <h1>Что такое CMS</h1>

<p>
  <strong>CMS</strong> - «система управления контентом» (<strong>движок</strong>) - написанная PHP-программистами основа для сайта, с помощью которой вы сможете управлять сайтом (добавлять контент, менять пункты меню и т.п.) не зная HTML и CSS.
</p>

<p>
  Однако, для того чтобы сделать сайт с помощью <strong>CMS</strong>, <span class="highlight">потребуются услуги</span> и программиста, и дизайнера, и верстальщика. И капиталовложения.
</p>

<h2>Какие бывают cms</h2>

<p>
  Бывают различные системы управления контентом: для интернет-магазинов, для блогов, для форумов и т.д.
</p>

<h2>Примеры cms</h2>

<p>
  <span class="highlight">Примеры популярных CMS</span>: Joomla, WordPress (для блогов), PhpBB (для форумов).
</p>

<p>
  <strong>CMS</strong>-ки бывают <span class="highlight">платные</span> и <span class="highlight">бесплатные</span>.
</p>
</body>
<style>
    body 
    {
      font-family: sans-serif;
      text-align: center;
      padding-left: 700px;
      padding-right: 700px;
      line-height: 30px;
    }
    h1 /*tag selected*/
    {
      text-align: center;
      color:blue;
      font-size: medium;
      font-family: 'Times New Roman', Times, serif;
    }
    .highlight /*class selected*/
    {
      font-style: italic;
      color: blue;

    }
    h2
    {
        text-align: center;
        color:blue;
        font-size: small;
        font-family: 'Times New Roman', Times, serif;
    }
    strong 
    {
        color: red;
        font-weight: bold;
    }
    * /*all selected*/
    {
      margin: 0;
      padding:0;
    }
  </style>
</html>
```
<h2 style="text-align: center">Файл Задания 35 </h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>35</title>
</head>
<body>
    <h1 style="font-family: 'Times New Roman', Times, serif;">Что нужно знать, чтобы делать сайты</h1>

<ol>
  <li><span class="highlight">HTML</span></li>
  <li><span class="blue">CSS</span></li>
  <li>PHP</li>
  <li>SQL</li>
  <li>JavaScript</li>
  <li>jQuery</li>
  <li>Flash</li>
  <li>SEO</li>
</ol>

<h2 style="font-family: 'Times New Roman', Times, serif; color:green">PHP и JavaScript</h2>

<p>
  Языки программирования <span class="highlight">PHP</span> и <span class="highlight">JavaScript</span> позволяют сделать сайт динамичным, то есть реагирующим на действия пользователя. Например, можно сделать красивую выпадающую менюшку или слайдер.
</p>

<h2 style="font-family: 'Times New Roman', Times, serif; color:green">Виды скриптов</h2>

<p>
  Для этого пишутся скрипты (англ. <span class="blue">script</span> - "сценарий") - программы, позволяющие реагировать на действия пользователя. Скрипты бывают двух видов:
</p>

<ul>
  <li>
    те, которые выполняются на сервере, а результат их выполнения приходит в браузер к пользователю уже в готовом виде. Это скрипты, написанные на языке <span class="highlight">PHP</span>. На нем пишутся <span class="highlight">CMS-ки</span> - системы управления контентом.
  </li>
  <li>
    те, которые выполняются прямо в браузере пользователя. Это скрипты, написанные на языке <span class="highlight">JavaScript</span>. Они чаще всего используются для того, чтобы сделать страницу более удобной и красивой.
  </li>
</ul>

    <style>
        body {
          font-family: sans-serif;
        }
        h1 {
          text-align: center;
          color: red;
        }
        .highlight {
          font-weight: bold;
          color: red;
          font-size:x-large;
        }
        ol 
        {
            font-family: 'Times New Roman', Times, serif;
            margin-left: 20px;
            color: red;
        }
        .blue
        {
            color:blue;
            font-style: italic;
            font-weight: bold;
        }
        ul
        {
            color: rgb(177, 82, 82);
            font-style: italic;
            font-family: 'Times New Roman', Times, serif;
        }
      </style>
</body>
</html>
```

<h2 style="text-align: center">Файл Задания 36 </h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>36</title>
    <link rel="stylesheet" href="styles/36.css">
</head>
<body>
    <button class="button">button</button>
</body>
</html>
```
<h2 style="text-align: center">использованный styles/36.css</h2>

```css
.button {
    background-color: red;
    border: none;
    color: white;
    padding: 15px 32px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
    margin: 4px 2px;
    cursor: pointer;
    transition: all 0.3s ease;
    border-radius: 5px;
  }

  .button:hover {
    background-color: red;
    box-shadow: 0px 5px 10px rgba(0, 0, 0, 0.2);
    transform: translateY(-2px);
  }
```

<h2 style="text-align: center">Файл Задания 37 </h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="styles/37.css">
</head>
<body>
    <div class="container">
        <div class="item">
          <h2>zagol 1</h2>
          <p>texttexttexttexttexttext</p>
        </div>
        <div class="item">
          <h2>zagol 2</h2>
          <p>texttexttexttexttexttexttexttext</p>
        </div>
        <div class="item">
          <h2>zagol 3</h2>
          <p>texttexttexttexttexttexttext</p>
        </div>
        <div class="item">
          <h2>zagol 4</h2>
          <p>texttexttexttexttexttext</p>
        </div>
      </div>
</body>
</html>
```
<h2 style="text-align: center">использованный styles/37.css</h2>

```css
body 
{
    margin: 0;
    font-family: sans-serif;
}

.container 
  {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
    padding: 20px;
  }

.item 
{
    background-color: #f5f5f5;
    padding: 20px;
    border-radius: 5px;
}
```

<h2 style="text-align: center">Файл Задания 38 </h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>38</title>
    <link rel="stylesheet" href="styles/38.css">
</head>
<body>
    <div class="wrapper">
        <div class="container">
            <form action="">
                <h1>
                    <i class="fas fa-shipping-fast"></i>
                    Deliver Info
                </h1>
                <div class="name">
                    <div>
                        <label for="f-name">First</label>
                        <input type="text" name="f-name">
                    </div>
                    <div>
                        <label for="l-name">Last</label>
                        <input type="text" name="l-name">
                    </div>
                </div>
                <div class="street">
                    <label for="name">Street</label>
                    <input type="text" name="address">
                </div>
                <div class="address-info">
                    <div>
                        <label for="city">City</label>
                        <input type="text" name="city">
                    </div>
                    <div>
                        <label for="state">State</label>
                        <input type="text" name="state">
                    </div>
                    <div>
                        <label for="zip">Country</label>
                        <input type="text" name="zip">
                    </div>
                </div>
                <h1>
                    <i class="far fa-credit-card"></i> Payment Information
                </h1>
                <div class="cc-num">
                    <label for="card-num">Credit Card No.</label>
                    <input id="id1" type="text" name="card-num">
                </div>
                <div class="cc-info">
                    <div>
                        <label for="card-num">Expire date</label>
                        <input type="date" name="expire">
                    </div>
                    <div>
                        <label for="card-num">CCV</label>
                        <input type="number" name="security">
                    </div>
                </div>
                <div class="btns">
                    <button onclick="checkotexto()">Purchase</button>
                    <script>
                        function checfornonnum(text)
                        {
                            let numeronot=/[^0-9\s]/;
                            if(numeronot.test(text))
                            {
                                return true;
                            }
                            else
                            {
                                return false;
                            }
                        }
                
                        function checkotexto()
                        {
                            let input=document.getElementById("id1").value;
                            if(checfornonnum(input))
                            {
                                alert("incorrect card num input!");
                            }
                            else
                            {
                                console.log("Yes!")
                            }
                        }
                    </script>
                </div>
            </form>
        </div>
    </div>
</body>
</html>
```
<h2 style="text-align: center">использованный styles/38.css</h2>

```css
body{font-family:Arial, Helvetica, sans-serif;}


body {
    display: flex;
    justify-content: center;
}

.wrapper {
    margin-top: 5%;
    width: 60%;
    display: flex;
    justify-content: center;
    font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: rgb(77, 212, 84);
    -webkit-box-shadow: 9px 13px 25px 0px rgba(0, 0, 0, 0.18);
    -moz-box-shadow: 9px 13px 25px 0px rgba(0, 0, 0, 0.18);
    box-shadow: 9px 13px 25px 0px rgba(0, 0, 0, 0.18);
}

@keyframes slideUp {
    0% {
        -webkit-transform: translateY(100%);
        transform: translateY(100%);
        visibility: visible;
    }

    100% {
        -webkit-transform: translateY(0);
        transform: translateY(0);

    }
}

.container {
    width: 65%;
    padding: 5% 10%;
}

h1 {
    align-self: center;
}

form {
    width: 100%;

    >* {
        margin-top: 20px;
    }

    input {
        width: 100%;
        min-height: 25px;
        border: 0;
        font-size: 1rem;
        letter-spacing: .15rem;
        font-family: "Arimo";
        margin-top: 5px;
        color: rgb(0, 0, 0);
        border-radius: 4px;
    }

    label {
        text-transform: uppercase;
        font-size: 12px;
        letter-spacing: 2px;
        color: rgb(3, 3, 3);
    }

    h1 {
        font-size: 24px;
        line-height: 10px;
        color: rgb(0, 0, 0);
        letter-spacing: 1px;
    }

    h1:nth-of-type(2) {
        margin-top: 10%;
    }
}

.name {
    justify-content: space-between;
    display: flex;
    width: 100%;

    div {
        width: 45%;
    }
}

.address-info {
    display: flex;
    justify-content: space-between;

    div {
        width: 30%;
    }
}

.cc-info {
    display: flex;
    justify-content: space-between;

    div {
        width: 45%;
    }
}

.btns {
    display: flex;
    flex-direction: column;
    align-items: flex-end;

    button {
        margin: 3px 0;
        height: 30px;
        width: 40%;
        color: #000000;
        background-color: rgb(255, 153, 0);
        text-transform: uppercase;
        border: 0;
        border-radius: .3rem;
        letter-spacing: 2px;

        &:hover {
            animation-name: btn-hov;
            animation-duration: 550ms;
            animation-fill-mode: forwards;
        }
    }
}

@keyframes btn-hov {
    100% {
        background-color: #dd78d5;
        color: #4a3b76;
        transform: scale(1.05)
    }
}

input:focus,
button:focus {
    outline: none;
}

@media (max-width: 736px) {
    .wrapper {
        width: 100%;
    }

    .container {
        width: 100%;
    }

    .btns {
        align-items: center;

        button {
            width: 50%;
        }
    }

    form h1 {
        text-align: center;
    }

    .name,
    .address-info,
    .cc-info {
        flex-direction: column;
        width: 100%;
        justify-content: space-between;

        div {
            align-items: center;
            flex-direction: column;
            width: 100%;
            display: flex;
        }
    }

    .street,
    .cc-num {
        text-align: center;
    }

    input {
        margin: 5px 0;
        min-height: 30px;
    }
}
```
<h2 style="text-align: center">Файл Задания 39 </h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="styles/39.css">
</head>
<body>
    <nav>
        <ul>
          <li><a href="#">Main</a></li>
          <li><a href="#">About us</a></li>
          <li><a href="#">services</a></li>
          <li><a href="#">contacts</a></li>
        </ul>
      </nav>
</body>
</html>
```
<h2 style="text-align: center">использованный styles/39.css</h2>

```css
body {
    font-family: Arial, sans-serif;
  }
  
  nav ul {
    list-style: none;
    padding: 0;
    margin: 0;
    display: flex;
  }
  
  nav ul li {
    margin: 0 20px;
  }
  
  nav ul li a {
    text-decoration: none;
    color: #333;
    position: relative;
  }
  
  nav ul li a::after {
    content: '';
    position: absolute;
    width: 100%;
    transform: scaleX(0);
    height: 2px;
    bottom: -5px;
    left: 0;
    background-color: #007bff;
    transform-origin: bottom right;
    transition: transform 0.3s ease;
  }
  
  nav ul li a:hover::after {
    transform: scaleX(1);
  }
```
<h2 style="text-align: center">Файл Заданий 41,42,44 </h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>41_42_44</title>
    <link rel="stylesheet" href="styles/41_42_44.css">
</head>
<body>
    <p>gradient</p>

    <div class="container">
        <div class="block block-static"></div>
        <div class="block block-relative"></div>
        <div class="block block-absolute"></div>
        <div class="block block-fixed"></div>
        <div class="block block-sticky"></div>
      </div>
</body>
</html>
```
<h2 style="text-align: center">использованный styles/41_42_44.css</h2>

```css
body 
{
    margin: 0;
    background-image: linear-gradient(to left, #67ffff, #237fbd);
    min-height: 100vh;
}

/*42*/
p
{
    color:rgb(151, 21, 21);
    text-align: center;
    font-weight: normal;
    font-size: 20px;
    font-family: Verdana;
}

.container {
    position: relative;
    width: 100%;
    height: 300px;
    background-color:linear-gradient(to left, #67ffff, #237fbd);
  }

  .block {
    width: 100px;
    height: 100px;
    border-radius: 5px;
    position: absolute;
  }

  .block-static {
    background-color: red;
  }

  .block-relative {
    position: relative;
    top: 20px;
    left: 30px;
    background-color: orange;
  }

  .block-absolute {
    position: absolute;
    top: 50px;
    right: 50px;
    background-color: rgb(162, 0, 255);
  }

  .block-fixed {
    position: fixed;
    top: 100px;
    left: 100px;
    background-color: green;
  }

  .block-sticky {
    position: sticky;
    top: 150px;
    background-color: blue;
  }
```

<h2 style="text-align: center">Файл Задания 43 </h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>43</title>
    <link rel="stylesheet" href="styles/43.css">
</head>
<body>
    <div>
        <div class="header">
          <div id="slider">
            <input type="radio" name="slide" id="slide1" checked>
            <input type="radio" name="slide" id="slide2">
            <input type="radio" name="slide" id="slide3">
            <input type="radio" name="slide" id="slide4">
            <div id="slides">
                <div id="overflow">
                  <div class="inner">
                      <div class="slide slide_1">
                        <div class="slide-content">
                          <img src="imgs/e331ef1e-2885-4718-bc0a-0b186bae8100.jpg" alt="" style="width: 100%; height: 100%;">
                        </div>
                      </div>
                    <div class="slide slide_2">
                        <div class="slide-content">
                          <img src="imgs/89919d66-1c7e-4193-964f-893cc1f57cb5.jpg" alt="" style="width: 100%; height: 100%;">
                        </div>
                      </div>
                    <div class="slide slide_3">
                        <div class="slide-content">
                          <img src="imgs/dNvDySKPNOk.jpg" alt="" style="width: 100%; height: 100%;">
                        </div>
                      </div>
                    <div class="slide slide_4">
                        <div class="slide-content">
                          <img src="imgs/0ysMermBNmw.jpg" alt="" style="width: 100%; height: 100%;">
                        </div>
                      </div>
                  </div>
                </div>
            </div>
            <div id="controls">
              <label for="slide1"></label>
              <label for="slide2"></label>
              <label for="slide3"></label>
              <label for="slide4"></label>
            </div>
            <div id="bullets">
              <label for="slide1">
                <img src="imgs/e331ef1e-2885-4718-bc0a-0b186bae8100.jpg" alt="">
              </label>
              <label for="slide2">
                <img src="imgs/89919d66-1c7e-4193-964f-893cc1f57cb5.jpg" alt="">
              </label>
              <label for="slide3">
                <img src="imgs/dNvDySKPNOk.jpg" alt="">
              </label>
              <label for="slide4">
                <img src="imgs/0ysMermBNmw.jpg" alt="">
              </label>
            </div>
          </div>
        </div>
</body>
</html>
```
<h2 style="text-align: center">использованный styles/43.css</h2>

```css
body {
    background: #dddddd;
    padding: 0;
    margin: 0;
  }
  
  h1 {
    margin: 0;
  }
  
  .header {
    background-color: #ffffff;
    width: 100%;
    height: 100vh;
  }
  
  #slider {
    margin: 0 auto;
    width: 100%;
    max-width: 100%;
    text-align:center;
    overflow: hidden;
  }
  
  #slider input[type=radio] {
    display:none;
  }
  
  #slider label {
    cursor: pointer;
    text-decoration: none;
  }
  
  #slides {
    background: #ffffff;
    position: relative;
    z-index: 1;
  }
  
  #overflow {
    width: 100%;
    overflow: hidden; 
  }
  
  #slide1:checked ~ #slides .inner {
    margin-left: 0;
      animation: slide1 1s forwards;
  }
  
  #slide2:checked ~ #slides .inner {
    margin-left: -100%;
    animation: slide2 1s forwards;
  }
  
  #slide3:checked ~ #slides .inner {
    margin-left: -200%;
    animation: slide3 1s forwards;
  }
  
  #slide4:checked ~ #slides .inner {
    margin-left: -300%;
    animation: slide4 1s forwards;
  }
  
  #slides .inner {

    width: 400%;
    line-height:0;
    height: 100vh;
  
  }
  
  
  #slides .slide {
    width:25%;
    float: left;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100%;
    color: #fff;
  }
  
  #slides .slide_1 {
    background: #000000;
  }
  
  #slides .slide_2 {
    background: #150f69;
  }
  
  #slides .slide_3 {
    background: #89c1db;
  }
  
  #slides .slide_4 {
    background: #586d5f;
  }
  
  
  #controls {
    width: 100%;
    height: 50px;
    z-index: 3;
    position: relative;
  }
  
  #controls label {
    transition: opacity 0.2s ease-out;
    display:none;
    width: 50px;
    height: 50px;
    opacity: .4;
  }
  
  #controls label:hover {
    opacity: .1;
  }
  
  #slide1:checked ~ #controls label:nth-child(2),
  #slide2:checked ~ #controls label:nth-child(3),
  #slide3:checked ~ #controls label:nth-child(4),
  #slide4:checked ~ #controls label:nth-child(1) {
    
    float:right;
    margin: 0 -100px 0 0;
    display:block;
    color:red;
  }
  
  #slide1:checked ~ #controls label:nth-last-child(1),
  #slide2:checked ~ #controls label:nth-last-child(4),
  #slide3:checked ~ #controls label:nth-last-child(3),
  #slide4:checked ~ #controls label:nth-last-child(2) {
    
    float:left;
    margin: 0 0 0 -100px;
    display:block;
    color:red;
  }
  
  #bullets {
    text-align:center;
    position: absolute;
    z-index:20;
    bottom: 20px;
    right: 100px;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
  }
  
  #bullets label {
    width: 180px;
    height: 250px;
    border-radius: 10px;
    background: #cccccc;
    flex-basis: 32%;
    box-shadow: 0 1px 3px rgba(0,0,0,0.12), 0 1px 2px rgba(0,0,0,0.24);
    animation: in .3s;
    position:relative;
  }
  #bullets label img {
    object-fit: cover;
    width: 100%;
    height: 100%;
    border-radius: 10px;
  }
  
  #bullets label:hover {
    box-shadow: 0 14px 28px rgba(0,0,0,0.25), 0 10px 10px rgba(0,0,0,0.22);
    position:relative;
    animation: out .3s forwards;
  }
  
  @keyframes in {
      0%   { bottom:25px; }
      100% { bottom:1px; }
  }
  
  
  @keyframes out {
      0%   { bottom:0px; }
      100% { bottom:25px; }
  }
  
  #slide1:checked ~ #bullets label:nth-child(1),
  #slide2:checked ~ #bullets label:nth-child(2),
  #slide3:checked ~ #bullets label:nth-child(3),
  #slide4:checked ~ #bullets label:nth-child(4) {
    background: #444;
    display:none;
  }
  
  #slide1:checked ~ #bullets label:nth-child(1) {
    order: 1;
  }
  
  #slide2:checked ~ #bullets label:nth-child(2) {
    order: 2;
  }
  
  #slide2:checked ~ #bullets label:nth-child(1) {
      order: 1;
  }
  
  #slide3:checked ~ #bullets label:nth-child(3) {
    order: 1;
  }
  
  #slide3:checked ~ #bullets label:nth-child(4) {
    order: -1;
  }
  
  .body {
    background-color: #cccccc;
    width: 100%;
    height: 100vh;
    padding: 20px;
    box-sizing: border-box;
  }
  
  .footer {
    background-color: #ffffff;
    width: 100%;
    height: 100vh;
  }
  
  
  @keyframes slide1 {
    0% { clip-path: polygon(0 0, 100% 0, 100% 100%, 100% 0);
  }
    100% {clip-path: polygon(0 0, 100% 0, 100% 100%, 0 100%);
  }
  }
  
  @keyframes slide2 {
    0% { clip-path: polygon(0 0, 100% 0, 100% 100%, 100% 0);
  }
    100% {clip-path: polygon(0 0, 100% 0, 100% 100%, 0 100%);
  }
  }
  
  @keyframes slide3 {
    0% { clip-path: polygon(0 0, 100% 0, 100% 100%, 100% 0);
  }
    100% {clip-path: polygon(0 0, 100% 0, 100% 100%, 0 100%);
  }
  }
  
  @keyframes slide4 {
    0% { clip-path: polygon(0 0, 100% 0, 100% 100%, 100% 0);
  }
    100% {clip-path: polygon(0 0, 100% 0, 100% 100%, 0 100%);
  }
  }
  
  @media (min-width: 900px) {

  
    }
```

<h2 style="text-align: center">Файл Задания 45 </h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>45</title>
    <link rel="stylesheet" href="styles/45.css">
</head>
<body>
    <div class="container">
    <div class="item">
      <h2>zagolo 1</h2>
      <p>texttexttext</p>
    </div>
    <div class="item">
      <h2>zagolo 2</h2>
      <p>texttexttexttext</p>
    </div>
    <div class="item">
      <h2>zagolo 3</h2>
      <p>texttexttexttexttexttext</p>
    </div>
    <div class="item">
      <h2>zagolo 4</h2>
      <p>texttexttexttexttexttexttext</p>
    </div>
  </div>

</body>
</html>
```
<h2 style="text-align: center">использованный styles/45.css</h2>

```css
body {
    margin: 0;
    font-family: sans-serif;
  }

  .container {
    display: flex;
    flex-wrap: wrap;
    padding: 20px;
  }

  .item {
    width: 25%;
    padding: 20px;
    margin-bottom: 20px;
    background-color: #f5f5f5;
    border-radius: 5px;
  }

  .item h2 {
    margin-top: 0;
  }

  @media screen and (max-width: 768px) {
    .item {
      width: 50%;
    }
  }

  @media screen and (max-width: 480px) {
    .item {
      width: 100%;
    }
  }
```

<h2 style="text-align: center">Файл Задания 46 </h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>46</title>
    <link rel="stylesheet" href="styles/46.css">
</head>
<body>
    <div class="container">
        <div class="box box-color-change"></div>
        <div class="box box-rotate"></div>
        <div class="box box-pulse"></div>
        <div class="box box-circle"></div>
        <div class="box box-fall"></div>
      </div>
</body>
</html>
```
<h2 style="text-align: center">использованный styles/46.css</h2>

```css
body {
    margin: 0;
    font-family: sans-serif;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    background-color: #f5f5f5;
  }

  .container {
    display: flex;
    gap: 50px;
  }

  .box {
    width: 100px;
    height: 100px;
    border-radius: 5px;
    background-color: #4CAF50;
  }

  /* color change*/
  .box-color-change:hover {
    background-color: #3e8e41;
    transition: background-color 0.5s ease-in-out;
  }

  /* turning around */
  .box-rotate {
    animation: rotate 3s linear infinite;
  }

  @keyframes rotate {
    0% { transform: rotate(0deg); }
    100% { transform: rotate(360deg); }
  }

  /* pulse */
  .box-pulse {
    animation: pulse 1.5s ease-in-out infinite;
  }

  @keyframes pulse {
    0% { transform: scale(1); }
    50% { transform: scale(1.1); }
    100% { transform: scale(1); }
  }

  /* in circle */
  .box-circle {
    animation: circle 5s linear infinite;
  }

  @keyframes circle {
    0% { transform: translateX(0) translateY(0); }
    25% { transform: translateX(100px) translateY(0); }
    50% { transform: translateX(100px) translateY(100px); }
    75% { transform: translateX(0) translateY(100px); }
    100% { transform: translateX(0) translateY(0); }
  }

  /* fall */
  .box-fall {
    animation: fall 2s ease-in-out forwards;
    position: relative;
    top: 0;
  }

  @keyframes fall {
    0% { transform: translateY(0); }
    100% { transform: translateY(200px); }
  }
```

<h2 style="text-align: center">Файл Задания 47 </h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="styles/47.css">
</head>
<body>
    <div class="container">
    <div class="card">
      <img src="imgs/89919d66-1c7e-4193-964f-893cc1f57cb5.jpg" alt="good 1">
      <div class="card-content">
        <h3>home</h3>
        <p>welcome</p>
        <p class="price">1000$</p>
        <button class="button">Buy now!</button>
      </div>
    </div>

    <div class="card">
      <img src="imgs/68173434-3d3d-469a-afa0-a8587befda8d.jpg" alt="good 2">
      <div class="card-content">
        <h3>memories</h3>
        <p>you will forget this</p>
        <p class="price">1500$</p>
        <button class="button">Buy now!</button>
      </div>
    </div>

    <div class="card">
      <img src="imgs/e331ef1e-2885-4718-bc0a-0b186bae8100.jpg" alt="good 3">
      <div class="card-content">
        <h3>void</h3>
        <p>enjoy your stay</p>
        <p class="price">800 $</p>
        <button class="button">Buy now!</button>
      </div>
    </div>
  </div>

</body>
</html>
```
<h2 style="text-align: center">использованный styles/47.css</h2>

```css
body {
    margin: 0;
    font-family: sans-serif;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    background-color: #f5f5f5;
  }

  .container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
  }

  .card {
    width: 300px;
    background-color: white;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    overflow: hidden;
  }

  .card img {
    width: 100%;
    height: 200px;
    object-fit: cover;
  }

  .card-content {
    padding: 20px;
  }

  .card-content h3 {
    margin-top: 0;
  }

  .card-content p {
    margin-bottom: 10px;
  }

  .card-content .price {
    font-weight: bold;
    font-size: 1.2em;
    color: #4CAF50;
  }

  .card-content .button {
    background-color: #4CAF50;
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    transition: background-color 0.3s ease;
  }

  .card-content .button:hover {
    background-color: #3e8e41;
  }
```

<h2 style="text-align: center">Файл Задания 49 </h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="styles/49.css">
</head>
<body>
    <div class="loader"></div>
</body>
</html>
```
<h2 style="text-align: center">использованный styles/49.css</h2>

```css
body {
    margin: 0;
    font-family: sans-serif;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    background-color: #f5f5f5;
  }

  .loader {
    width: 80px;
    height: 80px;
    border: 10px solid #f3f3f3;
    border-radius: 50%;
    border-top-color: #3498db; 
    animation: spin 1.2s linear infinite; /*round */
  }

  @keyframes spin {
    0% { transform: rotate(0deg); }
    100% { transform: rotate(360deg); }
  }
```

<h2 style="text-align: center">Файл Задания 50 </h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="styles/50.css">
</head>
<body>
    <div class="container">
        <div class="box box-default"> default</div>
        <div class="box box-inner">inner</div>
        <div class="box box-multi">multi</div>
        <div class="box box-blur">blur</div>
        <div class="box box-color">color</div>
        <div class="box box-radius">radius</div>
        <div class="box box-glow">glow</div>
        <div class="box box-lift">lift</div>
      </div>
</body>
</html>
```
<h2 style="text-align: center">использованный styles/50.css</h2>

```css
body {
    margin: 0;
    font-family: sans-serif;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    background-color: #f5f5f5;
  }

  .container {
    display: flex;
    gap: 50px;
  }

  .box {
    width: 150px;
    height: 150px;
    background-color: #4CAF50;
    border-radius: 10px;
    color: white;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 2em;
  }

  /*default */
  .box-default {
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  }

  /* inner */
  .box-inner {
    box-shadow: inset 0 4px 8px rgba(0, 0, 0, 0.1);
  }

  /* multi */
  .box-multi {
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2), 0 4px 8px rgba(0, 0, 0, 0.1);
  }

  /* blur */
  .box-blur {
    box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
  }

  /* color */
  .box-color {
    box-shadow: 0 4px 8px rgba(255, 1, 1, 0.2);
  }

  /* radius */
  .box-radius {
    box-shadow: 0 4px 8px 2px rgba(0, 0, 0, 0.1); 
  }

  /* glow */
  .box-glow {
    box-shadow: 0 0 10px rgba(162, 0, 255, 0.5); 
  }

  /* lift */
  .box-lift {
    box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
    transform: translateY(-5px);
  }
```

<h1 align = "center">Вывод</h1>
<p>По итогу проделанной лабораторной работы, были улучшены навыки работы с языками CSS и HTML, а также были созданы 14 страниц по заданиям с использованием HTML и CSS</p>
