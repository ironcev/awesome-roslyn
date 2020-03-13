<p align="center">
    <a href="https://github.com/dotnet/roslyn">
        <img src="https://raw.githubusercontent.com/ironcev/awesome-roslyn/master/images/awesome-roslyn-logo.png" alt="Awesome Roslyn" width="500">
    </a>
</p>

<p align="center">
    <a href="https://github.com/sindresorhus/awesome">
        <img src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg" alt="Awesome">
    </a>
</p>

> Curated list of Roslyn books, tutorials, open source projects, analyzers, code fixes, and refactorings.

Roslyn, officially named [.NET Compiler Platform](https://en.wikipedia.org/wiki/.NET_Compiler_Platform), is a set of open-source compilers and code analysis APIs for C# and Visual Basic .NET languages.

## Contents

- [Books](#books)
- [Tutorials](#tutorials)
- [Open Source Projects](#open-source-projects)
- [Open Source Analyzers, Code Fixes, and Refactorings](#open-source-analyzers-code-fixes-and-refactorings)
- [Libraries and Frameworks for Testing Analyzers, Code Fixes, and Refactorings](#libraries-and-frameworks-for-testing-analyzers-code-fixes-and-refactorings)
- [Blog Posts and Articles](#blog-posts-and-articles)
- [Talks](#talks)

## Books
Awesome books to give you a good start with Roslyn.

- [Roslyn Succinctly](https://www.syncfusion.com/ebooks/roslyn) - *Free e-book* by Alessandro Del Sole and the perfect book to start with. Explains Roslyn APIs and afterward focuses on writing analyzers and refactorings.
- [.NET Development Using the Compiler API](https://www.apress.com/la/book/9781484221105) - Book by Jason Bock. Besides analyzers and refactorings, it also explains the scripting API and provides an interesting reflection on the future of the Compiler API.
- [Roslyn Cookbook](https://www.packtpub.com/application-development/roslyn-cookbook) - Book by Manish Vasani, a member of the Roslyn analyzers team. After covering analyzers, refactorings, and scripting in detail, the book goes in-depth explaining how to develop new C# language features and contribute to the Roslyn source code.

## Tutorials
Awesome online tutorials to help you write your first analyzers and code fixes.

- [Learn Roslyn Now](https://joshvarty.com/learn-roslyn-now/) - Series of blog posts that explore the Roslyn compiler API. It introduces the power of Roslyn through small self-contained examples. A perfect tutorial to start with :-)
- [How To Write a C# Analyzer and Code Fix](https://github.com/dotnet/roslyn/wiki/How-To-Write-a-C%23-Analyzer-and-Code-Fix) - The mother of all Roslyn tutorials :-) A realistic step-by-step introduction to syntax and semantic analysis as well as the syntax transformation.
- [C# and Visual Basic - Use Roslyn to Write a Live Code Analyzer for Your API](https://msdn.microsoft.com/en-us/magazine/dn879356.aspx) - Older but still not outdated, very detailed MSDN article on writing code analyzers.
- [C# - Adding a Code Fix to Your Roslyn Analyzer](https://msdn.microsoft.com/en-us/magazine/dn904670.aspx) - The sequel to the previous MSDN article. A detailed introduction into code fixes.

## Open Source Projects
Awesome open source projects built on top of Roslyn.

- [Bridge](https://github.com/bridgedotnet/Bridge) - C# to JavaScript transpiler. Write modern mobile and web apps in C# and run them anywhere in JavaScript.
- [Code Converter](https://github.com/icsharpcode/CodeConverter/) - C# to VB.NET and VB.NET to C# transpiler.
- [CodeAnalysis.CSharp.PatternMatching](https://github.com/pvginkel/Microsoft.CodeAnalysis.CSharp.PatternMatching) - Intuitive pattern matching for Roslyn syntax trees. Simplifies C# syntax and semantic analysis.
- [CodeGeneration.Roslyn](https://github.com/AArnott/CodeGeneration.Roslyn) - Roslyn-based Code Generation during a build with design-time support.
- [dotnet-script](https://github.com/filipw/dotnet-script) - Runs C# scripts from the .NET CLI, defines NuGet packages inline and edit/debugs them in VS Code.
- [FlubuCore](https://github.com/dotnetcore/FlubuCore) - Cross platform build automation tool for building projects and executing deployment scripts using C# code.
- [MirrorSharp](https://github.com/ashmind/mirrorsharp) - Online C#, VB.NET, and F# code editor. Features code completion, method signature help, quick fixes, and diagnostics.
- [OmniSharp](http://www.omnisharp.net/) - Enables a cross platform .NET development in the editor of your choice. A family of open source projects, each with one goal: To enable a great .NET experience in your editor of choice.
- [roslyn-linq-rewrite](https://github.com/antiufo/roslyn-linq-rewrite) - Compiles C# code by first rewriting the syntax trees of LINQ expressions using plain procedural code. This increases performance by minimizes heap allocations and dynamic dispatch.
- [RoslynPad](https://roslynpad.net/) - Cross-platform C# editor. Features code completion, method signature help, quick fixes, and diagnostics.
- [RoslynQuoter](https://github.com/KirillOsenkov/RoslynQuoter) - Online tool that for a given C# program generates syntax tree API calls that construct syntax tree of that program.
- [scriptcs](http://scriptcs.net/) - Turns C# into a powerful scripting tool. Features C# REPL, installation of NuGet packages, and execution of scripts with a single line of code.
- [Scripty](https://github.com/daveaglick/Scripty) - Tool to use Roslyn-powered C# scripts for code generation. You can think of it as a scripted alternative to T4 templates.
- [Sharpen](http://sharpen.rocks) - Visual Studio extension that intelligently introduces new C# language features into your existing code base.
- [SharpLab](https://sharplab.io/) - .NET code playground. Displays intermediate steps and results of code compilation. Shows the code as compiler sees it. Allows selecting different branches and versions of Roslyn. Runs C#, VB.NET, and F# code in the browser.
- [Testura.Code](https://github.com/Testura/Testura.Code) - Wrapper around the Roslyn API used for generation, saving, and compiling C# code. Provides methods and helpers to generate classes, methods, statements, and expressions.
- [Uno SourceGenerator](https://github.com/nventive/Uno.SourceGeneration) - C# source code generator based on a project being built, using all of its syntactic and semantic model information.

## Open Source Analyzers, Code Fixes, and Refactorings
Awesome open source analyzers, code fixes, and refactorings.

- [.NET Analyzers](https://github.com/DotNetAnalyzers) - GitHub organization for the development of Roslyn analyzers. Various repositories within the organization cover analyzers for ASP.NET Core, WPF, IDisposable, usages of System.Reflection, etc.
- [.NET Compiler Platform ("Roslyn") Analyzers](https://github.com/dotnet/roslyn-analyzers) - Diagnostic analyzers developed by the Roslyn team. Initially developed to help flesh out the design and implementation of the static analysis APIs. The analyzers cover code quality, .NET Core, desktop .NET Framework, comments in code, and more.
- [Code Cracker](https://github.com/code-cracker/code-cracker) - Analyzer library for C# and VB.NET. Offers diagnostics in many categories like performance, coding styles, as well as some basic refactorings.
- [CSharpGuidelinesAnalyzer](https://github.com/bkoelman/CSharpGuidelinesAnalyzer) - Reports diagnostics for C# coding guidelines (https://csharpcodingguidelines.com/).
- [ErrorProne.NET](https://github.com/SergeyTeplyakov/ErrorProne.NET) - Set of analyzers and code fixes focusing on the correctness and performance of C# programs. Inspired with Google's [Error Prone](https://github.com/google/error-prone).
- [Refactoring Essentials for Visual Studio](https://github.com/icsharpcode/RefactoringEssentials/) - Refactorings, analyzers and code fixes for C# and VB.NET.
- [Roslyn Clr Heap Allocation Analyzer](https://github.com/Microsoft/RoslynClrHeapAllocationAnalyzer) - C# heap allocation analyzer that can detect explicit and many implicit allocations like boxing, closures, implicit delegate creations, etc.
- [Roslynator](https://github.com/JosefPihrt/Roslynator) - Collection of 190+ analyzers and 190+ refactorings for C#. Covers coding style, code readability and simplification, removing redundancies, fixing compiler errors, and many more.
- [SonarC#](https://github.com/SonarSource/sonar-csharp) - Static code analyzer for C# language used as an extension for the SonarQube platform.
- [StyleCop Analyzers for the .NET Compiler Platform](https://github.com/DotNetAnalyzers/StyleCopAnalyzers) - Port of StyleCop rules to Roslyn.
- [VSDiagnostics](https://github.com/Vannevelj/VSDiagnostics) - Collection of code-quality analyzers. Covers usages of async methods, flags enums, best practices in exception handling as well as many other code-quality checks.

## Libraries and Frameworks for Testing Analyzers, Code Fixes, and Refactorings
Awesome libraries and frameworks for testing analyzers, code fixes, and refactorings.

- [Microsoft.CodeAnalysis.Testing](https://github.com/dotnet/roslyn-sdk/tree/master/src/Microsoft.CodeAnalysis.Testing) - Library for testing analyzers and code fixes with NUnit, xUnit and MSTest frameworks. A part of [Roslyn SDK](https://github.com/dotnet/roslyn-sdk).
- [RoslynTestKit](https://github.com/cezarypiatek/RoslynTestKit) - Lightweight framework for writing unit tests for analyzers, code fixes, refactorings, and completion providers. It's unit testing framework agnostic.

## Blog Posts and Articles
Awesome blog posts and online articles covering various topics like performance, Roslyn internals and similar.

- [Inside the .NET Compiler Platform – Performance Considerations during Syntax Analysis (#SpeakRoslyn)](https://robinsedlaczek.com/2015/04/29/inside-the-net-compiler-platform-performance-considerations-during-syntax-analysis-speakroslyn/) - In-depth look at Roslyn's performance with the focus on memory consumption.
- [Persistence, Facades and Roslyn's Red-Green Trees](https://blogs.msdn.microsoft.com/ericlippert/2012/06/08/persistence-facades-and-roslyns-red-green-trees/) - Inspiring introduction on how Roslyn team implemented immutable, reusable trees with cheap parent references and many other goodies. Quote: "But on the Roslyn team we routinely do impossible things" :-)
- [ReSharper and Roslyn: Q&A](https://blog.jetbrains.com/dotnet/2014/04/10/resharper-and-roslyn-qa/) - Excellent explanation why ReSharper will not use Roslyn. Includes good discussion on static code analysis and some limits of Roslyn.
- [Roslyn performance (Matt Gertz)](https://blogs.msdn.microsoft.com/csharpfaq/2014/01/15/roslyn-performance-matt-gertz/) - Insight on how Roslyn team approaches the topic of evaluating and achieving performance.

## Talks
Awesome public talks about Roslyn.

- [The Power of Roslyn](https://www.youtube.com/watch?v=nXljhGDokqA) - Great talk by Kasey Uhlenhuth at NDC Oslo 2018 covering Roslyn essentials and APIs and tools for building code analyzers and fixes.

## Contribute

Contributions are welcome :-) The goal is to build a categorized community-driven collection of awesome Roslyn resources. Before contributing, please make sure to read the [contribution guidelines](contributing.md).

## License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, Igor Rončević has waived all copyright and related or neighboring rights to this work.
