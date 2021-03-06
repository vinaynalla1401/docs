---
title: "Activate Katalon Studio Enterprise"
sidebar: katalon_studio_docs_sidebar
permalink: katalon-studio/docs/activate-KSE.html
redirect_from:
    - "/katalon-studio/docs/katalon-studio-activation-since-70.html#activating-katalon-studio-enterprise"
    - "/katalon-studio/docs/katalon-studio-activation-since-70.html#other-options"
    - "/katalon-studio/docs/katalon-studio-activation-since-70.html#activating-katalon-studio-enterprise-trial-license"
description:
---
You need a license to activate Katalon Studio Enterprise (KSE) that can work with or without an Internet connection.

## Online Activation

You can activate KSE in an online environment with the [trial KSE license](/katalon-studio/docs/license.html), or an online license that grants permission to the registered users.

* Trial License: When you first download Katalon Studio version 7.0.0 and log in to your Katalon account, the trial license associated with your account is automatically activated. Each trial KSE license is tied to each Katalon account.
* Online License: Only the registered users who are added to the **Register Users** list can use online licenses.

In the **Katalon Studio Activation** window:

1. Enter the email and password registered for your Katalon account then click **Activate**.
2. You are navigated to your own organization, or you can select one of the organizations you belong to in the drop-down list, click **OK**.
3. You're recommended to install the plugins for a better experience with Katalon Studio.
4. Open an existing project or create a new one in Katalon Studio.
5. In Katalon TestOps Integration pop-up window:

* Select a team in the configured organization that you have permission to access.
* Select a project under that team you’d like to work on or create your own one if you have permission.

### Configuring proxy for online activation

If you're behind a Proxy Server, you need to configure the proxy settings before activating KSE. Click **Config Proxy** at the bottom of the Activation dialog box. In the Proxy Settings dialog box, you can select one of three options below.

* **Use system proxy configuration**: Katalon Studio tries to guess which proxy server your system is behind and sync with these settings.
* **No proxy**: there's no proxy.
* **Manual proxy configuration**: you can manually set up your proxy.

### Troubleshooting common issues with network

"_Network error! Please try Offline Activation_"- This error message indicates Katalon Studio's application cannot communicate with Katalon server to activate it.

Please check your Internet connection and try again. If you are behind a **Proxy Server**, please **Config Proxy** first and try to activate Katalon Studio again.

For Enterprise users with a private network, you may encounter a situation where you fail to execute test scripts or integrate Katalon Studio due to the network security error. Please contact your IT team to whitelist the following domains:

* store.katalon.com
* update.katalon.com
* analytics.katalon.com
* testops.katalon.com

## Offline Activation

A machine ID is required for generating an offline license. In the Katalon Studio Activation window, click **Offline Activation**:

1. **Generate an offline license**: Log in to [Katalon TestOps](https://analytics.katalon.com/home) > go to your organization > **License** > **Katalon Studio Enterprise** > **Create Offline License** > insert a **Machine ID** > click **Create**.

    > Notes:
    >
    >* Machine ID is granted for each computer installing Katalon Studio. In Katalon Studio Activation window, click **Offline Activation**, you can view and copy your machine ID.
    >* Only organizational owners or admins can access **License** in an organization. Learn more about [Roles and Permission](https://docs.katalon.com/katalon-analytics/docs/user-management.html#roles-and-default-permissions).

2. **Locate the generated license**: To use a license, click the **Download** button, the license will be downloaded as a `KSE_<machine_ID>.lic` file. Then click **Browse** in **Katalon Studio Enterprise Activation** to locate the downloaded license file.

3. Click **Activate**.

### Other options

After activating KSE, there will be a window requiring you to log in to your Katalon account for connecting to [Katalon TestOps](https://docs.katalon.com/katalon-studio/docs/katalon-analytics-beta-integration.html) and [Store](https://docs.katalon.com/katalon-store/docs/overview.html).

Currently, the KSE users can use [private plugins](https://docs.katalon.com/katalon-studio/docs/private-plugins.html) as an alternative option of using plugins from Katalon Store.

Regarding TestOps, there is currently no on-premises version; hence, the automatically generated [JUnit reports](https://docs.katalon.com/katalon-studio/docs/export-test-results-in-junit-format.html), and the [basic report plugin](https://docs.katalon.com/katalon-studio/docs/basic-report.html) can be a substitute for TestOps.
