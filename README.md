<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Biodiversity Update by Ancestors Holding</title>
    <style>
        :root {
            --green-main: #2E7D32;
            --green-light: #4CAF50;
            --yellow-accent: #FFD600;
            --white: #FFFFFF;
            --gray-light: #F5F5F5;
            --gray-dark: #212121;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background-color: var(--white);
            color: var(--gray-dark);
            line-height: 1.6;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        /* Corporate Header */
        .corporate-header {
            background: linear-gradient(135deg, var(--green-main), #1B5E20);
            color: var(--white);
            padding: 2rem 0;
            text-align: center;
            border-bottom: 5px solid var(--yellow-accent);
        }
        
        .company-name {
            font-size: 2.5rem;
            font-weight: 700;
            letter-spacing: 1px;
            margin-bottom: 0.5rem;
        }
        
        .division {
            font-size: 1.3rem;
            opacity: 0.9;
            font-weight: 300;
            margin-bottom: 1.5rem;
        }
        
        .project-title {
            margin-top: 1.5rem;
        }
        
        .project-title h1 {
            font-size: 2.8rem;
            margin-bottom: 0.5rem;
        }
        
        .project-tagline {
            font-size: 1.2rem;
            max-width: 800px;
            margin: 0 auto;
            opacity: 0.95;
        }
        
        /* Navigation */
        nav {
            background-color: var(--green-main);
            padding: 1rem 0;
            position: sticky;
            top: 0;
            z-index: 100;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }
        
        .nav-container {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 1.5rem;
        }
        
        nav a {
            color: var(--white);
            text-decoration: none;
            font-weight: 500;
            padding: 0.5rem 1.2rem;
            border-radius: 4px;
            transition: all 0.3s;
        }
        
        nav a:hover {
            background-color: var(--green-light);
            transform: translateY(-2px);
        }
        
        /* Sections */
        section {
            padding: 4rem 0;
        }
        
        section:nth-child(even) {
            background-color: var(--gray-light);
        }
        
        h2 {
            color: var(--green-main);
            font-size: 2.2rem;
            margin-bottom: 2rem;
            padding-bottom: 0.5rem;
            border-bottom: 3px solid var(--yellow-accent);
        }
        
        /* Cards */
        .card-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            margin-top: 2rem;
        }
        
        .card {
            background: var(--white);
            border-radius: 10px;
            padding: 2rem;
            box-shadow: 0 4px 15px rgba(0,0,0,0.08);
            transition: transform 0.3s;
        }
        
        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 6px 20px rgba(0,0,0,0.12);
        }
        
        .card h3 {
            color: var(--green-main);
            margin-bottom: 1rem;
            font-size: 1.4rem;
        }
        
        /* Team */
        .team-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
        }
        
        .team-member {
            text-align: center;
            padding: 1.5rem;
        }
        
        .member-icon {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            background: var(--green-light);
            margin: 0 auto 1rem;
            display: flex;
            align-items: center;
            justify-content: center;
            color: var(--white);
            font-size: 3rem;
            border: 4px solid var(--yellow-accent);
        }
        
        /* Contact */
        .contact-info {
            margin-top: 2rem;
        }
        
        .contact-item {
            display: flex;
            align-items: center;
            gap: 1rem;
            margin-bottom: 1rem;
            font-size: 1.1rem;
        }
        
        .contact-icon {
            font-size: 1.5rem;
            color: var(--green-main);
        }
        
        /* Footer */
        footer {
            background-color: var(--gray-dark);
            color: var(--white);
            padding: 3rem 0;
            text-align: center;
        }
        
        .footer-logo {
            font-size: 1.8rem;
            font-weight: 700;
            margin-bottom: 1rem;
        }
        
        /* Responsive */
        @media (max-width: 768px) {
            .company-name {
                font-size: 2rem;
            }
            
            .project-title h1 {
                font-size: 2rem;
            }
            
            .nav-container {
                flex-direction: column;
                align-items: center;
                gap: 0.5rem;
            }
            
            section {
                padding: 2rem 0;
            }
        }
    </style>
