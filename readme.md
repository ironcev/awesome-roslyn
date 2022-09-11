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

> Curated list of Roslyn books, tutorials, open source projects, analyzers, code fixes, refactorings, and source generators.

Roslyn, officially named [.NET Compiler Platform](https://en.wikipedia.org/wiki/.NET_Compiler_Platform), is a set of open-source compilers and code analysis APIs for C# and Visual Basic .NET languages.

## Contents

- [Books](#books)
- [Tutorials](#tutorials)
- [Open Source Projects](#open-source-projects)
- [Open Source Analyzers, Code Fixes, and Refactorings](#open-source-analyzers-code-fixes-and-refactorings)
- [Libraries and Frameworks for Testing Analyzers, Code Fixes, and Refactorings](#libraries-and-frameworks-for-testing-analyzers-code-fixes-and-refactorings)
- [Source Generators](#source-generators)
- [Blog Posts and Articles](#blog-posts-and-articles)
- [Talks](#talks)

## Books
Awesome books to give you a good start with Roslyn.

- [Roslyn Succinctly](https://www.syncfusion.com/ebooks/roslyn) - *Free e-book* by Alessandro Del Sole and the perfect book to start with. Explains Roslyn APIs and afterward focuses on writing analyzers and refactorings.
- [.NET Development Using the Compiler API](https://www.apress.com/la/book/9781484221105) - Book by Jason Bock. Besides analyzers and refactorings, it also explains the scripting API and provides an interesting reflection on the future of the Compiler API.
- [Roslyn Cookbook](https://www.packtpub.com/application-development/roslyn-cookbook) - Book by Manish Vasani, a member of the Roslyn analyzers team. After covering analyzers, refactorings, and scripting in detail, the book goes in-depth explaining how to develop new C# language features and contribute to the Roslyn source code.

## Tutorials
Awesome online tutorials to help you write your first analyzers, code fixes, and source generators.

- [Learn Roslyn Now](https://joshvarty.com/learn-roslyn-now/) - Series of blog posts that explore the Roslyn compiler API. It introduces the power of Roslyn through small self-contained examples. A perfect tutorial to start with :-)
- [How To Write a C# Analyzer and Code Fix](https://github.com/dotnet/roslyn/blob/master/docs/wiki/How-To-Write-a-C%23-Analyzer-and-Code-Fix.md) - The mother of all Roslyn tutorials :-) A realistic step-by-step introduction to syntax and semantic analysis as well as the syntax transformation.
- [C# and Visual Basic - Use Roslyn to Write a Live Code Analyzer for Your API](https://msdn.microsoft.com/en-us/magazine/dn879356.aspx) - Older but still not outdated, very detailed MSDN article on writing code analyzers.
- [C# - Adding a Code Fix to Your Roslyn Analyzer](https://msdn.microsoft.com/en-us/magazine/dn904670.aspx) - The sequel to the previous MSDN article. A detailed introduction into code fixes.
- [Introducing C# Source Generators](https://devblogs.microsoft.com/dotnet/introducing-c-source-generators/) - Original announcement of the C# 9.0 Source Generators feature. Explains what source generators are, in which scenarios they are useful, and shows how to write a simple source generator.
- [New C# Source Generator Samples](https://devblogs.microsoft.com/dotnet/new-c-source-generator-samples/) - Samples on how to write a non-trivial code generator driven by additional, non-code files like CSV files or [Mustache](https://mustache.github.io/) templates.
- [C# Source Generators](https://github.com/amis92/csharp-source-generators) - Comprehensive list of additional learning sources, samples, and experimental and productive source generators. A perfect reference once you grasp the basics.

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
- [Mapping Generator](https://github.com/cezarypiatek/MappingGenerator) - Code fix that generates arbitrary complex object-object mappings. It recognizes out of the box a large number of scenarios where mappings are used. A design-time alternative to [AutoMapper](https://automapper.org/).
- [Nullable.Extended](https://github.com/tom-englert/Nullable.Extended) - Roslyn tools and analyzers to improve the experience when coding with nullable reference types.
- [Refactoring Essentials for Visual Studio](https://github.com/icsharpcode/RefactoringEssentials/) - Refactorings, analyzers and code fixes for C# and VB.NET.
- [Roslyn Clr Heap Allocation Analyzer](https://github.com/Microsoft/RoslynClrHeapAllocationAnalyzer) - C# heap allocation analyzer that can detect explicit and many implicit allocations like boxing, closures, implicit delegate creations, etc.
- [Roslynator](https://github.com/JosefPihrt/Roslynator) - Collection of 190+ analyzers and 190+ refactorings for C#. Covers coding style, code readability and simplification, removing redundancies, fixing compiler errors, and many more.
- [SonarC#](https://github.com/SonarSource/sonar-csharp) - Static code analyzer for C# language used as an extension for the SonarQube platform.
- [StyleCop Analyzers for the .NET Compiler Platform](https://github.com/DotNetAnalyzers/StyleCopAnalyzers) - Port of StyleCop rules to Roslyn.
- [SharpSource](https://github.com/Vannevelj/SharpSource) - surfacing defects at compile time and preventing issues that would otherwise go unnoticed.

## Libraries and Frameworks for Testing Analyzers, Code Fixes, and Refactorings
Awesome libraries and frameworks for testing analyzers, code fixes, and refactorings.

- [Microsoft.CodeAnalysis.Testing](https://github.com/dotnet/roslyn-sdk/tree/master/src/Microsoft.CodeAnalysis.Testing) - Library for testing analyzers and code fixes with NUnit, xUnit and MSTest frameworks. A part of [Roslyn SDK](https://github.com/dotnet/roslyn-sdk).
- [RoslynTestKit](https://github.com/cezarypiatek/RoslynTestKit) - Lightweight framework for writing unit tests for analyzers, code fixes, refactorings, and completion providers. It's unit testing framework agnostic.

## Source Generators
Awesome (but mostly experimental at the moment, because .NET 5.0 and C# 9.0 are still in preview) source generators and open source projects that internally use source generators.

- [DpDtInject](https://github.com/lsoft/DpdtInject) - Proof-of-concept of a dependency injection container that transfers huge piece of resolving logic to the compilation stage. Offers additional compile-time safety and fast runtime resolution.
- [Generator.Equals](https://github.com/diegofrata/Generator.Equals) - Automatically implements equality and hashing for classes and records. Supports different comparison strategies. Offers similar functionality like IL weaving-based [Equals.Fody](https://github.com/Fody/Equals).
- [JsonSrcGen](https://github.com/trampster/JsonSrcGen) - Reflection-free JSON serializer. Allows extremely fast JSON processing by generating reflection-free serializers at the compile time.
- [Source Generator Playground](https://sourcegen.dev/) - Online application that lets you experiment with source generators. Perfect for learning and testing your ideas. Write your own source generator or learn from built-in examples and see the generated output.  
- [StrongInject](https://github.com/YairHalberstadt/stronginject) - Compile-time dependency injection container. Compile-time checked, reflection-free and runtime code generation free, thus fast and [app-trimming](https://devblogs.microsoft.com/dotnet/app-trimming-in-net-5/)-friendly. 
- [StructPacker](https://github.com/RudolfKurka/StructPacker) - Low-level, lightweight and performance-focused serializer for C# struct types. Auto-generates C# serialization code to achieve peak runtime performance and efficiency.
- [Svg to C# Source Generators](https://github.com/wieslawsoltes/SourceGenerators) - SVG to C# compiler. Compiles SVG drawing markup to C# using [SkiaSharp](https://github.com/mono/SkiaSharp) as rendering engine.
- [WrapperValueObject](https://github.com/martinothamar/WrapperValueObject) - Creates boilerplate free wrappers around types. Especially useful for creating [strongly typed wrappers around primitive types](https://andrewlock.net/series/using-strongly-typed-entity-ids-to-avoid-primitive-obsession/).

## Blog Posts and Articles
Awesome blog posts and online articles covering various topics like performance, Roslyn history, internals and similar.

- [How Microsoft rewrote its C# compiler in C# and made it open source](https://medium.com/microsoft-open-source-stories/how-microsoft-rewrote-its-c-compiler-in-c-and-made-it-open-source-4ebed5646f98) - Roslyn's journey, presented by Mads Torgersen, the lead designer of C#. Inspiring story on how Roslyn project started and why, and what it took to make it open source.
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
