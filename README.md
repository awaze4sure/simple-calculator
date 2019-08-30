# simple-calculator: this is a simple calculator with pure javascript and html/css



<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>simple calculator</title>
    <style>
        .bdy {
            background-color: orange;
            padding: 10px;
            display: flex;
            width: 400px;
            height: 300px;
        }

        .head {
            text-align: center;
            background: red;
            padding: 10px;
            width: 400px;
            height: 40px;
            font-size: 23px;
            font-weight: bold;

        }
         
        

        #foot {
            background-color: black;
            color: aliceblue;
            font-weight: bold;
            font-size: 14px;
            width: 400px;
            padding: 10px;
        }
    </style>
</head>
<body>
        <p class="head">Simple Calculator Created by AWEDA</p>
    <div class="bdy">
        

        <form name="myform">
            <input type="text" name="fst"><br><br><br>
            <input type="text" name="snd"><br><br><br>
            <input type="button" name="" value="ADD" onclick="add()">
            <input type="button" name="" value="SUBTRACT" onclick="subtract()">
            <input type="button" name="" value="MULTIPLY" onclick="multiply()">
            <input type="button" name="" value="DIVIDE" onclick="divide()"><br><br><br>
            <input type="text" name="result" height="150px" width="50px">

        </form>

        <script type="text/javascript">
            function add(){
                fst = parseFloat(myform.fst.value);
                snd = parseFloat(myform.snd.value);
                result = fst + snd;
                myform.result.value = result;
            } 

            function subtract(){
                fst = parseFloat(myform.fst.value);
                snd = parseFloat(myform.snd.value);
                result = fst - snd;
                myform.result.value = result;
            } 

            function multiply(){
                fst = parseFloat(myform.fst.value);
                snd = parseFloat(myform.snd.value);
                result = fst * snd;
                myform.result.value = result;
            } 

            function divide(){
                fst = parseFloat(myform.fst.value);
                snd = parseFloat(myform.snd.value);
                result = fst / snd;
                myform.result.value = result;
            } 

            

        
        </script>

        
    </div>
    <footer id="foot">
            &copy This calculator remains the properties of Aweda Azeez Adebayo
        </footer>
</body>
</html>
