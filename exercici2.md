Exercici GIT 1: Creació i actualització de repositoris
====================
David Serrano Mellinas
Centre: IES ENRIC VALOR (PEGO)
Curs 2023-2024
1.Exercici 1
2.Exercici 2
3.Exercici 3
4.Exercici 4
INDEX
***DESENVOLUPAMENT***
##Exercici 1
Mostra l'historial de canvis del repositori.
git log
Crea la carpeta capítols i dins d'ella crea el fitxer capitol1.txt amb el següent text:
mkdir capitols
echo "Git es un sistema de control de versiones ideat per Linus Torvalds" >
capitols/capitol1.txt
Afegeix els canvis a la zona d'intercanvi temporal (staging area)
git add capíiols/capitol1.txt
Fes un commit dels canvis amb el missatge "Afegit capítol 1."
git commit -m "Afegit capítol 1."
Torna a mostrar l'historial de canvis del repositori.
Git log
##Exercici 2
Crea el fitxer capitol2.txt a la carpeta capítols amb el següent text:
echo "El flux de treball bàsic amb Git consisteix en: 1- Fer canvis al repositori. 2-Afegit els canvis a
la zona d’intercanvi temoral. 2- Afegeix els canvis a la zona d'intercanvi temporal. 3Fer un
commit dels canvis."
Afegeix els canvis a la zona d'intercanvi temporal.
git add capitols/capitol2.txt
Fes un commit dels canvis amb el missatge "Afegit capítol 2."
git commit -m "Afegit capítol 2."
Mostra les diferències entre l'última versió i les dues versions anteriors.
git diff HEAD HEAD^ HEAD^^
##Exercici 3
Crea el fitxer capitol3.txt a la carpeta capítols amb el següent text:
echo "Git permet la creació de branques, la qual cosa permet tindre distintes versions del m ateix
projecte i treballar simultàniament en elles" > capitols/capitol3.txt
1. Afegeix els canvis a la zona d'intercanvi temporal.
git add capitols/capitol3.txt
2. Fes un commit dels canvis amb el missatge "Afegit capítol 3."
git commit -m "Afegit capítol 3."
3. Mostra les diferències entre la primera i l'última versió del repositori.
git diff HEAD^^ HEAD
##Exercici 4
1. Afegir al final del fitxer índex.txt la següent línia:
echo "Capitol 5: Conceptes avançats" >> índex.txt
2. Afegir els canvis a la zona d'intercanvi temporal.
git add index.txt
3. Fer un commit dels canvis amb el missatge "Afegit capítol 5 a l'índex."
git commit -m "Afegit capítol 5 a l'índex."
4. Mostrar qui ha fet canvis sobre el fitxer índex.txt.
git blame index.txt
6
