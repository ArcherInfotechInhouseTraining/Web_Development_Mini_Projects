<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="mandatory.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <style>
      .main-title {
        font-size: 2rem; /* Default font size */
      }
    
      /* Adjust for medium screens (tablets) and up */
      @media (min-width: 768px) {
        .main-title {
          font-size: 3rem; /* Larger font for medium screens */
        }
      }
    
      /* Adjust for large screens (desktops) and up */
      @media (min-width: 992px) {
        .main-title {
          font-size: 4rem; /* Even larger font for large screens */
        }
      }
    
      .sub-title {
        font-size: 1.5rem; /* Default font size */
      }
    
      /* Adjust for medium screens (tablets) and up */
      @media (min-width: 768px) {
        .sub-title {
          font-size: 2.5rem; /* Larger font for medium screens */
        }
      }
    
      /* Adjust for large screens (desktops) and up */
      @media (min-width: 992px) {
        .sub-title {
          font-size: 3rem; /* Even larger font for large screens */
        }
      }
    </style>
    
</head>
<body>
    <nav class="navbar navbar-expand-lg">
        <div class="container-fluid">
          <a class="navbar-brand text-white me-3" href="#"><img src="assets/img/navbar-logo.svg" width="160"></a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon bg-light"></span>
          </button>
          <div class="collapse navbar-collapse ms-auto text-end" id="navbarNav">
            <ul class="navbar-nav ms-auto text-end">
              <li class="nav-item">
                <a class="nav-link active text-white" aria-current="page" href="#">Home</a>
              </li>
              <li class="nav-item">
                <a class="nav-link text-white" href="#">Features</a>
              </li>
              <li class="nav-item">
                <a class="nav-link text-white" href="#">Pricing</a>
              </li>
            </ul>
          </div>
        </div>
      </nav>
      <!-- HTML Structure -->
<div class="bg-image main-img d-flex justify-content-center align-items-center">
  <div class="main-container text-light d-flex justify-content-center align-items-center flex-column text-center">
    
    <!-- Main Title with custom CSS for responsive font size -->
    <div class="roboto-slab fw-bold main-title">Welcome To Our Studio!</div>
    
    <!-- Subtitle with custom CSS for responsive font size -->
    <div>
      <h1 class="adjust text-uppercase fw-bold sub-title">It's Nice To Meet You</h1>
    </div>

    <!-- Button -->
    <a class="btn bgcolor-y btn-xl text-uppercase text-white" href="#services">Tell Me More</a>

  </div>
