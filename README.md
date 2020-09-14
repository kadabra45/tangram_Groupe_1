# tangram_Groupe_1

Objectif du projet : Construire un modèle apte à construire des modèles par lui-même à partir de tangrams pour un jeu pour enfants

Etapes du projet: 
- Enregistrement d'une vidéo de construction de modèles 
- Extraction des images constituant la vidéo et triage manuel de celle-ci pour ne retenir que les images contenant des modèles entiers. 
-Labellisation des images = déplacement des images correspondant à chaque modèle dans des dossiers portant les noms des modèles. Ces dossiers constitueront les classes du modèle. 
- Data Augmentation : Augmentation de la taille du dataset par diverses transformations des images avec la librairie Pillow.
- Preprocessing des images avant instanciation du modèle (réduction de la taille des pixels, division des dossiers contenant les images en diverses paquets pour les traiter séparément afin d'écononmiser les ressources de Google Collab). 
- Instanciation d'un CNN4, éventuellent d'un CNN3 selon les performances,avant et après Data Augmentation avec Keras.
- Paramètrage du modèle pour améliorer les performances


