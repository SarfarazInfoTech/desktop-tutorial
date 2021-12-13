<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Java Script</title>
</head>

<body>
    <!-- Exp 1 -->
    <!-- <script type="text/javascript">
        var a = 10;
        var b = 10;
        var c;

        c = a + b;
        document.write("<br> Addition is = " + c);
        c = a / b;
        document.write("<br> Division is =  " + c);
        c = a % b;
        document.write("<br> Modular is  = " + c);
        c = a * b;
        document.write("<br> Multiplication = " + c);
         
    </script>-->

    <!-- Exp 2 -->
    <!-- <script type="text/javascript">
        var x = 3;
        var y = 2;
        var z = 5;

        if ((x > y) && (x > z)) {
            document.write("Largest is = " + y);
        }
        else {
            document.write("Largest is = " + z);

        }
    </script> -->

    <!-- Exp 2 -->
    <!-- <script type="text/javascript">
        function factonial(num) {
            if (num <= 1) { return 1; }

            else {
                return (num * factonial(num - 1));
            }
        }
        var z = factonial(6);
        document.write(z);
    </script> -->

    <!-- Exp 3 -->
    <!-- <script type="text/javascript">
        var S = new Array();
        S[0] = "PHP";
        S[1] = "ASP";
        S[2] = "JSP";
        S[3] = "HTML";
        for (var i = 0; i < S.length; i++) {
            document.write(S[i] + "<br>");
        }
    </script> -->

    <!-- Exp 4 -->
    <!-- <p id="Demo"></p>
    <script type="text/javascript">
        var x = myFunction(4, 3);
        document.getElementById('Demo').innerHTML = x;

        function myFunction(a, b) {

            return (a + b);
        }

    </script> -->


    <!-- Exp 6 -->
    <!-- <h1>Registration Page</h1>
    <form action="post" name="registration">
        First Name : <input type="text" name="firstname" id="" /> <br><br>
        Last Name : <input type="text" name="lastname" id="" /> <br><br>
        Password : <input type="password" name="pass" id="" /> <br><br>
        Re Password : <input type="password" name="repass" id="" /> <br><br>
        Gender : <input type="radio" name="sex" value="f" /> Female
        <input type="radio" name="sex" value="m" /> Male <br><br>

        City You Travel <select name="city">
            <optgroup label="North">
                <option value="001"> Delhi </option>
                <option value="001"> Chandighar </option>
            </optgroup>
            <optgroup label="South">
                <option value="111"> Kerala </option>
                <option value="112"> Kanyankumari </option>
            </optgroup>
        </select>

        <br><br>
        <label for="margine">Do you want more cites </label>
        <input type="checkbox" name="moreinfo" id="moreinfo" />
        <br><br>
        Enter your comment :
        <textarea name="comment" id="" cols="30" rows="10"></textarea>
        <br><br>

        <h2>Additional Infomation </h2>
        <input type="checkbox" name="confrom" />
        About Infomation is Correct. <br><br>
        <input type="reset" value="Reset">
        <input type="submit" value="Submit">

    </form> -->

    <!-- Exp 7 -->
    <!-- <script>
        function react() {
            alert("Please enter any value");
        }
    </script>
    <form action="post" name="myform" method="POST" click="react">
        <input type="button" value="Click now here" onclick="react()">
    </form> -->

    <!-- Exp 8 -->
    <!-- <script>
        function react() {
            alert("Wellcome to event");
        }
    </script>
    <form action="" name="myform" method="POST" onmousemove="react()">
    <input type="button" value="Click on mouse button">
    </form> -->

    <!-- Ex 9 Error in img tag -->
    <!-- <form action="" name="myform" method="POST">
        <p>First Name : <input type="text" name="fname" ></p>
        <p>Last Name : <input type="text" name="lname" ></p>
        <img src="submit.gif" alt="" onclick="javascript.document.forms.myform.submit()" />

    </form> -->


    <!-- Ex 10 error in -->
    <!-- <script>
        function WriteCookies() {
            with (document.myform);
        }
        {
            document.cookie = "Name = " + person.value();
            {
                about("Cookies Written");
            }
        }
    </script>
    <form action="" name="myform">
        Enter your name :
        <input type="text" name="person" onchange="WriteCookies()" />
    </form> -->



    <!-- Exp 11 error in code  -->
    <!-- <frameset rows="20%, 40%, 40%">
        <frame  src"webpage1.html" name="top" frameborder="1" />
        <frame  src"webpage2.html" name="middle" frameborder="1" />
        <frame  src"webpage3.html" name="bottom" frameborder="1" />

    </frameset>

    
        <body onclick="top.middlefocus ();">
            <h1>webpage1</h1>
             -->


    <!-- Exp 12 -->
    <!-- <script>
        function check() {
            var reg = /abc/gmi;
            var str = document.getElementById("text").value;
            var res = str.search(reg);
            document.getElementById("demo1").innerHTML = res;
        }
    </script>
    Enter text <textarea name="" id="text" cols="30" rows="10"></textarea>
    <input value="Check" type="button" onclick="check()" />
    <p id="demo1"></p> -->

    <!-- Exp 13 error -->
    <!-- <img src="1.jpg" height="150" width="100" alt="no image" onmouseover="" src="2.jpg"> -->

    <!-- Exp 14  -->
    <!-- <div style="position: fixed;
                width: 200px;
                height: 50px;
                top: 70px;
                right: 10px;
                background: blue;
                z-index: 100;">
        floating menus
    </div>
    <br>
    this is a long webpage
    <br>
    this is a long webpage
    <br> -->

    <!-- Exp 15 -->
    <!-- <h3>Right Click on screen Content menu is enable </h3>
    <br>
    <h3>you can view sources of web page </h3> -->

    <!-- Exp 16 error -->
    <!-- <script>
        Banner = new Array("1.jpg", "WT.jpg", "VB.Net.jpg");
        count = 0;
        function rotate() {
            if (document.images) {
                count++;
                if (count == Banner.length) {
                    count = 0;

                }
                document.imgSrc = Banner, rotate();
                setTimeout("rotate()", 1000);
            }
        }
    </script>

    <body onload="rotate()">
        <center>
            <img src="1.jpg" alt="" width="300" height="400" />
        </center> -->


</body>

</html>
