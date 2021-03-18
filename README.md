# Website
<!DOCTYPE html>
<html>
    <head>
        <link rel="stylesheet" href="bootstrap.css">
        <link rel="stylesheet" href="path/to/font-awesome/css/font-awesome.min.css">

        <style>
            .jumbotron{
                background-image: url(bg5.jpg);
                text-align: center;
            }

            #appSumarry{
              text-align: center;

            }
            #footer{
              background-color: blueviolet;
              padding-top: 50px;
              margin-top: 50px;
              text-align: center;
              padding-bottom: 50px;
            }
          body {
            position: relative;
          }  
           
        </style>

    </head>

    <body data-spy="scroll" data-bs-target="#navbar">
        <nav class="navbar navbar-expand-lg navbar-light bg-light navbar-fixed-top" id="navbar">
            <div class="container-fluid">
              <a class="navbar-brand" href="#">MyApp</a>
              <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
              </button>
              <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                  <li class="nav-item">
                    <a class="nav-link active" aria-current="page" href="#jumbotron">Home</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" href="#card">About</a>
                  </li>
                  <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle" href="#footer" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                      Download the app
                    </a>
                    <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                      <li><a class="dropdown-item" href="#">Action</a></li>
                      <li><a class="dropdown-item" href="#">Another action</a></li>
                      <li><hr class="dropdown-divider"></li>
                      <li><a class="dropdown-item" href="#">Something else here</a></li>
                    </ul>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link disabled" href="#" tabindex="-1" aria-disabled="true">Disabled</a>
                  </li>
                </ul>
                <form class="d-flex">
                  <input class="form-control me-2" type="Email" placeholder="Email" aria-label="Search">
                  <input class="form-control me-2" type="Password" placeholder="Password" aria-label="Search">
                  <button class="btn btn-outline-success" type="submit">login</button>
                </form>
              </div>
            </div>
          </nav>
          <div class="jumbotron" id="jumbotron">
            <h1 class="display-4"> My App</h1>
            <p class="lead">This is you should download this App</p>
            <hr class="my-4">
            <p>Want to know more?Join our mailing list.</p>

            <form class="row gx-3 gy-2 align-items-center">
                <div class="col-sm-3">
                  <label class="visually-hidden" for="specificSizeInputName">Name</label>
                  <input type="text" class="form-control" id="specificSizeInputName" placeholder="Your Name">
                </div>
                <div class="col-sm-3">
                  <label class="visually-hidden" for="email">Email address></label>
                  <div class="input-group">
                    <div class="input-group-text">@</div>
                    <input type="text" class="form-control" id="email" placeholder="Your Email">
                  </div>
                </div>
                
                  
                
                <div class="col-auto">
                  <div class="form-check">
                    <input class="form-check-input" type="checkbox" id="autoSizingCheck2">
                    <label class="form-check-label" for="autoSizingCheck2">
                      Remember me
                    </label>
                  </div>
                </div>
                <div class="col-auto">
                  <button type="submit" class="btn btn-primary">Sign up</button>
                </div>
              </form>

           
          </div>
          <div class="container">
              <div class="row" id="appSumarry">
                 <h1>
                   Why this app is awesome
                </h1>
            <p class="lead">Summary</p>
              </div>
          </div>
          <div class="row row-cols-1 row-cols-md-3 g-4" id="card">
            <div class="col">
              <div class="card h-100">
                <img src="mug.jpg" class="card-img-top" alt="...">
                <div class="card-body">
                  <h5 class="card-title"><i class="fa fa-anchor" aria-hidden="true">Card title</h5></i>
                  <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
                </div>
                <div class="card-footer">
                  <small class="text-muted">Last updated 3 mins ago</small>
                </div>
              </div>
            </div>
            <div class="col">
              <div class="card h-100">
                <img src="mug.jpg" class="card-img-top" alt="...">
                <div class="card-body">
                  <h5 class="card-title">Card title</h5>
                  <p class="card-text">This card has supporting text below as a natural lead-in to additional content.</p>
                </div>
                <div class="card-footer">
                  <small class="text-muted">Last updated 3 mins ago</small>
                </div>
              </div>
            </div>
            <div class="col">
              <div class="card h-100">
                <img src="mug.jpg" class="card-img-top" alt="...">
                <div class="card-body">
                  <h5 class="card-title">Card title</h5>
                  <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This card has even longer content than the first to show that equal height action.</p>
                </div>
                <div class="card-footer">
                  <small class="text-muted">Last updated 3 mins ago</small>
                </div>
              </div>
            </div>
          </div>    
         <div id="footer">
            <div class="row">
              <h2>Download the app</h2>
              <p><a href=""><img src="play_store_icon.png"></a>
            </div>
         </div> 

    </body>
</html>
