---
layout: ballerina-tooling-guide-left-nav-pages-swanlake
title: Language Intelligence
permalink: /learn/tooling-guide/visual-studio-code-extension/language-support/language-intelligence/
active: language-intelligence
intro: The VS Code Ballerina extension brings in language intelligence to enhance the development experience and increase its efficiency. Language intelligence is built in to the extension via a Language Server implementation, which consists of the below language intelligence options.
redirect_from:
  - /learn/tools-ides/vscode-plugin/language-intelligence
  - /learn/tools-ides/vscode-plugin/language-intelligence/
  - /learn/vscode-plugin/language-intelligence/
  - /learn/vscode-plugin/language-intelligence
  - /learn/tools-ides/setting-up-visual-studio-code/language-intelligence
  - /learn/tools-ides/setting-up-visual-studio-code/language-intelligence/
  - /learn/setting-up-visual-studio-code/language-intelligence
  - /learn/setting-up-visual-studio-code/language-intelligence/
  - /learn/language-intelligence
  - /learn/language-intelligence/
  - /swan-lake/learn/getting-started/setting-up-visual-studio-code/language-intelligence/
  - /swan-lake/learn/getting-started/setting-up-visual-studio-code/language-intelligence
  - /learn/tooling-guide/vs-code-extension/language-support/language-intelligence
  - /learn/tooling-guide/vs-code-extension/language-support/language-intelligence/
  - /learn/tooling-guide/visual-studio-code-extension/language-support/language-intelligence
---

## Semantic and Syntactic Diagnostics

When there are syntax or semantic errors in your code, you will be notified with appropriate diagnostics during the development time. 

> **Tip**: The detailed description that appears when you hover over the lines underlined in red will be consistent with the error message that you get during compile-time.

![Semantic and syntactic diagnostics](/learn/images/semantic-and-syntactic.gif)

## Suggestions and Auto-Completion

The extension provides you with suggestions on keywords, variables, and code snippets of language constructs (such as functions, services, and iterable constructs, etc.,).

![Suggestions and auto completion](/learn/images/suggestions.gif)

> **Tip**: You can use these suggestions to access the contents of the modules available in your Ballerina home repo as well as in the Ballerina distribution.

## Code Actions

These allow you to perform the below tasks easily based on the diagnostics and the current scope where the cursor resides. 

- Add documentation for an entity such as a function, service, resource, object, record, etc.,
- Add documentation for all the available entities in the current file
- Add missing imports 
- Create variable definitions
- Create an undefined function
- Map the record types automatically

For example, you can use the automatic data mapping code action as shown below.
 > **Note**: By default, the automatic data mapping code action is disabled. To enable it, click **Settings**, select **Ballerina** from **Extensions**, and select the **Data Mapper: Enabled** checkbox. (If you are using macOS, you can go to **Settings** by pressing `Cmd` + `,`.)

 ![Code actions](/learn/images/data-mapper-code-action.gif)

For another example, you can add documentation for a function as shown below.

 ![Code actions](/learn/images/code-actions.gif)

## Hover Support

 Hover support provides you quick access to information about a certain entity. 
 
 For example, if you hover over a function name, you can view its description, information about its parameters, and the description of its return type as shown below.

  ![Hover support](/learn/images/hover-support.gif)
 
 > **Tip**: Likewise, if you hover over an entity name of an object or a record, you can view the description of the object/record as well as descriptions of its fields.

## Go to Definition

This option allows you to view the definition of a selected variable, function, an object, etc., within the same file, in a separate file, in the same module, or in a file of a different module, of the same project or of the [Standard Library](/learn/api-docs/ballerina/).

![Go to definition](/learn/images/go-to-definition-vscode.gif)

## What's Next?

 - For information on the next capability of the VS Code Ballerina extension, see [Run and Debug](/learn/vscode-plugin/run-and-debug).
 - For information on the VS Code Ballerina extension, see [The Visual Studio Code Ballerina Extension](/learn/vscode-plugin).
