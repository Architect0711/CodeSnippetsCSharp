# CodeSnippetsCSharp
Code Snippets for C# in Visual Studio

# Links
[MSDN: Walkthrough: Create a code snippet](https://docs.microsoft.com/en-us/visualstudio/ide/walkthrough-creating-a-code-snippet?view=vs-2019)
[Codeproject: Code Snippet: Step by Step Guideline from Creation to Installation of a Snippet](https://www.codeproject.com/Articles/42077/Code-Snippet-Step-by-Step-Guideline-from-Creation)
[Github: Visual Studio Docs](https://github.com/MicrosoftDocs/visualstudio-docs/tree/master/docs/ide)
[Github: Code Snippets](https://github.com/MicrosoftDocs/visualstudio-docs/blob/master/docs/ide/code-snippets.md)
[Github: Code Snippets Schema Reference](https://github.com/MicrosoftDocs/visualstudio-docs/blob/master/docs/ide/code-snippets-schema-reference.md)
[Github: Code Snippets Functions](https://github.com/MicrosoftDocs/visualstudio-docs/blob/master/docs/ide/code-snippet-functions.md)

# Escape the $ Character
[Stackoverflow: Escaping the $ character in snippets](https://stackoverflow.com/a/15070491/9351796)

Use the *Delimiter* Attribute on the *Code* Tag to define a different Delimiter than the Default Value "$":

`<Code Language="csharp" Delimiter="~"><![CDATA[ Your Snippet with a $ Sign ]]></Code>
`