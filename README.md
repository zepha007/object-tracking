Suivi d'objets avec un téléphone portable

Ce projet présente un TP pratique visant à appréhender les notions fondamentales du suivi d'objets dans une séquence vidéo, à estimer la vitesse et la trajectoire en deux dimensions, ainsi qu'à analyser l'impact de la perspective et de la distance sur les mesures.

Objectifs et Matériel
L'objectif principal est d'observer le déplacement d'un objet simple filmé par un téléphone portable, puis d'analyser son mouvement image par image pour comprendre les principes de base de la vision par ordinateur et du traitement vidéo.

Étapes de l'exercice
Premièrement, la phase de capture vidéo a consisté à filmer un objet en mouvement avec une caméra fixe en faisant varier les vitesses et les directions de déplacement horizontal, vertical ou diagonal.

Deuxièmement, l'observation et l'annotation ont permis de noter image par image la position approximative de l'objet dans le cadre pour en tracer la trajectoire. Cette étape a mis en évidence que la taille de l'objet change selon sa distance par rapport à l'objectif, et que la position apparente évolue plus rapidement lorsque l'objet est proche de la caméra.

Troisièmement, l'analyse du mouvement a consisté à calculer approximativement la vitesse en pixels par image selon les différentes directions, en mettant en relief l'effet de la perspective qui fait qu'un objet plus éloigné semble se déplacer plus lentement.

Réponses aux questions d'analyse
Concernant la comparaison des méthodes, le suivi automatique offre l'avantage de la rapidité et du traitement de grands volumes d'images, mais il peut être mis en défaut par des variations de luminosité ou des changements d'échelle, tandis que le suivi manuel est précis mais très chronophage. Par ailleurs, si l'objet est partiellement masqué, l'algorithme ou l'observateur risque de perdre la trace de sa position exacte ou de confondre l'objet avec son environnement, ce qui nécessite des techniques de prédiction de trajectoire.

[![Ouvrir dans Colab] https://colab.research.google.com/drive/11SROnduHHg7642Ed8HC7Jn9k4N3e_N6W?usp=sharing
