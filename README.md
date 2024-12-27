# Project Responsive Web Design using Bootstrap
## Date: 27.12.2024

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
    <title>Dribbble Clone</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
    <!-- Font Awesome (optional for icons) -->
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" rel="stylesheet">
    <style>
        /* Custom Styles for the Hero Section */
        .hero {
            background-color: #eb70a7;
            color: white;
            padding: 80px 0;
        }
        .hero h1 {
            font-size: 3rem;
        }
        .card-img-top {
            max-height: 200px;
            object-fit: cover;
        }
    </style>
</head>
<body>
    <!-- Navigation Bar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">Dribbble</a>   
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link active" aria-current="page" href="#">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Shots</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Explore</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Sign Up</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">LOGIN</a>
                    </li>
                    <form class="d-flex me-3" role="search">
                        <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
                        <button class="btn btn-outline-light" type="submit">Search</button>
                    </form>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="hero text-center">
        <div class="container">
            <h1>Welcome to Dribbble</h1>
            <p class="lead">Discover amazing design work and get inspired!</p>
            <a href="#" class="btn btn-light btn-lg">Explore Shots</a>
        </div>
    </section>

    <!-- Content Section: Featured Shots -->
    <section class="container py-5">
        <h2 class="text-center mb-4">Project Designs</h2>
        <hr><br>
        <div class="row row-cols-1 row-cols-md-3 g-4">
            <!-- Card 1 -->
            <div class="col">
                <div class="card">
                    <img src="mobile.jpg" class="card-img-top" alt="Shot 1">
                    <div class="card-body">
                        <h5 class="card-title">Mobile App Design</h5>
                        <p class="card-text">Showcase a modern, user-friendly mobile application design. This can be for various industries, such as e-commerce, fitness, or social media.
                        </p>
                    </div>
                </div>
            </div>
            <!-- Card 2 -->
            <div class="col">
                <div class="card">
                    <img src="potery.jpg" class="card-img-top" alt="Shot 2">
                    <div class="card-body">
                        <h5 class="card-title">Website Landing Page</h5>
                        <p class="card-text">Design a stunning landing page that grabs attention and encourages action, such as signing up or making a purchase.</p>
                    </div>
                </div>
            </div>
            <!-- Card 3 -->
            <div class="col">
                <div class="card">
                    <img src="logo.jpg" class="card-img-top" alt="Shot 3">
                    <div class="card-body">
                        <h5 class="card-title">Logo Design</h5>
                        <p class="card-text">Showcase a simple yet effective logo design that can be used for businesses, personal brands, or products.</p>
                    </div>
                </div>
            </div>
            <!-- Card 4 -->
            <div class="col">
                <div class="card">
                    <img src="projectfile.jpg" class="card-img-top" alt="Shot 4">
                    <div class="card-body">
                        <h5 class="card-title">E-commerce Product Page</h5>
                        <p class="card-text">Create an e-commerce product page with an intuitive design that improves user experience and drives conversions.</p>
                    </div>
                </div>
            </div>
            <!-- Card 5 -->
            <div class="col">
                <div class="card">
                    <img src="portfolio.jpg" class="card-img-top" alt="Shot 5">
                    <div class="card-body">
                        <h5 class="card-title"> Interactive Portfolio</h5>
                        <p class="card-text">Design a personal portfolio website to showcase design work and projects. Use a clean layout and easy navigation.</p>
                    </div>
                </div>
            </div>
            <!-- Card 6 -->
            <div class="col">
                <div class="card">
                    <img src="blog.jpg" class="card-img-top" alt="Shot 6">
                    <div class="card-body">
                        <h5 class="card-title">Blog Post Layout</h5>
                        <p class="card-text">Design a blog page for an online magazine or personal blog. Focus on a clean and readable layout.
                        </p>
                    </div>
                </div>
            </div>
            <!-- Card 7 -->
            <div class="col">
                <div class="card">
                    <img src="post.jpg" class="card-img-top" alt="Shot 7">
                    <div class="card-body">
                        <h5 class="card-title">Social Media Post Design</h5>
                        <p class="card-text">Create eye-catching social media graphics for platforms like Instagram, Facebook, or Twitter.</p>
                    </div>
                </div>
            </div>
            <!-- Card 8 -->
            <div class="col">
                <div class="card">
                    <img src="dashboard.jpg" class="card-img-top" alt="Shot 8">
                    <div class="card-body">
                        <h5 class="card-title">Dashboard Design</h5>
                        <p class="card-text">Design a dashboard interface for a SaaS or admin panel, focusing on usability and data visualization.</p>
                    </div>
                </div>
            </div>
            <!-- Card 9 -->
            <div class="col">
                <div class="card">
                    <img src="email.jpg" class="card-img-top" alt="Shot 9">
                    <div class="card-body">
                        <h5 class="card-title">Email Newsletter Template</h5>
                        <p class="card-text">Create a responsive email template for newsletters, highlighting updates, promotions, or company news.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer Section -->
    <footer class="bg-dark text-white text-center py-3">
        <p>&copy; 2024 | All rights reserved.</p>
        <p>Designed and Developed by MERIL GOLDLINA A (24007299)</p>
    </footer>

    <!-- Bootstrap JS and dependencies (optional for interactivity) -->
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.6/dist/umd/popper.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.min.js"></script>
</body>
</html>

```

## OUTPUT:
![Screenshot 2024-12-27 212258](https://github.com/user-attachments/assets/bd8e5e72-b096-4ffb-ac1e-8a95603d987a)


![Screenshot 2024-12-27 212542](https://github.com/user-attachments/assets/0f10f6a3-2edf-48cb-a41b-ab1fd24418d1)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
