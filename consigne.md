## Exo 1 : 
# Créer une class Heros , qui aura comme propriété : 
# Nom , attaque , soin , vie , objets , active .

# Créer une class Vilains , qui aura comme propriété : 
# Nom , attaque , vie , objets , active .

# Créer une class Objet , qui aura comme propriété :
# Nom , nombre .

## Exo 2 :
# Créer un Hero qui aura comme attaque : 500 , soin : 250 , vie : 1000 , objets : [] , active : "";
# Créer 5 objets , chaque objet à une fonction différente , mettez les dans un tableau :
// Champignon : Permet de frapper 25% plus fort à la prochaine attaque .
// Fleur : Permet d'enlever 50% de la vie de l'ennemi .
// Taser : bloque l'attaque de l'ennemi .
// Etoile : Permet d'éviter la prochaine attaque de l'ennemi ou objet.7
// Dent vampirique : Si l'utilisateur se soigne , le soigne de 50% en + , si il attaque , le soigne équivalent au dégat d'attaque
// Bombe : Permet de tuer n'importe qui .
# Le nombre dans chaque objet est aléatoire entre 1 et 3 

## Exo 3 : 
# Créer 3 vilains , qu'aurons comme attaque : 100 , vie : 1000 , objet : [] , active : "";
# Chaque vilain aura 2 objets de façon aléatoire .
# Mettez les 3 vilains dans un tableau .

## Exo 4 :
# Créer une fonction ou le hero se battera un vilain par un vilain à la fois de façon aléatoire , à chaque fois qu'un vilain meurt , un autre vilain aléatoire rentre dans l'arène .
// le 1er vilain à une chance sur 3 à chaque tour d'utiliser un de ses objets (aléatoirement).
// le 2ème vilain à une chance sur 2 à chaque tour d'utiliser un de ses objets (aléatoirement).
// le 3ème vilain à 100% de chance à chaque tour d'utiliser un de ses objets (aléatoirement).
# A chaque round : 
// si le hero à un objet , demande à l'utilisateur si il a envie d'en utiliser un , Puis demande lui de choisir entre l'attaque et le soin . 
// Si le hero n'as aucun objet , alors envoie lui une alert (`Vous n'avez aucun objet`); et demande lui de choisir entre l'attaque et le soin .

// A chaque utilisation d'objet , le nombre diminue evidement , utilisez la propriérté active pour vous aidez 

// Quand un vilain meurt , le Hero lui vole tout ses objets restants .

// Le jeu se finis si le hero meurt , ou si tout les vilains ont été vaincus .