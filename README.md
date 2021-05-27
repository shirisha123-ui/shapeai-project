<!DOCTYPE html>
<html>
  <head>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width">
    <title>repl.it</title>
   <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-+0n0xVW2eSR5OomGNYDnhzAbDsOXxcvSN1TPprVMTNDbiYZCxYbOOl7+AMvyTG2x" crossorigin="anonymous">
  </head>
  <body>

<!--navbar-->
<nav class="navbar navbar-expand-lg navbar-dark bg-primary">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">Rallabandi Shirisha</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#hero">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="# My skills">My Skills</a>
        </li>
         <li class="nav-item">
          <a class="nav-link" href="#My works">My Works</a>
        </li>
         <li class="nav-item">
          <a class="nav-link" href="#Contact me">Contact me</a>
        </li>
       
      </ul>
    
    </div>
  </div>
</nav>
<main>
  <main class="container mt-3">
  <section id="hero" class="d-flex justify-content-sm-center justify-content-md-evenly align-items-center flex-column-reverse gap-3 flex-md-row">
<!--hero-->
<div class="d-flex  justify-content-sm-center  align-items-center flex-column justify-content-md-start align-items-md-start"> 
  <h5>Hii...</h5>
  <h1>I'm Rallabandi Shirisha</h1>
  <p>A fullstack web developer!</p>
  <button  class="btn btn-primary btn-sm"> My Cool Resume</button>
</div>
<div class=" d-md-none w-25 h-25">
  <img src="https://www.pngitem.com/pimgs/m/0-6243_user-profile-avatar-scalable-vector-graphics-icon-woman.png" alt="Rallabandi shirisha" class="w-100 h-100 rounded circle shadow">
  </div>
  <div>
<div class="d-none d-md-block w-25 h-25">
   <img src="https://www.pngitem.com/pimgs/m/0-6243_user-profile-avatar-scalable-vector-graphics-icon-woman.png" alt="Rallabandi shirisha" class="w-100 h-100 rounded circle shadow">
</div>
</section>
  <section id="My skills">
<!--My skills-->
<h1 class="text-center text-primary">My Skill set</h1>
<div class="flex flex-column justify-content-sm-cneter">
  <div class="d-flex justify-content-evenly">
   <i class="fa fa-html5" style="font-size:48px;color:red"></i>
   <i class="fa fa-css3" style="font-size:48px;color:red"></i>
  </div>
</div>
  </section>
  
  <section>
    <section id="My works" class="mt-4 p-4">
      <!---My works--->
    <h1 class=" text-primary text-center">My Works</h1>
   <div class="d-flex flex column flex-md-row justify-content-evenly gap-3">
    <div class="card">
  <img src="https://images.unsplash.com/photo-1488590528505-98d2b5aba04b?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80" class="card-img-top" alt="...">
  <div class="card-body">
    <h5 class="card-title">Portfolio Website</h5>
    <p class="card-text">Built an amazing resposive website using Bootstrap</p>
    <a href="#" class="btn btn-primary">view source<i class="fa fa-github"></i></a>
    </div>
  </div>
  <div class="d-flex flex column flex-md-row justify-content-evenly gap-3">
    <div class="card">
  <img src="https://images.unsplash.com/photo-1488590528505-98d2b5aba04b?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80" class="card-img-top" alt="...">
  <div class="card-body">
    <h5 class="card-title">Portfolio Website</h5>
    <p class="card-text">Built an amazing resposive website using Bootstrap</p>
    <a href="#" class="btn btn-primary">view source<i class="fa fa-github"></i></a>
    </div>
  </div>
  <div class="d-flex flex column flex-md-row justify-content-evenly gap-3">
    <div class="card">
  <img src="https://images.unsplash.com/photo-1488590528505-98d2b5aba04b?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80" class="card-img-top" alt="...">
  <div class="card-body">
    <h5 class="card-title">Portfolio Website</h5>
    <p class="card-text">Built an amazing resposive website using Bootstrap</p>
    <a href="#" class="btn btn-primary">view source<i class="fa fa-github"></i></a>
    </div>
  </div>
</section>
  <section id="Contact me" class="mt-4 py-4"> 
  <!--Contact me-->
  <h1 class=" text-primary text-center">Contact Form</h1> 
  <form>
    <div class="mb-3">
  <label for="exampleFormControlInput1" class="form-label">Email address</label>
  <input type="email" reguired class="form-control" id="exampleFormControlInput1" placeholder="name@example.com">
</div>
<div class="mb-3">
  <label for="exampleFormControlTextarea1" class="form-label">your message</label>
  <textarea class="form-control" id="exampleFormControlTextarea1" required placeholder="enter your amazing message!" rows="3"></textarea>
</div>
        <button type="submit" class="btn-btn text-primary">Submit</button>
    </form>
</div>
<div=class="col-sm col-md-4"
<div class="mt-3">
<h3 class="text-primary">@shirisharallabandi25@gmail.com</h3>
<button type="button" class="btn-btn-link">
  <a href="https://desktop.github.com/">Github<i class="fa fa-github"></i></a>
  </div class="mt-3">
</section>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/js/bootstrap.bundle.min.js" integrity="sha384-gtEjrD/SeCtmISkJkNUaaKMoLD0//ElJ19smozuHV6z3Iehds+3Ulb9Bn9Plx0x4" crossorigin="anonymous">
</script> 
   
  </body>
    
</html>
