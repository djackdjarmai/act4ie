Cela décrit des services fourni par des entreprises au réseau. Ce sont typiquement des services lié à l'équilibrage du réseau et son contrôle en tension. 
On y retrouve différentes nécessités de temps d'activation. Des besoins de symétries, ou non. 

En France: services avec RTE
--
Rapport RTE sur la flexilité en 2022:
https://analysesetdonnees.rte-france.com/bilan-electrique-flexibilites

https://www.services-rte.com/fr/decouvrez-nos-offres-de-services/valorisez-vos-flexibilites.html
"Les mécanismes de valorisation de la la capacité"
**Mecanisme de capacité:** 
![image-redimensionnable-1](https://www.services-rte.com/files/live/sites/services-rte/files/pictures/schema-offre/schema-2-mecapa-fr.jpg)
Réserves Rapides et Complementaires:
![[Pasted image 20231215142433.png]]


En France: ENEDIS
--
Enedis, gestionnaire Français du réseau de distribution. Appel d'offre de flexibilité locale sur 6 zones en France en 2021. les zones ont été sélectionnées pour leur besoins de flex.

L'appel d'offre cherche [2 types de services de flex](zotero://open-pdf/groups/5242748/items/SWI5RU85?page=6&annotation=PTEYRH6B): 
avec réservation de capacité => rémunération fixe, 
sans réservation => rémunération ponctuelle suite à demande d'activation de ENEDIS

Les contrats de flexbilité d'Enedis spécifient:
- Avec/Sans réservation de capacité
- Début - fin de contrat.
- Puissance et durée minimale
- Périodes d'activation: Calendrier des besoins, avec les horaires
Toutes les infos ici: https://flexibilites-enedis.fr/  et [rapport générale sur leur démarche](zotero://select/groups/5242748/items/5CT5BV49)

Appel d'offre et exemples de 2023: [ici](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwi-jI3_2ZiDAxVTUaQEHXNcB98QFnoECBcQAQ&url=https%3A%2F%2Fwww.enedis.fr%2Fmedia%2F3594%2Fdownload&usg=AOvVaw3U_D6kS56e0nT8L-RLUvT_&opi=89978449)

En terme d'ODG, leur appel d'offre commence à 500kW, et souhaite passer à 250kW. Les  systèmes de rémunération sont aussi indiqués dans le rapport général sur leur démarche mentionné ci dessus.
Comment Participer avec les MES?
--
Edoardo Corsetti a travaillé récemment sur l'optimisation de la commande des MES pour maximiser les revenus liés au services de flexibilité.

Pour ce faire il procède à deux boucles d'optimisation, une première pour définir les échanges énergétiques et le dispatch de puissance afin de répondre au demande énergétique et de **minimiser les couts** en prenant en compte la participation aux marchés de l'énergie DA (Day Ahead) et ID (Inter Day?). Les [[Services de flexibilité]] pris en compte sont les FCAS. Les echanges de puissances sont exclusivement fait avec le reseau de transport (TSO).

Il utilise le Framework de "Energy lattice" pour la représentation des Energy layers mais reconnait que les équations sont équivalentes à celle de extended energy hub.
Il y mentionne Bruno c'est marrant
