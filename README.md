# rendezvous-cov19 : Initié par CREDIA(Centre de Recherche en Developement de l'Informatique Appliquée, à l'Ecole Supérieure d'Informatique Salama) et developé par le monde
Ce projet est un système de reservation de rendez-vous en ligne pour éviter les attroupements dans des banques, super marché et toutes les instutitions critiques qui doivent rester ouvertes et entrain de fonctionner pendant la période de crise. Pour éviter d'avoir plusieurs personnes dans un local, on prend en compte la capacité d'acceuil de chaque institution (batiment) et limiter le nombre de rendez-vous disponible par rapport à cette capacité d'acceuil. Cette application aide aussi de tracer toutes les personnes qui ont visité un endroit dans l'éventualité d'une possible contamination.
L'application devra avoir un dashboard pour les institutions afin de gérer les rendez-vous et une partie applicative qui exigera un email et un numéro de téléphone pour le client. L'email permet de synchroniser l'application google calendar sur le téléphone du client et le numéro de téléphone permettra de contacter ce dernier.
Une partie mobile pourrait etre proposée plus tard.
Le fonctionnement de l'application :
- l'instutition (entreprise, hopital, agence de l'Etat) crée un compte sur la plateforme et spécifie tous les bureaux (surfaces) susceptibles de recevoir les clients ou visiteurs
- l'institution accède au dashboard et spécifie les capacités d'acceuil (ou la surface disponible pour acceuillir les visiteurs en définissant la longeur et la largeur). L'application calcule le nombre de personnes qui peuvent y etre accepté en respectant les mesures de 1m de distance minimum et limite les créneaux de rendez vous disponible pour cette salle là.
- l'institution crée des créneaux de rendez-vous en spécifiant juste la date, l'application génére automatiquement les créneaux.
- l'utilisateur se connecte avec son adresse email et son numéro de téléphone obligatoirement
- une fois connecté, il clique sur un créneau pour le reserver s'il est disponible. 
- si le système accepte la reservation, il génére un code qu'on envoie par sms pour la reservation web et un QR Code pour les réservations par téléphone
- le client se présente devant l'entreprise, présente le code ou le QR au portier pour entrer dans l'insitution
* Dans quel cas le système peut réfuser la réservation ou ne pas générer un code ?
- Pour toutes les personnes à risque par exemple. Si vous visiter des zones à risques les derniers 15 jours par exemple. Les zones à risque peuvent etre l'Europe en entierete actuellement mais cela peut changer comme nous avons vu la chine qui ne serait plus considérée comme une zone rouge complétement.

L'avantage avec cette application est que les données pourront être utilisées par le ministère de la santé pour tracer les personnes qui ont visitées une institution où les gens ont été contaminés par exemple.
