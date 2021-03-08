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
