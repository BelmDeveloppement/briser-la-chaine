# Briser la chaîne

Jeu MITRE ATT&CK, plateau physique + application téléphone. Ouvrir la page (GitHub Pages) sur l'ordinateur de l'animateur, puis les équipes rejoignent avec le QR code.

Les Constats sont dans `scenarios.json` (à relire et vérifier).

© 2026 SAS BELM DEVELOPPEMENT. Tous droits réservés. Voir le fichier LICENSE.
ATT&CK® est une marque de The MITRE Corporation ; ce jeu n'est ni affilié ni approuvé par MITRE.

## Jeu 24 « MITRE » (21 novembre 2026)
Application d'interaction couplée au PowerPoint du module MSRC 1 : `quiz/` (QCM en direct) et `roue/` (tirage au sort).
- Joueurs : **PC d'abord**, QR code « secours téléphone » seulement.
- Transport : relais Cloudflare (voie principale), ntfy en secours uniquement ; voyant de synchro, bouton « Resynchroniser », plan B manuel.
- Liaison PowerPoint : complément JeuxLive, étiquette de présentation `JL_SID`, étiquette de diapo `AC_Q` = clé du quiz (ex. `surface`) ou `<clé>-<n>` pour la question n. Lien animateur : `quiz/?set=<clé>&sid=<JL_SID>`.
- Bouton « Signaler » (non anonyme, file hors ligne).
