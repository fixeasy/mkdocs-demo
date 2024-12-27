<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio DevOps</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* Conteneur principal */
        .intro-container {
            background-color: #f9f9f9;
            border: 1px solid #ddd;
            border-radius: 10px;
            padding: 20px;
            display: flex;
            align-items: center;
            gap: 20px;
            flex-wrap: wrap;
            justify-content: center;
        }

        .intro-container img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            max-width: 100%;
            height: auto;
        }

        .card {
            background-color: #ffffff;
            border: 1px solid #ddd;
            border-radius: 10px;
            padding: 20px;
            width: 120px;
            height: 120px;
            display: flex;
            align-items: center;
            justify-content: center;
            box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            margin-bottom: 20px;
        }

        .card:hover {
            transform: scale(1.1); /* Grossissement de 10% */
            box-shadow: 4px 4px 10px rgba(0, 0, 0, 0.3); /* Ombre plus marquée */
        }

        /* Flexbox pour la mise en page des icônes */
        .card-container {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
            margin-top: 30px;
        }

        .card-container a {
            text-decoration: none;
        }

        .card img {
            width: 60px;
            height: auto;
            max-width: 100%;
        }

        /* Liens utiles */
        .links {
            padding: 20px;
        }

        /* Media queries pour les petits écrans */
        @media (max-width: 768px) {
            .intro-container {
                flex-direction: column;
                align-items: center;
            }

            .card {
                width: 100px;
                height: 100px;
            }

            .card-container {
                gap: 15px;
            }
        }

        @media (max-width: 480px) {
            .card {
                width: 80px;
                height: 80px;
            }

            .intro-container img {
                width: 120px;
                height: 120px;
            }
        }
    </style>
</head>
<body>

    <h1>Bienvenue sur mon Portfolio DevOps</h1>

    <div class="intro-container">
        <img src="assets/pdp.jpg" alt="Photo de profil">
        <div>
            <p>Je suis <strong>Mehdi Kadar</strong>, un professionnel passionné par le DevOps, l'automatisation et l'optimisation des processus. Ce portfolio présente mes compétences, projets et articles.</p>
        </div>
    </div>

    <div class="card-container">
        <a href="skills/terraform.md">
            <div class="card">
                <img src="assets/terraform.png" alt="Terraform">
            </div>
        </a>
        <a href="skills/traefik.md">
            <div class="card">
                <img src="assets/traefik.webp" alt="Traefik">
            </div>
        </a>
        <a href="skills/ansible.md">
            <div class="card">
                <img src="assets/aws.png" alt="Ansible">
            </div>
        </a>
        <a href="skills/aws.md">
            <div class="card">
                <img src="assets/azure.png" alt="AWS">
            </div>
        </a>
    </div>

    <div class="links">
        <h2>Liens Utiles</h2>
        <ul>
            <li><a href="about">À propos de moi</a></li>
            <li><a href="skills">Mes compétences</a></li>
            <li><a href="projects/sncf/eul/project">Mes projets</a></li>
            <li><a href="cv">Mon CV</a></li>
            <li><a href="blog/thoughts-devops/">Articles de blog</a></li>
        </ul>
    </div>

</body>
</html>
