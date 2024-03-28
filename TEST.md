<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Page Interactive</title>
    <style>
        .container {
            text-align: center;
            margin-top: 100px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Bienvenue sur ma page interactive !</h1>
        <button id="btn">Cliquez ici</button>
        <p id="message"></p>
    </div>

    <script>
        // Sélectionnez le bouton
        const btn = document.getElementById('btn');

        // Ajoutez un gestionnaire d'événement de clic au bouton
        btn.addEventListener('click', () => {
            // Sélectionnez l'élément de message
            const message = document.getElementById('message');
            // Changez le texte du message
            message.textContent = 'Félicitations ! Vous avez cliqué sur le bouton.';
        });
    </script>
</body>
</html>
