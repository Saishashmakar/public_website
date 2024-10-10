                                <!DOCTYPE html>
                                <html lang="en">
                                <head>
                                    <meta charset="UTF-8">
                                    <meta name="viewport" content="width=device-width, initial-scale=1.0">
                                    <title>Vertex Overseas Consultancy</title>
                                    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/css/bootstrap.min.css" rel="stylesheet">
                                    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/swiper@10/swiper-bundle.min.css" />
                                    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.5/font/bootstrap-icons.css">
                                    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
                                    <style>
                                        body {
                                            font-family: 'Poppins', sans-serif;
                                            color: #333;
                                        }
                                        .navbar {
                                            background-color: #fff;
                                            box-shadow: 0 2px 4px rgba(0,0,0,.1);
                                        }
                                        .navbar-brand img {
                                            height: 40px;
                                        }
                                        .nav-link {
                                            color: #333;
                                            font-weight: 500;
                                        }
                                        .hero {
                                            background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url('https://i.postimg.cc/FzkpqK5C/web.png');
                                            background-size: cover;
                                            background-position: center;
                                            height: 80vh;
                                            display: flex;
                                            align-items: center;
                                            color: #fff;
                                        }
                                        .hero h1 {
                                            font-size: 3.5rem;
                                            font-weight: 700;
                                        }
                                        .btn-primary {
                                            background-color: #007bff;
                                            border: none;
                                        }
                                        .section-title {
                                            position: relative;
                                            display: inline-block;
                                            font-size: 2.5rem;
                                            font-weight: 700;
                                            margin-bottom: 2rem;
                                        }
                                        .section-title::after {
                                            content: '';
                                            position: absolute;
                                            left: 0;
                                            bottom: -10px;
                                            width: 50px;
                                            height: 3px;
                                            background-color: #007bff;
                                        }
                                        .card {
                                            border: none;
                                            box-shadow: 0 4px 8px rgba(0,0,0,.1);
                                            transition: transform 0.3s;
                                        }
                                        .card:hover {
                                            transform: translateY(-5px);
                                        }
                                        .testimonial {
                                            background-color: #f8f9fa;
                                        }
                                        .footer {
                                            background-color: #333;
                                            color: #fff;
                                        }
                                    </style>
                                </head>
                                <body>
                                    <nav class="navbar navbar-expand-lg sticky-top">
                                        <div class="container">
                                            <a class="navbar-brand" href="#"><img src="https://i.postimg.cc/8cwNVBDh/logo.jpg"
                                alt="Vertex Overseas Consultancy"></a>
                                            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                                                <span class="navbar-toggler-icon"></span>
                                            </button>
                                            <div class="collapse navbar-collapse" id="navbarNav">
                                                <ul class="navbar-nav ms-auto">
                                                    <li class="nav-item"><a class="nav-link" href="#home">Home</a></li>
                                                    <li class="nav-item"><a class="nav-link" href="#destinations">Destinations</a></li>
                                                    <li class="nav-item"><a class="nav-link" href="#services">Services</a></li>
                                                    <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
                                                    <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
                                                </ul>
                                            </div>
                                        </div>
                                    </nav>

                                    <section class="hero" id="home">
                                        <div class="container text-center">
                                            <h1>Your Gateway to Global Education</h1>
                                            <p class="lead">Empowering students to achieve their dreams of studying abroad since 2018</p>
                                            <a href="#contact" class="btn btn-primary btn-lg mt-3">Get Free Counselling</a>
                                        </div>
                                    </section>

                                    <section class="py-5" id="destinations">
                                        <div class="container">
                                            <h2 class="section-title text-center">Popular Destinations</h2>
                                            <div class="row g-4">
                                                <div class="col-md-4">
                                                    <div class="card">
                                                        <img src="https://i.postimg.cc/bJkyJX1d/uk.png" class="card-img-top" alt="Study in UK">
                                                        <div class="card-body">
                                                            <h5 class="card-title">Study in UK</h5>
                                                            <p class="card-text">Experience world-class education in the United Kingdom.</p>
                                                            <a href="#" class="btn btn-outline-primary">Learn More</a>
                                                        </div>
                                                    </div>
                                                </div>
                                                <div class="col-md-4">
                                                    <div class="card">
                                                        <img src="https://i.postimg.cc/9FnHtffF/USA.png" class="card-img-top" alt="Study in USA">
                                                        <div class="card-body">
                                                            <h5 class="card-title">Study in USA</h5>
                                                            <p class="card-text">Pursue your dreams in the land of opportunities.</p>
                                                            <a href="#" class="btn btn-outline-primary">Learn More</a>
                                                        </div>
                                                    </div>
                                                </div>
                                                <div class="col-md-4">
                                                    <div class="card">
                                                        <img src="https://i.postimg.cc/L5RM1F17/canada.png" class="card-img-top" alt="Study in Canada">
                                                        <div class="card-body">
                                                            <h5 class="card-title">Study in Canada</h5>
                                                            <p class="card-text">Discover excellence in engineering and technology.</p>
                                                            <a href="#" class="btn btn-outline-primary">Learn More</a>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                    </section>

                                    <section class="bg-light py-5" id="services">
                                        <div class="container">
                                            <h2 class="section-title text-center">Our Services</h2>
                                            <div class="row g-4">
                                                <div class="col-md-4">
                                                    <div class="card text-center">
                                                        <div class="card-body">
                                                            <i class="bi bi-chat-dots fs-1 text-primary mb-3"></i>
                                                            <h5 class="card-title">Free Counselling</h5>
                                                            <p class="card-text">Get expert advice on choosing the right course and university.</p>
                                                        </div>
                                                    </div>
                                                </div>
                                                <div class="col-md-4">
                                                    <div class="card text-center">
                                                        <div class="card-body">
                                                            <i class="bi bi-book fs-1 text-primary mb-3"></i>
                                                            <h5 class="card-title">Test Preparation</h5>
                                                            <p class="card-text">Comprehensive training for IELTS, TOEFL, GRE, and more.</p>
                                                        </div>
                                                    </div>
                                                </div>
                                                <div class="col-md-4">
                                                    <div class="card text-center">
                                                        <div class="card-body">
                                                            <i class="bi bi-file-earmark-text fs-1 text-primary mb-3"></i>
                                                            <h5 class="card-title">Visa Assistance</h5>
                                                            <p class="card-text">Expert guidance through the visa application process.</p>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                    </section>

                                    <section class="py-5" id="about">
                                        <div class="container">
                                            <div class="row align-items-center">
                                                <div class="col-lg-6">
                                                    <h2 class="section-title">About Vertex Overseas Consultancy</h2>
                                                    <p> Vertex Overseas Consultancy is a pioneering visa service provider offering a comprehensive range of immigration services. With over 17 years of experience, we've helped more than 15,000 students achieve their dreams of studying abroad.</p>
                                                    <ul class="list-unstyled">
                                                        <li><i class="bi bi-check-circle-fill text-primary me-2"></i>Expert career coaching</li>
                                                        <li><i class="bi bi-check-circle-fill text-primary me-2"></i>Personalized university selection</li>
                                                        <li><i class="bi bi-check-circle-fill text-primary me-2"></i>98% visa success rate</li>
                                                    </ul>
                                                </div>
                                                <div class="col-lg-6">
                                                    <img src="https://i.postimg.cc/8cwNVBDh/logo.jpg" alt="About Vertex Overseas Consultancy" class="img-fluid rounded">
                                                </div>
                                            </div>
                                        </div>
                                    </section>

                                    <section class="testimonial py-5" id="testimonials">
                                        <div class="container">
                                            <h2 class="section-title text-center">What Our Students Say</h2>
                                            <div class="swiper testimonialSwiper">
                                                <div class="swiper-wrapper">
                                                    <div class="swiper-slide">
                                                        <div class="card">
                                                            <div class="card-body">
                                                                <p class="card-text">"Vertex Overseas Consultancy made my dream of studying in the UK a reality. Their guidance was invaluable throughout the process."</p>
                                                                <footer class="blockquote-footer mt-2">Saishashmakar, University of Manchester</footer>
                                                            </div>
                                                        </div>
                                                    </div>
                                                    <div class="swiper-slide">
                                                        <div class="card">
                                                            <div class="card-body">
                                                                <p class="card-text">"The test preparation courses at Vertex Overseas helped me ace my IELTS exam. Highly recommended!"</p>
                                                                <footer class="blockquote-footer mt-2">Siva, University of Toronto</footer>
                                                            </div>
                                                        </div>
                                                    </div>
                                                </div>
                                                <div class="swiper-pagination"></div>
                                            </div>
                                        </div>
                                    </section>

                                    <section class="py-5" id="contact">
                                        <div class="container">
                                            <h2 class="section-title text-center">Contact Us</h2>
                                            <div class="row">
                                                <div class="col-lg-6">
                                                    <form>
                                                        <div class="mb-3">
                                                            <input type="text" class="form-control" placeholder="Your Name">
                                                        </div>
                                                        <div class="mb-3">
                                                            <input type="email" class="form-control" placeholder="Your Email">
                                                        </div>
                                                        <div class="mb-3">
                                                            <textarea class="form-control" rows="5" placeholder="Your Message"></textarea>
                                                        </div>
                                                        <button type="submit" class="btn btn-primary">Send Message</button>
                                                    </form>
                                                </div>
                                                <div class="col-lg-6">
                                                    <ul class="list-unstyled">
                                                        <li class="mb-3"><i class="bi bi-geo-alt-fill text-primary me-2"></i> H.No.2034, Near Hanuman Statue, Parimi, Thullur, Guntur - 522237</li>
                                                        <li class="mb-3"><i class="bi bi-telephone-fill text-primary me-2"></i> +91 8143256666</li>
                                                        <li class="mb-3"><i class="bi bi-envelope-fill text-primary me-2"></i> info@vertexoverseas.in</li>
                                                    </ul>
                                                </div>
                                            </div>
                                        </div>
                                    </section>

                                    <footer class="footer py-4">
                                        <div class="container">
                                            <div class="row">
                                                <div class="col-lg-4">
                                                    <img src="https://i.postimg.cc/8cwNVBDh/logo.jpg" alt="Vertex Overseas Consultancy" class="mb-3" style="height: 40px;">
                                                    <p>Your trusted partner in international education since 2018.</p>
                                                </div>
                                                <div class="col-lg-2">
                                                    <h5>Quick Links</h5>
                                                    <ul class="list-unstyled">
                                                        <li><a href="#home" class="text-white">Home</a></li>
                                                        <li><a href="#destinations" class="text-white">Destinations</a></li>
                                                        <li><a href="#services" class="text-white">Services</a></li>
                                                        <li><a href="#about" class="text-white">About</a></li>
                                                    </ul>
                                                </div>
                                                <div class="col-lg-3">
                                                    <h5>Popular Destinations</h5>
                                                    <ul class="list-unstyled">
                                                        <li><a href="#" class="text-white">Study in UK</a></li>
                                                        <li><a href="#" class="text-white">Study in USA</a></li>
                                                        <li><a href="#" class="text-white">Study in Canada</a></li>
                                                        <li><a href="#" class="text-white">Study in Australia</a></li>
                                                    </ul>
                                                </div>
                                                <div class="col-lg-3">
                                                    <h5>Follow Us</h5>
                                                    <div class="d-flex">
                                                        <a href="#" class="text-white me-3"><i class="bi bi-facebook"></i></a>
                                                        <a href="#" class="text-white me-3"><i class="bi bi-instagram"></i></a>
                                                        <a href="#" class="text-white me-3"><i class="bi bi-linkedin"></i></a>
                                                        <a href="#" class="text-white"><i class="bi bi-youtube"></i></a>
                                                    </div>
                                                </div>
                                            </div>
                                            <hr class="my-4">
                                            <div class="text-center">
                                                <p>&copy; 2024 Vertex Overseas Consultancy. All Rights Reserved.</p>
                                            </div>
                                        </div>
                                    </footer>

                                    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/js/bootstrap.bundle.min.js"></script>
                                    <script src="https://cdn.jsdelivr.net/npm/swiper@10/swiper-bundle.min.js"></script>
                                    <script>
                                        var swiper = new Swiper(".testimonialSwiper", {
                                            slidesPerView: 1,
