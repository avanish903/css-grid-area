# css-grid-area
 you can make amazing tampletes by this 
<!--
RESPONSIVE BY CSS 

-->

<html>
    <style>
        .container{
            display: grid;
            grid-gap: 1rem;
            grid-template-areas: 
            'navbar navbar navbar '
            'section section aside'
            'footer footer footer';
           
        }
        .box{
            /*text-align: center;*/
            background-color: cyan;
            border: 3px solid black;
            padding: 10px;
        }
        #navbar{
            grid-area: navbar;
            background-color: green;
            
        }
        #section{
            grid-area: section;
            height: 300px;
            background-color: yellow;
            
        }
        #aside{
            grid-area: aside;
            height: 300px;
            background-color: blue;
            
        }
        footer{
            grid-area: footer;
            background-color: red;
            
        }
    </style>
<body>
<div class="container">
    <div id="navbar" class="box">HOME   CONTACT US  REPORT</div>
    
    <div  id="section"class="box">Ayodhya is a city and the administrative headquarters of 
    Faizabad district and the Faizabad division of Uttar Pradesh, India.
    It shares a municipal corporation with its neighbouring twin city of Faiz</div>
    
    <div  id="aside"class="box">box3Ayodhya is a city and the administrative headquarters of 
    Faizabad district and the Faizabad division of Uttar Pradesh, India. 
    It shares a municipal corporation with its neighbouring twin city of Fai</div>
    
    <footer class="box"> hiii this is the website of 1998</footer>
    <!--<div class="box">box4</div>-->
    <!--<div class="box">box5</div>-->
    <!--<div class="box">box6</div>-->
    <!--<div class="box">box7</div>-->
    <!--<div class="box">box8</div>-->
    <!--<div class="box">box9</div>-->
    <!--<div class="box">box10</div>-->
    <!--<div class="box">box11</div>-->
    <!--<div class="box">box12</div>-->
    <!--<div class="box">box13</div>-->
    <!--<div class="box">box14</div>-->
    
    <!--<div class="box">box14</div>-->
    
</div>
</body>
</html>
