---
layout: docs
title: Templates
description: Base HTML page template
group: decooda-components
toc: true
---

The following page template includes a jumbotron and a 3 column grid to get started. See the [demo]({{ site.baseurl }}/docs/{{ site.docs_version }}/examples/social-site) for an example of this.

<div class="bd-example">
  <div class="bd-example-container">
    <div class="bd-example-container-header" style="background-color: #80bdff;"></div>
    <div class="d-example-container-body d-flex flex-row justify-content-center p-2 rounded">
     <div class="d-example-container-col mx-1"></div>
     <div class="d-example-container-col-m mx-1"></div>
     <div class="d-example-container-col mx-1"></div>
    </div>
  </div>
</div>

{% highlight html %}
<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="./path/to/bootstrap.min.css">
    <title>Hello, world!</title>
  </head>
  <body>
    <nav class="navbar navbar-expand-md navbar-dark fixed-top bg-primary">
      <a class="navbar-brand" href="#">Brand Logo</a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarsExampleDefault" aria-controls="navbarsExampleDefault" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse justify-content-end" id="navbarsExampleDefault">
        <ul class="navbar-nav align-items-baseline">
          <li class="nav-item active">
            <a class="nav-link initialism" href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link initialism" href="#">Link</a>
          </li>
          <li class="nav-item">
            <a class="nav-link initialism" href="#">Link</a>
          </li>
          <li class="nav-item">
            <a class="nav-link initialism" href="#">Link</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#"><i class="fas fa-search"></i></a>
          </li>
          <li class="nav-item">
            <a class="nav-link initialism" href="#">Create Account</i></a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle initialism" href="#" id="dropdown01" data-toggle="dropdown" aria-expanded="false">John Doe</a>
            <div class="dropdown-menu dropdown-menu-right" aria-labelledby="dropdown01">
              <a class="dropdown-item" href="#">Action</a>
              <a class="dropdown-item" href="#">Another action</a>
              <a class="dropdown-item" href="#">Something else here</a>
            </div>
          </li>
        </ul>
      </div>
    </nav>
    <main role="main">
      <!-- Main jumbotron for a primary marketing message or call to action -->
      <div class="jumbotron">
        <div class="container">
          <h1 class="display-3">Hello, world!</h1>
          <p>This is a template with example page components. Use this as a starting point to create something more unique. </p>
          <p><a class="btn btn-primary btn-lg" href="#" role="button">Learn more &raquo;</a></p>
        </div>
      </div>
      <div class="container">
        <!-- Example row of columns -->
        <div class="row mx-lg-n5 justify-content-center">
          <div class="col-lg-3">
            .. Left side content ..
          </div>
          <div class="col-lg-5">
            .. Main content ..
          </div>
          <div class="col-lg-3">
            .. Right side content ..
          </div>
        </div>
        <hr>
      </div> <!-- /container -->
    </main>
    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="./path/to/jquery-3.3.1.js"></script>
    <script src="./path/to/popper.js"></script>
    <script src="./path/to/bootstrap.min.js"></script>
  </body>
</html>

{% endhighlight %}
