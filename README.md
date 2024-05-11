# Project Responsive Web Design using Bootstrap
## Date:07-05-2024

## AIM:
To design a responsive website for a Pharmaceutical Company using Bootstrap.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :

#### project.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PharmaCo</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
</head>
<body>

<div class="container">
    <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
        <a class="navbar-brand" href="#">PharmaCo</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent"
                aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                <li class="nav-item">
                    <a class="nav-link" href="project.html">Home</a>
                </li>
                <li class="nav-item dropdown active">
                    <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownAbout" role="button"
                       data-bs-toggle="dropdown" aria-expanded="false">
                        About
                    </a>
                    <ul class="dropdown-menu" aria-labelledby="navbarDropdownAbout">
                        <li><a class="dropdown-item" href="#vision">Vision</a></li>
                        <li><a class="dropdown-item" href="#mission">Mission</a></li>
                        <li><a class="dropdown-item" href="#values">Values</a></li>
                    </ul>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="product.html">Products</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="contact.html">Contact</a>
                </li>
            </ul>
        </div>
    </nav>

    <div style="width: 10%;">
        <img src="pharmaco_logo.png" style="width: 80%;" class="img-fluid">
    </div>

    <h1 class="text-danger display-1">PharmaCo, Advancing Healthcare Together</h1>
    <h1 class="text-danger fs-5">PharmaCo is dedicated to revolutionizing healthcare through cutting-edge pharmaceuticals and innovative medical solutions. Our commitment lies in improving patient outcomes, enhancing quality of life, and addressing unmet medical needs globally.</h1>

    <div>
        <div class="card" style="width: 100%; margin: 30px;">
            <img src="drug1.webp" class="card-img-top" alt="...">
            <div class="card-body">
                <h5 class="card-title">New Breakthrough Drug Approval</h5>
                <p class="card-text">PharmaCo announces FDA approval for its latest breakthrough drug, offering hope for patients with chronic conditions. Learn more about how this innovative treatment is transforming lives.</p>
                <a href="#" class="btn btn-primary">READ MORE</a>
            </div>
        </div>
        <div class="card" style="width: 100%; margin: 30px;">
            <img src="drug2.webp" class="card-img-top" alt="...">
            <div class="card-body">
                <h5 class="card-title">Revolutionary Cancer Treatment Unveiled</h5>
                <p class="card-text">PharmaCo introduces a groundbreaking cancer treatment, leveraging advanced immunotherapy techniques to target malignant cells with unprecedented precision. Witness the future of oncology care.</p>
                <a href="#" class="btn btn-primary">EXPLORE NOW</a>
            </div>
        </div>
        <div class="card" style="width: 100%; margin: 30px;">
            <img src="drug3.jpg" class="card-img-top" alt="...">
            <div class="card-body">
                <h5 class="card-title">Breakthrough Alzheimer's Research Breaks New Ground</h5>
                <p class="card-text">PharmaCo's latest research initiative promises hope for millions affected by Alzheimer's disease. With promising early results, learn how we're tackling one of the most challenging medical mysteries of our time.</p>
                <a href="#" class="btn btn-primary">EXPLORE NOW</a>
            </div>
        </div>
    </div>

    <div id="carouselExampleIndicators" class="carousel slide" data-bs-ride="carousel" data-bs-interval="2000" style="margin-top: 20px;">
        <div class="carousel-inner">
            <div class="carousel-item active">
                <img src="pharma_slider1.jpg" class="d-block w-100" alt="...">
            </div>
            <div class="carousel-item">
                <img src="pharma_slider2.jpg" class="d-block w-100" alt="...">
            </div>
            <div class="carousel-item">
                <img src="pharma_slider3.png" class="d-block w-100" alt="...">
            </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
        </button>
    </div>
    <footer class="bg-dark text-light text-center py-3">
        <div class="container">
            <p>&#169 Sri Harish B [212223220110] 2024 PharmaCo. All rights reserved.</p>
        </div>
    </footer>
</div>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>

</body>
</html>

