# Le monstre écoute

La créature de l'affiche de l'Assemblée créative de Genève, dans le noir. Page autonome pour une performance de quatre minutes : une personne lit un conte, une autre l'accompagne à la guitare, devant un grand écran.

Le dessin de l'affiche est présent en entier mais invisible. La voix et les notes en révèlent des fragments : la lune, le dos de la créature, une fenêtre, les rayures de la tour, l'auvent perforé, les pavés, des lucioles. Les yeux suivent celui qui joue.

Tout tourne dans le navigateur (Chrome recommandé), sans serveur. Le micro sert uniquement à écouter : aucun son n'est enregistré ni envoyé.

## Deux versions

- **La cour dans le noir** (adresse du site) : le dessin de l'affiche, en couleurs, révélé par fragments.
- **L'invocation** (`invocation.html`) : noir et blanc, en 3D. Un mur noir percé d'une fenêtre, une boîte derrière. La musique appelle la créature : elle monte du fond, s'approche, passe la tête par la fenêtre, puis la lève au-dessus du cadre et la penche vers le conteur, la guitare et le public. Chaque note est une luciole ; la voix les attire, certaines sortent de l'écran.

La version se choisit aussi sur l'écran de départ et depuis la régie.

## Utilisation

- Ouvrir la page, choisir « Démarrer avec le micro de l'ordinateur », puis `F` pour le plein écran.
- `H` ouvre les réglages : calibration du silence, position du conteur et de la guitare, cadrage, lumière, dévoilement, couches d'animation.
- `Espace` lance la performance, `Entrée` lance la fin.
- « Démonstration guidée » montre le dispositif en 45 secondes, sans micro.

## Régie au téléphone

Dans les réglages de la scène, scanner le QR code (ou ouvrir l'adresse terminée par `#regie` et saisir le code). La régie guide les yeux, déclenche chaque animation et règle la lumière. Les ordres passent par des relais de messagerie publics (MQTT) : il faut Internet sur les deux appareils. Seuls des ordres y transitent.

## Crédits

Illustration de l'affiche : Assemblée créative de Genève, Downtown Studio. Bibliothèques : three.js (voir `vendor/LICENSE-three.txt`), MQTT.js (voir `vendor/LICENSE-mqtt.md`), qrcode-generator.
