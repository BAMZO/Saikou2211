<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio Informaticien</title>
    <style>
        :root {
            --primary-color: #3498db;
            --secondary-color: #2c3e50;
            --text-color: #333;
            --light-bg: #f5f5f5;
            --hover-color: #2980b9;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Arial', sans-serif;
        }
        
        body {
            color: var(--text-color);
            line-height: 1.6;
        }
        
        header {
            background-color: var(--secondary-color);
            color: white;
            padding: 2rem 0;
            text-align: center;
        }
        
        .profile-container {
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 1rem;
        }
        
        .profile-pic {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            border: 3px solid white;
            background-color: #ddd;
            display: flex;
            align-items: center;
            justify-content: center;
            margin-bottom: 1rem;
            overflow: hidden;
        }
        .profile-pic img {
    width: 100%;
    height: 100%;
    object-fit: cover;
}
        
        nav {
            background-color: var(--primary-color);
            padding: 1rem 0;
        }
        
        nav ul {
            display: flex;
            justify-content: center;
            list-style: none;
        }
        
        nav ul li {
            margin: 0 1rem;
        }
        
        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s ease;
        }
        
        nav ul li a:hover {
            color: var(--light-bg);
        }
        
        section {
            padding: 3rem 2rem;
        }
        
        section:nth-child(odd) {
            background-color: var(--light-bg);
        }
        
        .section-title {
            text-align: center;
            margin-bottom: 2rem;
            color: var(--secondary-color);
        }
        
        .skills-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 1rem;
        }
        
        .skill-item {
            background-color: white;
            padding: 1rem;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            width: calc(33.333% - 1rem);
            min-width: 250px;
            text-align: center;
        }
        
        .projects-container {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 2rem;
        }
        
        .project-card {
            background-color: white;
            border-radius: 5px;
            overflow: hidden;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            transition: transform 0.3s ease;
        }
        
        .project-card:hover {
            transform: translateY(-5px);
        }
        
        .project-img {
            width: 100%;
            height: 200px;
            background-color: #ddd;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        
        .project-info {
            padding: 1.5rem;
        }
        
        .experience-item {
            margin-bottom: 2rem;
            padding: 1.5rem;
            background-color: white;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        
        .experience-date {
            color: var(--primary-color);
            font-weight: bold;
        }
        
        .contact-container {
            max-width: 600px;
            margin: 0 auto;
        }
        
        .contact-form input,
        .contact-form textarea {
            width: 100%;
            padding: 0.8rem;
            margin-bottom: 1rem;
            border: 1px solid #ddd;
            border-radius: 4px;
        }
        
        .contact-form textarea {
            min-height: 150px;
        }
        
        .submit-btn {
            background-color: var(--primary-color);
            color: white;
            border: none;
            padding: 0.8rem 2rem;
            font-size: 1rem;
            border-radius: 4px;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }
        
        .submit-btn:hover {
            background-color: var(--hover-color);
        }
        
        footer {
            background-color: var(--secondary-color);
            color: white;
            text-align: center;
            padding: 2rem 0;
        }
        
        .social-links {
            margin-top: 1rem;
        }
        
        .social-links a {
            color: white;
            margin: 0 0.5rem;
            font-size: 1.2rem;
            text-decoration: none;
        }
        
        @media (max-width: 768px) {
            nav ul {
                flex-direction: column;
                align-items: center;
            }
            
            nav ul li {
                margin: 0.5rem 0;
            }
            
            .skill-item {
                width: 100%;
            }
            
            .projects-container {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="profile-container">
            <div class="profile-pic">
                <!-- Remplacer par votre photo -->
                    <img src="WhatsApp Image 2025-03-31 à 10.31.35_9f6882ab.jpg" alt="Votre nom">
            </div>
            <h1>Saîkou Ba</h1>
            <p>Génie en Informatique</p>
        </div>
    </header>
    
    <nav>
        <ul>
            <li><a href="#apropos">À propos</a></li>
            <li><a href="#competences">Compétences</a></li>
            <li><a href="#projets">Projets</a></li>
            <li><a href="#experience">Expérience</a></li>
            <li><a href="#formation">Formation</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    
    <section id="apropos">
        <h2 class="section-title">À propos de moi</h2>
        <div class="container">
            <p>Je suis un informaticien passionné par les nouvelles technologies et tous ce qui touche le domaine  l'informatique. Avec une bonne expérience dans le développement web et les systèmes d'information, je m'efforce de créer des solutions efficaces et innovantes.</p>
            <p>Mon objectif est de combiner créativité et expertise technique qui répondent parfaitement aux besoins des utilisateurs.</p>
        </div>
    </section>
    
    <section id="competences">
        <h2 class="section-title">Mes compétences</h2>
        <div class="skills-container">
            <div class="skill-item">
                <h3>Développement Front-end</h3>
                <p>HTML5, CSS3, JavaScript,</p>
            </div>
            <div class="skill-item">
                <h3>Développement Back-end</h3>
                <p>PHP, Python</p>
            </div>
            <div class="skill-item">
                <h3>Bases de données</h3>
                <p>MySQL</p>
            </div>
            <div class="skill-item">
                <h3>Infographie</h3>
                <p>Illustrator, Photoshop, Premiere pro</p>
            </div>
            <div class="skill-item">
                <h3>Réseau</h3>
                <p>Adressage, configuration, installation</p>
            </div>
            <div class="skill-item">
                <h3>burautique</h3>
                <p>Word,Excel </p>
            </div>
        </div>
    </section>
    
    <section id="projets">
        <h2 class="section-title">Mes projets</h2>
        <div class="projects-container">
            <div class="project-card">
                <div class="project-img">
                    <!-- Image du projet -->
                    <span>Image Projet 1</span>
                </div>
                <div class="project-info">
                    <h3>Projet 1</h3>
                    <p>Description du projet. Expliquez ici les technologies utilisées et le but du projet.</p>
                    <p><strong>Technologies:</strong> HTML, CSS, JavaScript</p>
                </div>
            </div>
            <div class="project-card">
                <div class="project-img">
                    <!-- Image du projet -->
                    <span>Image Projet 2</span>
                </div>
                <div class="project-info">
                    <h3>Projet 2</h3>
                    <p>Description du projet. Expliquez ici les technologies utilisées et le but du projet.</p>
                    <p><strong>Technologies:</strong> React, Node.js, MongoDB</p>
                </div>
            </div>
            <div class="project-card">
                <div class="project-img">
                    <!-- Image du projet -->
                    <span>Image Projet 3</span>
                </div>
                <div class="project-info">
                    <h3>Projet 3</h3>
                    <p>Description du projet. Expliquez ici les technologies utilisées et le but du projet.</p>
                    <p><strong>Technologies:</strong> Python, Django, PostgreSQL</p>
                </div>
            </div>
        </div>
    </section>
    
    <section id="experience">
        <h2 class="section-title">Expérience professionnelle</h2>
        <div class="container">
            <div class="experience-item">
                <h3>Développeur Full Stack</h3>
                <p class="experience-date">Janvier 2023 - Présent</p>
                <p><strong>Entreprise XYZ</strong></p>
                <ul>
                    <li>Développement et maintenance d'applications web</li>
                    <li>Collaboration avec les équipes de design et marketing</li>
                    <li>Optimisation des performances et de l'expérience utilisateur</li>
                </ul>
            </div>
            <div class="experience-item">
                <h3>Développeur Front-end</h3>
                <p class="experience-date">Mars 2021 - Décembre 2022</p>
                <p><strong>Agence Web ABC</strong></p>
                <ul>
                    <li>Création d'interfaces utilisateur réactives</li>
                    <li>Intégration de maquettes design</li>
                    <li>Amélioration des performances web</li>
                </ul>
            </div>
            <div class="experience-item">
                <h3>Stage en développement web</h3>
                <p class="experience-date">Septembre 2020 - Février 2021</p>
                <p><strong>Startup Tech</strong></p>
                <ul>
                    <li>Participation au développement d'une application mobile</li>
                    <li>Correction de bugs et amélioration de fonctionnalités existantes</li>
                    <li>Apprentissage des méthodes agiles</li>
                </ul>
            </div>
        </div>
    </section>
    
    <section id="formation">
        <h2 class="section-title">Formation</h2>
        <div class="container">
            <div class="experience-item">
                <h3>Master en Informatique</h3>
                <p class="experience-date">2018 - 2020</p>
                <p><strong>Université de Paris</strong></p>
                <p>Spécialisation en développement d'applications web et mobiles</p>
            </div>
            <div class="experience-item">
                <h3>Licence en Informatique</h3>
                <p class="experience-date">2015 - 2018</p>
                <p><strong>Université de Lyon</strong></p>
                <p>Formation générale en informatique et programmation</p>
            </div>
        </div>
    </section>
    
    <section id="contact">
        <h2 class="section-title">Me contacter</h2>
        <div class="contact-container">
            <form class="contact-form">
                <div>
                    <input type="text" placeholder="Nom" required>
                </div>
                <div>
                    <input type="email" placeholder="Email" required>
                </div>
                <div>
                    <input type="text" placeholder="Sujet">
                </div>
                <div>
                    <textarea placeholder="Message" required></textarea>
                </div>
                <button type="submit" class="submit-btn">Envoyer</button>
            </form>
        </div>
    </section>
    
    <footer>
        <div class="container">
            <p>&copy; 2025 - Portfolio de [Votre Nom]</p>
            <div class="social-links">
                <a href="#">LinkedIn</a>
                <a href="#">GitHub</a>
                <a href="#">Twitter</a>
                <a href="#">Email</a>
            </div>
        </div>
    </footer>

    <script>
        // Script pour gérer la navigation fluide
        document.querySelectorAll('nav a').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                
                const targetId = this.getAttribute('href');
                const targetElement = document.querySelector(targetId);
                
                window.scrollTo({
                    top: targetElement.offsetTop,
                    behavior: 'smooth'
                });
            });
        });
        
        // Script pour le formulaire de contact
        document.querySelector('.contact-form').addEventListener('submit', function(e) {
            e.preventDefault();
            alert('Message envoyé ! (Ceci est une simulation, ajoutez votre propre logique pour envoyer réellement le message)');
            this.reset();
        });
    </script>
</body>
</html>
