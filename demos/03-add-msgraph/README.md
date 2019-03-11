# <a name="how-to-run-the-completed-project"></a><span data-ttu-id="9db13-101">Exécution du projet terminé</span><span class="sxs-lookup"><span data-stu-id="9db13-101">How to run the completed project</span></span>

## <a name="prerequisites"></a><span data-ttu-id="9db13-102">Conditions requises</span><span class="sxs-lookup"><span data-stu-id="9db13-102">Prerequisites</span></span>

<span data-ttu-id="9db13-103">Pour exécuter le projet terminé dans ce dossier, vous avez besoin des éléments suivants:</span><span class="sxs-lookup"><span data-stu-id="9db13-103">To run the completed project in this folder, you need the following:</span></span>

- <span data-ttu-id="9db13-104">[Visual Studio](https://visualstudio.microsoft.com/vs/) installé sur votre ordinateur de développement.</span><span class="sxs-lookup"><span data-stu-id="9db13-104">[Visual Studio](https://visualstudio.microsoft.com/vs/) installed on your development machine.</span></span> <span data-ttu-id="9db13-105">Si vous ne disposez pas de Visual Studio, reportez-vous au lien précédent pour obtenir les options de téléchargement.</span><span class="sxs-lookup"><span data-stu-id="9db13-105">If you do not have Visual Studio, visit the previous link for download options.</span></span> <span data-ttu-id="9db13-106">(**Remarque:** ce didacticiel a été écrit avec Visual Studio 2017 version 15,81.</span><span class="sxs-lookup"><span data-stu-id="9db13-106">(**Note:** This tutorial was written with Visual Studio 2017 version 15.81.</span></span> <span data-ttu-id="9db13-107">Les étapes de ce guide peuvent fonctionner avec d'autres versions, mais cela n'a pas été testé.)</span><span class="sxs-lookup"><span data-stu-id="9db13-107">The steps in this guide may work with other versions, but that has not been tested.)</span></span>
- <span data-ttu-id="9db13-108">Soit un compte Microsoft personnel avec une boîte aux lettres sur Outlook.com, soit un compte professionnel ou scolaire Microsoft.</span><span class="sxs-lookup"><span data-stu-id="9db13-108">Either a personal Microsoft account with a mailbox on Outlook.com, or a Microsoft work or school account.</span></span>

<span data-ttu-id="9db13-109">Si vous n'avez pas de compte Microsoft, vous disposez de deux options pour obtenir un compte gratuit:</span><span class="sxs-lookup"><span data-stu-id="9db13-109">If you don't have a Microsoft account, there are a couple of options to get a free account:</span></span>

- <span data-ttu-id="9db13-110">Vous pouvez vous [inscrire pour obtenir un nouveau compte Microsoft personnel](https://signup.live.com/signup?wa=wsignin1.0&rpsnv=12&ct=1454618383&rver=6.4.6456.0&wp=MBI_SSL_SHARED&wreply=https://mail.live.com/default.aspx&id=64855&cbcxt=mai&bk=1454618383&uiflavor=web&uaid=b213a65b4fdc484382b6622b3ecaa547&mkt=E-US&lc=1033&lic=1).</span><span class="sxs-lookup"><span data-stu-id="9db13-110">You can [sign up for a new personal Microsoft account](https://signup.live.com/signup?wa=wsignin1.0&rpsnv=12&ct=1454618383&rver=6.4.6456.0&wp=MBI_SSL_SHARED&wreply=https://mail.live.com/default.aspx&id=64855&cbcxt=mai&bk=1454618383&uiflavor=web&uaid=b213a65b4fdc484382b6622b3ecaa547&mkt=E-US&lc=1033&lic=1).</span></span>
- <span data-ttu-id="9db13-111">Vous pouvez vous [inscrire au programme pour les développeurs office 365](https://developer.microsoft.com/office/dev-program) pour obtenir un abonnement gratuit à Office 365.</span><span class="sxs-lookup"><span data-stu-id="9db13-111">You can [sign up for the Office 365 Developer Program](https://developer.microsoft.com/office/dev-program) to get a free Office 365 subscription.</span></span>

## <a name="register-a-web-application-with-the-application-registration-portal"></a><span data-ttu-id="9db13-112">Enregistrer une application Web avec le portail d'inscription des applications</span><span class="sxs-lookup"><span data-stu-id="9db13-112">Register a web application with the Application Registration Portal</span></span>

1. <span data-ttu-id="9db13-113">Ouvrez un navigateur et accédez au [portail d'inscription des applications](https://apps.dev.microsoft.com).</span><span class="sxs-lookup"><span data-stu-id="9db13-113">Open a browser and navigate to the [Application Registration Portal](https://apps.dev.microsoft.com).</span></span> <span data-ttu-id="9db13-114">Connectez-vous à l'aide d'un compte **personnel** (alias Microsoft) ou **compte professionnel ou scolaire**.</span><span class="sxs-lookup"><span data-stu-id="9db13-114">Login using a **personal account** (aka: Microsoft Account) or **Work or School Account**.</span></span>

1. <span data-ttu-id="9db13-115">Sélectionnez **Ajouter une application** en haut de la page.</span><span class="sxs-lookup"><span data-stu-id="9db13-115">Select **Add an app** at the top of the page.</span></span>

    > <span data-ttu-id="9db13-116">**Remarque:** Si vous voyez plus d'un bouton **Ajouter une application** sur la page, sélectionnez celui qui correspond à la liste **applications** convergées.</span><span class="sxs-lookup"><span data-stu-id="9db13-116">**Note:** If you see more than one **Add an app** button on the page, select the one that corresponds to the **Converged apps** list.</span></span>

1. <span data-ttu-id="9db13-117">Sur la page **inscrire votre application** , définissez le **nom** de l'application sur **REACT Graph Tutorial** , puis sélectionnez **créer**.</span><span class="sxs-lookup"><span data-stu-id="9db13-117">On the **Register your application** page, set the **Application Name** to **React Graph Tutorial** and select **Create**.</span></span>

    ![Capture d'écran de la création d'une nouvelle application dans le site Web du portail d'inscription des applications](/tutorial/images/arp-create-app-01.png)

1. <span data-ttu-id="9db13-119">Sur la page **d'inscription du didacticiel de graphique REACT** , dans la section **Propriétés** , copiez l' **ID d'application** , car vous en aurez besoin plus tard.</span><span class="sxs-lookup"><span data-stu-id="9db13-119">On the **React Graph Tutorial Registration** page, under the **Properties** section, copy the **Application Id** as you will need it later.</span></span>

    ![Capture d'écran de l'ID de l'application nouvellement créée](/tutorial/images/arp-create-app-02.png)

1. <span data-ttu-id="9db13-121">Faites déFiler \*\*\*\* vers le bas jusqu'à la section plateformes.</span><span class="sxs-lookup"><span data-stu-id="9db13-121">Scroll down to the **Platforms** section.</span></span>

    1. <span data-ttu-id="9db13-122">Sélectionnez **Ajouter une plateforme**.</span><span class="sxs-lookup"><span data-stu-id="9db13-122">Select **Add Platform**.</span></span>
    1. <span data-ttu-id="9db13-123">Dans la boîte de dialogue **Ajouter une plateforme** , sélectionnez **Web**.</span><span class="sxs-lookup"><span data-stu-id="9db13-123">In the **Add Platform** dialog, select **Web**.</span></span>

        ![Capture d'écran création d'une plateforme pour l'application](/tutorial/images/arp-create-app-03.png)

    1. <span data-ttu-id="9db13-125">Dans la zone plateforme **Web** , entrez `http://localhost:3000` pour les **URL**de redirection.</span><span class="sxs-lookup"><span data-stu-id="9db13-125">In the **Web** platform box, enter `http://localhost:3000` for the **Redirect URLs**.</span></span>

        ![Capture d'écran de la plateforme Web récemment ajoutée pour l'application](/tutorial/images/arp-create-app-04.png)

1. <span data-ttu-id="9db13-127">Faites déFiler la page jusqu'en bas et sélectionnez **Enregistrer**.</span><span class="sxs-lookup"><span data-stu-id="9db13-127">Scroll to the bottom of the page and select **Save**.</span></span>

## <a name="configure-the-sample"></a><span data-ttu-id="9db13-128">Configurer l'exemple</span><span class="sxs-lookup"><span data-stu-id="9db13-128">Configure the sample</span></span>

1. <span data-ttu-id="9db13-129">Renommez `./graph-tutorial/src/Config.js.example` le fichier `./graph-tutorial/src/Config.js`.</span><span class="sxs-lookup"><span data-stu-id="9db13-129">Rename the `./graph-tutorial/src/Config.js.example` file to `./graph-tutorial/src/Config.js`.</span></span>
1. <span data-ttu-id="9db13-130">Modifiez le `./graph-tutorial/src/Config.js` fichier et effectuez les modifications suivantes.</span><span class="sxs-lookup"><span data-stu-id="9db13-130">Edit the `./graph-tutorial/src/Config.js` file and make the following changes.</span></span>
    1. <span data-ttu-id="9db13-131">Remplacez `YOUR_APP_ID_HERE` par l' **ID d'application** que vous avez obtenu à partir du portail d'inscription des applications.</span><span class="sxs-lookup"><span data-stu-id="9db13-131">Replace `YOUR_APP_ID_HERE` with the **Application Id** you got from the App Registration Portal.</span></span>
1. <span data-ttu-id="9db13-132">Dans votre interface de ligne de commande (CLI), accédez au `graph-tutorial` répertoire et exécutez la commande suivante pour installer les conditions requises.</span><span class="sxs-lookup"><span data-stu-id="9db13-132">In your command-line interface (CLI), navigate to the `graph-tutorial` directory and run the following command to install requirements.</span></span>

    ```Shell
    npm install
    ```

## <a name="run-the-sample"></a><span data-ttu-id="9db13-133">Exécution de l’exemple</span><span class="sxs-lookup"><span data-stu-id="9db13-133">Run the sample</span></span>

1. <span data-ttu-id="9db13-134">Exécutez la commande suivante dans votre interface CLI pour démarrer l'application.</span><span class="sxs-lookup"><span data-stu-id="9db13-134">Run the following command in your CLI to start the application.</span></span>

    ```Shell
    npm start
    ```

1. <span data-ttu-id="9db13-135">Ouvrez un navigateur et accédez à `http://localhost:3000`.</span><span class="sxs-lookup"><span data-stu-id="9db13-135">Open a browser and browse to `http://localhost:3000`.</span></span>