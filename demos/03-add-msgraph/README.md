# <a name="how-to-run-the-completed-project"></a>Exécution du projet terminé

## <a name="prerequisites"></a>Conditions requises

Pour exécuter le projet terminé dans ce dossier, vous avez besoin des éléments suivants:

- [Visual Studio](https://visualstudio.microsoft.com/vs/) installé sur votre ordinateur de développement. Si vous ne disposez pas de Visual Studio, reportez-vous au lien précédent pour obtenir les options de téléchargement. (**Remarque:** ce didacticiel a été écrit avec Visual Studio 2017 version 15,81. Les étapes de ce guide peuvent fonctionner avec d'autres versions, mais cela n'a pas été testé.)
- Soit un compte Microsoft personnel avec une boîte aux lettres sur Outlook.com, soit un compte professionnel ou scolaire Microsoft.

Si vous n'avez pas de compte Microsoft, vous disposez de deux options pour obtenir un compte gratuit:

- Vous pouvez vous [inscrire pour obtenir un nouveau compte Microsoft personnel](https://signup.live.com/signup?wa=wsignin1.0&rpsnv=12&ct=1454618383&rver=6.4.6456.0&wp=MBI_SSL_SHARED&wreply=https://mail.live.com/default.aspx&id=64855&cbcxt=mai&bk=1454618383&uiflavor=web&uaid=b213a65b4fdc484382b6622b3ecaa547&mkt=E-US&lc=1033&lic=1).
- Vous pouvez vous [inscrire au programme pour les développeurs office 365](https://developer.microsoft.com/office/dev-program) pour obtenir un abonnement gratuit à Office 365.

## <a name="register-a-web-application-with-the-application-registration-portal"></a>Enregistrer une application Web avec le portail d'inscription des applications

1. Ouvrez un navigateur et accédez au [portail d'inscription des applications](https://apps.dev.microsoft.com). Connectez-vous à l'aide d'un compte **personnel** (alias Microsoft) ou **compte professionnel ou scolaire**.

1. Sélectionnez **Ajouter une application** en haut de la page.

    > **Remarque:** Si vous voyez plus d'un bouton **Ajouter une application** sur la page, sélectionnez celui qui correspond à la liste **applications** convergées.

1. Sur la page **inscrire votre application** , définissez le **nom** de l'application sur **REACT Graph Tutorial** , puis sélectionnez **créer**.

    ![Capture d'écran de la création d'une nouvelle application dans le site Web du portail d'inscription des applications](/tutorial/images/arp-create-app-01.png)

1. Sur la page **d'inscription du didacticiel de graphique REACT** , dans la section **Propriétés** , copiez l' **ID d'application** , car vous en aurez besoin plus tard.

    ![Capture d'écran de l'ID de l'application nouvellement créée](/tutorial/images/arp-create-app-02.png)

1. Faites déFiler **** vers le bas jusqu'à la section plateformes.

    1. Sélectionnez **Ajouter une plateforme**.
    1. Dans la boîte de dialogue **Ajouter une plateforme** , sélectionnez **Web**.

        ![Capture d'écran création d'une plateforme pour l'application](/tutorial/images/arp-create-app-03.png)

    1. Dans la zone plateforme **Web** , entrez `http://localhost:3000` pour les **URL**de redirection.

        ![Capture d'écran de la plateforme Web récemment ajoutée pour l'application](/tutorial/images/arp-create-app-04.png)

1. Faites déFiler la page jusqu'en bas et sélectionnez **Enregistrer**.

## <a name="configure-the-sample"></a>Configurer l'exemple

1. Renommez `./graph-tutorial/src/Config.js.example` le fichier `./graph-tutorial/src/Config.js`.
1. Modifiez le `./graph-tutorial/src/Config.js` fichier et effectuez les modifications suivantes.
    1. Remplacez `YOUR_APP_ID_HERE` par l' **ID d'application** que vous avez obtenu à partir du portail d'inscription des applications.
1. Dans votre interface de ligne de commande (CLI), accédez au `graph-tutorial` répertoire et exécutez la commande suivante pour installer les conditions requises.

    ```Shell
    npm install
    ```

## <a name="run-the-sample"></a>Exécution de l’exemple

1. Exécutez la commande suivante dans votre interface CLI pour démarrer l'application.

    ```Shell
    npm start
    ```

1. Ouvrez un navigateur et accédez à `http://localhost:3000`.