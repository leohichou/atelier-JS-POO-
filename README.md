**Rapport : Exercices POO**
Ce rapport présente les solutions aux exercices de programmation orientée objet (POO) fournis.

**Exercice 1 : Classes Voiture et Hyundai**
Cet exercice concerne la création de classes Voiture et Hyundai pour représenter des voitures.

**Classe Voiture:**

_Attributs:_
annee: Année de fabrication
model: Modèle de la voiture
marque: Marque de la voiture
type: Type de voiture (Sedan, Coupe, Hatchback, ...)
carburant: Type de carburant (Essence, Diesel, Electrique)

_Méthode:_
Getannee(): Retourne l'année de fabrication
Classe Hyundai (héritant de Voiture):

_Attributs supplémentaires:_
serie: Série du modèle Hyundai
hybride: Indique si la voiture est hybride
Méthode supplémentaire:
alarmer(): Active l'alarme de la Hyundai

**Exercice 2 : Classes Etudiant et Professeur**
Cet exercice concerne la création de classes Etudiant et Professeur pour gérer des étudiants et des professeurs.

**Classe Etudiant:**

_Attributs:_
nom: Nom de l'étudiant
prenom: Prénom de l'étudiant
age: Âge de l'étudiant
cne: Code national d'étudiant

_Méthode:_
étudier(matier): Retourne une phrase indiquant que l'étudiant étudie la matière spécifiée

**Classe Professeur:**

_Attributs:_
nom: Nom du professeur
age: Âge du professeur
cin: Carte d'identité nationale du professeur

_Méthode:_
enseigner(Groupe): Retourne une phrase indiquant que le professeur enseigne au groupe spécifié

**Exercice 3 : Classes Vecteur2d, Rectangle, Carré, Point et Segment**
Cet exercice porte sur la création de classes pour représenter des structures géométriques en 2 dimensions.

**Classe Vecteur2d:**

_Attributs:_
x: Coordonnée x du vecteur
y: Coordonnée y du vecteur

_Méthodes:_
constructeur(x = 0, y = 0): Initialise les coordonnées du vecteur
afficher(): Affiche les coordonnées du vecteur
Additioner(vecteur): Additionne les coordonnées du vecteur courant avec celles d'un autre vecteur

**Classe Rectangle:**
Hérite de la classe Vecteur2d

_Attributs:_
nom: Nom du rectangle (par défaut "Rectangle")
longuer: Longueur du rectangle
largeur: Largeur du rectangle

_Méthodes:_
constructeur(nom, longuer, largeur): Initialise le nom, la longueur et la largeur du rectangle
afficher(): Affiche le nom, la longueur et la largeur du rectangle
surface(): Calcule et affiche la surface du rectangle

**Classe Carré:**
Hérite de la classe Rectangle

_Attributs:_
nom: Nom du carré (par défaut "Carré")
longuer: Longueur du côté du carré (la longueur et la largeur sont égales)

_Méthode:_
constructeur(nom = "Carré", longuer = 5): Initialise le nom et la longueur du côté du carré

**Classe Point:**

_Attributs:_
x: Coordonnée x du point
y: Coordonnée y du point

_Méthode:_
constructeur(x = 0.0, y = 0.0): Initialise les coordonnées du point
afficher(): Affiche les coordonnées du point

**Classe Segment:**

_Attributs:_
orig: Objet de type Point représentant l'origine du segment
ext: Objet de type Point représentant l'extrémité du segment

_Méthode:_
constructeur(orig1, orig2, ext1, ext2): Initialise les coordonnées de l'origine et de l'extrémité du segment en utilisant deux objets Point

