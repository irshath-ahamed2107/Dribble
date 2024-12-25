# Project Responsive Web Design using Bootstrap
## Date: 25/12/24

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


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
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Photography Portfolio</title>
    
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        .navbar-brand {
            font-weight: bold;
            font-size: 1.5rem;
        }
        .gallery img {
            width: 100%;
            height: auto;
            border-radius: 5px;
            transition: transform 0.3s ease-in-out;
        }
        .gallery img:hover {
            transform: scale(1.05);
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
        }
        .content-header {
            text-align: center;
            margin-top: 30px;
        }
    </style>
</head>
<body>
    
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="#">PhoneGallery</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#gallery">Gallery</a></li>
                    <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <header class="bg-light text-dark py-5">
        <div class="container text-center">
            <h1>WELCOME TO MY PHONE-PHOTOGRAPHY PORTFOLIO</h1>
            <p class="lead">Explore the beauty of the world through my lens of my phone's camera.</p>
        </div>
    </header>

    <section id="gallery" class="py-5">
        <div class="container">
            <h2 class="content-header">GALLERY</h2>
            <div class="row">
                <div class="col-lg-4 col-md-6 mb-4">
                    <img src="IMG_20240808_192810.jpg" alt="Photo 1" class="gallery img-fluid">
                </div>
                <div class="col-lg-4 col-md-6 mb-4">
                    <img src="IMG_20241012_113257.jpg" alt="Photo 2" class="gallery img-fluid">
                </div>
                <div class="col-lg-4 col-md-6 mb-4">
                    <img src="Snapchat-598353131.jpg" alt="Photo 3" class="gallery img-fluid">
                </div>
                <div class="col-lg-4 col-md-6 mb-4">
                    <img src="Snapchat-1367110144.jpg" alt="Photo 4" class="gallery img-fluid">
                </div>
                <div class="col-lg-4 col-md-6 mb-4">
                    <img src="Snapchat-1485056475.jpg" alt="Photo 5" class="gallery img-fluid">
                </div>
                <div class="col-lg-4 col-md-6 mb-4">
                    <img src="IMG_20241122_150903.jpg" alt="Photo 6" class="gallery img-fluid">
                </div>
            </div>
        </div>
    </section>
    <section id="about" class="bg-light py-5">
        <div class="container text-center">
            <h2>About Me</h2>
            <p>Hello! I'm Irshath, a passionate photographer who loves to capture the beauty of the world around us. Every picture tells a story, and I aim to share those stories with you.</p>
        </div>
    </section>
    <section id="contact" class="py-5">
        <div class="container text-center">
            <h2>Contact Me</h2>
            <p>If you'd like to work together or have any inquiries, feel free to reach out.</p>
            <a href="mailto:example@example.com" class="btn btn-primary">Send an Email</a>
        </div>
    </section>
    <footer>
        <p>Designed by Irshath Ahamed.N</p>
    </footer>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```

## OUTPUT: 
![alt text](<proj 10 output 1.png>)
![alt text](<proj 10 output 2.png>)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
