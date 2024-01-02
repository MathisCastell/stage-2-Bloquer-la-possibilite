# Bloquer la possibilité d'avoir une mesure qui début et se termine le même jour

## Demande

![image](https://github.com/MathisCastell/stage-2-Bloquer-la-possibilite/assets/148212506/6176c77c-61cd-461d-bf42-ccf884a7b658)

## Modification Procédure

Ajout de conditions pour bloquer la possibilité que la date soit la même.

![image](https://github.com/MathisCastell/stage-2-Bloquer-la-possibilite/assets/148212506/8e104495-4428-4b60-ac06-c8b3610883bc)

## Insertion dans la base de donnée

Insertion de donnée dans la base de donnée pour mettre un nouveau code d'erreur

INSERT INTO app_code_retour(code_id, libelle, fk_code_retour_type_id) VALUES (203, 'La date de levée doit être postérieure à la date d\'ouverture et les dates de LRAR doivent être postérieures ou égales aux dates d\'audience.', 2);

## Résultat 

![image](https://github.com/MathisCastell/stage-2-Bloquer-la-possibilite/assets/148212506/8f217d1d-ef85-4b5f-be68-3e18149c0bb6)



