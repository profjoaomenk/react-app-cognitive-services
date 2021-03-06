# React App x Cognitive Services

![](https://docs.microsoft.com/azure/developer/javascript/media/static-web-app/browser-screenshot-react-computervision-app-image-analysis-result.png)

## Features

The React (create-react-app) provides the following functionality: 
* Display message if Azure key and endpoint for Cognitive Services Computer Vision isn't found
* Allows you to analyze an image with Cognitive Services Computer Vision
    * Enter a public image URL or analyze image from collection
    * When analysis is complete
        * Display image
        * Display Computer Vision JSON results 

### Prerequisites

- [Node.js and npm](https://nodejs.org/en/download) - installed to your local machine
- [Visual Studio Code](https://code.visualstudio.com/) - installed to your local machine 
    - [Azure Static Web Apps (plugin)](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-azurestaticwebapps) - used to deploy React app to Azure Static Web app
- [Git](https://git-scm.com/downloads) - used to push to GitHub - which activates the GitHub action
- [GitHub account](https://github.com/join) - to fork and push to a repo
- Use [Azure Cloud Shell](https://docs.microsoft.com/azure/cloud-shell/quickstart) using the bash environment

- If you prefer, [install](https://docs.microsoft.com/cli/azure/install-azure-cli) the Azure CLI to run CLI reference commands
   - If you're using a local install, sign in with Azure CLI by using the [az login](https://docs.microsoft.com/cli/azure/reference-index#az-login) command.  To finish the authentication process, follow the steps displayed in your terminal.  See [Sign in with Azure CLI](https://docs.microsoft.com/cli/azure/authenticate-azure-cli) for additional sign-in options
  - When you're prompted, install Azure CLI extensions on first use.  For more information about extensions, see [Use extensions with Azure CLI](https://docs.microsoft.com/cli/azure/azure-cli-extensions-overview)
  - Run [az version](https://docs.microsoft.com/cli/azure/reference-index?#az_version) to find the version and dependent libraries that are installed. To upgrade to the latest version, run [az upgrade](https://docs.microsoft.com/cli/azure/reference-index?#az_upgrade)
