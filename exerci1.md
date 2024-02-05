Exercici GIT 1: Creació i actualització de repositoris
====================
David Serrano Mellinas
Centre: IES ENRIC VALOR (PEGO)
Curs 2023-2024
1.Exercici 1
2.Exercici 2
3.Exercici 3
4.Exercici 4
5.Exercici 5
***DESENVOLUPAMENT ***
 ##Exercici 1
➢
Crea un repositori nou amb el nom llibre i mostrar el seu contingut.
Mkdir llibre cd llibre git init ls -a
➢
Configura Git definint el nom de l'usuari, el correu electrònic i activar l'exida en
color. Mostrar la configuració final.
*git config --global user.name "David"
*git config --global user.email "david@gmail.com"
git config --global color.ui auto
➢
➢
➢
➢
➢
Exercici 2
Comprova l'estat del repositori. git status
Crea un fitxer índex.txt amb el següent contingut:
Comprova de nou l'estat del repositori. git status
Afegeix el fitxer a la zona d'intercanvi temporal. Gid add intex.txt
Tornar a comprovar una vegada més l'estat del repositori. git status
3Exercici 3
Realitza un commit dels últims canvis amb el missatge "Afegit índex del llibre." i veure l'estat del
repositori.
git commit -m "Afegit índex del llibre."
git status
Exercici 4
➢ Canvia el fitxer índex.txt perquè continga el següent:
➢Mostra els canvis respecte a l'última versió guardada al repositori.
git diff
➢Fer un commit dels canvis amb el missatge "Afegit capítol 3 sobre gestió de
branques".
git add index.txt
git commit -m "Afegit capítol 3 sobre gestió de branques"
4Exercici 5
➢Mostrar els canvis de l'última versió del repositori respecte a l'anterior. git log
➢Canviar el missatge de l'últim commit a "Afegit capítol 3 sobre gestió de branques a
l'índex."
git diff HEAD^ HEAD
git commit --amend -m "Afegit capítol 3 sobre gestió de branques a l'índex."
➢
git log
Tornar a mostrar els últims canvis del repositori.
git diff HEAD^ HEAD
5Exercici 6
Indica a Git que vols ignorar tots els fitxers que comencen per "daw", tots els que tenen
l'extensió out i les imatges (jpg, png, bmp i gif).
echo "daw*" > .gitignore
echo "*.out" >> .gitignore
echo "*.jpg" >> .gitignore
echo "*.png" >> .gitignore
echo "*.bmp" >> .gitignore
echo "*.gif" >> .gitignore
git add .gitignore
git commit -m "Afegit arxiu .gitignore amb les especificacions d'ignorar
fitxers."
6
