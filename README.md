<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>🔐 LOGIN PAGE COLLECTION - Disha Computer Institute</title>
    
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
    
    <!-- Font Awesome -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@700&family=Roboto:wght@400;500&display=swap" rel="stylesheet">
    
    <!-- Custom Styles -->
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            background-color: #f8f9fa; /* Light background for a modern look */
            color: #333;
            margin: 0;
            padding: 0;
        }
        
        .header-title {
            font-family: 'Poppins', sans-serif;
            font-size: 2.5rem;
            background: linear-gradient(45deg, #007BFF, #28a745);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.1);
            margin-top: 20px;
            padding: 10px;
            border-radius: 10px;
            text-align: center;
        }
        
        .subheader {
            font-family: 'Roboto', sans-serif;
            font-size: 1.2rem;
            color: #333;
            margin: 10px 0;
            text-align: center;
            transition: color 0.3s ease;
        }
        
        .subheader:hover {
            color: #007BFF;
        }
        
        .animated-header {
            animation: fadeInDown 1s ease-in-out;
        }
        
        @keyframes fadeInDown {
            from {
                opacity: 0;
                transform: translateY(-20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
        
        section {
            margin: 40px 0;
        }
        
        .hover-effect {
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        
        .hover-effect:hover {
            transform: scale(1.05);
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
        }
    </style>
</head>
<body>

    <!-- Header Section -->
    <h1 class="header-title animated-header">🔐 LOGIN PAGE COLLECTION</h1>
    <p class="subheader">10 Unique, Modern & Animated Login Page Designs<br>Created by <b>Disha Computer Institute, Jaysingpur</b></p>
    
    <!-- About Section -->
    <section id="about" class="container my-5">
        <div class="card text-center p-4 shadow-lg" style="background: linear-gradient(135deg, #f0f8ff, #e6f7ff); border-radius: 15px;">
            <div class="card-body">
                <h2 class="card-title" style="color: #007BFF;">💻 About This Project</h2>
                <p class="card-text">This repository contains <b>10 different Login Page designs</b>, all written in a <b>single HTML file</b> with integrated <b>CSS, JavaScript, and Bootstrap</b>.  
                Each design is fully responsive, includes 2D/3D animation effects, and is ideal for use in: <br>
                - Institute websites <br>
                - Student projects <br>
                - Demo exams & admin panels
                </p>
            </div>
        </div>
    </section>
    
    <!-- Features Section -->
    <section id="features" class="container my-5">
        <h2 class="text-center mb-4" style="color: #28a745;">🧩 Features</h2>
        <div class="row">
            <div class="col-md-4 mb-3">
                <div class="card h-100 shadow-sm hover-effect">
                    <div class="card-body text-center">
                        <i class="fas fa-palette fa-2x mb-2" style="color: #007BFF;"></i>
                        <h5>🌈 Responsive and mobile-friendly design</h5>
                    </div>
                </div>
            </div>
            <div class="col-md-4 mb-3">
                <div class="card h-100 shadow-sm hover-effect">
                    <div class="card-body text-center">
                        <i class="fas fa-film fa-2x mb-2" style="color: #28a745;"></i>
                        <h5>🎨 2D & 3D animation effects</h5>
                    </div>
                </div>
            </div>
            <div class="col-md-4 mb-3">
                <div class="card h-100 shadow-sm hover-effect">
                    <div class="card-body text-center">
                        <i class="fas fa-code fa-2x mb-2" style="color: #007BFF;"></i>
                        <h5>⚡ Built with HTML, CSS, JavaScript & Bootstrap</h5>
                    </div>
                </div>
            </div>
            <div class="col-md-4 mb-3">
                <div class="card h-100 shadow-sm hover-effect">
                    <div class="card-body text-center">
                        <i class="fas fa-save fa-2x mb-2" style="color: #28a745;"></i>
                        <h5>💾 All-in-one file (easy to modify)</h5>
                    </div>
                </div>
            </div>
            <div class="col-md-4 mb-3">
                <div class="card h-100 shadow-sm hover-effect">
                    <div class="card-body text-center">
                        <i class="fas fa-lightbulb fa-2x mb-2" style="color: #007BFF;"></i>
                        <h5>💡 Perfect for beginners and developers</h5>
                    </div>
                </div>
            </div>
        </div>
    </section>
    
    <!-- Technologies Section -->
    <section id="technologies" class="container my-5 text-center">
        <h2 class="mb-4" style="color: #007BFF;">🛠️ Technologies Used</h2>
        <div class="row justify-content-center">
            <div class="col-auto mb-2"><span class="badge bg-primary"><i class="fab fa-html5"></i> HTML5</span></div>
            <div class="col-auto mb-2"><span class="badge bg-primary"><i class="fab fa-css3-alt"></i> CSS3</span></div>
            <div class="col-auto mb-2"><span class="badge bg-primary"><i class="fab fa-js"></i> JavaScript</span></div>
            <div class="col-auto mb-2"><span class="badge bg-primary"><i class="fab fa-bootstrap"></i> Bootstrap 5</span></div>
            <div class="col-auto mb-2"><span class="badge bg-primary"><i class="fas fa-font"></i> Google Fonts</span></div>
            <div class="col-auto mb-2"><span class="badge bg-primary"><i class="fas fa-icons"></i> Font Awesome</span></div>
        </div>
    </section>
    
    <!-- Demo Section -->
    <section id="demo" class="container my-5">
        <h2 class="text-center" style="color: #28a745;">🌐 Demo Preview</h2>
        <p class="text-center">You can preview each login design by scrolling through the sections below.</p>
        
        <!-- Placeholder for Login Designs -->
        <div class="row">
            <div class="col-md-12">
                <div class="card p-4 shadow-sm">
                    <h3>Login Design 1 (Placeholder)</h3>
                    <p>This is a sample login page. Replace this with your actual HTML code for the animated login form.</p>
                    <!-- Example: Add your login form HTML here -->
                    <div style="border: 1px solid #ddd; padding: 20px; border-radius: 10px;">
                        <h4>Sample Login Form</h4>
                        <form>
                            <input type="email" placeholder="Email" class="form-control mb-2">
                            <input type="password" placeholder="Password" class="form-control mb-2">
                            <button type="submit" class="btn btn-primary">Login</button>
                        </form>
                    </div>
                </div>
            </div>
            <!-- Add more cards or sections for the other 9 designs -->
        </div>
    </section>
    
    <!-- Footer Section -->
    <footer class="bg-dark text-white text-center py-3 mt-5">
        <p>✨ "Learn. Code. Create. Grow with Disha Computer Institute." ✨</p>
        <p>Created By: Disha Computer Institute, Jaysingpur<br>
            Email: <a href="mailto:dishajaysingpur2949@gmail.com" style="color: #28a745;">dishajaysingpur2949@gmail.com</a><br>
            Website: <a href="https://website.dishagroup.in/b/444" style="color: #28a745;">https://website.dishagroup.in/b/444</a>
        </p>
    </footer>
    
    <!-- Scroll to Top Button -->
    <button id="scrollTop" class="btn btn-primary btn-floating btn-lg" style="position: fixed; bottom: 20px; right: 20px; display: none;"><i class="fas fa-arrow-up"></i></button>
    
    <!-- JavaScript -->
    <script>
        window.onscroll = function() {scrollFunction()};
        function scrollFunction() {
            if (document.body.scrollTop > 20 || document.documentElement.scrollTop > 20) {
                document.getElementById("scrollTop").style.display = "block";
            } else {
                document.getElementById("scrollTop").style.display = "none";
            }
        }
        document.getElementById("scrollTop").onclick = function() {
            window.scrollTo({top: 0, behavior: 'smooth'});
        };
    </script>
    
</body>
</html>
