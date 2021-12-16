# Activitat NADAL

## **Alumne**: nom alumne

### Base de dades a fer servir

**A)** Base de dades: **Empresa**

**B)** Base de dades: **exemple**  (ActAva_20211125)

**C)** Base de dades: **videoclub**

Cal que feu un enunciat, per a cada apartat que es mostra a continuació, com si fos per un examen, en el que calgui fer servir el següent per fer la consulta.

Recordeu que, per a cada apartat, cal:
1. Que formuleu un enunciat,
1. Aporteu la consulta que resol l'enunciat que demaneu i
1. El resultat que torna la consulta.


Els apartats són els següents:

1. Fer una consulta que retorni un recompte de registres de la mateixa taula. (**```<CognomNomDelAlumne>```**```_En_001.sql```)
1. Fer una consulta que retorni un recompte de registres d'una altra taula.(**```<CognomNomDelAlumne>```**```_En_002.sql```)
1. Fer una consulta que faci servir una subconsulta. (**```<CognomNomDelAlumne>```**```_En_003.sql```)
    * Recordeu que una subconsulta té el següent format:
    ```sql
        SELECT ????	
        FROM ????
        WHERE ??? = (SELECT ????	
                    FROM ????
                    WHERE ???)
    ```
				
1. Fer una consulta que que concateni com a minim tres camps de la base de dades i que tingui un calcul aritmètic. Com per exemple el que feiem servir per calcular l'edat. (Edat actor = ```year(Curdate()) - anyNaixement```) (**```<CognomNomDelAlumne>```**```_En_004.sql```)

1. Fer una consulta que vinculi com a minim tres taules diferents. (**```<CognomNomDelAlumne>```**```_En_005.sql```)

## Lliurament

El lliurament cal que el feu, creant un repositori privat al vostre compte de github i convidant a l'usuari **```joanpardogine```**.

El nom del repositori cal que sigui:
**```<CognomNomDelAlumne>```**```ActNadal```

Els noms dels fitxers caldrà que tinguin el següent format.
**```<CognomNomDelAlumne>```**```_En_001.sql```
I a l'interior de cada fitxer caldrà que feu apareixer **TOTA** la informació demanada.



|Alumne|Carpeta|Base de dades|Nom repositori|1r control|
|---|---|:---:|:---:|:---:|
|Armijo Carcamo, Benjamin Alonso|Armijo|A|||
|Bermudez, Xavier|Bermudez|C|||
|Bueno Arola, Max|Bueno|A|||
|Carbó Garcia, Marc|Carbo|Cv
|Corral Garcia, Pau|Corral|B|||
|De los Reyes Galban, Ismael|DeLosReyes|B|||
|De Paco Ripoll, Moisés|DePaco|A|||
|Garcia Fernández, Xavier|Garcia|C|||
|González Echeverria, Adrián|Gonzalez|A|||
|Manzano Vilà, Antonio|Manzano|B|||
|Martínez Martínez, Rubén|Martinez|B|||
|Mitu, George-Iulian|Mitu|C|||
|Peregrin Soler, Francesc|Peregrin|C|||
|Sedas Peña, Hugo|Sedas|C|||
|Sison Rius, Alex|Sison|C|||
|Subirà Viñas, César|Subira|C|||a
|Urquieta Cea, Cristian Ignacio|Urquieta|C|||
|Valle Pérez, Imanol|Valle|A|||
|Vilert Bertran, Pol|Vilert|A|||