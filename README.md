# Project Responsive Web Design using Bootstrap
## Date:03.01.2025

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
<html>
<head>
    <meta charset="UTF-8">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand fw-bold text-danger" href="#">Dribbble</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav m-auto">
                    <li class="nav-item"><a class="nav-link text-white" href="#">Shots</a></li>
                    <li class="nav-item"><a class="nav-link text-white" href="#">Designers</a></li>
                    <li class="nav-item"><a class="nav-link text-white" href="#">Teams</a></li>
                    <li class="nav-item"><a class="nav-link text-white" href="#">Community</a></li>
                    <li class="nav-item"><a class="nav-link text-white" href="#">Jobs</a></li>
                </ul>
            </div>
            <a class="btn btn-outline-light m-2" href="#">Sign in</a>
            <a class="btn btn-outline-light m-2" href="#">Sign Up</a>
            <input type="search" class="form-control w-auto" placeholder="Search" style="margin: 20px;">
        </div>
    </nav>

    <section id="home" class="bg-white py-5"  style="height: 45vh;" >
        <div class="container">
            <div class="row align-items-center">
                <div class="col-md-6 text-center text-md-middle">
                    <h1 class="display-4 fw-bold">What are you working on?</h1>
                    <button class="btn btn-secondary m-2">Learn More</button>
                    <button class="btn btn-primary">Sign up</button>
                </div>
               
            </div>
        </div>
    </section>

    <section class="py-5">
        <div class="container">
            <div class="row mb-4">
                <div class="col-md-4">
                    <h2 class="fw-bold">Popular</h2>
                </div>
                <div>
            </div>
            <div class="row g-4">
                <div class="col-md-3 col-sm-6">
                    <div class="card shot-card">
                        <img src="cider.jpg" width="300" height="220" alt="jean">
                      
                        <div class="card-body text-center">
                            <p class="card-text mb-0">🔗 Corquette</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="card shot-card">
                        <img src="fluid.jpg" width="300" height="220" alt="fluid">
                        
                        <div class="card-body text-center">
                            <p class="card-text mb-0">🔗 Fluid Gradient</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="card shot-card">
                        <img src="lumni.jpg" width="300" height="220" alt="lumniscence">
                        <div class="card-body text-center">
                            <p class="card-text mb-0">🔗Lumniscence</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="card shot-card">
                        <img src="kapoor.jpg" class="card-img-top" alt="Kapoor" width="300" height="220">
                       
                        <div class="card-body text-center">
                            <p class="card-text mb-0">🔗 Kapoor Sisters</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="card shot-card">
                        <img src="mark.jpg" class="card-img-top" alt="mark" width="300" height="220">
                        <div class="card-body text-center">
                            <p class="card-text mb-0">🔗 Mark Kim</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="card shot-card">
                        <img src="slomo.jpg" width="300" height="220" alt="slomo">
                        <div class="card-body text-center">
                            <p class="card-text mb-0">🔗 Van Huntert</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="card shot-card">
                        <img src="paper.jpg"width="300" height="220" alt="paper">
                        <div class="card-body text-center">
                            <p class="card-text mb-0">🔗 Atlanta</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-3 col-sm-6">
                    <div class="card shot-card">
                        <img src="shadow.jpg" class="card-img-top" alt="shadow" width="300" height="220">
                        <div class="card-body text-center">
                            <p class="card-text mb-0">🔗 Rene</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-dark text-white py-3">
        <div class="container text-center">
            <p class="mb-0">Designed and developed by Indhu Priya.T</p>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

```

## OUTPUT:

![alt text](<cloneweb/cloneapp/static/Screenshot (76).png>)

![alt text](<cloneweb/cloneapp/static/Screenshot (77).png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
