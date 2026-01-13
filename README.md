# Igor-CIAN.github.io
Site pédagogique sur l'IA pour les élèves de 3ème

<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>L'IA Expliquée - Projet 3ème</title>

    <link rel="icon" type="image/png" href="favicon/logo_IA.png">

    <link rel="stylesheet" href="CSS/main.css">
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;700&display=swap" rel="stylesheet">
    <link href="https://fonts.google.com/share?selection.family=JetBrains+Mono:ital,wght@0,100..800;1,100..800|Montserrat:ital,wght@0,100..900;1,100..900|Roboto:ital,wght@0,100..900;1,100..900" rel="stylesheet">
</head>


<!-- Corp du Site -->
<body>
    <!-- HEADER (MENU) -->
    <header>
        <nav class="custom-container">
            <div class="logo">IA & Futur</div>

            <button type="button" class="btn-burger btn-toggle" id="burger-button">
                &#9776
            </button>

            <ul class="menu">
                <li><a href="#definition">C'est quoi ?</a></li>
                <li><a href="#section-types">Diférent type d'IA</a></li>
                <li><a href="#exemples">Utilisations</a></li>
                <li><a href="#futur">Le Futur</a></li>
                <li><a href="cas-concret.html">Un Cas Concret!</a></li>
            </ul>
        </nav>
    </header>

    <!-- SECTION HERO (PHOTO+TITRE) -->
    <section class="hero">
        <div class="hero-content">
            <h1 class="premier-titre">
                L'Intelligence<br/>Artificielle
            </h1>
            <p>
                Comprendre la technologie qui change notre monde.
            </p>
            <a href="#definition" class="btn">Découvrir</a>
        </div>
    </section>

    <!-- SECTION DEFINITION D'UNE IA -->

    <section id="presentation" class ="custom-container">
        <h2>Présentation</h2>
        <div class="content-block">
            <p>
                Bonjour à toi! Tu as peut-être entendu parler de l'<strong>IA</strong> autour de toi mais tu n'arrives pas à comprendre son utilité ou même comment s'en servir.
                Ça tombe bien, ce site est là pour t'expliquer tout en détail!!
            </p>
        </div>

        <div class="custom-container photo-pres">
            <div class="photo1"></div>
            <div class="photo2"></div>
            <div class="photo3"></div>
        </div>
    </section>
    

    <section id="definition" class="background-def">
        <h2>C'est quoi l'IA ?</h2>
        <div class="custom-container content-block">
            <p>
                Imagine un ordinateur capable d'apprendre comme un être humain. L'IA, c'est un ensemble de techniques qui permettent aux machines d'imiter l'intelligence humaine : reconnaître des images, comprendre le langage ou résoudre des problèmes complexes.
            </p>
            <p>
                Contrairement à un programme classique où l'humain écrit chaque règle (via un code), l'IA utilise souvent le <strong>Machine Learning</strong> : Elle s'entraîne sur des milliers d'exemples pour s'améliorer toute seule avec l'aide de bases de données créer par l'Homme et, pour certaine, l'ensemble d'internet.
            </p>
        </div>

        <div class="photo-def">
            <img src="images/Machine_learning.png" alt="Schéma Machine Learning" class="photo4">
        </div>

    </section>

    <!-- SECTION TYPES D'IA -->
    <section id="section-types" class="custom-container">
        <h2>Les différend types d'IA</h2>
        <div class="section-style">
            <p class="content-block">
                Il existe plusieurs types d'IA, les IA textuelles, les IA génératives (image, vidéo, musique...) et même les IA de vision pour les voitures autonomes. 
            </p>

            <div class="cards-types">
                <div class="card-type">
                    <div class="icon">✍️</div>
                    <h3>IA Textuelle</h3>
                    <p>Elle peut rédiger des textes, traduire ou répondre à des questions complexes.</p>
                    <span class="exemple-tag">Exemple : ChatGPT et GEMINI</span>
                </div>
                <div class="card-type">
                    <div class="icon">🎨</div>
                    <h3>IA Générative</h3>
                    <p>Elle crée des images, des dessins, des vidéos ou même des musiques à partir d'une simple description.</p>
                    <span class="exemple-tag">Exemple : Midjourney</span>
                </div>
                <div class="card-type">
                    <div class="icon">👁️</div>
                    <h3>IA de Vision</h3>
                    <p>Elle permet aux voitures autonomes de voir les obstacles ou à ton téléphone de reconnaître ton visage.</p>
                    <span class="exemple-tag">Exemple : FaceID et les voitures autonomes</span>
                </div>
                <div class="card-type">
                    <div class="icon">🧑‍💼​​</div>
                    <h3>Assistant virtuel</h3>
                    <p>L'IA peut aussi être utilisée comme un assistant virtuel. C'est à dire qu'elle va avoir accès à toutes les informations de travail (comme un employé lambda). Elle va ainsi pouvoir aider voir faire des tâches rébarbatives à la place des employés.</p>
                    <span class="exemple-tag">Exemple : Claude</span>
                </div>
            </div>
        </div>
    </section>

    <!-- SECTION EXEMPLES D'IA -->
    <section id="exemples" class="background-exemples">
        <div class="custom-container">
            <h2>L'IA dans ton quotidien</h2>
            <div class="cards">
                <div class="card">
                    <h3>Les Réseaux Sociaux</h3>
                    <p>TikTok et Instagram utilisent l'IA pour analyser ce que tu aimes et te proposer des vidéos qui te retiennent sur les réseaux sociaux. Cela peut se deffinir par l'algorythme.</p>
                </div>
                <div class="card">
                    <h3>Les Jeux Vidéo</h3>
                    <p>Dans FIFA ou F1, les adversaires contrôlés par l'ordinateur (les bots) utilisent une IA pour réagir à tes mouvements. Ainsi, les bots vont réagir différement selon comment tu joues.</p>
                </div>
                <div class="card">
                    <h3>Assistants Vocaux</h3>
                    <p>Siri, Alexa et Google utilisent le traitement du langage naturel pour comprendre ta voix et te répondre le plus précisément possible.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- SECTION "ET DANS LE FUTUR" -->
    <section id="futur" class="custom-container">
        <h2>Faut-il avoir peur de l'IA ?</h2>
        <p class="content-block">
            L'IA offre des possibilités incroyables (aide à la médecine, voitures autonomes), mais elle pose aussi des questions :
        </p>
        <ul class="liste-enjeux">

            <li>
                <strong>Les Fake News :</strong> On peut créer de fausses images très réalistes (Deepfakes) puis les publier sur les réseaux sociaux pour faire croire un mensonge.
            </li>

            <li>
                <strong>L'emploi :</strong> Certains métiers vont disparaître, mais d'autres vont être créés.
            </li>

            <li>
                <strong>La vie privée :</strong> L'IA utilise beaucoup de données personnelles pour fonctionner et être plus précise sur ces réponses.
            </li>

            <li>
                <strong>L'environnement :</strong> L'IA consomme énormément de ressource énergétique. Cela est dû aux serveurs qui sont créés pour effectuer les calculs. Ces serveurs doivent être constamment réfroidis (par des climatisations très énergivore en électricité).
            </li>
        </ul>
    </section>

<!-- FOOTER (CREDIT) -->
    <footer>
        <p>
            Projet réalisé par Igor Brossard - CIAN 2025/2026
        </p>
    </footer>
   <script>
    const burgerButton = document.getElementById('burger-button');
    const navLinks = document.getElementById('nav-links');

    burgerButton.addEventListener('click', () => {
        // "toggle" veut dire : si la classe y est, enlève-la. Si elle n'y est pas, ajoute-la.
        navLinks.classList.toggle('active');
    });
</script>
</body>
</html>
