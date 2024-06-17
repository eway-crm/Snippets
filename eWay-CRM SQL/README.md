# Snippets

## SSMS

This folder contains SQL code snippets for server databases of eWay-CRM that can be used in Microsoft Management Studio.

## Azure Data Studio

To use the snippets in the Azure Data Studio you need to convert them into the new format.

```
git clone https://github.com/eway-crm/VisualStudioSnippetConverter.git
cd VisualStudioSnippetConverter
code .
```

Run the application from the VS Code terminal. Change source directory path appropriately.

```
cd SnippetConverter
dotnet run "\Snippets\eWay-CRM SQL" -o "%APPDATA%\azuredatastudio\User\snippets\eWay-CRM SQL.json"
```
