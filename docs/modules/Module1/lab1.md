---
title: Tab App Using JavaScript
parent: Module 1 - Tab Apps
has_children: false
nav_order: 1

---

# Module 1 - Tab App Using JavaScript

In this tutorial, you learn:

- How to set up a new project with Teams Toolkit.
- How to build a tab app.
- The structure of the app:
  - The tab portion with JavaScript using React.
  - The rest of the features with Node.js.
- How to deploy your app.

## Create your tab project workspace

1. Open Visual Studio Code.

2. Select the Teams Toolkit ![icon](../../assets/images/module1/teams-toolkit-sidebar-icon.png) icon in the Visual Studio Code Activity Bar.

3. Select **Create a new app**.

4. Select **Create a new Teams app** to create an app using Teams Toolkit.

5. Ensure that **Tab** is selected as the capability that you want to build in your app. Select OK.
![Select Tab](../../assets/images/module1/select-tab.png)

6. Select **JavaScript** as the programming language.

7. Select **Default folder** to store your project root folder in default location

8. Enter **HelloWOrld** name for your app. Select **Enter**.
   The Teams tab app is created in a few seconds.
  ![Create Tab App](../../assets/images/module1/tap-app-created1.png)
9. After your app is created, Teams Toolkit displays the following message:![Local Debug](../../assets/images/module1/preview-project.png)
You can select **Local debug** to preview your project.
10. Use your Microsoft 365 account to sign in to Teams.
  1. Select the Teams Toolkit ![icon](../../assets/images/module1/teams-toolkit-sidebar-icon.png) icon in the sidebar.
  1. Select **Sign in to M365**.
  1. Return to Teams Toolkit within Visual Studio Code.
  1. The **ACCOUNTS** section of the sidebar shows your Microsoft 365 account name. Teams Toolkit displays **Sideloading enabled** if sideloading is enabled for your Microsoft 365 account ![Sideloading enabled](../../assets/images/module1/m365-sideloading-enabled.png).
11. To build and run your app locally, select F5 to run the application in debug mode.

12. Select Add when prompted to sideload the app onto Teams on your local machine.
  ![Add to Teams](../../assets/images/module1/add-tab-app-local-debug.png)

13. Congratulations, your first app is running on Teams!

## Deploy and run your app in Azure

1. Select the Teams Toolkit ![icon](../../assets/images/module1/teams-toolkit-sidebar-icon.png) icon

1. Select **Sign in to Azure**.

1. Close the browser when prompted and return to Visual Studio Code.

1. Select the Teams Toolkit ![icon](../../assets/images/module1/teams-toolkit-sidebar-icon.png) icon

1. Select **Provision in the Cloud**. ![Provision in the Cloud](../../assets/images/module1/provisioning-commands.png)

1. Select anyone of the existing subscription.

1. Select or create a **Resource Group** to use for the Azure resources.

1. Select **Provision**.

1. After a few minutes, you see the following notice:
![Provisioned](../../assets/images/module1/deploy-provision-successmsgext.png)

1. The provisioned resource appears in the **Environment** section.
![Environment](../../assets/images/module1/provisioned-resources-env.png)

1. Select **Deploy to the Cloud** from the **Deployment** panel after provisioning is complete.
![Deploy to the Cloud](../../assets/images/module1/deploy-cloud.png)

1. Open the debug panel (**Ctrl+Shift+D** / **⌘⇧-D or View > Run**) from Visual Studio Code.

1. Select **Launch Remote (Edge)** from the launch configuration drop-down.

1. Select the **Start debugging (F5)** to launch your app from Azure.
![Start Debugging](../../assets/images/module1/launch-remote.png)

1. Select **Add** when prompted to sideload the app onto Teams.

Congratulations, your first tab app is running in your Azure environment! 