</head>
<body>
    <!-- Corporate Header -->
    <header class="corporate-header">
        <div class="container">
            <div class="company-name">ANCESTORS HOLDING</div>
            <div class="division">LIVINGBYNATURE</div>
            
            <div class="project-title">
                <h1>Biodiversity Update</h1>
                <p class="project-tagline">Smart and green business for circular economy about common good, anywhere and everywhere</p>
            </div>
        </div>
    </header>

    <!-- Navigation -->
    <nav>
        <div class="container nav-container">
            <a href="#about">About</a>
            <a href="#objectives">Objectives</a>
            <a href="#methodology">Methodology</a>
            <a href="#team">Team</a>
            <a href="#contact">Contact</a>
        </div>
    </nav>

    <!-- About Section -->
    <section id="about">
        <div class="container">
            <h2>About the Project</h2>
            <p>Biodiversity Update is a LivingByNature initiative by Ancestors Holding, dedicated to developing smart green business solutions for circular economy. Our mission is to create sustainable impact for the common good, with scalable models deployable worldwide.</p>
            <p><strong>Project Duration:</strong> 24 months | <strong>Estimated Budget:</strong> €250,000</p>
        </div>
    </section>

    <!-- Objectives Section -->
    <section id="objectives">
        <div class="container">
            <h2>Core Objectives</h2>
            <div class="card-grid">
                <div class="card">
                    <h3>🌱 Sustainable Innovation</h3>
                    <p>Develop cutting-edge green technologies that reduce environmental impact while creating economic value.</p>
                </div>
                <div class="card">
                    <h3>♻️ Circular Economy</h3>
                    <p>Implement circular business models that minimize waste and maximize resource efficiency across value chains.</p>
                </div>
                <div class="card">
                    <h3>🌍 Global Scalability</h3>
                    <p>Create solutions designed for deployment anywhere and everywhere, adaptable to diverse ecosystems and communities.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Methodology Section -->
    <section id="methodology">
        <div class="container">
            <h2>Our Methodology</h2>
            <p>We combine scientific research, technological innovation, and community engagement through a three-phase approach:</p>
            <div class="card-grid">
                <div class="card">
                    <h3>Research & Design</h3>
                    <p>Comprehensive ecosystem analysis and solution design based on local biodiversity data.</p>
                </div>
                <div class="card">
                    <h3>Pilot Implementation</h3>
                    <p>Controlled deployment and testing of circular economy models in diverse environments.</p>
                </div>
                <div class="card">
                    <h3>Scale & Replicate</h3>
                    <p>Global scaling of proven solutions through partnerships and technology transfer.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Team Section -->
    <section id="team">
        <div class="container">
            <h2>Our Team</h2>
            <div class="team-grid">
                <div class="team-member">
                    <div class="member-icon">👩‍🔬</div>
                    <h3>Dr. Sarah Johnson</h3>
                    <p>Lead Environmental Scientist<br>PhD in Ecology, 15+ years experience</p>
                </div>
                <div class="team-member">
                    <div class="member-icon">👨‍💻</div>
                    <h3>Michael Chen</h3>
                    <p>Circular Economy Specialist<br>Technology & Business Development</p>
                </div>
                <div class="team-member">
                    <div class="member-icon">👩‍🏫</div>
                    <h3>Dr. Elena Rodriguez</h3>
                    <p>Sustainability Policy Advisor<br>International Development Expert</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <div class="container">
            <h2>Contact Us</h2>
            <p>For partnership opportunities or more information about Biodiversity Update:</p>
            <div class="contact-info">
                <div class="contact-item">
                    <span class="contact-icon">📧</span>
                    <span>contact@ancestorsholding.com</span>
                </div>
                <div class="contact-item">
                    <span class="contact-icon">🌐</span>
                    <span>www.ancestorsholding.com</span>
                </div>
                <div class="contact-item">
                    <span class="contact-icon">📍</span>
                    <span>Global Headquarters: Paris, France | Regional hubs worldwide</span>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <div class="footer-logo">ANCESTORS HOLDING</div>
            <p style="opacity: 0.9; margin-bottom: 1rem;">LIVINGBYNATURE Division</p>
            <p>© 2024 Biodiversity Update Project. All rights reserved.</p>
            <p style="margin-top: 1rem; font-size: 0.9rem; opacity: 0.8;">This platform demonstrates our commitment to green circular economy solutions for the common good.</p>
        </div>
    </footer>

    <script>
        // Smooth scrolling
        document.querySelectorAll('nav a').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                const targetId = this.getAttribute('href');
                const targetElement = document.querySelector(targetId);
                window.scrollTo({
                    top: targetElement.offsetTop - 80,
                    behavior: 'smooth'
                });
            });
        });
        
        // Add animation on scroll
        const observerOptions = {
            threshold: 0.1
        };
        
        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.style.opacity = "1";
                    entry.target.style.transform = "translateY(0)";
                }
            });
        }, observerOptions);
        
        // Observe cards for animation
        document.querySelectorAll('.card').forEach(card => {
            card.style.opacity = "0";
            card.style.transform = "translateY(20px)";
            card.style.transition = "opacity 0.5s ease, transform 0.5s ease";
            observer.observe(card);
        });
    </script>
</body>
</html>
