<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Felight</title>
    <link rel="stylesheet" href="website.css">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</head>

<body>
    <header>
        <nav class="navbar">
            <ul>
                <img id="logo" src="felight.jpg" height="40" alt="logo" >

                <li><a href="#">Home</a></li>
                <li><a href="#">Courses</a></li>
                <li><a href="#">Fee Payment</a></li>
                <li><a href="#">Contact us</a></li>
                <div class="search">
                    <input type="text" name="search" id="search" placeholder="Search this website">
                </div>
            </ul>       
                <!-- Dropdown -->
                <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle" href="#" id="navbardrop" data-toggle="dropdown">
                        User Menu
                    </a>
                    <div class="dropdown-menu">
                        <a class="dropdown-item" href="#">Account</a>
                        <a class="dropdown-item" href="#">Status</a>
                        <a class="dropdown-item" href="#">Logout</a>
                    </div>
                </li>
           </nav>
    </header>

    <div class="cards">
        <div class="card">
          <img
            src="advancejs.png" alt="" class="card__image" height="150" />
            <h6>10 Chapters</h6>
          <div class="crad__container">
            <p>
              <b> Advance JavaScript</b>
            </p>
          </div>
          <div class="card__info">
            <div class="card__name">USD 70</div>
          </div>
        </div>

        
      <div class="card">
        <img src="html.jpg" alt="" class="card__image" height="150"/>
        <h6>10 Chapters</h6>
        <div class="crad__container">
          <p>
            <b> HTML CSS</b>
          </p>
        </div>
        <div class="card__info">
          <div class="card__name">USD 70</div>
        </div>
      </div>
      <div class="card">
        <img src="b.jpg" alt="" class="card__image" height="150" />
        <h6>10 Chapters</h6>
        <div class="crad__container">
          <p>
            <b> Bootstrap</b>
          </p>
        </div>
        <div class="card__info">
          <div class="card__name">USD 70</div>
        </div>
      </div>
      <div class="card">
        <img
          src="git.png" alt=""class="card__image" height="150" />
          <h6>10 Chapters</h6>
        <div class="crad__container">
          <p>
            <b> Git-Hub</b>
          </p>
        </div>
        <div class="card__info">
          <div class="card__name">USD 70</div>
        </div>
      </div>
      <div class="card">
        <img src="js.png" alt="" class="card__image" height="150" />
        <h6>10 Chapters</h6>
        <div class="crad__container">
          <p>
            <b> Basics of JavaScript</b>
          </p>
        </div>
        <div class="card__info">
          <div class="card__name">USD 70</div>
        </div>
      </div>
      <div class="card">
        <img
          src="reactjs-2.png" alt="" class="card__image" height="150"/>
          <h6>10 Chapters</h6>
        <div class="crad__container">
          <p>
            <b> React</b>
          </p>
        </div>
        <div class="card__info">
          <div class="card__name">USD 70</div>
        </div>
    </div>
    <div class="card">
        <img
          src="mango.png" alt="" class="card__image" height="150"/>
          <h6>10 Chapters</h6>
        <div class="crad__container">
          <p>
            <b> Mango DB</b>
          </p>
        </div>
        <div class="card__info">
          <div class="card__name">USD 70</div>
        </div>
    </div>
    <div class="card">
        <img
          src="nodejs.png" alt="" class="card__image" height="150"/>
          <h6>10 Chapters</h6>
        <div class="crad__container">
          <p>
            <b> Node JS</b>
          </p>
        </div>
        <div class="card__info">
          <div class="card__name">USD 70</div>
        </div>
    </div>
    <footer class="foot">
      &copy; 2021-Felight
    </footer>
  </div>
</body>
  
</html>




@import url('https://fonts.googleapis.com/css2?family=Ubuntu&display=swap');

body{
    
    font-family: 'Ubuntu', sans-serif;
    
}
#logo{
    margin-top: 1px;
    float: left;
    cursor: pointer;
}
.navbar{
    height:60px;
    margin-top: 10px;
    margin-right:5px;
    margin-left:5px;
    background-color: black;
    border-radius: 10px;
    
}
.navbar ul{
/*     margin-top:20px; */
    overflow: auto;
}
.navbar li{
    float:left;
    list-style: none; 
    margin: 10px 25px;
    font-size:larger;
    
}
.navbar li a{
    padding: 1px 1px;
    text-decoration: none;
    color: rgb(241 235 235);
}
.navbar li a:hover{
    color: rgb(235, 32, 32)
}
.search{
    float:left;
    color: white;
    
}
.navbar input{
    margin-top:5px;
    border: 2px solid black;
    border-radius: 5px;
    padding: 5px 17px;
}

#navbardrop:hover{
    color: red;
}

.dropdown-menu:hover{
    background-color: rgb(14, 13, 14);
}


.cards{
    margin-top: 30px;  
    margin-left: 13px;
    margin-right:13px;
    max-width: 10000px;
    display: grid;
    /* grid-template-columns: repeat(4, 1fr); */
    grid-template-columns: repeat(auto-fill,minmax(225px,1fr));
    gap:20px;
    font-family: 'Ubuntu', sans-serif ;
    
    
    
}

.card{
    /* box-shadow: 0 0 3px rgba(0, 0, 0, 0.1); */
    box-shadow: 5px 5px 15px rgba(0, 0, 0, 0.9);
    border-radius: 10px;
}

.card:hover{
    transform: translateY(-0.5%);
    box-shadow: 0 4rem 8rem rgba(0,0,0,0.5);
}

.card__image{

    display: block;
    
}

.crad__container{
    margin-top:0px;
    line-height: 0.5;
    font-size: 0.9em;
    padding: 30px;
    background: #ffffff;
    text-align: center;
    font-size: 20px;
    cursor: pointer;
}
.crad__container:hover{
    color:red;
   
}

.card__content > p:last-of-type {
    margin-bottom: 0;
    
}

.card__info{
    padding: 15px;
    /* display: flex; */
    justify-content: space-between;
    background: #fffcfc00;
    font-size: 0.8em;
    border-bottom: 2px solid #fcfbfb;
    float: right;
    align-items: center;
    border-top: 1px solid rgba(0, 0, 0, 0.1);

}

.cards:hover{
    background-color:transparent
}

.card__name{
    float: right;
    font-size:20px;

}

.cards .card h6{
    margin-top:15px;
    color:#74b674;
}

.foot{
    /* text-align: center; */
    font-size: 20px;
    float: left;
    border-top: 2px solid rgba(0, 0, 0, 0.1);
   
}
