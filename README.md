# DataMedicales


Descriptif du jeu de données:

Une ligne du jeu de donnée est un ensemble constitué d’un unique type de médicament, vendu à un même groupe de personnes, et prescrit par des médecins d’une même spécialité.

1.	L’ensemble constitué d’un même médicament est décrit par les attributs

    1.1.	CIP13 : L’identifiant du médicament
    
    1.2.	L_CIP13 : Le nom complet du médicament
    1.3.	BOITES : Le nombre de boites prescrites
    1.4.	BSE : La base de remboursement pour l’ensemble de boites prescrites
    1.5.	REM : Le montant remboursé pour l’ensemble des boites prescrites

2.	Le même groupe de personnes est décrit par les attributs

    2.1.	AGE : La tranche d’âge du groupe de personnes.
    2.2.	SEXE : Le sexe du groupe de personnes.
    2.3.	BEN_REG : Région de résidence du groupe de personnes.
    2.4.	NBC : Nombre de personnes dans le groupe.

3.	Les  médecins d’une même spécialité sont décrits avec l’attribut

    3.1.	PSP_SPE : Spécialité professionnelle du Médecin ayant fait la prescription.


L’identifiant d’un médicament est à coupler avec le fichier ‘tags.csv’ pour récupérer la classification ATC de chaque médicament.

