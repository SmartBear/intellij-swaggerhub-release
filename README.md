# intellij-swaggerhub-release: Issue Tracker

[SwaggerHub extension for Intellij](https://plugins.jetbrains.com/) lets you view and edit OpenAPI definitions stored in [SwaggerHub](https://swagger.io/tools/swaggerhub/) directly from Intellij.

In this repository, you can:

:grey_question: Ask questions about the extension  
:bug: Report bugs  
:bulb: Suggest new features or enhancements  
:+1: Upvote existing requests  
:memo: Submit general feedback

Please search existing issues before opening a new one.

## Plugin Features
* View and navigate definitions from your SwaggerHub organizations.
* Edit and save definitions to SwaggerHub.
* Create new APIs and domains from scratch or using a template.
* Create new versions of your APIs and domains.
* Preview your APIs in Swagger UI.
* Delete definitions by the version or the entire definition.
* Validate your definitions against the OpenAPI 3.0 and 2.0 schemas.
* Add API mocks for quick definition testing

## Plugin Configuration
After downloading the zip file from the release page, please follow [install from disk](https://www.jetbrains.com/help/idea/managing-plugins.html#install_plugin_from_disk) instructions.

Before using the SwaggerHub extension, you need to configure its settings, after installation you will see the below panel

![Screen Shot 2021-05-17 at 14 31 48](https://user-images.githubusercontent.com/38886638/118497806-513fc380-b71d-11eb-8a71-7cd28ab47ca7.png)

Clicking the "Add First Organization" you will see the below modal

![Screen Shot 2021-05-17 at 14 32 06](https://user-images.githubusercontent.com/38886638/118498102-94019b80-b71d-11eb-9ded-71a75d213f74.png)

* *On-Prem address:* If you use SwaggerHub On-Premise, change the value to http(s)://YOUR_SERVER/v1. SwaggerHub SaaS users should leave the default value, https://api.swaggerhub.com.
* *Api Key:* Specify your SwaggerHub API key found at https://app.swaggerhub.com/settings/apiKey or at http(s)://YOUR_SERVER/settings/apiKey if you use SwaggerHub On-Premise.
* *User's organizations:* Add a list of SwaggerHub organizations that you want to access

## Resources
* [SwaggerHub documentation](https://app.swaggerhub.com/help/index): Learn more about SwaggerHub
* [OpenAPI syntax guide](https://swagger.io/docs/specification/basic-structure/): Learn how to write OpenAPI definitions

If you need help with SwaggerHub itself (not the Intellij extension), [contact Support](https://support.smartbear.com/message?product=SwaggerHub).
