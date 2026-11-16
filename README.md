# Guide Pratique et Fondamentaux HTML5 & CSS3

Recueil pedagogique et aide-memoire complet destine a l'apprentissage et a la maitrise des bases du developpement web frontend. Ce depot rassemble 30 modules pratiques autonomes couvrant l'ensemble des notions fondamentales, de la structure semantique HTML5 jusqu'au stylisme avance et aux techniques de mise en page en CSS3.

---

## Vue d'Ensemble du Programme

Le projet est organise sous forme d'exercices independants et progressifs, directement executables dans n'importe quel navigateur web.

### 1. Structure et Semantique HTML (Modules 01 a 08)
- **01 - Titres et Paragraphes** : Hierarchie des balises de titre (`h1` a `h6`) et structuration des paragraphes de contenu (`p`).
- **02 - Espaces et Retours a la Ligne** : Gestion des sauts de ligne avec `br` et separation thematique avec `hr`.
- **03 - Importance et Mise en Valeur du Texte** : Semantique de l'accentuation (`strong`, `em`, `mark`, `small`).
- **04 - Listes Ordonnees et Non Ordonnees** : Construction de listes a puces (`ul`), numerotees (`ol`) et imbriquees (`li`).
- **05 - Liens Hypertextes** : Liens externes, relatifs, cibles de navigation (`target="_blank"`) et attributs associes.
- **06 - Autres Types de Liens** : Ancres internes vers une section de la page, liens d'envoi d'email (`mailto:`) et d'appel telephonique.
- **07 - Insertion d'Images** : Balise `img`, chemins d'acces relatifs, dimensionnement et texte alternatif d'accessibilite (`alt`).
- **08 - Echappement de Caracteres** : Entites HTML pour afficher les caracteres reserves (`&lt;`, `&gt;`, `&amp;`, espaces insecables `&nbsp;`).

### 2. Selecteurs et Comportements Fondamentaux (Modules 09 a 12)
- **09 - Identifiants et Classes** : Ciblage precis des elements avec les selecteurs d'identifiant (`#id`) et de classe (`.classe`).
- **10 - Heritage et Cascade CSS** : Transmission des proprietes de style des parents vers les enfants et priorite des regles CSS.
- **11 - Elements Block et Inline** : Differences structurelles fondamentales entre elements de flux de type bloc et en ligne.
- **12 - Balises Generiques div et span** : Structuration de blocs conteneurs avec `div` et mise en forme de portions de texte avec `span`.

### 3. Typographie et Proprietes de Texte (Modules 13 a 17)
- **13 - Familles de Polices (font-family)** : Choix des polices systemes, polices de secours (fallbacks) et typographie serife / sans-serife.
- **14 - Proprietes des Fontes** : Taille (`font-size`), graisses (`font-weight`) et styles italiques (`font-style`).
- **15 - Couleurs et Opacite** : Formats de couleur hexadecimaux, noms standards, RGB et gestion de la transparence avec le canal alpha (`rgba`, `opacity`).
- **16 - Proprietes de Texte** : Alignement horizontal (`text-align`), decorations (`text-decoration`), transformation de casse (`text-transform`) et hauteur de ligne (`line-height`).
- **17 - Espacements Typographiques** : Ajustement de l'espacement entre les lettres (`letter-spacing`) et entre les mots (`word-spacing`).

### 4. Le Modele de Boite - Box Model (Modules 18 a 22)
- **18 - Modele des Boites (Box Model)** : Notion essentielle du developpement web combinant le contenu (content), la marge interne (padding), la bordure (border) et la marge externe (margin).
- **19 - Hauteurs et Largeurs** : Proprietes de dimensionnement `width`, `height`, et contraintes `min-width`, `max-width`.
- **20 - Bordures** : Styles de bordures (`solid`, `dashed`, `dotted`), epaisseurs, couleurs et arrondis d'angles (`border-radius`).
- **21 - Padding et Margin** : Espacements internes et externes, raccourcis a 1, 2 ou 4 valeurs, et technique de centrage horizontal automatique avec `margin: auto`.
- **22 - Ombres Portees (box-shadow)** : Generation de reliefs, ombres exterieures et interieures (`inset`), decalages X/Y, rayon de flou et couleur d'ombre.

### 5. Positionnement et Agencement (Modules 23 a 26)
- **23 - Propriete Display** : Transformation du comportement des balises (`block`, `inline`, `inline-block`, masquage avec `none`).
- **24 - Propriete Position et z-index** : Positionnement `static`, `relative`, `absolute`, `fixed`, et ordre d'empilement visuel 3D avec `z-index`.
- **25 - Propriete Float et Clearfix** : Flottement d'elements a gauche ou a droite pour l'habillage de texte et annulation du flux avec `clear`.
- **26 - Techniques d'Alignement Horizontal** : Solutions d'alignement pour elements en ligne, blocs et conteneurs.

### 6. Arriere-plans et Degrades Graphiques (Modules 27 a 30)
- **27 - Couleur de Fond (background-color)** : Application et superposition de teintes d'arriere-plan.
- **28 - Images de Fond (background-image)** : Positionnement (`background-position`), repetition (`background-repeat`), couverture d'espace (`background-size: cover/contain`) et attachement fixe (`background-attachment`).
- **29 - Degrades Lineaires (linear-gradient)** : Transitions harmonieuses de couleurs avec directions angulaires ou cardinales (`to right`, `to bottom`, `45deg`) et paliers de couleur.
- **30 - Degrades Radiaux (radial-gradient)** : Diffusions circulaires et elliptiques de couleurs depuis un point d'origine central ou personnalise.

---

## Utilisation Pratique des Fichiers

Chaque fichier du depot est un module autonome concu pour l'apprentissage :

1. Cloner le depot sur votre machine :
   ```bash
   git clone https://github.com/maximedefaleouna/HTML-CSS.git
   cd HTML-CSS
   ```
2. Double-cliquer sur le fichier HTML de votre choix (ou l'ouvrir avec un navigateur tel que Chrome ou Firefox) pour visualiser le resultat.
3. Ouvrir le code source dans votre editeur pour observer l'interaction entre le balisage HTML et les declarations CSS associees, puis modifier les valeurs pour constater immediatement le rendu.

---

## Auteur

**Maxime DEFALEOUNA**
- Profil GitHub : [@maximedefaleouna](https://github.com/maximedefaleouna)
- Portfolio : [https://maximedefa.netlify.app](https://maximedefa.netlify.app)
