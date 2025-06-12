# TMDL Extension for Visual Studio Code

A Visual Studio Code extension that adds rich language support for the **Tabular Model Definition Language (TMDL)**.
TMDL is a human-readable language designed for describing tabular models in Microsoft Fabric and Analysis Services.
→ [Learn more about TMDL](https://learn.microsoft.com/en-us/analysis-services/tmdl/tmdl-overview?view=asallproducts-allversions)
→ [Explore TMDL in Power BI](https://learn.microsoft.com/en-us/power-bi/transform-model/desktop-tmdl-view)
→ [Download from Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=analysis-services.TMDL)

---

## Features

* **Semantic Highlighting**: Enhances TMDL readability with context-aware syntax coloring.
* **Error Diagnostics**: Detects and highlights issues that may cause TMDL deserialization failures.
* **Auto Complete**: Offers intelligent suggestions for TMDL tokens.
* **Code Formatting**: Automatically formats code to ensure consistent structure.
* **Hover Support**: Displays detailed information for TMDL tokens on hover.
* **Code Actions**: Provides quick fixes and refactoring tools.
* **Breadcrumbs Navigation**: Visualizes the hierarchical structure of your TMDL file.
* **Power Query Support**:

  * Syntax highlighting
  * Inline diagnostics for syntax errors
  * Auto completion of tokens and functions
  * Smart formatting of embedded expressions
* **Localized Error Messages**: Adapts diagnostics to your editor’s language settings.
* ...and more features coming soon!


## Code Structure

| Directory           | Description                                         |
|---------------------|-----------------------------------------------------|
| Root                | Essential project files and documentation.         |
|                     | - `.gitignore`                                      |
|                     | - `CODE_OF_CONDUCT.md`                             |
|                     | - `LICENSE`                                         |
|                     | - `package.json`                                    |
|                     | - `README.md`                                       |
|                     | - `SECURITY.md`                                     |
|                     | - `SUPPORT.md`                                      |
|                     |
| .vscode             | VSCode-specific configuration files.                |
|                     | - `launch.json`                                     |
|                     |
| config              | Project configuration files.                        |
|                     | - `tmdl-configuration.json`                         |
|                     |
| syntaxes            | Syntax definition files.                            |
|                     | - `tmdl.tmLanguage.json`                            |


## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft 
trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.
