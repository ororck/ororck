Partie 1 
---
1. Quelle est la différence entre `git add` et `git commit` ? gi add prepare le changement et git commit le finalise.
2. Pourquoi utilise-t-on des branches plutôt que de modifier directement `main` ? pour pouvoir tester les modifications sans changer le main et garder une branche principal saine
3. Que se passe-t-il si tu fais `git push` sans avoir fait `git pull` au préalable ? Ca depend, si il n'y a rien de nouveau git accepte le push mais si le remote a des commits en plus git refuse avec une erreur
4. À quoi sert la zone de staging (`git add`) ? Pourquoi ne pas commiter directement ? ca permet de permet de faire un commit pour chaque modificaiton, le principe est de faire un commit par "idée"

Partie 2 

---
1. Qu'aurais-tu dû faire si vous aviez tous les deux modifié la même ligne du README en même temps ? github ne permettra pas la 2eme modification et afficheras un message d'erreur et le deuxime personne devra pull la version modifié avant de faire sa modification si il y'a encore besoin d'une modification
2. Pourquoi est-il important de travailler sur une branche dédiée plutôt que directement sur `main` quand on collabore ?
3. À quoi ressemble ce workflow dans un vrai projet open source sur GitHub ?

