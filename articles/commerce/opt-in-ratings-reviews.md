---
# required metadata

title: Opt in to use ratings and reviews 
description: This topic explains how to opt in to use ratings and reviews on your Microsoft Dynamics 365 Commerce site.
author:  gvrmohanreddy 
manager: annbe
ms.date: 10/01/2019
ms.topic: article
ms.prod: 
ms.service: dynamics-ax-retail
ms.technology: 

# optional metadata

# ms.search.form: 
# ROBOTS: 
audience: Application User
# ms.devlang: 
ms.reviewer: v-chgri
ms.search.scope: Retail, Core, Operations
# ms.tgt_pltfrm: 
ms.custom: 
ms.assetid: 
ms.search.region: Global
ms.search.industry: 
ms.author: gmohanv
ms.search.validFrom: 2019-10-31
ms.dyn365.ops.version: Release 10.0.5
---

# Opt in to use ratings and reviews

[!include [banner](includes/preview-banner.md)]
[!include [banner](includes/banner.md)]

This topic explains how to opt in to use ratings and reviews on your Microsoft Dynamics 365 Commerce site.

## Overview

The ratings and reviews solution is an omnichannel solution that you can make available in Dynamics 365 Commerce by using Microsoft Dynamics Lifecycle Services (LCS). LCS is an administration portal that retailers use to manage their environments from provisioning to decommissioning.

If you want to use the ratings and reviews solution on your Commerce website, you must first opt in.

## Opt in to use ratings and reviews

To opt in to use ratings and reviews on your site, follow these steps.

1. Follow the steps in [Deploy a new e-Commerce site](deploy-ecommerce-site.md).
2. While you're still in LCS, go to **Retail deployment setup \> Other settings**.
3. Set the **Enable ratings and reviews service** option to **Yes**.
4. In the **AAD security group for ratings and review moderator (security group object id)** field, enter the ID of the Microsoft Azure Active Directory (Azure AD) security group that includes the ratings and reviews moderators.

    ![Opt in to use ratings and reviews](media/LCS_RnR_Preference.png)

5. Complete the e-Commerce initialization process.
