# dummy-extension
Testing integration with Azure Pipelines 

[![Build Status](https://dev.azure.com/aws-scripting-guy/dummy-extension/_apis/build/status/Build%20Pipeline?branchName=master)](https://dev.azure.com/aws-scripting-guy/dummy-extension/_build/latest?definitionId=2?branchName=master)

## Snippet Sample

This is the source code for [Snippet Guide](https://vscode-ext-docs.azurewebsites.net/api/language-extensions/snippet-guide).

## VS Code API

### Contribution Points

- [`contributes.snippets`](https://vscode-ext-docs.azurewebsites.net/api/references/contribution-points#contributes.snippets)

## Running the Sample

- Run the `Run Extension` target in the Debug View
- When you type `log` in a JavaScript file, you would see the snippet `Print to console`.

## Publish extension 

- you can have multiple publishers
- have the 'publisher' field in your package.json filled 
- personal token with All Available Organizations scope 

```
vsce package
vsce publish -p <token> 
```
