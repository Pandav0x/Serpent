***************
 INTRODUCTION
***************

Ce programme se veut p�dagogique : il � �t� cr�er dans le but de faire d�couvrir
la programmation imp�rative par le biais d'appel de fonctions dans un ordre pr�cis.

***************
   PRINCIPE
***************

Le but est de faire atteindre la sortie du labyrinthe a la fleche qui est control�e par
l'utilisateur.
Le controle se fait par l'appel des fonctions suivantes :

	avance() => fait avancer la fleche vers la case ou elle pointe si cela est possible
	tourne_gauche() => fait tourner la fleche vers la gauche
	tourne_droite() => fait tourner la fleche vers la droite

L'arrivee est symbolis�e par un carr� vert, les chemins par des carr�s cr�mes et les murs
par des carr�s noirs.

	***************
   	   EDITION
	***************

L'�dition est la partie principale de ce programme, c'est elle qui d�termine le comportement
du programme.
Afin d'�diter ce comportement, ouvrez le fichier 'code.py' avec n'importe quel �diteur de texte brut.
J'enttend par la le bloc-note de windows, notepad++ ou n'importe quel �diteur de texte 'basique'.
(si vous n'en avez pas, vous pouvez en t�l�charger un ici : https://atom.io/download/windows)


***************
 CONFIGURATION 
***************


	***************	
 	 MODULES REQUIS
	***************
	
Ce programme est d�velopp� avec python 2.7, il n�c�ssite donc les outils suivants pour
son fonctionnement :

	- Python 2.7 (disponible ici : https://www.python.org/ftp/python/2.7.11/python-2.7.11.msi)
	
	- Pygame 1.9.1 (disponible ici : pygame.org/ftp/pygame-1.9.1.win32-py2.7.msi)

	
	***************
	 INSTALLATION
	***************

Une fois ces deux �l�ments t�l�charg�s, vous n'avez plus qu'� installer python 2.7 en premier
lieu, puis pygame une fois la pr�c�dente installation termin�e.
Ces deux installations ne sont que des installations 'Next next finish', vous n'avez
th�oriquement rien d'autre � faire que de cliquer sur 'suivant' quelques fois puis sur
'terminer'.


	***************
	 VERIFICATION
	***************

Afin de v�rifier que tout � correctement �t� installer, ouvrez la console windows
soit par le menu d�marrer > Tous les programmes > Accessoires > invite de commande
Soit par le racourcis [windows]+[r], entrez 'cmd' puis appuyez sur entrer.
Entrez ensuite la commande suivante :
	
	start python.exe

Si une nouvelle console s'ouvre, python � bien �t� install�. Sinon, r�installez-le.
Une fois cette nouvelle fen�tre ouverte, patientez jusqu'� ce que la derni�re ligne
affich�e soit '>>>' puis tapez les commandes suivantes :
	
	import pygame

	pygame.ver

Si le programme vous r�pond '1.9.1release', tout � correctement �t� install�. Sinon, si une erreur
survient lors de la r�alisation d'une de ces �tapes, recommencez l'installation.

***************
   EXECUTION
***************

Pour lancer le programe, vous n'aurez qu'� double-cliquer sur 'maze.py'.
Si cela de fonctionne pas, faite [shift]+[clique droit] dans le dossier o� se trouve maze.py et cliquer
sur 'ouvrir une fenetre de commande ici'.
Vous devrez alors taper le chemin absolu de votre executable python (par defaut C:\python27\python.exe)
un espace puis maze.py 
Votre console devrait ressembl�e � ceci 

C:\Users\Admin\Desktop\python>C:\python27\python.exe maze.py

appuyez sur entrer, vous n'aurez alors plus qu'� appuyer sur la fl�che du haut pour remettre cette ligne
et r�appuyer sur entrer

