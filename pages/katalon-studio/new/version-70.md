---
title: "Version 7.0 (Beta)" 
sidebar: katalon_studio_docs_sidebar
permalink: katalon-studio/new/version-70.html
redirect_from:
    - "/katalon-studio/new/version-70/"
description: Release note 7.0 (beta)
---

## Version 7.0 (Beta)

> **Katalon Studio 7.0 (Beta)** is currently available. Click [here](https://github.com/katalon-studio/katalon-studio/releases) to download.

### New Features

* Support Custom Keywords refactoring. [Learn more](https://docs.katalon.com/katalon-studio/docs/custom-keywords-refactor.html).
* Support private plugins. [Learn more](https://docs.katalon.com/katalon-studio/docs/private-plugins.html).
* Support Windows 10 desktop application testing. See [Windows Desktop Apps Test Design](https://docs.katalon.com/katalon-studio/docs/introduction-desktop-app-testing.html).
* Support sharing test artifacts across projects. [Learn more](https://docs.katalon.com/katalon-studio/docs/import-export-test-artifact.html).
* Support Smart Wait function in a script and a project. See [[WebUI] Smart Wait Function](https://docs.katalon.com/katalon-studio/docs/webui-smartwait.html).
* Support [the WinAppDriver installation](https://docs.katalon.com/katalon-studio/docs/introduction-desktop-app-testing.html) and [`Terminate running WebDrivers`](https://docs.katalon.com/katalon-studio/docs/handle-webdrivers.html) options in Katalon Studio Tools.
* Support WebDriver event listeners. [Learn more](https://docs.katalon.com/katalon-studio/docs/webdriver-event-listeners.html).
* Support customizing the Console log. [Learn more](https://docs.katalon.com/katalon-studio/docs/working-with-execution-log.html).

### Improvements

* Add plugins reloading options to the Project Settings.
* Support parsing the Request Message's template from the associated `XSD` file when importing test objects from WSDL.
* Support adding the Organisation ID parameter to the Command Generator.
* Support selecting a Katalon TestOps's organization on the activation.
* Enhancement: Add some JVM options to reduce Katalon Studio's memory consumption.
* Support a hotkey of Spy Utility in Web Recorder to capture objects. [Learn more](https://docs.katalon.com/katalon-studio/docs/record-web-utility.html).
* Update **Quick Start** in Katalon Studio after activation.
* Support adding `.gitignore` and `build.gradle` files when creating a project.
* Support uploading reports with pdf, HTML, CSV formats (generated by Basic Report plugin) to Katalon TestOps. [Learn more](https://docs.katalon.com/katalon-studio/docs/katalon-analytics-beta-integration.html).
* Support submitting test run results with captured videos to Katalon TestOps. [Learn more](https://docs.katalon.com/katalon-studio/docs/katalon-analytics-beta-integration.html).
* Support uploading the `*.rp` file to Katalon TestOps to parse more information on test results.
* Support creating a test plan right from the test suite collection screen in Katalon Studio to enhance the integration of Katalon Studio with Katalon TestOps. [Learn more](https://docs.katalon.com/katalon-studio/docs/katalon-analytics-beta-integration.html).
* Support uploading Project Code from Katalon Studio to Katalon TestOps. [Learn more](https://docs.katalon.com/katalon-studio/docs/katalon-analytics-beta-integration.html).
* Update the integration mechanism with Katalon TestOps. [Learn more](https://docs.katalon.com/katalon-studio/docs/katalon-analytics-beta-integration.html).
* Update the integration configurations with Katalon TestOps when a new project is created.
* Support autofilling the input of [Katalon API Key](https://docs.katalon.com/katalon-studio/docs/katalon-apikey-70.html) in the command-line generator.
* Support generating test results in JUnit format.
* Support uploading reports of test suite collections to Katalon TestOps.
* Remove unnecessary information in the console log when users execute in the console mode for the first time.
* Support passing more information to the console mode execution with `--info -buildLabel="text" -buildURL="text"`. See [General Options ](https://docs.katalon.com/katalon-studio/docs/console-mode-execution.html#general-options) in Console Mode Execution.
* Upgrade the activation mechanism in Katalon Studio to seamlessly integrate with Katalon TestOps. See [Activate Katalon Studio](https://docs.katalon.com/katalon-studio/docs/katalon-studio-activation-since-70.html).
* Merge the Plugins menu into the Tools menu.
* Support MySQL Database version **8.0.17**.
* Support automatically reloading plugins when opening a project.

### Fixes

* Bug: [Mobile Testing] Cannot retry executing failed test cases.
* Bug: Web service response displays garbled text as non-latin characters.
* Bug: [Basic Report Plugin] CSV Report status is always Incomplete.
* Bug: The Log Viewer’s cursor incorrectly renders when selecting a log message.
* Bug: Newly added variables disappear after a switch from the Variable tab to another tab.
* Bug: An issue related to Variable binding when the data contains special characters.
* Bug: The Delay keyword doesn't work when the passing data is BigDecimal.
* Bug: Har files disappear after having been opened for the first time with the current Web Service object.
* Bug: [Custom Keyword] an issue related to the default package name when users create a keyword without entering a package name.
* Bug: [Katalon TestOps] Cannot navigate to the URL configured by users in View Execution History.
* Bug: [Katalon TestOps] an issue related to the error message when users create a new project for the invited team without permission.
* Bug: [GlobalVariable] Cannot execute a script with a profile that has a Global Variable with invalid syntax.
* Bug: [WebUI Keywords]  The `verifyElementPresent()` and `verifyElementNotPresent()` keywords should return `false` instead of throwing an exception when the verified elements do not exist.
* Bug: The `Delay between actions` fails to perform as configured.
* Bug: An issue causes `callTestCase` to fail.
* Bug: `findWebElements` fails when the `Default wait for element timeout` is set to 0 in the Execution Settings.
* Bug: [Web Recorder] An issue related to the `Cannot save entity: file path length limit exceeded.` error when saving test objects.
* Bug: Custom Keywords are not displayed in the Recent keywords after being used.
* Bug: An issue related to renaming a folder with uppercase or lowercase characters. [More details](https://github.com/katalon-studio/katalon-studio/issues/189).