</div>

      <div class="d-flex justify-content-center align-items-center flex-column">
        <div class="container px-4 py-5" id="hanging-icons">
          <h1 class="pb-2 text-center fs-1">SERVICES</h1>
          <h6 class="text-center">Lorem, ipsum dolor sit amet consectetur adipisicing elit.</h6>
          <div class="row g-4 py-5 row-cols-1 row-cols-lg-3 justify-content-center">
            <!-- Service 1 -->
            <div class="col d-flex justify-content-center align-items-center flex-column"style="width: 25rem;">
              <div class="icon-square text-body-emphasis bg-body-secondary d-inline-flex align-items-center justify-content-center fs-4 mb-3"></div>
              <h3 class="fs-2 text-body-emphasis"><img width="150" src="assets/img/logo/CART.png" alt="CART Logo"></h3>
              <p class="text-center">Paragraph of text beneath the heading to explain the heading. We'll add onto it with another sentence and probably just keep going until we run out of words.</p>
            </div>
            
            <!-- Service 2 -->
            <div class="col d-flex justify-content-center align-items-center flex-column"style="width: 25rem;">
              <div class="icon-square text-body-emphasis bg-body-secondary d-inline-flex align-items-center justify-content-center fs-4 mb-3"></div>
              <h3 class="fs-2 text-body-emphasis"><img width="150" src="assets/img/logo/lap.png" alt="Laptop Logo"></h3>
              <p class="text-center">Paragraph of text beneath the heading to explain the heading. We'll add onto it with another sentence and probably just keep going until we run out of words.</p>
            </div>
            
            <!-- Service 3 -->
            <div class="col d-flex justify-content-center align-items-center flex-column"style="width: 25rem;">
              <div class="icon-square text-body-emphasis bg-body-secondary d-inline-flex align-items-center justify-content-center fs-4 mb-3"></div>
              <h3 class="fs-2 text-body-emphasis"><img width="150" src="assets/img/logo/web.png" alt="Web Logo"></h3>
              <p class="text-center">Paragraph of text beneath the heading to explain the heading. We'll add onto it with another sentence and probably just keep going until we run out of words.</p>
            </div>
          </div>
        </div>
      </div>

      <div class="bg-light">
        <div  class="d-flex justify-content-center align-items-center flex-column size">
          <div class="container px-4 py-5" id="hanging-icons">
            <h1 class="pb-2 text-center fs-1">PORTFOLIO</h1>
            <h6 class="text-center">Lorem, ipsum dolor sit amet consectetur adipisicing elit.</h6>
          </div>
        </div>
        <div class="row row-cols-md-4 g-4">
          <div class="col-md-4 d-flex justify-content-center">
            <div class="card text-center">
              <img src="assets/img/portfolio/1.jpg" class="img-thumbnail" alt="Hollywood Sign on The Hill" style="width: 250px; height: 180px; padding: 10px; margin: auto;"/>
              <div class="card-body">
                <h5 class="card-title">Card title</h5>
                <p class="card-text">illustration</p>
              </div>
            </div>
          </div>
        
          <div class="col-md-4 d-flex justify-content-center">
            <div class="card text-center">
              <img src="assets/img/portfolio/2.jpg" class="img-thumbnail" alt="Palm Springs Road" style="width: 250px; height: 180px; padding: 10px; margin: auto;"/>
              <div class="card-body">
                <h5 class="card-title">Card title</h5>
                <p class="card-text">graphics design</p>
              </div>
            </div>
          </div>
        
          <div class="col-md-4 d-flex justify-content-center">
            <div class="card text-center">
              <img src="assets/img/portfolio/3.jpg" class="img-thumbnail" alt="Image 3" style="width: 250px; height: 180px; padding: 10px; margin: auto;"/>
              <div class="card-body">
                <h5 class="card-title">Card title</h5>
                <p class="card-text">identity</p>
              </div>
            </div>
          </div>
        
          <div class="col-md-4 d-flex justify-content-center">
            <div class="card text-center">
              <img src="assets/img/portfolio/4.jpg" class="img-thumbnail" alt="Skyscrapers" style="width: 250px; height: 180px; padding: 10px; margin: auto;"/>
              <div class="card-body">
                <h5 class="card-title">Card title</h5>
                <p class="card-text">branding</p>
              </div>
            </div>
          </div>
        
          <div class="col-md-4 d-flex justify-content-center">
            <div class="card text-center">
              <img src="assets/img/portfolio/5.jpg" class="img-thumbnail" alt="Image 5" style="width: 250px; height: 180px; padding: 10px; margin: auto;"/>
              <div class="card-body">
                <h5 class="card-title">Card title</h5>
                <p class="card-text">Website design</p>
              </div>
            </div>
          </div>
        
          <div class="col-md-4 d-flex justify-content-center">
            <div class="card text-center">
              <img src="assets/img/portfolio/6.jpg" class="img-thumbnail" alt="Image 6" style="width: 250px; height: 180px; padding: 10px; margin: auto;"/>
              <div class="card-body">
                <h5 class="card-title">Card title</h5>
                <p class="card-text">photography</p>
              </div>
            </div>
          </div>
        </div>
      
      </div> 

        <!-------------------------------------------------------------------------->
