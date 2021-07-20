  <!DOCTYPE html>
 <html lang="en">
 <head>
     <meta charset="UTF-8">
     <meta http-equiv="X-UA-Compatible" content="IE=edge">
     <meta name="viewport" content="width=device-width, initial-scale=1.0">
     <title>Document</title>
     <!-- font awesome -->
     <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
    <link rel="stylesheet" href="hello.css">

     <style>
         *{
             margin: 0;
             padding: 0;
             scroll-behavior: smooth;
         }
          
          
         .logo{
             
             height: 50px;
         }
         .navbar{
              
              
             align-items: center;
             
             
         }
         ul{
             display: inline-flex;
             text-align: right;
             margin: 10px;
             float: right;
              
             
         }
         .navbar ul li{
              list-style: none;
             margin-left: 50px;
              text-align: center;
             font-size: 22px;
             /* background-color: aqua; */
             font-weight: bold;
             font-family: sans-serif;
             text-transform: capitalize;

             
         }
         .navbar ul li a {
             text-decoration: none;
             color: black ;


         }
         .fas{
             /* margin: 4px; */
             padding: 4px;
         }
         /* #home{
             display: flex;
             justify-content: center;
             align-items: center;
             font-weight: bold;
         } */
         section{
             height: 100vh;
             width: 100%;
             display: flex;
             align-items: center;
             justify-content: center;
             font-size: 50px;
         }
         .footer{
             font-size: 50px;
             height: 35vh;
              
            /* align-items: center;
             justify-content: center; */
             background-color: black;
              color: white;
              
               
                
         }
         .footer ul {
              
             width: 100%;
             
              
            
             
         }
         
         .footer ul li{
             list-style: none;
            margin: 50px;
            text-align: center;
             
             
         }
         .footer ul li a{
             color: skyblue;
             text-align: left;
             
         }
         .footer ul li a:hover{
             color: red;
            
         }
         .good{
             color: white;
             text-align: center ;
             background: black;
             
         }
     </style>
 </head>
 <body>
     <header>
         <div class="main">
             <nav>
                 <img class="logo" src="Logo.jpg" alt="logo">
                 <span class="navbar">
                     <ul>
                         <li><a href="#home"><i class="fas fa-home"></i>Home</a></li>
                         <li><a href="#contract"><i class="fas fa-users"></i>contract</a></li>
                         <li><a href="#info"><i class="fas fa-users"></i>notification</a></li>
                         <li><a href="#sub"><i class="fas fa-phone-alt"></i>subscribe</a></li>
                         <li><a href="#help"><i class="fas fa-users"></i>help</a></li>
                     </ul>
                 </span>
             </nav>
         </div>
     </header><hr>
     <section id="home" style="background-color: #f1f1f1;">home</section>
     <section id="contract" style="background-color: whitesmoke;">contract</section>
     <section id="info" style="background-color: #f1f1f1;">notiification</section>
     <section id="sub" style="background-color: wheat;"><p>
         Lorem ipsum dolor sit amet consectetur, adipisicing elit. Maxime illum consequatur assumenda expedita obcaecati porro cupiditate dicta. Deleniti, doloremque incidunt accusantium repudiandae adipisci culpa veniam sed dolorum autem commodi mollitia, non est fugit ipsam amet! Soluta autem exercitationem atque aspernatur non quis voluptatibus.
     </p></section>
     <section id="help" style="background-color: #f1f1f1;">help me</section>
     <footer>
        <div class="footer">
            <ul>
                <li><a href="#"><i class="fab fa-facebook-square"></a></i></li>
                <li><a href="#"><i class="fab fa-twitter"></a></i></li>
                <li><a href="#"><i class="fab fa-telegram-plane"></i></a></li>
            </ul>
             
        </div><hr>
        <p class="good">copyright 1990-2021</p>
    </footer>
 </body>
 </html>
