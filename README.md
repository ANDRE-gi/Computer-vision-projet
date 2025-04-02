# Computer-vision-projet

Le cancer de la peau, et en particulier le mélanome, représente une menace sérieuse pour la santé mondiale en raison de sa capacité à évoluer rapidement et à devenir mortel s’il n’est pas détecté à temps. La détection précoce est donc cruciale pour améliorer les chances de survie des patients. Cependant, le diagnostic manuel par les dermatologues peut être sujet à des erreurs dues à la variabilité des lésions cutanées et à la charge de travail importante. Dans ce contexte, l’intelligence artificielle (IA), notamment les réseaux de neurones convolutionnels (CNN) et les techinques de vision par ordinateur offrent une solution prometteuse pour assister les professionnels de santé en automatisant et en améliorant la précision du diagnostic.
	
	L’objectif de ce projet est de:
	\begin{description}
		\item[$\bullet$] Développer un modèle de deep learning capable de classifier des images médicales selon plusieurs catégories (par exemple : lésions bénignes, malignes et indeterminées).
		
		\item[$\bullet$] Exploiter une architecture CNN pré-entraînée via le transfer learning afin de bénéficier de connaissances issues d’un vaste jeu de données.
		
		\item[$\bullet$] Optimiser le processus d’entraînement par des stratégies de régularisation, d’augmentation de données et de fine-tuning pour améliorer la robustesse et la précision du modèle.
		
		\item[$\bullet$] Fournir une analyse quantitative et qualitative permettant d’identifier les points forts et les limites de l’approche proposée.
	\end{description}
	
	%===============================
	%  Dataset 
	%===============================
	\section{Dataset}
	Pour ce projet, nous avons utilisé le dataset ISIC (International Skin Imaging Collaboration), une ressource largement reconnue dans le domaine de la dermatologie
