# Installation
Ce guide explique comment installer et configurer les bots vendus ou loués par **Code Works**.

## Pour les bots achetés
1. **Réception du bot**  
   Après l'achat, vous recevrez un message privé de Code Works contenant un lien **MediaFire** pour télécharger les fichiers du bot.

2. **Création de l'application Discord**  
   * Rendez-vous sur le [Discord Developer Portal](https://discord.com/developers/applications).  
   * Cliquez sur **"New Application"** pour créer une nouvelle application.  
   * Donnez un nom à votre application et confirmez.  
   * Dans l'onglet **"Installation"**, dans la section **"Install Link"**, sélectionnez **None**.  
   * Dans l'onglet **"Bot"**, décochez la case **"Public Bot"**.

3. **Activation des intents**  
   Dans l'onglet **"Bot"** :  
   * Activez les 3 intents suivants :  
     * Presence Intent  
     * Server Members Intent  
     * Message Content Intent

4. **Gestion du token**  
   * Cliquez sur **"Reset Token"** pour générer un nouveau token sécurisé.  
   * Copiez ce token.

5. **Configuration du bot**  
   * Ouvrez le fichier `.env` dans les fichiers du bot téléchargés.  
   * Collez votre token Discord dans la variable prévue (exemple : `TOKEN=VOTRE_TOKEN_ICI`).  
   * Sauvegardez le fichier.

6. **Ajout du bot au serveur Discord**  
   * Retournez dans le Discord Developer Portal, onglet **"OAuth2"**, puis **"URL Generator"**.  
   * Cochez la case **"bot"** dans les scopes.  
   * Dans les permissions, sélectionnez **"Administrator"** (ou les permissions requises).  
   * Copiez le lien généré en bas.  
   * Ouvrez ce lien dans un navigateur et ajoutez le bot à votre serveur Discord.

7. **Démarrage du bot**  
   * Lancez le bot sur votre machine ou hébergement.  
   * Votre bot est maintenant opérationnel.

## Pour les bots loués
1. **Création de l'application Discord**  
   * Comme pour un bot acheté, vous devez créer une application Discord sur le [Discord Developer Portal](https://discord.com/developers/applications).  
   * Activez les 3 intents nécessaires (Presence Intent, Server Members Intent, Message Content Intent).  
   * Générez un token via **"Reset Token"** et copiez-le.  
   * Pensez aussi à mettre **Install link** sur **None** dans l'onglet "**Installation**" et décocher **Public Bot** dans l'onglet **Bot**.

2. **Ajout du bot au serveur Discord**  
   * Utilisez l’onglet **"OAuth2"** → **"URL Generator"** pour générer un lien d’invitation avec le scope **"bot"** et la permission **"Administrator"**.  
   * Ajoutez le bot à votre serveur via ce lien.

3. **Communication du token**  
   * Envoyez le token généré au staff Code Works via le canal Discord **#gestion-locations**.  
   * Le staff configurera et démarrera le bot hébergé pour vous avec ce token.

## Support et contact
Pour toute question ou problème concernant l’installation ou la location/achat des bots, veuillez contacter le staff de Code Works dans le salon **#「🎫」tickets** ou via message privé.

## Liens utiles
* Serveur Discord Code Works : [Invitation](https://discord.gg/8X25qRmUh2)  

* Contact direct : [@matrax.dev](https://discord.com/users/1235588660854915132)  