<div>
  <div>
    <div  class="d-flex justify-content-center align-items-center flex-column size">
      <div class="container px-4 py-5" id="hanging-icons">
        <h1 class="pb-2 text-center fs-1">ABOUT</h1>
        <h6 class="text-center">Lorem, ipsum dolor sit amet consectetur adipisicing elit.</h6>
      </div>
    </div>
    <link href="//maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" rel="stylesheet" id="bootstrap-css">
    <script src="//maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js"></script>
    <script src="//cdnjs.cloudflare.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
    <!------ Include the above in your HEAD tag ---------->
    
    <div class="container">
          <div class="timeline ">
            <div class="row no-gutters justify-content-end justify-content-md-around align-items-start  timeline-nodes">
              <div class="col-10 col-md-5 order-3 order-md-1 timeline-content">
                <h3 class=" text-light">Timeline Heading</h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Saepe, eaque amet deleniti hic quas qui cumque delectus aliquid, eius quia quod, quae, aliquam aspernatur facilis. Minima quod corporis dignissimos porro.</p>
              </div>
              <div class="col-2 col-sm-1 px-md-3 order-2 timeline-image text-md-center">
                <img src="assets/img/about/1.jpg" class="img-fluid rounded-circle imgg" alt="img">
              </div>
              <div class="col-10 col-md-5 order-1 order-md-3 py-3 timeline-date">
                <time>2018-02-23</time>
              </div>
            </div>
            <div class="row no-gutters justify-content-end justify-content-md-around align-items-start  timeline-nodes">
              <div class="col-10 col-md-5 order-3 order-md-1 timeline-content">
                <h3 class=" text-light">Timeline Heading</h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Saepe, eaque amet deleniti hic quas qui cumque delectus aliquid, eius quia quod, quae, aliquam aspernatur facilis. Minima quod corporis dignissimos porro.</p>
              </div>
              <div class="col-2 col-sm-1 px-md-3 order-2 timeline-image text-md-center">
                <img src="assets/img/about/2.jpg" class="img-fluid rounded-circle" alt="img">
              </div>
              <div class="col-10 col-md-5 order-1 order-md-3 py-3 timeline-date">
                <time>2018-02-23</time>
              </div>
            </div>
            <div class="row no-gutters justify-content-end justify-content-md-around align-items-start  timeline-nodes">
              <div class="col-10 col-md-5 order-3 order-md-1 timeline-content">
                <h3 class=" text-light">Timeline Heading</h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Saepe, eaque amet deleniti hic quas qui cumque delectus aliquid, eius quia quod, quae, aliquam aspernatur facilis. Minima quod corporis dignissimos porro.</p>
              </div>
              <div class="col-2 col-sm-1 px-md-3 order-2 timeline-image text-md-center">
                <img src="assets/img/about/3.jpg" class="img-fluid rounded-circle" alt="img">
              </div>
              <div class="col-10 col-md-5 order-1 order-md-3 py-3 timeline-date">
                <time>2018-02-23</time>
              </div>
            </div>
            <div class="row no-gutters justify-content-end justify-content-md-around align-items-start  timeline-nodes">
              <div class="col-10 col-md-5 order-3 order-md-1 timeline-content">
                <h3 class=" text-light">Timeline Heading</h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Saepe, eaque amet deleniti hic quas qui cumque delectus aliquid, eius quia quod, quae, aliquam aspernatur facilis. Minima quod corporis dignissimos porro.</p>
              </div>
              <div class="col-2 col-sm-1 px-md-3 order-2 timeline-image text-md-center">
                <img src="assets/img/about/4.jpg" class="img-fluid rounded-circle" alt="img">
              </div>
              <div class="col-10 col-md-5 order-1 order-md-3 py-3 timeline-date">
                <time>2018-02-23</time>
              </div>
            </div>
          </div>
        </div>
    <!-------------------------------------------------------------------------------------------------------->    
<div>
  <div class=" bg-light d-flex justify-content-center align-items-center flex-column size">
    <div >
      <div class="container px-4 py-5" id="hanging-icons">
        <h1 class="pb-2 text-center fs-1">OUR AMAZING TEAM</h1>
        <h6 class="text-center">Lorem, ipsum dolor sit amet consectetur adipisicing elit.</h6>
      </div>
    </div>
  <div class="card bg-light border-0 d-flex justify-content-center align-items-center">
    <div class="bg-image hover-overlay">
      <img width="250rem" height="236rem" class="rounded-circle  " src="assets/img/team/1.jpg" class="img-fluid"/>
    </div>
    <div class="card-body d-flex justify-content-center align-items-center flex-column size">
      <h5 class="card-title">Parveen Anand</h5>
      <p class="card-text">Lead Designer</p>
      <div class="d-flex justify-content-center align-items-center"> 
        <img class="img-size1" src="assets/img/social/1.png">
        <img class="img-size2" src="assets/img/social/2.png">
        <img class="img-size1" src="assets/img/social/3.png">
      </div>
    </div>
    
    <div class="card bg-light border-0 d-flex justify-content-center align-items-center">
      <div class="bg-image hover-overlay">
        <img width="250rem" height="236rem" class="rounded-circle  " src="assets/img/team/2.jpg" class="img-fluid"/>
      </div>
      <div class="card-body border-0 d-flex justify-content-center align-items-center flex-column size">
        <h5 class="card-title">Dianac Petersen</h5>
        <p class="card-text">Lead Marketer</p>
        <div class="d-flex justify-content-center align-items-center"> 
          <img class="img-size1" src="assets/img/social/1.png">
          <img class="img-size2" src="assets/img/social/2.png">
          <img class="img-size1" src="assets/img/social/3.png">

        </div>
      </div>
      <div class="card bg-light border-0 d-flex justify-content-center align-items-center">
        <div class="bg-image hover-overlay">
          <img width="250rem" height="236rem" class="rounded-circle  " src="assets/img/team/3.jpg" class="img-fluid"/>
        </div>
        <div class="card-body border-0 d-flex justify-content-center align-items-center flex-column size">
          <h5 class="card-title">Larry Parker</h5>
          <p class="card-text">Lead Developer</p>
          <div class="d-flex justify-content-center align-items-center"> 
            <img class="img-size1" src="assets/img/social/1.png">
            <img class="img-size2" src="assets/img/social/2.png">
            <img class="img-size1" src="assets/img/social/3.png">

          </div>
