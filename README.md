# Documentation Fondamentale : Matrice Pure 5D (Espace-Temps Déterministe)

## 1. Introduction Théorique
La Matrice Pure 5D est un modèle algorithmique quantitatif et déterministe conçu pour s'affranchir des indicateurs techniques traditionnels de type oscillatoire ou tendanciel. Le système n'analyse pas le marché sous l'angle exclusif des variations de prix (Espace), mais intègre le Temps comme une variable dynamique, élastique et bidirectionnelle. 

En mesurant la synchronisation structurelle d'une séquence stricte de six échelles de temps verrouillées (12 Mois, 1 Mois, 1 Semaine, 1 Jour, 1 Heure, 5 Minutes), la matrice identifie les points de rupture cinétique et de convergence absolue appelés Apex.

## 2. Invariants Géométriques et Équations de la Matrice

### 2.1 Compression Multi-Timeframe par Tuple
Pour optimiser les ressources de calcul et éviter la latence des serveurs, l'intégralité des états de tendance des six unités de temps est encapsulée dans une fonction vectorielle unique. Les structures de masses actives découlent de l'alignement binaire de ces couples :
* Masse active maximale : 15 M (Convergence absolue, Densité d'Énergie à 100%)
* Masse active critique d'équilibre : 8 M (Seuil de rupture structurelle)

### 2.2 Loi de Polarité Asymétrique des Cycles
Le temps ne s'écoule pas de manière identique selon l'orientation vectorielle du flux :
* En phase d'Achat (LONG) : Le temps est dégressif. Le cycle s'initialise à sa pression maximale de 60 / 60 Bougies et se vide vers 0 à mesure que l'énergie cinétique se dissipe.
* En phase de Vente (SHORT) : Le temps est progressif. Le cycle s'enclenche par aspiration à 0 / 60 Bougies et se remplit linéairement jusqu'à saturation complète à 60 bougies.

### 2.3 Mécanique du Gel Asymétrique
Au moment précis du choc de masse initial, les variables temporelles et spatiales appliquent un protocole de verrouillage strict :
* Le Passé et le Présent sont figés : Le prix d'entrée Pivot et le niveau du Stop Loss (SL) sont scellés dans le passé de l'ancrage. Le Stop Loss intègre une barrière de tolérance calculée sur la vitesse relative de la mèche et l'écart Bid/Ask réel du carnet d'ordres pour neutraliser le spread du courtier.
* Le Futur reste élastique : Le Take Profit (TP) et l'horloge de l'Apex s'adaptent en temps réel aux variations de l'énergie de la masse active, jusqu'au relâchement automatique des verrous lors de l'impact du prix.

## 3. Notice d'Exécution et Protocole Opérationnel

### Étape 1 : Phase de Radar (Attente)
Le système affiche le statut RECHERCHE CHOC. Le marché est en phase de dilatation temporelle, aucune intervention n'est tolérée. La matrice indique en continu la fréquence vibratoire optimale convertie en unité de temps officielle (GRAPH REQUIS : 4h, 1h, 15m, etc.). Le trader doit aligner son graphique sur cette unité.

### Étape 2 : Phase d'Impulsion (Saisie de l'Ordre)
Au moment exact du choc, la direction se verrouille. Le tableau de bord calcule instantanément les prix limites basés sur les frictions réelles du carnet d'ordres (Ask pour un LONG, Bid pour un SHORT). Saisissez immédiatement un ordre différé chez le broker (ActiveTrades / MetaTrader) en recopiant strictement les valeurs numériques affichées :
* Coordonnée d'entrée : SAISIR BUY LIMIT ou SELL LIMIT
* Coordonnée de protection : STOP LOSS REQUIS (Calculé et figé sur le passé de l'ancrage)

### Étape 3 : Phase de Gel (Échéance Absolue)
Dès la clôture horaire validée, le terminal passe au statut PRÉSENT GELÉ (ou STATUT : TEMPS GELÉ). Le plan d'exécution est sanctuarisé contre le bruit et la manipulation des mèches de marché. Conservez la position de manière totalement passive. Liquidez l'intégralité de la position à la seconde près dès que le cours live touche la valeur du TAKE PROFIT REQUIS ou lorsque l'horloge atteint l'heure calendrier fixe indiquée par la cellule PROCHAIN APEX TIME. Le système efface alors sa mémoire et réactive le radar.
