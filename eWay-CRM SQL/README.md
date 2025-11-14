# Snippets

## SSMS

This folder contains SQL code snippets for server databases of eWay-CRM that can be used in Microsoft Management Studio.

## Azure Data Studio / VS Code

To use the snippets in the Azure Data Studio you need to convert them into the new format.

```
git clone https://github.com/eway-crm/VisualStudioSnippetConverter.git
cd VisualStudioSnippetConverter
code .
```

Run the application from the VS Code terminal. Change source directory path appropriately.

```
cd SnippetConverter
dotnet run "\Snippets\eWay-CRM SQL" -o "%APPDATA%\azuredatastudio\User\snippets\eWay-CRM SQL.code-snippets"
```

To get snippets in VS Code run the code bellow.
```
dotnet run "\Snippets\eWay-CRM SQL" -o "%APPDATA%\Code\User\snippets\eWay-CRM SQL.code-snippets"
```

You can also download the [pre-created](https://raw.githubusercontent.com/eway-crm/Snippets/refs/heads/master/eWay-CRM%20SQL/eWay-CRM%20SQL.code-snippets) version.

Instructions for Azure Data Studio on MacOS:
```
cd ~/Library/Application\ Support/azuredatastudio/User/snippets
wget https://raw.githubusercontent.com/eway-crm/Snippets/refs/heads/master/eWay-CRM%20SQL/eWay-CRM%20SQL.code-snippets
```
