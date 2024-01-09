# QTripStatic<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>QTrip</title>
    <link rel="stylesheet" href="css/styles.css" />

    <!-- TODO: MODULE_LAYOUT -->
    <!-- 1. Create a <link> to the first stylesheet needed for Bootstrap -->
    <link
      rel="stylesheet"
      href="https://cdn.jsdelivr.net/npm/bootstrap@4.4.1/dist/css/bootstrap.min.css"
      integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh"
      crossorigin="anonymous"
    />
    <style>
      .body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
        box-sizing: border-box;
      }

      

      .logo {
        text-decoration: none;
        color: #fff;
        font-weight: bold;
        font-size: 1.5rem;
      }

      .nav {
        display: flex;
      }

      .nav  {
        margin-left: 20px;
        text-decoration: none;
        color: #fff;
      }

      .main {
        text-align: center;
        padding: 20px;
      }

      .title {
        font-size: 2rem;
        margin-bottom: 10px;
      }

      .description {
        font-size: 1.2rem;
        margin-bottom: 20px;
      }

      .search-bar {
        width: 60%;
        padding: 10px;
        font-size: 1rem;
      }
      .h1 {
        margin-top: 0;
    margin-bottom: .5rem;
    font-weight: 500;
    line-height: 1.2;
      }

      .image-grid {
        display: grid;
        grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
        gap: 20px;
        justify-content: center;
        margin-top: 20px;
      }

      .image {
        width: 100%;
        max-width: 100%;
        height: auto;
      }
    </style>
  </head>

  <body>
    <!-- TODO: MODULE_LAYOUT -->
    <header>
      <nav class="navbar navbar-expand-lg navbar-light bg-light ps-3">
        <a class="navbar-brand" href="#">QTrip</a>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarNavDropdown"
          aria-controls="navbarNavDropdown"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNavDropdown">
          <ul class="navbar-nav d-flex justify-content-end w-100">
            <li class="nav-item active">
              <a class="nav-link" href="#">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="./pages/adventures/resort/ => {
                
              }"
              
                >Reservations</a
              >
            </li>
          </ul>
        </div>
      </nav>
    </header>
    <!-- 1. Use appropriate css classes on nav element. -->

    <!-- 2. Add child elements as required. -->

    <div class="hero-image d-flex justify-content-center align-items-center text-white flex-column text-center">
        <div class="container">
            <h1>Welcome to QTrip</h1>
            <p class="hero-subheading">
                Explore the world with fantastic places to venture around
            </p>
            <input class="hero-input" placeholder="Search a City">
        </div>
    </div>

    <!-- TODO: MODULE_LAYOUT -->
    <!-- 1. Use appropriate css classes on the hero image container element. -->
    <!-- 2. Add child elements as required. -->

  

    
      <!-- TODO: MODULE_LAYOUT -->
      <div class="container">
        <div class="content text-white">
            <div class="row" id="data"><div class="col-6 col-md-4 col-lg-3 mb-4">
  <a href="pages/adventures/?city=bengaluru" id="bengaluru">
    <div class="tile">
      <div class="tile-text text-center">
        <h5>Bengaluru</h5>
        <p>100+ Places</p>
      </div>
    <img class="img-responsive" src="https://images.pexels.com/photos/3573382/pexels-photo-3573382.jpeg?auto=compress&amp;cs=tinysrgb&amp;dpr=2&amp;h=750&amp;w=1260">
    </div>
  </a>
  </div><div class="col-6 col-md-4 col-lg-3 mb-4">
  <a href="pages/adventures/?city=goa" id="goa">
    <div class="tile">
      <div class="tile-text text-center">
        <h5>Goa</h5>
        <p>250+ Places</p>
      </div>
    <img class="img-responsive" src="https://images.pexels.com/photos/1078983/pexels-photo-1078983.jpeg?auto=compress&amp;cs=tinysrgb&amp;dpr=2&amp;h=750&amp;w=1260">
    </div>
  </a>
  </div><div class="col-6 col-md-4 col-lg-3 mb-4">
  <a href="pages/adventures/?city=kolkata" id="kolkata">
    <div class="tile">
      <div class="tile-text text-center">
        <h5>Kolkata</h5>
        <p>100+ Places</p>
      </div>
    <img class="img-responsive" src="https://images.pexels.com/photos/2524368/pexels-photo-2524368.jpeg?auto=compress&amp;cs=tinysrgb&amp;dpr=2&amp;w=500">
    </div>
  </a>
  </div><div class="col-6 col-md-4 col-lg-3 mb-4">
  <a href="pages/adventures/?city=singapore" id="singapore">
    <div class="tile">
      <div class="tile-text text-center">
        <h5>Singapore</h5>
        <p>100+ Places</p>
      </div>
    <img class="img-responsive" src="https://i.ibb.co/WVL7n8K/singapore.jpg">
    </div>
  </a>
  </div><div class="col-6 col-md-4 col-lg-3 mb-4">
  <a href="pages/adventures/?city=malaysia" id="malaysia">
    <div class="tile">
      <div class="tile-text text-center">
        <h5>Malaysia</h5>
        <p>100+ Places</p>
      </div>
    <img class="img-responsive" src="https://images.pexels.com/photos/2940925/pexels-photo-2940925.jpeg?auto=compress&amp;cs=tinysrgb&amp;dpr=2&amp;w=500">
    </div>
  </a>
  </div><div class="col-6 col-md-4 col-lg-3 mb-4">
  <a href="pages/adventures/?city=bangkok" id="bangkok">
    <div class="tile">
      <div class="tile-text text-center">
        <h5>Bangkok</h5>
        <p>250+ Places</p>
      </div>
    <img class="img-responsive" src="https://images.pexels.com/photos/1682748/pexels-photo-1682748.jpeg?cs=srgb&amp;dl=pexels-ingo-joseph-1682748.jpg&amp;fm=jpg">
    </div>
  </a>
  </div><div class="col-6 col-md-4 col-lg-3 mb-4">
  <a href="pages/adventures/?city=new-york" id="new-york">
    <div class="tile">
      <div class="tile-text text-center">
        <h5>New York</h5>
        <p>100+ Places</p>
      </div>
    <img class="img-responsive" src="https://images.pexels.com/photos/2422588/pexels-photo-2422588.jpeg?auto=compress&amp;cs=tinysrgb&amp;dpr=2&amp;h=750&amp;w=1260">
    </div>
  </a>
  </div><div class="col-6 col-md-4 col-lg-3 mb-4">
  <a href="pages/adventures/?city=paris" id="paris">
    <div class="tile">
      <div class="tile-text text-center">
        <h5>Paris</h5>
        <p>100+ Places</p>
      </div>
    <img class="img-responsive" src="https://images.pexels.com/photos/1461974/pexels-photo-1461974.jpeg?auto=compress&amp;cs=tinysrgb&amp;dpr=2&amp;w=500">
    </div>
  </a>
  </div></div>
        </div>
    </div>
   

    <footer>
      <div class="container">© QTrip 2020</div>
    </footer>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>

    <!-- TODO: MODULE_LAYOUT -->
    <!-- Add scripts needed for bootstrap to work -->
  </body>
</html>
