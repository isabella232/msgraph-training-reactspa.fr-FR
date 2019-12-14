# <a name="how-to-run-the-completed-project"></a>Exécution du projet terminé

## <a name="prerequisites"></a>Conditions préalables

Pour exécuter le projet terminé dans ce dossier, vous avez besoin des éléments suivants :

- [Node. js](https://nodejs.org) installé sur votre ordinateur de développement. Si vous n’avez pas node. js, consultez le lien précédent pour obtenir les options de téléchargement. (**Remarque :** ce didacticiel a été écrit avec le nœud version 10.15.3. Les étapes de ce guide peuvent fonctionner avec d’autres versions, mais cela n’a pas été testé.)
- Soit un compte Microsoft personnel avec une boîte aux lettres sur Outlook.com, soit un compte professionnel ou scolaire Microsoft.

Si vous n’avez pas de compte Microsoft, vous disposez de deux options pour obtenir un compte gratuit :

- Vous pouvez vous [inscrire pour obtenir un nouveau compte Microsoft personnel](https://signup.live.com/signup?wa=wsignin1.0&rpsnv=12&ct=1454618383&rver=6.4.6456.0&wp=MBI_SSL_SHARED&wreply=https://mail.live.com/default.aspx&id=64855&cbcxt=mai&bk=1454618383&uiflavor=web&uaid=b213a65b4fdc484382b6622b3ecaa547&mkt=E-US&lc=1033&lic=1).
- Vous pouvez vous [inscrire au programme pour les développeurs office 365](https://developer.microsoft.com/office/dev-program) pour obtenir un abonnement gratuit à Office 365.

## <a name="register-a-web-application-with-the-azure-active-directory-admin-center"></a>Enregistrer une application Web avec le centre d’administration Azure Active Directory

1. Ouvrez un navigateur et accédez au [Centre d’administration Azure Active Directory](https://aad.portal.azure.com). Connectez-vous à l’aide d’un **compte personnel** (compte Microsoft) ou d’un **compte professionnel ou scolaire**.

1. Sélectionnez **Azure Active Directory** dans le volet de navigation gauche, puis sélectionnez **Inscriptions d’applications** sous **Gérer**.

    ![Capture d’écran des inscriptions d’application ](/tutorial/images/aad-portal-app-registrations.png)

    > **Remarque :** Les utilisateurs Azure AD B2C peuvent uniquement voir les **inscriptions des applications (héritées)**. Dans ce cas, accédez directement à [https://aka.ms/appregistrations](https://aka.ms/appregistrations).

1. Sélectionnez **Nouvelle inscription**. Sur la page **Inscrire une application**, définissez les valeurs comme suit.

    - Définissez le **Nom** sur `React Graph Tutorial`.
    - Définissez les **Types de comptes pris en charge** sur **Comptes dans un annuaire organisationnel et comptes personnels Microsoft**.
    - Sous **URI de redirection**, définissez la première flèche déroulante sur `Web`, et la valeur sur `http://localhost:3000`.

    ![Capture d’écran de la page inscrire une application](/tutorial/images/aad-register-an-app.png)

1. Choisissez **Inscrire**. Sur la page **didacticiel de graphique angulaire** , copiez la valeur de l' **ID d’application (client)** et enregistrez-la, vous en aurez besoin à l’étape suivante.

    ![Capture d’écran de l’ID d’application de la nouvelle inscription de l’application](/tutorial/images/aad-application-id.png)

1. Sous **Gérer**, sélectionnez **Authentification**. Recherchez la section **Grant implicite** et activez les **jetons d’accès** et les **jetons ID**. Cliquez sur **Enregistrer**.

    ![Capture d’écran de la section Grant implicite](/tutorial/images/aad-implicit-grant.png)

## <a name="configure-the-sample"></a>Configurer l’exemple

1. Renommez `./graph-tutorial/src/Config.js.example` le fichier `./graph-tutorial/src/Config.js`.
1. Modifiez le `./graph-tutorial/src/Config.js` fichier et effectuez les modifications suivantes.
    1. Remplacez `YOUR_APP_ID_HERE` par l' **ID d’application** que vous avez obtenu à partir du portail d’inscription des applications.
1. Dans votre interface de ligne de commande (CLI), accédez au `graph-tutorial` répertoire et exécutez la commande suivante pour installer les conditions requises.

    ```Shell
    npm install
    ```

## <a name="run-the-sample"></a>Exécution de l’exemple

1. Exécutez la commande suivante dans votre interface CLI pour démarrer l’application.

    ```Shell
    npm start
    ```

1. Ouvrez un navigateur et accédez à `http://localhost:3000`.
