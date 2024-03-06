<!DOCTYPE html>
<html>
  <head>
    <title>
      Calculator
    </title>
    <style>
      button {
        background-color: rgb(68, 68, 68);
        color: white;
        border-radius: 100%;
        height:40px;
        width: 40px;
        border: none;
        font-weight: bolder;
      }

      .sign {
        background-color: orange;
      }

      
    </style>

  
  </head>
  <body style="background-color: black;">

    <p>
      <button onclick="
      calculation += '1';
      console.log(calculation);
      ">
      1
    </button>

    <button onclick="
    calculation += '2';
    console.log(calculation);
    ">
      2
    </button>

    <button onclick="
    calculation += '3';
    console.log(calculation);
    ">
      3
    </button>

    <button class="sign" onclick="
    calculation += ' + ';
    console.log(calculation);
    ">
      +
    </button>
    </p>

    <p>
      <button onclick="
    calculation += '4' ;
    console.log(calculation);
    ">
      4
    </button>

    <button onclick="
    calculation += '5' ;
    console.log(calculation);
    ">
      5
    </button>

    <button onclick="
    calculation += '6' ;
    console.log(calculation);
    ">
      6
    </button>

    <button class="sign" onclick="
    calculation += '-' ;
    console.log(calculation);
    ">
      -
    </button>
    </p>

    <p>
      <button onclick="
    calculation += '7' ;
    console.log(calculation);
    ">
      7
    </button>

    <button onclick="
    calculation += '8' ;
    console.log(calculation);
    ">
      8
    </button>

    <button onclick="
    calculation += '9' ;
    console.log(calculation);
    ">
      9
    </button>

    <button class="sign" onclick="
    calculation += '*' ;
    console.log(calculation);
    ">
      *
    </button>
    </p>

    <p>
      <button onclick="
    calculation += '0' ;
    console.log(calculation);
    ">
      0
    </button>

    <button onclick="
    calculation += '.' ;
    console.log(calculation);
    ">
      .
    </button>

    
    <button onclick="
    calculation = eval(calculation);
    console.log(calculation);
    ">
      =
    </button>

    <button class="sign" onclick="
    calculation += ' / ' ;
    console.log(calculation);
    ">
      /
    </button>
    </p>

    <p>
      <button onclick="
    calculation += '';
    console.log(calculation);
    ">
      clear
    </button>
    </p>
    
    <script>
      let calculation = '';
      console.log(calculation);
    </script>
  </body>
</html>
