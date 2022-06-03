## Improve your .NET code

In the post about Clean Code, I wrote how to avoid writing bad code and identify code smells. However, many tools can help you do this quicker and easier.

Most of these tools will help you:

- analyze code quality
- refactor code 
- enforce coding standards
- fix common errors
- suggest an alternative syntax

## ReSharper (paid)

Extension for Visual Studio, ReSharper is probably one of the best known and most popular tools for .NET developers.

https://www.jetbrains.com/resharper/

## SonarQube (paid)

A tool which analyzes code quality and security, SonarQube is available for C#, VB.NET and many other languages. SonarQube is used in the CI/CD pipelines and code reviews.

It's best used by teams, but can also help individual developers. However, it's not cheap and needs to be integrated into the development workflow.

SonarCloud is a SaaS offering of the SonarQube and can be a better solution in some cases.

https://www.sonarsource.com/

## SonarLint (free)

SonarLint integrates with the IDE and can help you catch problems sooner. It complements SonarQube or SonarCloud perfectly.

It's available for Visual Studio, VS Code, JetBrains IDEs, and Eclipse. It's free and open-source.

https://www.sonarsource.com/products/sonarlint/

## CodeMaid (free)

Visual Studio extension that works with C#, VB.NET, F# and some other languages.

https://www.codemaid.net/

## Roslynator (free)

Free, open-source collection of over 500 analyzers, refactorings, and code fixes for C#. It's available as an extension for Visual Studio and VS Code and as a NuGet package.

https://github.com/JosefPihrt/Roslynator