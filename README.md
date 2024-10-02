# SCSS-Base

# IMPORTANT

ne pas oublier de faire la commande ; npm run sass:w

# liste des variables :

les neutrale c'est toute les variante de gris

--clr-neutral-100: hsl(0, 0%, 100%);
--clr-neutral-200: hsl(0, 0%, 96%);
--clr-neutral-300: hsl(0, 0%, 88%);
--clr-neutral-400: hsl(0, 0%, 74%);
--clr-neutral-500: hsl(0, 0%, 62%);
--clr-neutral-600: hsl(0, 0%, 46%);
--clr-neutral-700: hsl(0, 0%, 38%);
--clr-neutral-800: hsl(0, 0%, 26%);
--clr-neutral-900: hsl(210, 50%, 21%);

les primary c'est un dégrader de bleu

--clr-primary-100: hsl(204, 100%, 95%);
--clr-primary-200: hsl(204, 89%, 86%);
--clr-primary-300: hsl(204, 82%, 75%);
--clr-primary-400: hsl(204, 77%, 67%);
--clr-primary-500: hsl(204, 90%, 63%);
--clr-primary-600: hsl(204, 100%, 50%);
--clr-primary-700: hsl(204, 85%, 51%);
--clr-primary-800: hsl(204, 72%, 47%);
--clr-primary-900: hsl(204, 79%, 43%);

les secondary c'est un dégrader de rose

--clr-secondary-100: hsl(340, 100%, 97%);
--clr-secondary-200: hsl(340, 77%, 88%);
--clr-secondary-300: hsl(340, 78%, 79%);
--clr-secondary-400: hsl(340, 79%, 71%);
--clr-secondary-500: hsl(340, 80%, 64%);
--clr-secondary-600: hsl(340, 82%, 53%);
--clr-secondary-700: hsl(340, 83%, 47%);
--clr-secondary-800: hsl(340, 82%, 41%);
--clr-secondary-900: hsl(340, 82%, 36%);

les succes c'est un dégrader de vert

--clr-success-100: hsl(120, 50%, 93%);
--clr-success-200: hsl(120, 39%, 83%);
--clr-success-300: hsl(120, 33%, 73%);
--clr-success-400: hsl(120, 37%, 64%);
--clr-success-500: hsl(120, 39%, 60%);
--clr-success-600: hsl(120, 39%, 53%);
--clr-success-700: hsl(120, 43%, 47%);
--clr-success-800: hsl(120, 50%, 39%);
--clr-success-900: hsl(120, 55%, 31%);

la c'est un degrader de oranges

--clr-warning-100: hsl(36, 100%, 93%);
--clr-warning-200: hsl(36, 100%, 83%);
--clr-warning-300: hsl(36, 100%, 73%);
--clr-warning-400: hsl(36, 100%, 67%);
--clr-warning-500: hsl(36, 100%, 63%);
--clr-warning-600: hsl(36, 100%, 50%);
--clr-warning-700: hsl(36, 100%, 47%);
--clr-warning-800: hsl(36, 100%, 43%);
--clr-warning-900: hsl(36, 100%, 39%);

la c'est un dégrader de rouge

--clr-danger-100: hsl(0, 100%, 97%);
--clr-danger-200: hsl(0, 100%, 88%);
--clr-danger-300: hsl(0, 83%, 77%);
--clr-danger-400: hsl(0, 71%, 65%);
--clr-danger-500: hsl(0, 79%, 63%);
--clr-danger-600: hsl(0, 83%, 58%);
--clr-danger-700: hsl(0, 79%, 55%);
--clr-danger-800: hsl(0, 79%, 51%);
--clr-danger-900: hsl(0, 79%, 45%);

les c'eest du noire avec différent opactité

--clr-opacity-100: hsla(0, 0%, 0%, 0.1);
--clr-opacity-200: hsla(0, 0%, 0%, 0.2);
--clr-opacity-300: hsla(0, 0%, 0%, 0.3);
--clr-opacity-400: hsla(0, 0%, 0%, 0.4);
--clr-opacity-500: hsla(0, 0%, 0%, 0.5);
--clr-opacity-600: hsla(0, 0%, 0%, 0.6);
--clr-opacity-700: hsla(0, 0%, 0%, 0.7);
--clr-opacity-800: hsla(0, 0%, 0%, 0.8);
--clr-opacity-900: hsla(0, 0%, 0%, 0.9);
--clr-opacity-1000: hsl(0, 0%, 0%);

les on a les font sizes

--fs-900: 3.75rem;
--fs-800: 3rem;
--fs-700: 1.6875rem;
--fs-600: 1.5rem;
--fs-500: 1.25rem;
--fs-400: 1.125rem;
--fs-300: 1rem;
--fs-200: 0.875rem;
--fs-100: 0.75rem;

les c'est des tailles a utilser pour les padding et margin

--size-small: 0.5rem;
--size-medium: 1rem;
--size-large: 1.5rem;
--size-xlarge: 2rem;
--size-xxlarge: 2.5rem;
--size-xxxlarge: 3rem;
--size-huge: 4rem;
--size-gigantic: 5rem;

la c'esst pour les graisses des couleurs

--fw-400: 400;
--fw-700: 700;

et la il y a une typo de base

--ff-sans: "Open-Sans", sans-serif;
--ff-serif: "Bellefair", serif;
--ff-sans-cond: "Barlow-Condensed", sans-serif;
--ff-sans-normal: "Barlow", sans-serif;

# Tuto pour utiliser les mixins

Bien sûr! Le code que vous avez sélectionné est un extrait de SCSS (Sass), un préprocesseur CSS qui ajoute des fonctionnalités comme les variables, les mixins, et les fonctions. Voici une explication de ce que fait ce code et comment l'utiliser :

Explication du Code
Définition des Breakpoints:

Ici, vous définissez une carte (map) de breakpoints avec des tailles minimales et maximales pour différentes tailles d'écran (sm, md, lg, xl, xxl).
Mixin de Breakpoint:

Ce mixin permet de générer des règles CSS conditionnelles basées sur les breakpoints définis.
Il prend deux paramètres : $breakpoint (le nom du breakpoint ou une valeur personnalisée) et $direction (par défaut min pour min-width, mais peut être max pour max-width).
Il vérifie si le breakpoint existe dans la carte $breakpoints. Si oui, il utilise les valeurs min ou max correspondantes. Sinon, il utilise la valeur personnalisée fournie.
Comment Utiliser ce Mixin
Pour utiliser ce mixin dans votre fichier SCSS, vous pouvez l'inclure dans vos règles CSS comme suit :

Explication de l'Utilisation
Définir une Classe:

Ici, .my-class a une couleur de texte bleue par défaut.
Inclure le Mixin pour un Breakpoint Spécifique:

Pour les écrans de taille sm et plus grands (min-width: 576px), la couleur du texte devient rouge.
Inclure le Mixin pour un Breakpoint avec max-width:

Pour les écrans de taille md et plus petits (max-width: 767.98px), la couleur du texte devient verte.
Conclusion
Ce mixin est très utile pour écrire des styles réactifs de manière concise et maintenable. Vous pouvez facilement adapter vos styles en fonction des différentes tailles d'écran en utilisant les breakpoints définis.
