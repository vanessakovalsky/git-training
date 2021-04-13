# Je demarre sur un projet

# nouveau projet

git init

# projet existant

git clone url

# Matin en arrivant

git fetch && git pull ## Recupération des données distantes

git rebase develop  ## MAJ ma branche sur la branche develop 

# Je developpe une nouvelle fonctionnalité 

git branch mabranch

# Quand j'ai fini une modif

git add mon fichier
git commit -m 'Modification' 

* X le nombre de fois nécessaire

# Quand j'ai fini ma fonctionnalité

git fetch && git pull
git rebase develop 

# Je demande à mes collègues : "Je peux merger?"

git checkout develop 
git merge mabranch

# Si conflit je résous mes conflits 

git push 

# "j'ai fini de merge"


