<!DOCTYPE html>
<html>
  <meta name="viewport" content="width:device-width, initial-scale=1.0">
  <head>
    <title>Quicktakes</title>
    <script src="https://kit.fontawesome.com/abfd1c10c3.js" crossorigin="anonymous"></script>
  </head>
  <style>
    header{
      background: url(quicktakes1.jpeg) repeat-x  fixed;
      text-align: center;
      color: rgb(233, 10, 58);
      padding: 6px;
      border-radius: 100px;
      width: 100%;
      margin: 0;
      font-size: xx-large;
      font-family: fantasy;
      text-shadow: 4px;
      background-position: center;
      background-color: rgb(231, 234, 236);
      border: none;
      animation-name: header;
      animation-duration: 120s;
      animation-delay: 5s;
      animation-iteration-count: infinite;
      animation: header 120s 5s infinite;
    }
    @keyframes header{
      0%{color: rgba(184, 144, 12, 0.74);background-color: rgb(0, 0, 0);}
      100%{color: rgb(233, 17, 100);background-color: rgb(255, 255, 255);}

    }
    

    footer{background-color: black;
           background: linear-gradient(black,yellow);
           padding: 0px;
           text-align: center;}
    body{
      background-color: black;
     
      
    }

    button {
      background-color: chocolate;
      text-align: center;
    }
    button:hover{
      background-color: coral;
      color: burlywood;
    }
    nav{
      background-color: rgb(31, 29, 29);
      overflow: hidden;
      margin-top: 5px;
      position: sticky;
      top: 0;
      
      }
    nav a{
      float: left;
      display: block;
      text-decoration: none;
      padding: 10px;
      color: darkgoldenrod;
      width: auto;
      
      
    }
    nav a:hover{background-color: rgb(208, 212, 210);}  
    *{box-sizing: border-box;}
    section{background-color: antiquewhite;}
    .content {
              float: left;
     }
    #Home{
      content: "";
      display: table;
      clear: both;
      width: 100%;
    }
    table, th, td {
    border: 0 solid black;
    background-color: aqua;
}
    @media screen and (max-width: 600px) {
    .content{   
        width: 100%;
        padding: 0;
    }
    }

    @media screen and (max-width: 500px) { 
    nav a {
        float: none;
        width: 100%;}
    }
                 
  </style>
  <body>
    <header><p><b><i class="fa-solid fa-hotel"></i>Quicktakes</b><sub><q>best dishes</q></sub></p></header>
    <nav>
      <a href="#Home"><i class="fa-solid fa-house"></i>Home</a>
      <a href="#Menu">Menu</a>
      <a href="#About Us" style="float:right;">About Us</a>
      <a href="login.html" style="float:right;">Login</a>
      <a href="order.html" style="float:right;">Order</a>


    </nav>
      <section id="Home">
        <article class="content" style="width: 25%;">
          <h3>Membership</h3>
          <button id="register"><a href="register.html" style="float:right;">Register</a></button>
          <h3>Events bookings</h3>
          <p></p>
          <h3>Special Recipes</h3>
        </article>
        
        <article class="content" style="width: 75%;">
        <h2>Quicktakes Hotel</h2>
        <p>The hotel started in the mid 20s by C.M.K the third.<br>
        And since the it has 39 branches across the the major own in the country<br>
        Quicktakes is known for various dishes but <strong style="text-decoration: underline;">Meat-Cheese banger</strong> is the customers favourite<br>
        <p><img src="quicktakes1.jpeg" alt="building" style="width: auto;"></p>    
        </article>
      </section>
<section id="Menu">
<h2>Menu</h2>
<h3>Beverages</h3>
<table>
  <tr>
    <th>Item</th>
    <th>Price (Ksh)</th>
    <th>Image</th>
  </tr>
  <tr>
    <td>Coffee-extra creamy</td> 
    <td>250</td>
    <td><img src="coffee.jpg" alt="coffee" style="width:50px;"></td>
  </tr>
  <tr>
    <td>Coffee-black</td> 
    <td>50</td>
    <td><img src="coffee.jpg" alt="tea" style="width:50px;"></td>
  </tr>
  <tr>
    <td>Coffee-white</td> 
    <td>100</td>
    <td><img src="coffee.jpg" alt="tea" style="width:50px;"></td>
  </tr>
  <tr>
    <td>Coffee-with cream</td> 
    <td>150</td>
    <td><img src="coffee.jpg" alt="tea" style="width:50px;"></td>
  </tr>
  <tr>
    <td>Tea-green</td> 
    <td>150</td>
    <td><img src="tea.jpg" alt="tea" style="width:50px;"></td>
  </tr>
  <tr>
    <td>Tea-black</td> 
    <td>50</td>
    <td><img src="tea.jpg" alt="tea" style="width:50px;"></td>
  </tr>
  <tr>
    <td>Tea-with milk</td> 
    <td>150</td>
    <td><img src="tea.jpg" alt="tea" style="width:50px;"></td>
  </tr>
  <tr>
    <td>Tea-ginger</td> 
    <td>150</td>
    <td><img src="tea.jpg" alt="tea" style="width:50px;"></td>
  </tr>
</table>

      </section>
    <footer id="About Us">

      <p>Where we serve the best dishes</p>
    </footer>
  </body>
</html>
