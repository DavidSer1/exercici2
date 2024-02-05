Exercici GIT 1: Creació i actualització de repositoris
David Serrano Mellinas
Centre: IES ENRIC VALOR (PEGO)
Curs 2023-2024
###INDEX
1.Exercici 1
2.Exercici 2
3.Exercici 3 Realitza un commit dels últims canvis amb el missatge "Afegit índex del llibre." i veure
l'estat del repositori.
4.Exercici 4
5.Exercici 5
###DESENVOLUPAMENT
##Exercici 1
Crea una nova branca bibliografia i mostrar les branques del repositori.
##Exercici 2
1. Crear el fitxer capítols/capitol4.txt i afegir el següent text
2. Afegir els canvis a la zona d'intercanvi temporal.
3. Fer un commit amb el missatge "Afegit capítol 4."
4. Mostrar la història del repositori incloent totes les branques.
##Exercici 3
1. Canvia a la branca bibliografia.
2. Crea el fitxer bibliografia.txt i afegir la següent referència
3. Afegeix els canvis a la zona d'intercanvi temporal.
4. Fes un commit amb el missatge "Afegida primera referència bibliogràfica."
5. Mostra la història del repositori incloent totes les branques.
##Exercici 4
1. Fusiona la branca bibliografia amb la branca master.
2. Mostra la història del repositori incloent totes les branques.
3. Elimina la branca bibliografia.
4. Mostra de nou la història del repositori incloent totes les branques.
##Exercici 5
1. Crea la branca bibliografia.
2. Canvia a la branca bibliografia.
3. Canvia el fitxer bibliografia.txt perquè continga les següents referències:
4. Afegeix els canvis a la zona d'intercanvi temporal i fer un commit amb el missatge
"Afegida nova referència bibliogràfica."
5. Canvia a la branca master.
6. Canvia el fitxer bibliografia.txt perquè continga les següents referències:
7. Afegeix els canvis a la zona d'intercanvi temporal i fer un commit amb el missatge
"Afegida nova referència bibliogràfica."
8. Fusiona la branca bibliografia amb la branca master.
9. Resol el conflicte deixant el fitxer bibliografia.txt amb les referències:
git merge bibliografia
10.Afegeix els canvis a la zona d'intercanvi temporal i fes un commit amb el missatge
"Resolt conflicte de bibliografia."
git add bibliografia.txt
git commit -m "Resolt conflicte de bibliografia."
611.Mostra la història del repositori incloent totes les branques.
git log --all --graph --decorate
78910
