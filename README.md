<!doctype html>
<html>
<head>
    <!-- 1. Подключим библиотеку jQuery (без нее jQuery UI не будет работать) -->
    <script src="http://ajax.googleapis.com/ajax/libs/jquery/1.12.1/jquery.min.js"></script>;

<link  href="jquery-ui-1.12.1.custom/jquery-ui.css" rel="stylesheet" />
<script  src="jquery-ui-1.12.1.custom/jquery-ui.js"></script>
    
    <style>
  #draggable { width: 150px; height: 50px; padding: 0.5em; }
  </style>
  <script>
  $( function() {
    $( "#accordion" ).accordion();
  } );
  </script>
     <script>
  $( function() {
    $( "#draggable" ).draggable();
  } );
    </script>
    <script>
  $( function() {
    $( "#resizable" ).resizable();
  } );
  </script>
    <script>
  $( function() {
    $( "#sortable" ).sortable();
    $( "#sortable" ).disableSelection();
  } );
    </script>
    <style>
        .ui-widget-header {
            text-align: center;
        }
  #sortable { list-style-type: none; margin: 0; padding: 0; width: 60%; }
  #sortable li { margin: 0 3px 3px 3px; padding: 0.4em; padding-left: 1.5em; font-size: 1.4em; height: 18px; }
        li {
            border-radius: 100px;
        }
  #sortable li span { position: absolute; margin-left: -1.3em; }
  </style>
    <style>
  #resizable { width: 150px; height: 150px; padding: 0.5em; }
  #resizable h3 { text-align: center; margin: 0; }
  </style>
<body><div id="accordion">
  <h3>Section 1</h3>
  <div>
    <p>
    Аутсо́рсинг (от англ. outsourcing: (outer-source-using) использование внешнего источника и/или ресурса) — передача организацией на основании договора определённых видов или функций производственной предпринимательской деятельности другой компании, действующей в нужной области. В отличие от услуг и поддержки, имеющих разовый, эпизодический или случайный характер и ограниченных началом и концом, на аутсорсинг обычно передаются функции по профессиональной поддержке бесперебойной работы отдельных систем и инфраструктуры на основе длительного контракта (не менее 1 года).
    </p>
  </div>
  <h3>Section 2</h3>
  <div>
    <p>
    Аутсорсинг позволяет повысить эффективность предприятия в целом и использовать освободившиеся организационные, финансовые и человеческие ресурсы для развития новых направлений или концентрации усилий, не требующих повышенного внимания.
    </p>
  </div>
  <h3>Section 3</h3>
  <div>
    <p>
    В российской предпринимательской практике на аутсорсинг чаще всего передаются такие функции, как ведение бухгалтерского учёта, обеспечение функционирования офиса (например, уборка помещений), переводческие услуги, транспортные услуги, поддержка работы компьютерной сети и информационной инфраструктуры, рекламные услуги, обеспечение безопасности.
    </p>
    <ul>
      <li>List item one</li>
      <li>List item two</li>
      <li>List item three</li>
    </ul>
  </div>
  <h3>Section 4</h3>
  <div>
    <p>
   По данным Института аутсорсинга (Outsourcing Institute, США), аутсорсинг является развивающимся видом оптимизации деятельности предприятий, причём наибольший рост наблюдается в сфере финансов и бухгалтерского учёта. Статистика, собранная в 1997 году Американской ассоциацией управления, показала, что уже тогда 20 % из числа 600 опрошенных фирм передали на аутсорсинг хотя бы некоторую часть финансовых и бухгалтерских операций, а 80 % — часть административных функций.
    </p>
    <p>
    Suspendisse eu nisl. Nullam ut libero. Integer dignissim consequat lectus.
    Class aptent taciti sociosqu ad litora torquent per conubia nostra, per
    inceptos himenaeos.
    </p>
  </div>
</div><div id="draggable" class="ui-widget-content">
  <p>Делай, что хочешь</p>
</div>
    <ul id="sortable">
    <h1>Поставь в правильном порядке</h1>
  <li class="ui-state-default"><span class="ui-icon ui-icon-arrowthick-2-n-s"></span>6</li>
  <li class="ui-state-default"><span class="ui-icon ui-icon-arrowthick-2-n-s"></span>5</li>
  <li class="ui-state-default"><span class="ui-icon ui-icon-arrowthick-2-n-s"></span>4</li>
  <li class="ui-state-default"><span class="ui-icon ui-icon-arrowthick-2-n-s"></span>2</li>
  <li class="ui-state-default"><span class="ui-icon ui-icon-arrowthick-2-n-s"></span>1</li>
  <li class="ui-state-default"><span class="ui-icon ui-icon-arrowthick-2-n-s"></span>7</li>
  <li class=
"ui-state-default"><span class="ui-icon ui-icon-arrowthick-2-n-s"></span>3</li>
</ul>
    <div id="resizable" class="ui-widget-content">
    <br>
    <br>
    <br>
  <h3 class="ui-widget-header">Увеличь до размеров секций сверху</h3>
</div>
   <style>
       h1{
           text-align: center;
           
       }  
       body {
        background-color: green;
       }
</style></body>
    </html>
