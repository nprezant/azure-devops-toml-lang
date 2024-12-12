# TOML language support in Azure Devops

## Contributing

Copy the language variable out of `vss-extension.json` and paste into the [monaco monarch editor](https://microsoft.github.io/monaco-editor/monarch.html). Copy changes you like back into `vss-extension.json`.

Useful links
- https://github.com/microsoft/azure-devops-extension-sample/tree/master/src/Examples/CodeEditorContribution
- https://github.com/jincao1/perl-syntax-ado/tree/main
- https://learn.microsoft.com/en-us/azure/devops/extend/get-started/node?view=azure-devops

## Publishing

[Instructions here](https://learn.microsoft.com/en-us/azure/devops/extend/publish/overview?view=azure-devops)

1. npm install -g tfx-cli
1. Bump version
1. npx tfx-cli extension create
1. Upload to https://marketplace.visualstudio.com/manage/publishers/

## Credits

Original monaco toml language found [here](https://github.com/ota-meshi/site-kit/blob/main/packages/site-kit-monarch-syntaxes/src/languages/toml.ts)
