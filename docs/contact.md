<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact</title>
    <link rel="stylesheet" href="styles.css"> <!-- Lien vers votre fichier CSS -->
</head>
<body>
    <div class="container">
        <h1>Contactez-moi</h1>
        <form id="contact-form" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
            <div class="form-group">
                <label for="name">Nom</label>
                <input type="text" id="name" name="name" required>
            </div>
            <div class="form-group">
                <label for="email">Email</label>
                <input type="email" id="email" name="_replyto" required>
            </div>
            <div class="form-group">
                <label for="message">Message</label>
                <textarea id="message" name="message" rows="5" required></textarea>
            </div>
            <button type="submit">Envoyer</button>
        </form>
    </div>

    <!-- Optionnel : Script pour gérer le retour d'information après l'envoi -->
    <script>
        const form = document.getElementById('contact-form');
        form.addEventListener('submit', function(event) {
            event.preventDefault();
            alert("Votre message a été envoyé !");
            form.reset();
        });
    </script>
</body>
</html>
