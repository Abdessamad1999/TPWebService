# TPWebService

## Web service - Partie 1 :

Dans cete partie on va créer un web service qu'on appelle 'BanqueWS',
puis on va créer le serveur JaxWS qui déployé le web service 'BanqueWS' et on va créer aussi une classe qu'on appelle Compte.

Après on va lancer le Serveur JaxWS, puis on va ouvrir le serveur dans le browser
Voici le WSDL (format XML) :

<img width="479" alt="Capture d’écran (31)" src="https://user-images.githubusercontent.com/83142853/163492003-5874de57-44fc-4df3-a6d1-23dddd9d9070.png">

Après on va tester le web serveur à l'aide de SoapUI:
- tester la méthode ConversionEuroToDH

![Capture d’écran (33)](https://user-images.githubusercontent.com/83142853/163492120-26ecf053-6488-4029-bdc9-100270442aba.png)

- tester la méthode getCompte

![Capture d’écran (34)](https://user-images.githubusercontent.com/83142853/163492179-a872dbbe-e01d-43e9-81d3-ae87fa02bf67.png)


- tester la méthode listComptes

![Capture d’écran (35)](https://user-images.githubusercontent.com/83142853/163492194-88d333b5-4c9a-4c98-9797-28e94ed18416.png)

- tester la méthode getCompte après la modification

![Capture d’écran (38)](https://user-images.githubusercontent.com/83142853/163492317-58678d66-972f-410f-95fb-68e36f7a00fe.png)
