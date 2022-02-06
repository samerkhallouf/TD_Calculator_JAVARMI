# TD_Calculator_JAVARMI!
[Calculator_TD](https://user-images.githubusercontent.com/80248505/152502791-1d935a75-9758-46fc-add2-c04c9d542644.png)
L'interface "Calculator" n'est autre que le contrat: on definit dans cette interface java les methodes qui devront être exportées.

1- La première étape consiste à démarrer le Naming service sur le port 1099( port par défaut) en démarrant rmiregistry

2- La deuxième étape consiste à démarrer le serveur(CalculatorServer) qui fait un rebing pour changer le nom rmiregsitry de l'objet instance de la classe CalculatorImpl.

3- La troisième étape consiste à démarrer l'application client qui fait un lookup dynamique du nom indiqué pour obtenir le stub et ensuite invoquer les méthodes désirées qui seront exécutées du côté du serveur
