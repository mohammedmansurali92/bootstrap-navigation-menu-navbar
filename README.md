# bootstrap-navigation-menu-navbar
Bootstrap navigation menu and navbar.
<head>
  <title>Bootstrap 4 Example</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <script src="https://kit.fontawesome.com/b99e675b6e.js"></script>
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
  <style>
  	.my-link-style:hover{
      text-decoration: underline;
    }
  </style>
  <title>Bootstrap grid Layout</title>
</head>
<body> 
	<div class="container">
    <header class="bg-primary">
     <div class="row">
       <div class="col-lg-5 m-auto">
         <h1 class=" text-white mb-0 py-2 text-center">My bootstrap study</h1>
       </div>
       <div class="col-lg-7">
         <ul class="nav justify-content-center">
           <li class="nav-item"><a class="nav-link text-white my-link-style" href="#">Home</a></li>
           <li class="nav-item"><a class="nav-link text-white my-link-style" href="#">About</a></li>
           <li class="nav-item"><a class="nav-link text-white my-link-style" href="#">Contact</a></li>
           <li class="nav-item"><a class="nav-link text-white my-link-style" href="#">Servises</a></li>
         </ul>
       </div>
     </div>
    </header><!-- /header -->
    <main>
  <div class="service-section bg-light pt-3">
    <div class="title text-center mb-3">
      <h3 class="font-weight-bolder">Services</h3>
     
    <div class="row text-left text-md-center">
        <div class="col-lg-3 col-md-6">
          <i class="bg-primary text-white rounded-circle mb-3 p-2 fa-2x fas fa-hands-helping"></i>
          <h5 class="text-uppercase">Web designing</h5>
          <p class="small text-muted">Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remain</p>
        </div>
        <div class="col-lg-3 col-md-6">
          <i class="bg-primary text-white rounded-circle mb-3 p-2 fa-2x fas fa-hands-helping"></i>
          <h5 class="text-uppercase">Web designing</h5>
          <p class="small text-muted">Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, </p>
        </div>
        <div class="col-lg-3 col-md-6">
          <i class="bg-primary text-white rounded-circle mb-3 p-2 fa-2x fas fa-hands-helping"></i>
          <h5 class="text-uppercase">Web designing</h5>
          <p class="small text-muted"
          >Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged.</p>
        </div>
        <div class="col-lg-3 col-md-6">
          <i class="bg-primary text-white rounded-circle mb-3 p-2 fa-2x fas fa-hands-helping"></i>
          <h5 class="text-uppercase">Web designing</h5>
          <p class="small text-muted">Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged.</p>
        </div>
      </div>
      </div>
  </div>
      
                                     <!..About me section..>
     <div class="about-me">
       <div class="jumbotron pt-2">
         <div class="title text-center mb-3">
      <h3 class="font-weight-bolder">About Me</h3>
      <div class="row">
        <div class="col-sm-4">
          <img class="rounded-circle" src="D:\New image1\mansur_cv.jpg">
        </div>
        <div class="col-sm-8">
          <p class="text-left">Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, ultricies nec, pellentesque eu, pretium quis, sem. 
            <a href="#demo" data-toggle="collapse">Learn More</a>
            <div id="demo" class="collapse">
              Nulla consequat massa quis enim. Donec pede justo, fringilla vel, aliquet nec, vulputate eget, arcu. In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo. Nullam dictum felis eu pede mollis pretium. Integer tincidunt. Cras dapibus. Vivamus elementum semper nisi. Aenean vulputate eleifend tellus. Aenean leo ligula, porttitor eu, consequat vitae, eleifend ac, enim. Aliquam lorem ante, dapibus in, viverra quis, feugiat a, tellus. Phasellus viverra nulla ut metus varius laoreet. Quisque rutrum. Aenean imperdiet. Etiam ultricies nisi vel augue. Curabitur ullamcorper ultricies nisi. Nam eget dui. Etiam rhoncus. Maecenas tempus, tellus eget condimentum rhoncus, sem quam semper libero, sit amet adipiscing sem neque sed ipsum. Nam quam nunc, blandit vel, luctus pulvinar, hendrerit id, lorem. Maecenas nec odio et ante tincidunt tempus.
            </div>
         </p>
         <div class="btn btn-group">
         <button class="btn btn-outline-primary btn-lg mb-3">Download CV </button>
         <button class=" btn btn-outline-primary btn-lg mb-3">Download CV </button>
         <a class="btn btn-outline-primary btn-lg mb-3" href="https://www.youtube.com/watch?v=IAAH220j_OM">Visit My Chanel</a>
       </div>
         <div class="alert alert-success alert-dismissible">
          <button class="close" data-dismiss="alert">&times;</button>
           Have you visit my website URL:<a href="https://trmorning.com">Visit Me</a>
         </div>
         <div class="alert alert-warning alert-dismissible">
          <button class="close" data-dismiss="alert">&times;</button>
           Have you visit my website URL:<a href="https://trmorning.com/?page_id=2264">Visit My Resume</a>
         </div>
        </div>
      </div>
       </div>
     </div>
     <!-- About me section End here-->
     <!--customer review section start here-->
     <div class="customer-review text-center">
       <div class="title text-center mb-3">
      <h3 class="font-weight-bolder background-light">Customer Review</h3>
      <div class="row">
        <div class="col-lg-4">
          <blockquote class="blockquote">
            <i class="p-2 fa-3x fas fa-user-circle"></i>
            <p class="small">Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries.In this website We can learn <abbr title="bootstrap4">Bs4</abbr></p>
             <footer class="blockquote-footer">
           Mohammad Mansur Ali<cite>Web Developer</cite> 
          </footer>
          </blockquote>
         
        </div>
        <div class="col-lg-4">
          <blockquote class="blockquote">
            <i class="p-2 fa-3x fas fa-user-circle"></i>
            <p class="small">Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.In this website We can learn <abbr title="bootstrap4">Bs4</abbr></p>
             <footer class="blockquote-footer">
           Mohammad Mansur Ali<cite>Web Developer</cite> 
          </footer>
          </blockquote>
         
        </div>
        <div class="col-lg-4">
          <blockquote class="blockquote">
            <i class="p-2 fa-3x fas fa-user-circle"></i>
            <p class="small">Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.In this website We can learn <abbr title="bootstrap4">Bs4</abbr></p>
             <footer class="blockquote-footer">
           Mohammad Mansur Ali<cite>Web Developer</cite> 
          </footer>
          </blockquote>
         
        </div>
      </div>
    </div>
     </div>
      <!--customer review syestem end here-->
      <!--student list syestem start here-->
       <div class="student-list">
         <ul class="list-group">
           <li class="list-group-item bg-primary text-white">Mohammad Mansur</li>
            <li class="list-group-item bg-warning text-white">Tahmina Rahman</li>
             <li class="list-group-item bg-success text-white">Sumon Sarker</li>
             <a class="list-group-item list-group-item-action bg-danger text-white text-center" href="#">Towhid</a>
         </ul>
       </div>
      <!--student list syestem end here-->
    </main>
    <footer class="bg-dark">
     <ul class="pagination py-3 justify-content-center">
      <li class="page-item"><a class="page-link" href="https://trmorning.com">1</a></li>
      <li class="page-item"><a class="page-link" href="https://blog.trmorning.com">2</a></li>
      <li class="page-item"><a class="page-link" href="https://e-commerce.trmorning.com">3</a></li>
       <li class="page-item"><a class="page-link" href="https://www.youtube.com/watch?v=IAAH220j_OM">4</a></li>
     </ul>
    </footer>
  </div>
 <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html> 
