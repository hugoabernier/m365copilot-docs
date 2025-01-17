---
title: Set up your dev environment to build message extension plugins for Microsoft Copilot for Microsoft 365
description: Prerequisites to build your first message extension plugin for Microsoft Copilot for Microsoft 365
author: girliemac
ms.author: timura
ms.topic: overview
ms.date: 11/15/2023
---

# Set up your dev environment to build message extension plugins for Microsoft Copilot for Microsoft 365

[!INCLUDE [preview-disclaimer](includes/preview-disclaimer.md)]

Before you get started to build a search-based message extension plugin for Copilot, make sure that Copilot for Microsoft 365 is available for your organization. You have two ways to get a developer environment for Copilot: (1) with a sandbox Microsoft 365 tenant with Copilot (available in limited preview through [TAP membership](prerequisites#isv-partners-in-microsoft-365-developer-tap)), or with (2) through an enterprise customer production environment with Microsoft Copilot for Microsoft 365 licenses.

Read the general requirements at [Your development environment for Microsoft Copilot for Microsoft 365 extensibility](prerequisites.md) for more.

## Set up your Teams development tenant

A **tenant** is like a space, or a container for your organization in Microsoft Teams, where you chat, share files, and run meetings. This space is also where your *sideload* (installing and testing your app directly into your Teams environment for development) and test your app. Let's check if you're ready to develop with the tenant.
Do you already have a tenant, and do you have the admin access? Let's check if you really do!

In the Teams client,

1. Select the **Apps** icon
1. Select **Manage your apps**
1. Select **Upload an app**
1. Look for the option to **Upload a custom app**. If you see the option, sideloading apps is enabled!

:::image type="content" source="assets/images/build-me/sideloadable.png" alt-text="A screenshot of Teams client that shows how to check if your custom app is sideloadable":::

If you don't have the option to upload a custom app, talk to your Teams administrator.

## Install prerequisites to your machine

Now make sure you install the following tools for building and deploying your apps:

- [Visual Studio Code](https://code.visualstudio.com/download) latest version
- [Node.js](https://nodejs.org/en/download/) v14.x, v16.x or v18.x
- [Microsoft Team client](https://www.microsoft.com/microsoft-teams/download-app)
- [Microsoft Edge](https://www.microsoft.com/edge)(recommended) or [Google Chrome](https://www.google.com/chrome/)

## Install Teams Toolkit to Visual Studio Code

The Teams Toolkit helps simplify the development process with tools to provision and deploy cloud resources for your app, publish to the Teams Store, and more.

You can use the toolkit with VS Code (Visual Studio Code), or CLI (command-line interface) called `TeamsFx`. Let's install both tools now.

1. Open VS Code and select the **Extensions** view (**Ctrl+Shift+X** / **⌘⇧-X** or **View > Extensions**).
1. In the search box, enter **Teams Toolkit**.
1. Select **Install** next to the Teams Toolkit.

:::image type="content" source="assets/images/build-me/install-toolkit-vscode.png" alt-text="A screenshot of VS Code that shows how to install Teams Toolkit extension":::

The Teams Toolkit :::image type="icon" source="assets/icons/teams-toolkit-sidebar-icon.png"::: icon appears in the VS Code **Activity Bar** after it's installed.

You can also find the Teams Toolkit on the [Visual Studio Code Marketplace](https://marketplace.visualstudio.com/items?itemName=TeamsDevApp.ms-teams-vscode-extension).

Now you are ready to build your first message extension plugin for Copilot!

## Next step

Follow the step-by-step guides to build your first message extension plugin:

> [!div class="nextstepaction"]
> [Build your first message extension plugin for Copilot](/microsoftteams/platform/messaging-extensions/build-bot-based-plugin?tabs=visual-studio&context=/microsoft-365-copilot/extensibility/context)
