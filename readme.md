<p align="center">
    <img src="https://raw.githubusercontent.com/ironcev/awesome-roslyn/master/images/awesome-roslyn-logo.png" alt="Awesome Roslyn" style="max-width:100%;">
</p>

# Awesome Roslyn [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of Roslyn books, tutorials, open source projects, analyzers, code fixes, and refactorings.

Roslyn, officially named [.NET Compiler Platform](https://en.wikipedia.org/wiki/.NET_Compiler_Platform), is a set of open-source compilers and code analysis APIs for C# and Visual Basic .NET languages.

## Contents

- [Books](#books)
- [Tutorials](#tutorials)
- [Open Source Projects](#open-source-projects)
- [Open Source Analyzers, Code Fixes, and Refactorings](#open-source-analyzers-code-fixes-and-refactorings)
- [Blog Posts and Articles](#blog-posts-and-articles)
- [Talks](#talks)

## Books
Awesome books to give you a good start with Roslyn.

- [Roslyn Succinctly](https://www.syncfusion.com/ebooks/roslyn) by Alessandro Del Sole *(free e-book)*
- [.NET Development Using the Compiler API](https://www.apress.com/la/book/9781484221105) by Jason Bock
- [Roslyn Cookbook](https://www.packtpub.com/application-development/roslyn-cookbook) by Manish Vasani

## Tutorials
Awesome online tutorials to help you write your first analyzers and code fixes.

- [Learn Roslyn Now](https://joshvarty.com/learn-roslyn-now/) - A series of blog posts that explore the Roslyn compiler API. It introduces the power of Roslyn through small self-contained examples. A perfect tutorial to start with :-)
- [How To Write a C# Analyzer and Code Fix](https://github.com/dotnet/roslyn/wiki/How-To-Write-a-C%23-Analyzer-and-Code-Fix) - The mother of all Roslyn tutorials :-) A realistic step-by-step introduction to syntax and semantic analysis as well as syntax transformation.
- [C# and Visual Basic - Use Roslyn to Write a Live Code Analyzer for Your API](https://msdn.microsoft.com/en-us/magazine/dn879356.aspx) - A bit older but still not outdated, very detailed MSDN article on writing code analyzers.
- [C# - Adding a Code Fix to Your Roslyn Analyzer](https://msdn.microsoft.com/en-us/magazine/dn904670.aspx) - The sequel of the previous MSDN article. A detailed introduction into code fixes.

## Open Source Projects
Awesome open source projects built on top of Roslyn.

- [Bridge](https://github.com/bridgedotnet/Bridge) - C# to JavaScript compiler. Write modern mobile and web apps in C#. Run them anywhere in JavaScript with Bridge.NET. 
- [Code Converter](https://github.com/icsharpcode/CodeConverter/) - Converts code from C# to VB.NET and vice versa.
- [CodeAnalysis.CSharp.PatternMatching](https://github.com/pvginkel/Microsoft.CodeAnalysis.CSharp.PatternMatching) - Simplifies C# syntax and semantic analysis by providing an intuitive pattern matching for Roslyn syntax trees.
- [CodeGeneration.Roslyn](https://github.com/AArnott/CodeGeneration.Roslyn) - Roslyn-based Code Generation.
- [dotnet-script](https://github.com/filipw/dotnet-script) - Run C# scripts from the .NET CLI, define NuGet packages inline and   edit/debug them in VS Code - all of that with full language services support from OmniSharp.
- [FlubuCore](https://github.com/flubu-core/flubu.core) - Fluent Builder. A cross platform build automation tool for building projects and executing deployment scripts using C# code.
- [MirrorSharp](https://github.com/ashmind/mirrorsharp) - An online C#, VB.NET, and F# code editor. Features code completion, method signature help, quick fixes, and diagnostics.
- [OmniSharp](http://www.omnisharp.net/) - Enables a cross platform .NET development in the editor of your choice. A family of open source projects, each with one goal: To enable a great .NET experience in your editor of choice.
- [roslyn-linq-rewrite](https://github.com/antiufo/roslyn-linq-rewrite) - Compiles C# code by first rewriting the syntax trees of LINQ expressions using plain procedural code. This increases performance by minimizes heap allocations and dynamic dispatch.
- [RoslynPad](https://roslynpad.net/) - A cross-platform C# editor. Features code completion, method signature help, quick fixes, and diagnostics.
- [RoslynQuoter](https://github.com/KirillOsenkov/RoslynQuoter) - A tool that for a given C# program generates syntax tree API calls that construct the syntax tree of that program.
- [scriptcs](http://scriptcs.net/) - Turns C# into a powerful scripting tool. Features C# REPL, installation of NuGet packages, execution of scripts with a single line of code.
- [Scripty](https://github.com/daveaglick/Scripty) - Tools to let you use Roslyn-powered C# scripts for code generation.
- [Sharpen](http://sharpen.rocks) - A Visual Studio extension that intelligently introduces new C# language features into your existing code base.
- [SharpLab](https://sharplab.io/) - .NET code playground. Displays intermediate steps and results of code compilation. Shows the code as compiler sees it. Allows selecting different branches and versions of Roslyn. Runs C#, VB.NET, and F# code in the browser.
- [Testura.Code](https://github.com/Testura/Testura.Code) - A wrapper around the Roslyn API used for generation, saving and compiling C# code. Provides methods and helpers to generate classes, methods, statements and expressions.

## Open Source Analyzers, Code Fixes, and Refactorings
Awesome open source analyzers, code fixes, and refactorings.

- [.NET Compiler Platform ("Roslyn") Analyzers](https://github.com/dotnet/roslyn-analyzers) - Diagnostic analyzers developed by the Roslyn team. Initially developed to help flesh out the design and implementation of the static analysis APIs. The analyzers cover code quality, .NET Core, desktop .NET Framework, comments in code, and more.
- [Code Cracker](https://github.com/code-cracker/code-cracker) - An analyzer library for C# and VB.NET. Offers diagnostics in many categories like performance, coding styles, as well as some basic refactorings.
- [CSharpGuidelinesAnalyzer](https://github.com/bkoelman/CSharpGuidelinesAnalyzer) - Reports diagnostics for C# coding guidelines (https://csharpcodingguidelines.com/).
- [Refactoring Essentials for Visual Studio](https://github.com/icsharpcode/RefactoringEssentials/) - Refactorings, analyzers and code fixes for C# and VB.NET.
- [Roslyn Clr Heap Allocation Analyzer](https://github.com/Microsoft/RoslynClrHeapAllocationAnalyzer) - A C# heap allocation analyzer that can detect explicit and many implicit allocations like boxing, display classes a.k.a closures, implicit delegate creations, etc.
- [Roslynator](https://github.com/JosefPihrt/Roslynator) - A collection of 190+ analyzers and 190+ refactorings for C#. Covers coding style, code readability and simplification, removing redundancies, fixing compiler errors and many more.
- [SonarC#](https://github.com/SonarSource/sonar-csharp) - SonarC# is a static code analyzer for C# language used as an extension for the SonarQube platform. 
- [StyleCop Analyzers for the .NET Compiler Platform](https://github.com/DotNetAnalyzers/StyleCopAnalyzers) - A port of StyleCop rules to Roslyn.
- [VSDiagnostics](https://github.com/Vannevelj/VSDiagnostics) - A collection of code-quality analyzers. Covers usages of async methods, flags enums, best practices in exception handling as well as many other code-quality checks.

## Blog Posts and Articles
Awesome blog posts and online articles covering various topics like performance, Roslyn internals and similar.

- [Inside the .NET Compiler Platform – Performance Considerations during Syntax Analysis (#SpeakRoslyn)](https://robinsedlaczek.com/2015/04/29/inside-the-net-compiler-platform-performance-considerations-during-syntax-analysis-speakroslyn/) - An in-depth look at Roslyn's performance with the focus on memory consumption.
- [Persistence, Facades and Roslyn's Red-Green Trees](https://blogs.msdn.microsoft.com/ericlippert/2012/06/08/persistence-facades-and-roslyns-red-green-trees/) - An inspiring introduction on how Roslyn team implemented immutable, reusable trees with cheap parent references and many other goodies. Quote: "But on the Roslyn team we routinely do impossible things." :-)
- [ReSharper and Roslyn: Q&A](https://blog.jetbrains.com/dotnet/2014/04/10/resharper-and-roslyn-qa/) - An excellent explanation why ReSharper will not use Roslyn. A good discussion on static code analysis and the limits of Roslyn.
- [Roslyn performance (Matt Gertz)](https://blogs.msdn.microsoft.com/csharpfaq/2014/01/15/roslyn-performance-matt-gertz/) - An insight on how Roslyn team approaches the topic of evaluating and achieving performance.

## Talks
Awesome talks about Roslyn

- [The Power of Roslyn](https://www.youtube.com/watch?v=nXljhGDokqA) - Great talk by Kasey Uhlenhuth at NDC Oslo 2018 about Roslyn, analyzers, APIs and tools for building an analyzer/fixer. She also builds a simple analyzer and fixer and gives us some great references.

## Contribute

Contributions are welcome :-) The goal is to build a categorized community-driven collection of awesome Roslyn resources. Before contributing, please make sure to read the [contribution guidelines](contributing.md).

## License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, Igor Rončević has waived all copyright and related or neighboring rights to this work.