```

#### product.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PharmaCo - Products</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
</head>
<body>

<div class="container">
    <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
        <a class="navbar-brand" href="#">PharmaCo</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent"
                aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                <li class="nav-item">
                    <a class="nav-link" href="project.html">Home</a>
                </li>
                <li class="nav-item dropdown active">
                    <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownAbout" role="button"
                       data-bs-toggle="dropdown" aria-expanded="false">
                        About
                    </a>
                    <ul class="dropdown-menu" aria-labelledby="navbarDropdownAbout">
                        <li><a class="dropdown-item" href="#vision">Vision</a></li>
                        <li><a class="dropdown-item" href="#mission">Mission</a></li>
                        <li><a class="dropdown-item" href="#values">Values</a></li>
                    </ul>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="product.html">Products</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="contact.html">Contact</a>
                </li>
            </ul>
        </div>
    </nav>

    <div style="width: 10%;">
        <img src="pharmaco_logo.png" style="width: 80%;" class="img-fluid">
    </div>

    <!-- Product Section -->

    <div class="mt-5">
        <div class="card" style="width: 100%; margin: 30px;">
            <!-- Product Image -->
            <img src="p2.avif" class="card-img-top" alt="Product Image">
            <div class="card-body">
                <!-- Product Heading -->
                <h5 class="card-title">Human Cell Line Research Kits:</h5>
                <!-- Product Body -->
                <p class="card-text">These kits allow research on specific human cells for medical research. Prices vary depending on the cell line.</p>
                <!-- Product Price -->
                <h6 class="card-subtitle mb-2 text-muted">Price: $100.00 to $500.00 [USD]</h6>
                <!-- Button to learn more -->
                <a href="#" class="btn btn-primary">Learn More</a>
            </div>
        </div>
    </div>
    <div class="mt-5">
        <div class="card" style="width: 100%; margin: 30px;">
            <!-- Product Image -->
            <img src="p1.avif" class="card-img-top" alt="Product Image">
            <div class="card-body">
                <!-- Product Heading -->
                <h5 class="card-title">DNA Ancestry Kits:</h5>
                <!-- Product Body -->
                <p class="card-text">These kits allow you to learn about your ancestry through DNA analysis. Prices depend on the company and the level of detail offered..</p>
                <!-- Product Price -->
                <h6 class="card-subtitle mb-2 text-muted">Price: $59.00 to $200.00 [USD]</h6>
                <!-- Button to learn more -->
                <a href="#" class="btn btn-primary">Learn More</a>
            </div>
        </div>
    </div>    
    <!-- Repeat this structure for each product -->

    <!-- Footer -->
    <footer class="bg-dark text-light text-center py-3 mt-5">
        <div class="container">
            <p>&#169 Sri Harish B [212223220110] 2024 PharmaCo. All rights reserved.</p>
        </div>
    </footer>
</div>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>

</body>
</html>

```

#### contact.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PharmaCo - Contact</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
</head>
<body>

<div class="container">
    <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
        <a class="navbar-brand" href="#">PharmaCo</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent"
                aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                <li class="nav-item">
                    <a class="nav-link" href="project.html">Home</a>
                </li>
                <li class="nav-item dropdown active">
                    <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownAbout" role="button"
                       data-bs-toggle="dropdown" aria-expanded="false">
                        About
                    </a>
                    <ul class="dropdown-menu" aria-labelledby="navbarDropdownAbout">
                        <li><a class="dropdown-item" href="#vision">Vision</a></li>
                        <li><a class="dropdown-item" href="#mission">Mission</a></li>
                        <li><a class="dropdown-item" href="#values">Values</a></li>
                    </ul>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="product.html">Products</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="contact.html">Contact</a>
                </li>
            </ul>
        </div>
    </nav>

    <div style="width: 10%;">
        <img src="pharmaco_logo.png" style="width: 80%;" class="img-fluid">
    </div>

    <!-- Contact Section -->
    <div class="mt-5">
        <h1 class="text-danger display-3">Contact Us</h1>
        <div class="contact-details">
            <!-- Instagram Link -->
            <p>Instagram: <a href="https://www.instagram.com/your_instagram_username/">@sriharish.here</a></p>
            <!-- LinkedIn Link -->
            <p>LinkedIn: <a href="https://www.linkedin.com/in/your_linkedin_profile/">Sri Harish B</a></p>
            <!-- Phone Number -->
            <p>Phone Number: 9150851749</p>
            <!-- Address -->
            <p>Address: 44, srinivasa nagar, Thirumullaivoyal, Ambattur, Chennai-65</p>
        </div>
    </div>

    <!-- Footer -->
    <footer class="bg-dark text-light text-center py-3 mt-5">
        <div class="container">
            <p>&#169 Sri Harish B [212223220110] 2024 PharmaCo. All rights reserved.</p>
        </div>
    </footer>
</div>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>

</body>
</html>

```

## OUTPUT:

![alt text](<Screenshot 2024-05-11 213800.png>)

![alt text](<Screenshot 2024-05-11 213809.png>)

![alt text](<Screenshot 2024-05-11 213817.png>)
## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
