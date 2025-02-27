<!DOCTYPE html>
<html lang="en">
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta charset="UTF-8">
    <title>My Custom Landing Page</title>
    <meta name="description" content="Contact us for any business inquiries">
    
    <link rel="icon" type="image/png" href="img/my_logo.png">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" type="text/css" href="css/custom-style.css">
</head>
<body>
    <!-- Preloader -->
    
    
    
            <button class="btn btn-lg btn-light mt-3" onclick="document.getElementById('contact_section').scrollIntoView({ behavior: 'smooth' });">Amine</button>
        
    
    <section id="contact_section" class="container py-5">
        <h2 class="text-center mb-4">Contact Us</h2>
        <form id="contact_form" class="row g-3">
            <div class="col-md-6">
                <label for="name" class="form-label">Name</label>
                <input type="text" class="form-control" id="name" required>
            </div>
            <div class="col-md-6">
                <label for="email" class="form-label">Email</label>
                <input type="email" class="form-control" id="email" required>
            </div>
            <div class="col-12">
                <label for="message" class="form-label">Message</label>
                <textarea class="form-control" id="message" rows="3" required></textarea>
            </div>
            <div class="col-12">
                <button type="submit" class="btn btn-primary">Send</button>
            </div>
        </form>
    </section>
    <footer>
        <centre>&copy; 2025 My Custom Landing Page</centre>
    </footer>
    
    <script>
        document.addEventListener("DOMContentLoaded", function() {
            document.getElementById("preloader").style.display = "none";
        });
    </script>
</body>
</html>
