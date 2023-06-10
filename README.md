<!DOCTYPE html>
<html>
<head>
<title>Вантажні перевезення</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}


body {
  font-family: 
yellow;
  margin: 0;
}


.header {
  padding: 75px;
  text-align: center;
  background:#eef207;
  color: black;
}


.navbar {
  display: flex;
  background-color: #333;
}




.row {
  display: flex;
  flex-wrap: wrap;
}


.side {
  flex: 30%;
  background-color: #f1f1f1;
  padding: 20px;
}


.main {
  flex: 70%;
  background-color: white;
  padding: 20px;
}


.fakeimg {
  background-color: #aaa;
  width: 100%;
  padding: 20px;
}


.footer {
  padding: 20px;
  text-align: center;
  background: #ddd;
}


@media screen and (max-width: 700px) {
  .row, .navbar {
    flex-direction: column;
  }
}
</style>
</head>
<body>

<!-- Примітка -->
<div style="background:blue;padding:90px">
  <h4 style="text-align:center"></h4>
</div>

<!-- Header -->
<div class="header">
  <h1>Вантажні перевезення</h1>
  <p><b>ЕкспресТранс Україна</b> </p>
</div>

<!-- Гибка сітка (контент) -->
<div class="row">
  <div class="side">
    <h2>Про мене</h2>
    <p>Доброго дня. Мене звати Мар'ян, я засновник та власник компанії "ЕкспресТранс Україна"</p>
    <h3>Дзвоніть нам</h3>
    <p>Номера по Україні</p>
    <div class="fakeimg" style="height:60px;">0324422095</div><br>
    <div class="fakeimg" style="height:60px;">0682384349</div><br>
    <div class="fakeimg" style="height:60px;">0322940305</div>
  </div>
  <div class="main">
    <h2>Експрес транс україна</h2>
    <h5>Ми працюємо з, 18 лютого, 2000</h5>
    <div class="fakeimg" style="height:200px;">ЕкспресТранс Україна задовільняє Логістичні потреби не однієї фірми на протязі двадцяти трьох років якщо ви працюєте за межами України ми б могли запропунувати вам свої послуги адже маємо не маленький стаж робити повязаний з логістикою. Хочу вас познайомити поближче з нашою компанією. </div>
    <p></p>
    <p></p>
    <br>
    <h2>Про нашу компанію</h2>
    <h5></h5>
    <div class="fakeimg" style="height:200px;">
    ЕкспресТранс Україна працює з 18 лютого 2000року компанія займаєтся грамотним плануванням та узгодженням усіх деталей для вашого комфортного перевезення також ЕкспресТранс Україна має транспортний парк якй включає різновид автомобілів за допомогою цього підбираются комфортні автомобілі та лінії які задовільняють кожного з наших клієнтів. </div>
    <p></p>
    <p></p>
  </div>
</div>

<!-- Footer -->
<div class="footer">
  <h2>Дякую що обрали нас</h2>
</div>

</body>
</html>