</div>
<div class="main-container mt-5 mb-5">
  <div class="d-flex  justify-content-center align-items-center gap-5">
    <img src="assets/img/logos/microsoft.svg" class="img-fluid" style="height: 5rem; width: auto;">
    <img src="assets/img/logos/facebook.svg" class="img-fluid" style="height: 5rem; width: auto;">
    <img src="assets/img/logos/google.svg" class="img-fluid" style="height: 5rem; width: auto;">
    <img src="assets/img/logos/ibm.svg" class="img-fluid" style="height: 4rem; width: auto;">
  </div>
</div>



</div>
<div class="bg-img ">
 
  <div class="main-container mt-5 text-light d-flex justify-content-center align-items-center flex-column text-center">
    
    <!-- Main Title with custom CSS for responsive font size -->
    <div class="roboto-slab fw-bold main-title">CONTACT US</div>
    
    <!-- Subtitle with custom CSS for responsive font size -->
    <div>
      <h1 class="sub-title fs-6">lorem ipsum dolor sit amet concenceter </h1>
    </div>

    <div class="container mt-5">
    
      <form>
          <div class="row">
              <!-- Left Column for Name, Email, and Phone -->
              <div class="col-md-6">
                  <div class="mb-3">
                      <label for="name" class="form-label">Name</label>
                      <input type="text" class="form-control" id="name" placeholder="Enter your name">
                  </div>
                  <div class="mb-3">
                      <label for="email" class="form-label">Email address</label>
                      <input type="email" class="form-control" id="email" placeholder="Enter your email">
                  </div>
                  <div class="mb-3">
                      <label for="phone" class="form-label">Phone</label>
                      <input type="tel" class="form-control" id="phone" placeholder="Enter your phone number">
                  </div>
              </div>
  
              <!-- Right Column for Message -->
              <div class="col-md-6">
                  <div class="mb-3">
                      <label for="message" class="form-label">Message</label>
                      <textarea class="form-control" id="message" rows="8" placeholder="Enter your message"></textarea>
                  </div>
              </div>
          </div>
          
          <!-- Send Message Button -->
          <div class="text-center mt-4">
              <button type="submit" class="btn text-dark" style="background-color: rgb(214, 214, 65);">Send Message</button>
          </div>
      </form>
  </div>  
  </div>
</div>    
<footer class=" text-center py-4">
  <div class="container">
      <!-- Copyright Info -->
      <p class="mb-2">copyright © Website 2023</p>

      <!-- Social Media Icons (Using Images) -->
      <div class="mb-3">
          <a href="https://twitter.com" target="_blank" class="me-3">
              <img src="assets/img/social/1.png" alt="Twitter" width="40" height="40">
          </a>
          <a href="https://facebook.com" target="_blank" class="me-3">
              <img src="assets/img/social/2.png" alt="Facebook" width="50" height="50">
          </a>
          <a href="https://linkedin.com" target="_blank">
              <img src="assets/img/social/3.png" alt="LinkedIn" width="40" height="40">
          </a>
      </div>

      <!-- Privacy Policy and Terms of Use Links -->
      <div>
          <a href="#" class="text-dark me-3">Privacy Policy</a>
          <a href="#" class="text-dark">Terms of Use</a>
      </div>
  </div>
</footer>

        
       <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
</body>
</html># Mini Project 1

- Project Folder
- Output Screenshot
- <img = src "https://github.com/ArcherInfotechInhouseTraining/Web_Development_Mini_Projects/blob/main/NItin/Mini%20Project%201/Output%20Screenshots/website%20screen%20shot.png?raw=true">

- And also write README.MD
