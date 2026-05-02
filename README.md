AHP Project_0
Description
Application web qui implémente la méthode AHP pour l'aide à la décision multicritère.
Fonctionnalités
1. Définition des critères de décision
2. Matrice de comparaison par paires avec échelle de Saaty 1-9
3. Calcul automatique des poids des critères
4. Vérification de la cohérence: CR < 0.1
5. Explication en cas d'incohérence
Utilisation
1. Remplir la matrice: si Critère A est 3x plus important que B, mettre 3
2. Cliquer "Calculer AHP"
3. Si CR < 0.1: matrice cohérente, utiliser les poids
4. Si CR > 0.1: matrice incohérente, revoir les jugements

Lancer en local
npm install
npm start
Demo en ligne
https://ahp-projet-21-2ij6bip59-rayanlb6s-projects.vercel.app/
