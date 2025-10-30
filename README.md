#  TP11 : Généricité  

---

##  Objectifs pédagogiques
Ce TP a pour but de maîtriser la **généricité en Java**, un concept permettant d’écrire du **code réutilisable, sûr et flexible**.

À travers trois exercices progressifs, vous allez apprendre à :
- Créer des **classes et méthodes génériques** avec un ou plusieurs paramètres de type.
- Manipuler la **sécurité de type** sans conversion explicite.
- Utiliser les **bornes de types** (`extends`, `super`) pour restreindre les types acceptés.

---

##  Structure du projet
 ```
src
│
├── ma/projet
  │
  ├── Exercice1
  │   ├── Triplet.java           
  │   └── TestTriplet.java       
  │
  ├── Exercice2
  │   ├── TripletH.java          
  │   └── TestTripletH.java     
  │
  └── README.md 
 ```

##  Exercice 1 : Triplet homogène

### Objectif pédagogique
Apprendre à définir une **classe générique simple** (`Triplet<T>`) permettant de stocker et manipuler trois objets du **même type**, tout en conservant la sécurité de type.

 ## Sortie du programme
 ```
Triplet : [1, 2, 3]
Triplet : [A, B, C]
Second élément de tInt : 2

 ```
 ## Exemple d’exécution (image)

Voici un exemple de l'exécution du programme (screenshot) :

<img width="385" height="208" alt="image" src="https://github.com/user-attachments/assets/0a9bf3d1-b939-4233-9d22-0f96b3a1f94b" />



## Exercice 2 – Triplet hétérogène

  ### Objectif

Créer une classe générique `TripletH<A,B,C>` pour stocker trois objets de types différents.

 ## Sortie du programme
 ```
TripletH : [42, Answer, 3.14]
TripletH : [Alice, 30, true]

 ```
## Exemple d’exécution (image)

Voici un exemple de l'exécution du programme (screenshot) :

<img width="458" height="108" alt="image" src="https://github.com/user-attachments/assets/19a6cceb-b5fd-4981-b179-d8311776af93" />







