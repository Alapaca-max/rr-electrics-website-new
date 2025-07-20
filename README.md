<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="R.R Electrics: Professional electrical services and products">
    <title>R.R Electrics - Electrical Services & Products</title>
    <!-- Fixed Bootstrap CSS with HTTPS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f8f9fa;
        }
        .navbar {
            background-color: #0056b3;
        }
        .navbar-brand, .nav-link, .footer {
            color: white !important;
        }
        .hero {
            background-color: #004080;
            color: white;
            padding: 60px 0;
            text-align: center;
        }
        .footer {
            background-color: #003366;
            text-align: center;
            padding: 15px;
            margin-top: 20px;
            color: white;
        }
        .card {
            transition: transform 0.3s;
        }
        .card:hover {
            transform: translateY(-5px);
        }
    </style>
</head>
<body>

<nav class="navbar navbar-expand-lg">
  <div class="container">
    <a class="navbar-brand" href="#">R.R Electrics</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item"><a class="nav-link" href="#services">Services</a></li>
        <li class="nav-item"><a class="nav-link" href="#products">Products</a></li>
        <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
      </ul>
    </div>
  </div>
</nav>

<div class="hero">
    <div class="container">
        <h1>Professional Electrical Services</h1>
        <p>Fast, Reliable, and Affordable Electrical Solutions</p>
    </div>
</div>

<div class="container mt-5" id="services">
    <h2 class="mb-4">Our Services</h2>
    <div class="row">
        <div class="col-md-4 mb-4">
            <div class="card h-100">
                <div class="card-body">
                    <h5 class="card-title">Home Wiring</h5>
                    <p class="card-text">Complete electrical wiring services for your home.</p>
                    <a href="#contact" class="btn btn-primary">Book Now</a>
                </div>
            </div>
        </div>
        <div class="col-md-4 mb-4">
            <div class="card h-100">
                <div class="card-body">
                    <h5 class="card-title">Appliance Installation</h5>
                    <p class="card-text">Safe installation of home appliances.</p>
                    <a href="#contact" class="btn btn-primary">Book Now</a>
                </div>
            </div>
        </div>
        <div class="col-md-4 mb-4">
            <div class="card h-100">
                <div class="card-body">
                    <h5 class="card-title">Electrical Repair</h5>
                    <p class="card-text">Reliable repair services for any issues.</p>
                    <a href="#contact" class="btn btn-primary">Book Now</a>
                </div>
            </div>
        </div>
    </div>
</div>

<div class="container mt-5" id="products">
    <h2 class="mb-4">Shop Products</h2>
    <div class="row">
        <div class="col-md-3 mb-4">
            <div class="card h-100">
                <div class="card-body">
                    <h5 class="card-title">Electrical Wire Roll</h5>
                    <p class="card-text">₹500 per roll</p>
                    <button class="btn btn-success">Add to Cart</button>
                </div>
            </div>
        </div>
        <div class="col-md-3 mb-4">
            <div class="card h-100">
                <div class="card-body">
                    <h5 class="card-title">LED Bulb (12W)</h5>
                    <p class="card-text">₹150 each</p>
                    <button class="btn btn-success">Add to Cart</button>
                </div>
            </div>
        </div>
        <div class="col-md-3 mb-4">
            <div class="card h-100">
                <div class="card-body">
                    <h5 class="card-title">Switch Board Set</h5>
                    <p class="card-text">₹350 per set</p>
                    <button class="btn btn-success">Add to Cart</button>
                </div>
            </div>
        </div>
        <div class="col-md-3 mb-4">
            <div class="card h-100">
                <div class="card-body">
                    <h5 class="card-title">Extension Cord (5m)</h5>
                    <p class="card-text">₹250 each</p>
                    <button class="btn btn-success">Add to Cart</button>
                </div>
            </div>
        </div>
    </div>
</div>

<div class="container mt-5" id="contact">
    <h2 class="mb-4">Contact Us</h2>
    <form action="https://formspree.io/f/xdkdknkk" method="POST">
        <div class="mb-3">
            <label for="name" class="form-label">Name</label>
            <input type="text" class="form-control" id="name" name="name" required>
        </div>
        <div class="mb-3">
            <label for="email" class="form-label">Email</label>
            <input type="email" class="form-control" id="email" name="email" required>
        </div>
        <div class="mb-3">
            <label for="message" class="form-label">Message</label>
            <textarea class="form-control" id="message" name="message" rows="3" required></textarea>
        </div>
        <button type="submit" class="btn btn-primary">Send Message</button>
    </form>
</div>

<div class="footer">
    <p>&copy; 2025 R.R Electrics. All Rights Reserved. Contact: <a href="tel:7980773078" style="color:white;">79807 73078</a></p>
</div>

<!-- Fixed Bootstrap JS with HTTPS -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
