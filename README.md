Api:

- L'objectif du projet étant de réaliser un outil de scoring permettant de prédire si un client pourrait rembourser son crédit (prédiction égale à 0), ou ne pourra pas rembourser son crédit (prédiction égale 1).
- un calcul de la probabilité d'accord ou de refus sera calculé en plus de la prédiction, au final le modèle sera traité sous forme d'api qui sera déployé sur le cloud via un outil approprié en l'occurence RENDER pour mon cas.
- Un nouveau repositery a été réalisé afin de donnéer le chemin à mon dossier où se trouve mon api, il s'agit du repositery Api_credit, on y trouve l'api nommé api_deploy.py,
  un notebook nommé api.ipynb pour l'appel de mon api et les tests, et enfin un fichier requests qui intègre tous les packages nécessaires pour le traitement du test.
- Enfin l'url de mon déploiment est enregistré dans mon notebook qui rélaise l'appel de mon api et le test sur les différents clients.
   
