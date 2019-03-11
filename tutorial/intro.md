<!-- markdownlint-disable MD002 MD041 -->

<span data-ttu-id="83447-101">Ce didacticiel vous apprend à créer une application à page unique REACT qui utilise l'API Microsoft Graph pour récupérer des informations de calendrier pour un utilisateur.</span><span class="sxs-lookup"><span data-stu-id="83447-101">This tutorial teaches you how to build a React single-page app that uses the Microsoft Graph API to retrieve calendar information for a user.</span></span>

> [!TIP]
> <span data-ttu-id="83447-102">Si vous préférez télécharger simplement le didacticiel terminé, vous pouvez télécharger ou cloner le [référentiel GitHub](https://github.com/microsoftgraph/msgraph-training-reactspa).</span><span class="sxs-lookup"><span data-stu-id="83447-102">If you prefer to just download the completed tutorial, you can download or clone the [GitHub repository](https://github.com/microsoftgraph/msgraph-training-reactspa).</span></span>

## <a name="prerequisites"></a><span data-ttu-id="83447-103">Conditions requises</span><span class="sxs-lookup"><span data-stu-id="83447-103">Prerequisites</span></span>

<span data-ttu-id="83447-104">Avant de commencer ce didacticiel, [node. js](https://nodejs.org) doit être installé sur votre ordinateur de développement.</span><span class="sxs-lookup"><span data-stu-id="83447-104">Before you start this tutorial, you should have [Node.js](https://nodejs.org) installed on your development machine.</span></span> <span data-ttu-id="83447-105">Si vous n'avez pas node. js, consultez le lien précédent pour obtenir les options de téléchargement.</span><span class="sxs-lookup"><span data-stu-id="83447-105">If you do not have Node.js, visit the previous link for download options.</span></span>

> [!NOTE]
> <span data-ttu-id="83447-106">Ce didacticiel a été écrit avec le nœud version 10.7.0.</span><span class="sxs-lookup"><span data-stu-id="83447-106">This tutorial was written with Node version 10.7.0.</span></span> <span data-ttu-id="83447-107">Les étapes de ce guide peuvent fonctionner avec d'autres versions, mais cela n'a pas été testé.</span><span class="sxs-lookup"><span data-stu-id="83447-107">The steps in this guide may work with other versions, but that has not been tested.</span></span>

## <a name="feedback"></a><span data-ttu-id="83447-108">Commentaires</span><span class="sxs-lookup"><span data-stu-id="83447-108">Feedback</span></span>

<span data-ttu-id="83447-109">Veuillez fournir des commentaires sur ce didacticiel dans le [référentiel GitHub](https://github.com/microsoftgraph/msgraph-training-reactspa).</span><span class="sxs-lookup"><span data-stu-id="83447-109">Please provide any feedback on this tutorial in the [GitHub repository](https://github.com/microsoftgraph/msgraph-training-reactspa).</span></span>