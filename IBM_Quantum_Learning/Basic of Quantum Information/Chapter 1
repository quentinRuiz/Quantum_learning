# Chapitre 1 : Single systems

Sommaire : 

1. Classical Information
2. Quantum Information
    1. Quantum state vector
    2. Standard basis Measurement
    3. Unitary operations

Introduction : 

Représentation d’un été quantique:

- Un etat quantique est représenté par un vecteur, les operations par des matrices unitaires (simplifié)
- Un etat quantique est représenté par un une matrice de densité. cela permet une plus large. class de mesures et d’operations (avancé)

1. Classical Information : 
    
    Un etat classique correspond à un nombre fini, ou une supperposition de nombre fini, ex : binaire avec 0 ou 1. Peut correspondre aussi à plusieurs état pour une tension (low, mid, high, off). 
    
    Représentation d’un état probabilistique pour un etat quantique:
    
    $$
    P(X = 0) = \alpha ,\space\space P(X = 1) = \beta
    $$
    
    La somme des etats vaut 1, les valeurs sont comprises entre 0 et 1 inclus. 
    
    Notation de dirac :
    
    $$
    |0> = \binom{\alpha}{0}, \space\space |1> = \binom{0}{\beta}
    $$
    
    Vecteurs de cette forme sont appellés vecteur de la base standard. Chaque vecteur peut etre exprimé comme combinaison lineaire  des vecteurs de la base. (Ici |0> et |1>).(appelé ket)
    
    Que se passe t il si on mesure un systeme porobabilistique:
    
    on obtient un état classique, et l’etat probabilistique devient la valeur mesurée
    
    $$
    P(X = \alpha) = 1
    $$
    
    Operations deterministique : 
    
    Pour toute fonction de \sigma dans \sigma décrit comme opération deterministique la transofrmation d’un etat classique a en f(a), pour tout a appartenant à \sigma. 
    
    Cette matrice a une valeur egal à 1 dans chaque colonne et 0 pour toute les autres entrées.
    
    $$
    M|a> = |f(a)>
    $$
    
    Permet la construction des matrices, voir matrice de pauli en exemple. 
    
    Notion de bra. notatino : <a|
    
    ecriture : 
    
    $$
    <x| = (1 \space 0), \space \space |x> = \binom{1}{0}
    $$
    
    Le produit d’une colonne par une ligne donne une matrice.(exemple avec des vecteur colonne de dimension 2.
    
    $$
    |\alpha><\beta| = \begin{pmatrix} *&*  \\ *&* \end{pmatrix}
    $$
    
    Expression de la matrice deterministique, pour toute fonction f de Sigma dans Sigma:
    
    $$
    M = \sum_{a \in \Sigma}^{}|f(a)><a|
    $$
    
    notion d’inner product.
    
    Opération probabilistique sont des operations classiques qui peuvent introduire une incertitude ou un hasard.
    
2. Quantum Information
    1. Quantum state vector
    
    Un etat quantique est representé par un un vecteur colonne qui indique dans quelles états classique il peut etre. Les entrées sont complex, lasomme des valeurs absolues au carré est égal à 1. (Norme euclidienne)
    
    $$
    v = \begin{pmatrix}
    \alpha_1 \\
     ...\\
    \alpha_n
    
    \end{pmatrix}
    
    \Rightarrow 
    
    ||v|| = \sqrt{\sum_{i=1}^{n}|\alpha_i|^2} = 1
    $$
    
    Ce sont des vecteurs unitaires.
    
    Exemple de vecteur d’etat, plus and minus states:
    
    $$
    |+> = \frac{1}{\sqrt{2}}|0> + \frac{1}{\sqrt{2}}|1>, \space and \space |-> = \frac{1}{\sqrt{2}}|0> - \frac{1}{\sqrt{2}}|1>
    $$
    
    Exemple avec des complexes (ket)
    
    $$
    |\psi> = \frac{1+2i}{3}|0> - \frac{2}{3}|1>
    $$
    
    Conjugué complexe
    
    $$
    <\psi| = |\psi>^\dag 
    $$
    
    Exemple:
    
    $$
    |\psi> = \frac{1+2i}{3}|0> - \frac{2}{3}|1> \space = \binom{\frac{1+2i}{3}}{-\frac{2}{3}} \\ <\psi| = \frac{1-2i}{3}<0| - \frac{2}{\sqrt{3}}<1| \space = \begin{pmatrix}
     \frac{1-2i}{3}& {-\frac{2}{3}}
    \end{pmatrix}
    $$
    
    b. Standard basis Measurement
    
    Mesure d’un état quantique (standard basis measurement)
    
    - Les sorties possibles sont les états classiques
    - La probabilité d’obtenir chaque etat classique correspond a la valeur absolue au carré de la valeur du vecteur d’état, exemple pour l’etat |+>, la probabilité d’obtenir 0 est de 1/2, et la probabilité d’obtenir 1 est de 1/2. Apres avoir effectué la mesure, le vecteur d’état devient le vecteur correspondant à la valeur mesurée avec une probabilité de 1. Il y a donc modification du vecteur d’état après la mesure.
    
    c. Unitary operations
    
    Une matrice U est dite unitaire si le produit de U avec son conjugué complexe donne la matrice identité, cad
    
    $$
    UU^\dag = I = U^\dag U
    $$
    
    et, il y a conservation de la norme, pour v un vecteur d’etat:
    
    $$
     ||Uv|| = ||v||
    $$
    
    Operations unitaire sur les Qubits : 
    
    Matrice de Pauli :
    
    $$
    I = \begin{pmatrix} 1&0  \\ 0&1 \end{pmatrix} \\ \sigma_x = \begin{pmatrix} 0&1  \\ 1&0 \end{pmatrix} \\ \sigma_y = \begin{pmatrix} 0&-i  \\ i&0 \end{pmatrix} \\ \sigma_z = \begin{pmatrix} 1&0  \\ 0&-1 \end{pmatrix}
    $$
    
    L’operateur $\sigma_x$ est appelé *bit flit*, et L’operateur $\sigma_z$ est appelé *phase flit*
    
    $$
    \sigma_x |0> =|1> \\ \sigma_x |1> =|0> \\ \sigma_z |0> =|0> \\ \sigma_z |1> =-|1>
    $$
    
    Operation de hadamard:
    
    $$
    H = \begin{pmatrix} \frac{1}{\sqrt{2}} &\frac{1}{\sqrt{2}} \\ \frac{1}{\sqrt{2}}&-\frac{1}{\sqrt{2}} \end{pmatrix} 
    $$
    
    Opération de phase, pour theta un nombre réel : 
    
    $$
    P_\theta = \begin{pmatrix} 1&0  \\ 0&e^{i\theta} \end{pmatrix}
    $$
    
    Exemple importants:
    
    $$
    S = P_{\pi/2} = \begin{pmatrix} 1&0  \\ 0&i \end{pmatrix} \\ T = P_{\pi/4} = \begin{pmatrix} 1&0  \\ 0&\frac{1+i}{\sqrt{2}} \end{pmatrix}
    $$
    
    Exemple importants:
    
    $$
    H|0> = |+> \\ H|1> = |-> \\ H|+> = |0> \\ H|-> = |1>
    $$
    
    La composition de matrice unitaire sont représentés comme une multiplication de matrice. Exemple pour square root Not:
    
    $$
    HSH = \begin{pmatrix} \frac{1+i}{2}&\frac{1-i}{2}  \\ \frac{1-i}{2}&\frac{1+i}{2} \end{pmatrix} \\ (HSH)^2 = \begin{pmatrix} 0&1  \\ 1&0 \end{pmatrix}
    $$
