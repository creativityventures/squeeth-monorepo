# oSQTH et power perpetual

Le token oSQTH représente l’exposition au carré de l’ETH. Les paramètres de volatilité implicite, de prix et de marge structurent les positions longues et courtes. Les contrats calculent les montants dus et appliquent les contrôles nécessaires avant une modification d’état.

La mécanique n’est pas un simple ERC-20 : les utilisateurs prennent une exposition dérivée dont la sensibilité augmente avec le prix de l’ETH. Il faut donc lire les fonctions de règlement avec les unités, arrondis et bornes de risque.

Suite : [Crab et couverture](./03-crab-couverture.md).
