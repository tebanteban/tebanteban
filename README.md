<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="estilos.css">
    <title>Calculadora</title>
    
</head>
<body>
    <div class="micalculadora">
     <form name="calculadora " id="calculadora">

      <input type="text" name="display" id="display">
        <div>
        <input type="button" id="uno" value="1" onclick="valor(document.getElementById(`uno`).value)"> 
        <input type="button" id="dos" value="2" onclick="valor(document.getElementById(`dos`).value)"> 
        <input type="button" id="tres" value="3" onclick="valor(document.getElementById(`tres`).value)"> 
        <input type="button" id="suma" value="+" onclick="valor(document.getElementById(`suma`).value)"> 
        </div>

        <div>
            <input type="button" id="cuadro" value="4" onclick="valor(document.getElementById(`cuadro`).value)"> 
            <input type="button" id="cinco" value="5" onclick="valor(document.getElementById(`cinco`).value)"> 
            <input type="button" id="seis" value="6" onclick="valor(document.getElementById(`seis`).value)"> 
            <input type="button" id="resta" value="-" onclick="valor(document.getElementById(`resta`).value)"> 
      </div>

      <div>
        <input type="button" id="siete" value="7" onclick="valor(document.getElementById(`siete`).value)"> 
        <input type="button" id="ocho" value="8" onclick="valor(document.getElementById(`ocho`).value)"> 
        <input type="button" id="nueve" value="9" onclick="valor(document.getElementById(`nueve`).value)"> 
        <input type="button" id="multi" value="*" onclick="valor(document.getElementById(`multi`).value)"> 
    </div>
     
    <div>
        <input type="button" id="cero" value="0" onclick="valor(document.getElementById(`cero`).value)"> 
        <input type="button" id="decimal" value="." onclick="valor(document.getElementById(`decimal`).value)"> 
        <input type="button" id="div" value="/" onclick="valor(document.getElementById(`div`).value)"> 
        <input type="button" id="porc" value=" % " onclick="valor(document.getElementById(`porc`).value)"> 
        </div>

        <div class="resultado">
            <input type="button" id="igual" value="=" onclick="cal_resultado()">
            <input type="button" id="borrar" value="" onclick="borrardisplay(document.getElementById(`borrar`).value)">


        </div>



     </form>



    </div>




   <script src="cal.js"></script>
</body>
</html>
