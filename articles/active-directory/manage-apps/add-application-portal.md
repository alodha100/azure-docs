---
title: 'Quickstart: Add an application to your Azure Active Directory (Azure AD) tenant'
description: This quickstart uses the Azure portal to add a gallery application to your Azure Active Directory (Azure AD) tenant.
services: active-directory
author: kenwith
manager: celestedg
ms.service: active-directory
ms.subservice: app-mgmt
ms.topic: quickstart
ms.workload: identity
ms.date: 10/29/2019
ms.author: kenwith
ms.collection: M365-identity-device-management
---

# Quickstart: Add an application to your Azure Active Directory (Azure AD) tenant

Azure Active Directory (Azure AD) has a gallery that contains thousands of pre-integrated applications. Many of the applications your organization uses are probably already in the gallery. This quickstart uses the Azure portal to add a gallery application to your Azure AD tenant. This quickstart focuses on adding an app that is already part of the gallery. Apps that are not included in the gallery can also be integrated with Azure AD but that is not covered in this quickstart. 

After an application is added to your Azure AD tenant, you can:

- Configure properties for the app.
- Manage user access to the app with a Conditional Access policy.
- Configure single sign-on so users can sign in to the app with their Azure AD credentials.

## Prerequisites

To add an application to your Azure AD tenant, you need:

- An Azure account with an active subscription. [Create an account for free](https://azure.microsoft.com/free/?WT.mc_id=A261C142F).
- One of the following roles: Global Administrator, Cloud Application Administrator, Application Administrator, or owner of the service principal.
- (Optional: Completion of [View your apps](view-applications-portal.md)).

>[!IMPORTANT]
>We recommend using a non-production environment to test the steps in this quickstart.

## Add an app to your Azure AD tenant

To add a gallery application to your Azure AD tenant:

1. In the [Azure portal](https://portal.azure.com), on the left navigation panel, select **Azure Active Directory**.

1. In the **Azure Active Directory** pane, select **Enterprise applications**. The **All applications** pane opens and displays a random sample of the applications in your Azure AD tenant.

1. In the **Enterprise applications** pane, select **New application**. 

    ![Select New application to add a gallery app to your tenant](media/add-application-portal/new-application.png)

1. Switch to the new gallery preview experience: In the banner at the top of the **Add an application page**, select the link that says **Click here to try out the new and improved app gallery**.

1. The **Browse Azure AD Gallery (Preview)** pane opens and displays tiles for cloud platforms, on-premises applications, and featured applications. Applications listed in the **Featured applications** section have icons indicating whether they support federated single sign-on (SSO) and provisioning.

    ![Search for an app by name or category](media/add-application-portal/browse-gallery.png)

1. You can browse the gallery for the application you want to add, or search for the application by entering its name in the search box. Then select the application from the results. In the form, you can edit the name of the application to match the needs of your organization. In this example, we've changed the name to **GitHub-test**.

    ![Shows how to add an application from the gallery](media/add-application-portal/create-application.png)

1. Select **Create**. A getting started page appears with the options for configuring the application for your organization.

You've finished adding an application. The next quickstart shows you how to change the logo and edit other properties for your application.

## Next steps

- [Configure an app](add-application-portal-configure.md)
- [Set up single sign-on](add-application-portal-setup-sso.md)
- [Delete an app](delete-application-portal.md)