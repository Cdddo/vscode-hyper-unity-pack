# Hyper Unity Extension Pack

This extension pack includes various useful tools for working with Unity3D in Visual Studio Code.

## Essential Extensions

- [C# for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csharp) - Enables C# language syntax highlighting, intellisense, and other OmniSharp features.

## Unity Tools

- [Debugger for Unity](https://marketplace.visualstudio.com/items?itemName=Unity.unity-debug) - Enables debugging Unity projects.

- [Unity Code Snippets Newline](https://marketplace.visualstudio.com/items?itemName=Cdddo.unity-code-snippets-newline) - Code faster with this snippet collection including all Unity methods with included XML documentation.

- [Unity Event Lens](https://marketplace.visualstudio.com/items?itemName=dgileadi.unity-event-lens) - Enable CodeLens to show references for UnityEvents that are configured in the inspector.

- [Unity Tools](https://marketplace.visualstudio.com/items?itemName=Tobiah.unity-tools) - Adds commands to search and open the Unity and Microsoft documentation, as well as the ability to generate preset folders for organizing your project.

## General Coding Tools

- [Error Lens](https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens) - Makes error fixing easier by highlighting the entire line and showing the diagnostic message inline.

- [Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments) - Helps to categorise your comments with custom styling.

- [Live Share](https://marketplace.visualstudio.com/items?itemName=ms-vsliveshare.vsliveshare) - Enables you to collaboratively edit and debug with others in real time.

- [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens) - Helps you to navigate and explore Git repositories, visualize code authorship, view file history and compare file versions, among other features.

- [Setting Toggle](https://marketplace.visualstudio.com/items?itemName=Ho-Wan.setting-toggle) - Adds buttons to let you toggle up to 3 custom VS Code settings.

## File Support

- [Markdown Lint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint) - Styling rules to encourage standards and consistency for Markdown files.

- [Edit CSV](https://marketplace.visualstudio.com/items?itemName=janisdd.vscode-edit-csv) - Allows you to edit csv (comma separated values) files with an Excel-like table UI.

- [Yarn Spinner Support](https://marketplace.visualstudio.com/items?itemName=SecretLab.yarn-spinner) - [Yarn Spinner](https://yarnspinner.dev) is an open source tool that helps you build branching narrative and dialogue in games. This extension adds support for the Yarn Spinner dialogue language used in .yarn files.

## Recommended Settings

Add these to your settings.json

// Files
"files.associations": { "*.jslib": "javascript" },

// Code Formatting
"editor.guides.bracketPairs": "active",
"editor.bracketPairColorization.enabled": true,
"editor.formatOnType": true,
"editor.formatOnPaste": true,
"omnisharp.organizeImportsOnFormat": true,

// Editor
"workbench.editor.highlightModifiedTabs": true,
"editor.renderControlCharacters": true,
"editor.renderLineHighlight": "all",
"editor.stickyTabStops": true,
"editor.codeLens": true,
"editor.suggest.preview": true,

// Diagnostics
"csharp.suppressHiddenDiagnostics": false,
"omnisharp.enableRoslynAnalyzers": true,
"omnisharp.analyzeOpenDocumentsOnly": true,

// Inlay Hints
"editor.inlayHints.enabled": "on",
"csharp.inlayHints.parameters.enabled": true,
"csharp.inlayHints.parameters.forIndexerParameters": true,
"csharp.inlayHints.parameters.forLiteralParameters": true,
"csharp.inlayHints.parameters.forObjectCreationParameters": true,
"csharp.inlayHints.parameters.forOtherParameters": true,
"csharp.inlayHints.parameters.suppressForParametersThatMatchArgumentName": true,
"csharp.inlayHints.parameters.suppressForParametersThatDifferOnlyBySuffix": true,
"csharp.inlayHints.types.enabled": true,
"csharp.inlayHints.types.forImplicitObjectCreation": true,
"csharp.inlayHints.types.forLambdaParameterTypes": true,

// Settings Toggle
"toggle.primarySettingText": "Code Lens",

// Unity Tools
"unity-tools.documentationVersion": "2021.3",
"unity-tools.defaultOrganizationFolders": [
    "_PROJECT",
    "_SANDBOX"
],

// Unity Event Lens
"unity-event-lens.onlyScenesInBuildSettings": false,
"unity-event-lens.useAccurateParsing": true,

// Error Lens
"errorLens.gutterIconsEnabled": true,
"errorLens.gutterIconSize": "auto",
"errorLens.statusBarIconsEnabled": true,
"errorLens.statusBarIconsUseBackground": true,

// Live Share
"liveshare.launcherClient": "visualStudioCode",
"liveshare.showReadOnlyUsersInEditor": "always",
"liveshare.nameTagVisibility": "Always",
