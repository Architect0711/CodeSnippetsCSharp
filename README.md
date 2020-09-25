# CodeSnippetsCSharp
Code Snippets for C# in Visual Studio

# Links
[MSDN: Walkthrough: Create a code snippet](https://docs.microsoft.com/en-us/visualstudio/ide/walkthrough-creating-a-code-snippet?view=vs-2019)

# Escape the $ Character
[Stackoverflow: Escaping the $ character in snippets](https://stackoverflow.com/a/15070491/9351796)

Use the *Delimiter* Attribute on the *Code* Tag to define a different Delimiter than the Default Value "$":

`<Code Language="csharp" Delimiter="~"><![CDATA[ Your Snippet with a $ Sign ]]></Code>
`