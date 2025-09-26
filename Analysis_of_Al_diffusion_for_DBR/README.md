# Description

# First meeting: 09/26/25
DBR avec une slope pour le matériel.
Al_xGa_{1-x}As
Al_xGa_{1-x}As

avec x = 0.8 et x=0
DBR x=0.8 avec une épaisseur de 0.07991 um pour lambda=980nm
DBR x=0 avec une épaisseur de 0.06712 um pour même lambda

Une slope seulement sur un type d'interface, (à gauche des couche en 0.079 
um par example)

Utilisée TMM pour obtenir le profil de réflexion.
discrétisé la slope par 10, 100, ou 1000 layers en TMM. Il y a typiquement
50 couches 0.8/0 sur un DBR.

On veut utilisé un TMM fait maison, et dire à la fin que l'on a utilisé 
celui de Silvaco. Et utiliser celui de Silvaco à la fin pour vérifier.

A la fin des fins on peut faire une simulation 2D en RCWA, avec un grating carré
et optimizé le profil du grating pour obtenir un VCSEL polarisé

En suivant l'article
KEELER 2006, Control of VCSEL POlarization using deeply etched surface gratings. 2006

On peut aussi regarder en détail TMM et voir s'il est possible de ne pas 
discrétisé la slope avec des layers, mais plutôt d'utiliser directement 
un profil analytique.




