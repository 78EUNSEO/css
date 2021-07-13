# css
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8"
    <title>day-5</title>
    <style>
      p{
        color: blueviolet;
        font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
      }
      div{
        width: 300px;
        height: 200px;
        background: red;
        margin-left: 40px;
        animation: mymove 5s infinite;
      }
      @keyframes mymove
      {
        from {background-color: red;}
        to{background-color: blue;}
      }
      /*Safari and Chrome:*/
      @-webkit-keyframes mymove
      {
        from{background-color: red;}
        to{background-color: blue;}
      }
    </style>
  </head>
  <body>
    <p>The background-color gradually changes from red to blue</p>
    <div id="div"></div>
  </body>
</html>
