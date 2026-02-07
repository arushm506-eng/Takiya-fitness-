# Takiya-fitness-
30 days fitness challenge 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fitness Hub</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="#">Fitness Hub</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#home">Home</a></li>
                    <li class="nav-item"><a class="nav-link" href="#workouts">Workouts</a></li>
                    <li class="nav-item"><a class="nav-link" href="#nutrition">Nutrition</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <section id="home" class="hero bg-primary text-white text-center py-5">
        <div class="container">
            <h1>Welcome to Fitness Hub</h1>
            <p>Your journey to a healthier you starts here.</p>
            <a href="#workouts" class="btn btn-light btn-lg">Get Started</a>
        </div>
    </section>

    <section id="workouts" class="py-5">
        <div class="container">
            <h2 class="text-center mb-4">Workouts</h2>
            <div class="row">
                <div class="col-md-4">
                    <div class="card">
                        <img src="https://via.placeholder.com/300x200?text=Cardio" class="card-img-top" alt="Cardio">
                        <div class="card-body">
                            <h5 class="card-title">Cardio</h5>
                            <p class="card-text">Boost your heart health with running, cycling, and more.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card">
                        <img src="https://via.placeholder.com/300x200?text=Strength" class="card-img-top" alt="Strength">
                        <div class="card-body">
                            <h5 class="card-title">Strength Training</h5>
                            <p class="card-text">Build muscle with weights and resistance exercises.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card">
                        <img src="https://via.placeholder.com/300x200?text=Yoga" class="card-img-top" alt="Yoga">
                        <div class="card-body">
                            <h5 class="card-title">Yoga</h5>
                            <p class="card-text">Improve flexibility and mindfulness.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="nutrition" class="bg-light py-5">
        <div class="container">
            <h2 class="text-center mb-4">Nutrition</h2>
            <p class="text-center">Fuel your body with balanced meals. Check out these tips:</p>
            <ul class="list-group list-group-flush">
                <li class="list-group-item">Eat a variety of fruits and vegetables.</li>
                <li class="list-group-item">Incorporate lean proteins like chicken and fish.</li>
                <li class="list-group-item">Stay hydrated and limit processed foods.</li>
            </ul>
        </div>
    </section>

    <section id="contact" class="py-5">
        <div class="container">
            <h2 class="text-center mb-4">Contact Us</h2>
            <form id="contactForm">
                <div class="mb-3">
                    <label for="name" class="form-label">Name</label>
                    <input type="text" class="form-control" id="name" required>
                </div>
                <div class="mb-3">
                    <label for="email" class="form-label">Email</label>
                    <input type="email" class="form-control" id="email" required>
                </div>
                <div class="mb-3">
                    <label for="message" class="form-label">Message</label>
                    <textarea class="form-control" id="message" rows="3" required></textarea>
                </div>
                <button type="submit" class="btn btn-primary">Send</button>
            </form>
        </div>
    </section>

    <footer class="bg-dark text-white text-center py-3">
        <p>&copy; 2023 Fitness Hub. All rights reserved.</p>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
    <script src="script.js"></script>
</body>
</html>
