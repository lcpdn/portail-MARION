## Entrées:
- Heures d'ouverture et de fermeture du dispositif 
-- datetime;datetime
- Nombre d'heure de repos entre chaque poste
-- float;
- Tranche horaire du déjeuner
-- datetime;datetime
- Tranche horaire du dîner
-- datetime;datetime
- Types de qualifications des IS
-- ("Stagiaire";"LAT";"OPR";"PSE1";"PSE2";"CI";"CDPE";"CDME";"Chauffeur Ambulance";"Chauffeur VL";"Cycliste";"Cavalier";"BNSSA";"Permis côtier";"Permis drone";"CTNO")
- Type de véhicule (places;qualification de conduite;nombre de place)
-- "VL_5places";"Chauffeur_VL";5
-- "VLTT_5places";"Chauffeur_VL";5
-- "Minibus_8places";"Chauffeur_VL";8
-- "VPS";"Chauffeur_VPS";5
-- "Velo";"Cycliste";1
-- "Cheval";"Cavalier";1
-- "JetSki";"BNSSA";1
-- "Zodiac";"BNSSA";2
- Pour chaque poste de secours : heure d'ouverture et de fin, nombre et qualifications des IS
-- datetime;datetime;"Nb_Stagiaire";"Nb_LAT";"Nb_OPR";"Nb_PSE1";"Nb_PSE2";"Nb_CI";"Nb_CDPE";"Nb_CDME";"Nb_Chauffeur Ambulance";"Nb_Chauffeur VL";"Nb_Cycliste";"Nb_Cavalier";"Nb_BNSSA";"Nb_Permis côtier";"Nb_Permis drone";"Nb_CTNO"
- Pour chaque IS: qualification, heures d'arrivée et de départ, nom, prénom, NIVOL, numéro de téléphone, adresse mail
-- "$Qualifications";datetime;datetime;"Nom";"Prénom";"NIVOL";"Telephone";"Mail"
- Pour chaque véhicule: type, heures d'arrivée et de départ
-- "$Type";datetime;datetime


## Sorties: 
- Planning général
- Planning par poste de secours
- Planning par IS
- Planning par véhicule

## Qualifications
- Stagiaire
- LAT
- OPR
- PSE1
- PSE2
- CI
- CDPE
- CDME
- Chauffeur Ambulance
- Chauffeur VL
- Cycliste
- Cavalier
- BNSSA
- Permis côtier
- Permis drone
- CTNO

## Types de véhicule
- VL_5places
- VLTT_5places
- Minibus_8places
- VPS
- Velo
- Cheval
- JetSki
- Zodiac
