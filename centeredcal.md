<!DOCTYPE HTML>
<html>
  <head><title></title>
  <style type="text/css">
    #container{
        background-color: black;
        height:50% ;
        width: 100%;
        text-align: center;
        font-family: Monospace;
        font-weight: bold;
        position: relative;
    }
    legend{
      background-color: gray;
      color: lawngreen;
      text-align: left;
    }
    #display{
      background-color: black;
      color: white;
      text-align: center;
      font-size: 40px;
      height: 80px;
      width: 100%;
      font-weight: bold;
      border: none;
    }
    .digits{
      background-color: black;
      color: white;
      height: 60px;
      width: 54px;
      font-size: 30px;
      font-weight: bold;
      font-family: Monospace;
      border: none;
    }
    .maths{
      background-color: crimson;
      color: white;
      height: 60px;
      width: 54px;
      font-size: 30px;
      font-weight: bold;
      font-family: Monospace;
      border: none;
    }
    .eval{
      background-color: black;
      color: white;
      height: 60px;
      width: 110px;
      font-size: 30px;
      font-weight: bold;
      font-family: Monospace;
      border: none;
    }
  </style>
  </head>
  <body>
    <div class="container">
      <fieldset id="container">
        <legend>UZ CALCULATOR</legend>
        <form name="calculator">
          <input id="display" name="display" type="text" readonly/><br/>
          <br/>
          <hr/>
          <input class="digits" type="button" value="7" onclick="calculator.display.value+='7'"/>
          <input class="digits" type="button" value="8" onclick="calculator.display.value+='8'"/>
          <input class="digits" type="button" value="9" onclick="calculator.display.value+='9'"/>
          <input class="maths" type="button" value="+" onclick="calculator.display.value+='+'"/>
          <input class="maths" type="button" value="-" onclick="calculator.display.value+='-'"/><br/>
      <br/>    
    <input class="digits" type="button" value="6" onclick="calculator.display.value+='6'"/>
          <input class="digits" type="button" value="5" onclick="calculator.display.value+='5'"/>
          <input class="digits" type="button" value="4" onclick="calculator.display.value+='4'"/>
          <input class="maths" type="button" value="/" onclick="calculator.display.value+='/'"/>
          <input class="maths" type="button" value="*" onclick="calculator.display.value+='*'"/><br/>
      <br/>    
    <input class="digits" type="button" value="1" onclick="calculator.display.value+='1'"/>
          <input class="digits" type="button" value="2" onclick="calculator.display.value+='2'"/>
          <input class="digits" type="button" value="3" onclick="calculator.display.value+='3'"/>
        
          <input class="eval" type="button" value="=" onclick="calculator.display.value=eval(calculator.display.value)"/><br/>
<br/>
  <input class="digits" type="button" value="0" onclick="calculator.display.value+='0'"/>
  <input class="digits" type="button" value="00" onclick="calculator.display.value+='00'"/>
  <input class="digits" type="button" value="." onclick="calculator.display.value+='.'"/>
  <input class="eval" type="button" value="CLEAR" onclick="calculator.display.value=''"/>
        </form>
      </fieldset>
    </div>
  </body>
</html>
