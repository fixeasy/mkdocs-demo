<style>
    /* Section de présentation */
    .about-me {
        padding: 40px 20px;
        background-color: #f8f9fa;
        text-align: center;
        margin-bottom: 40px;
        border-radius: 12px;
        box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
        animation: slideIn 1.5s ease-out;
    }

    /* Animation pour la présentation */
    @keyframes slideIn {
        0% {
            transform: translateY(50px);
            opacity: 0;
        }
        100% {
            transform: translateY(0);
            opacity: 1;
        }
    }

    .about-me h2 {
        font-size: 32px;
        color: #333;
        margin-bottom: 15px;
        animation: fadeIn 1.2s ease-in;
    }

    .about-me p {
        font-size: 18px;
        color: #666;
        line-height: 1.6;
        margin-bottom: 20px;
        animation: fadeIn 1.4s ease-in;
    }

    .about-me ul {
        list-style-type: none;
        padding: 0;
        display: flex;
        justify-content: center;
        gap: 30px;
    }

    .about-me ul li {
        display: flex;
        align-items: center;
        justify-content: center;
        font-size: 18px;
        color: #333;
    }

    .about-me ul li i {
        font-size: 20px;
        margin-right: 10px;
    }

    /* Logos des entreprises */
    .company-logos {
        display: flex;
        justify-content: center;
        gap: 40px;
        margin-top: 20px;
        animation: fadeIn 1.5s ease-in;
    }

    .company-logos .logo-card {
        width: 160px;
        height: 160px;
        background-color: #ffffff;
        border-radius: 20px;
        box-shadow: 0 6px 15px rgba(0, 0, 0, 0.2);
        overflow: hidden;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        transition: transform 0.4s ease, box-shadow 0.4s ease;
        position: relative;
    }

    .company-logos .logo-card:hover {
        transform: translateY(-10px);
        box-shadow: 0 10px 20px rgba(0, 0, 0, 0.3);
    }

    .company-logos .logo-card img {
        width: 80px;
        height: auto;
        margin-bottom: 10px;
        transition: transform 0.4s ease;
    }

    .company-logos .logo-card:hover img {
        transform: scale(1.1);
    }

    .company-logos .logo-card h3 {
        font-size: 16px;
        font-weight: 600;
        color: #333;
        margin-top: 10px;
        text-align: center;
    }

    /* Animation fadeIn */
    @keyframes fadeIn {
        0% {
            opacity: 0;
        }
        100% {
            opacity: 1;
        }
    }
</style>

<style>
    .image-container {
        position: relative;
        width: 300px;
        height: 300px;
        margin: 0 auto 20px;
        border-radius: 50%;
        box-shadow: 0 8px 20px rgba(0, 0, 0, 0.15), inset 0 0 0 3px rgba(255, 255, 255, 0.7);
        overflow: hidden;
        background: linear-gradient(145deg, #f0f0f0, #d6d6d6);
        display: flex;
        align-items: center;
        justify-content: center;
    }

    .image-container img {
        width: 110%;
        height: 110%;
        object-fit: cover;
        border-radius: 50%;
        transition: transform 0.5s ease, box-shadow 0.5s ease;
    }

    .image-container:hover img {
        transform: scale(1.05); /* Zoom léger */
        box-shadow: 0 10px 25px rgba(0, 0, 0, 0.2); /* Ombre plus marquée */
    }
</style>

<div class="about-me">
    <div class="image-container">
        <img src="https://media.licdn.com/dms/image/v2/D4E03AQHGmvRp4xdyXg/profile-displayphoto-shrink_400_400/profile-displayphoto-shrink_400_400/0/1720705478336?e=1740614400&v=beta&t=KB2-Op_En75wNMhpaNo6wVzYql29qA1adthjtqM2Br8" alt="Photo de profil">
    </div>
    <h2>À propos de moi</h2>
    <p>Je suis <strong>Mehdi Kadar</strong>, ingénieur DevOps avec plus de 5 ans d'expérience dans le domaine. Passionné par l'automatisation, l'optimisation des processus et l'amélioration continue, j'ai eu l'opportunité de travailler sur des projets complexes et stimulants pour plusieurs entreprises de renom.</p>
    <p>Au cours de mon parcours, j'ai eu le privilège de collaborer avec des équipes talentueuses dans des environnements variés, où j'ai mis en place des solutions robustes et évolutives pour répondre aux besoins d'infrastructure et de déploiement. Mon expertise couvre des technologies comme Kubernetes, Terraform, Jenkins, Docker, et bien d'autres encore.</p>
    
    <p>Voici quelques-unes des entreprises avec lesquelles j'ai travaillé :</p>

    <!-- Logos des entreprises -->
    <div class="company-logos">
        <!-- SNCF -->
        <div class="logo-card">
            <!-- <img src="https://www.presse-citron.net/app/uploads/2023/05/sncf-ter-train.jpg" alt="SNCF"> -->
            <h3>SNCF</h3>
        </div>
        <!-- Enedis -->
        <div class="logo-card">
            <!-- <img src="https://upload.wikimedia.org/wikipedia/commons/3/34/Logo_Enedis_2016.svg" alt="Enedis"> -->
            <h3>Enedis</h3>
        </div>
        <!-- Alstom -->
        <div class="logo-card">
            <!-- <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d5/Alstom.svg/512px-Alstom.svg.png" alt="Alstom"> -->
            <h3>Alstom</h3>
        </div>
    </div>

    <p>Mon objectif est d'apporter des solutions fiables et évolutives, tout en maintenant une culture de collaboration et d'innovation pour assurer la réussite des projets sur lesquels je travaille.</p>
</div>
