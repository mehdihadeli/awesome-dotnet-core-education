
# 🎨 Awesome .Net Core Education [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

[![Twitter URL](https://img.shields.io/badge/-@mehdi_hadeli-%231DA1F2?style=flat-square&logo=twitter&logoColor=ffffff)](https://twitter.com/mehdi_hadeli)
[![blog](https://img.shields.io/badge/blog-dotnetuniversity.com-brightgreen?style=flat-square)](https://dotnetuniversity.com/)
![Twitter URL](https://img.shields.io/twitter/url?label=Tweet&url=https%3A%2F%2Fgithub.com%2Fmehdihadeli%2Fawesome-dotnet-core-education)

![](./banner.jpg)


> Collection of useful Articles and resources for learning and practicing about .Net Core and its related technologies, this repository will update continuously, keep yourself up to date.

Contributions are always welcome! Please take a look at the [contribution guidelines](https://github.com/mehdihadeli/awesome-dotnet-core-education/blob/master/contributing.md) pages first.

Thanks to all [contributors](https://github.com/mehdihadeli/awesome-dotnet-core-education/graphs/contributors), you're awesome and wouldn't be possible without you! The goal is to build a categorized community-driven collection of very well-known resources.

## Give a Star! ⭐️
My primary focus in this repository is on quality. Creating a good quality of resources. It takes a lot of time. If you like this, learned something or you are using it in your applications, please give it a star ⭐. This is the best motivation for me to continue this work. Thanks!

## Share It
If you think this repository makes a difference and is worth it, please share it with your friends and on social networks. I will be extremely grateful.

## Contents
* [.Net](#.net)
  * [.Net Core](#.net-core)
  * [.Net Standard](#.net-standard)
  * [.Net 5](#.net-5)
* [C#](#c#)
  * [C# 7](#c#-7)
  * [C# 8](#c#-8)
  * [C# 9](#c#-9)
* [.Net CLI](#.net-cli)
* [.Net Tools](#.net-tools)
* [.Net Core Tips](#.net-core-tips)
* [MetaPack](#metapack)
* [MAUI](#maui)
* [Source Generators](#source-generators)
* [Performance](#performance)
* [Serialization](#serialization)
* [Generic Host And Web Host](#generic-host-and-web-host)
* [DotNet Core Architecture](#dotnet-core-architecture)
* [Hosting](#hosting)
* [Kestrel](#kestrel)
* [Middleware](#middleware)
* [Action Filters](#action-filters)
* [Configuration](#configuration)
* [Options Pattern](#options-pattern)
* [Grpc](#grpc)
* [WebSockets](#websockets)
* [SignalR](#signalr)
* [HttpClient](#httpclient)
* [WEB API](#web-api)
* [Background Tasks](#background-tasks)
* [Validation](#validation)
* [Razor Pages](#razor-pages)
* [GraphQL](#graphql)
* [NoSQL](#nosql)
  * [CosmosDB](#cosmosdb)
  * [PostgreSQL](#postgrsql)
  * [MongoDB](#mongodb)
  * [RavenDB](#ravendb)
* [Docker](#docker)
* [API Versioning](#api-versioning)
* [Hosted Service](#hosted-service)
* [Test Host And WebApplicationFactory](#test-host-and-webapplicationfactory)
* [Routing](#routing)
* [Dependency Injection](#dependency-injection)
* [Security](#security)
   * [Encryption And Data Protection](#encryption-and-data-protection)
   * [DotNet Core Identity](#dotnet-core-identity)
   * [Authentication](#authentication)
   * [Authorization](#authorization)
* [Logging And Auditing](#logging-and-auditing)
* [Tracing](#tracing)
* [Testing](#testing)
    * [TDD](#tdd)
    * [BDD](#bdd)
    * [Unit Testing](#unit-testing)
    * [Integration Testing](#integration-testing)
    * [End-To-End Testing](#end-to-end-testing)
    * [Load Testing](#load-testing)
	* [Architectural Testing](architectural-testing)
    * [Mocking](#mocking)
    * [XUnit](#xunit)
* [Exception Handling](#exception-handling)    
* [EF Core](#ef-core)
* [Environment](#environment)
* [MediatR](#mediatr)
* [Mapping](#mapping)
* [Benchmarking](#benchmarking)
* [Package Versioning](#package-versioning)
* [Orleans](#orleans)
* [Identity Server](#identity-server)
* [CI/CD](#ci/cd)
    *[Azure Devops](#azure-devops)
    *[GitHub Actions](#gitHub-actions)
* [PaaS](PaaS)
	* [Heroku](#heroku)
	* [Netlify](#netlify)
* [Roslyn](#roslyn)
* [Others](#others)
* [Books](#books)


## .Net

### 📝 Articles 
<details><summary>Links</summary>
	
* [The Many Flavors of .NET - Sean Killeen](https://flavorsof.net)

</details>

### 📹 Videos
<details><summary>Links</summary>
	
* [What is .NET? What's C# and F#? What's the .NET Ecosystem? .NET Core Explained, what can .NET build?](https://www.youtube.com/watch?v=bEfBfBQq7EE)

</details>

<div align="right">
  <b><a href="#contents">↥ Back To Top</a></b>
</div>

### .Net Core

#### Resources

<details><summary>Links</summary>
	
* [ASP.NET Core Application Architecture](https://dotnet.microsoft.com/learn/aspnet/architecture)
* [ASP.NET Core architecture e-book](https://dotnet.microsoft.com/download/e-book/aspnet/pdf)
* [Porting existing ASP.NET Apps to .NET Core e-book](https://dotnet.microsoft.com/download/e-book/porting-aspnet-apps/pdf)

</details>

#### 📝 Articles

<details><summary>Links</summary>
	
* [What's new in ASP.NET Core 2.1](https://docs.microsoft.com/en-us/aspnet/core/release-notes/aspnetcore-2.1)
* [What's new in ASP.NET Core 2.2](https://docs.microsoft.com/en-us/aspnet/core/release-notes/aspnetcore-2.2)
* [What's new in ASP.NET Core 3.0](https://docs.microsoft.com/en-us/aspnet/core/release-notes/aspnetcore-3.0)
* [What's new in ASP.NET Core 3.1](https://docs.microsoft.com/en-us/aspnet/core/release-notes/aspnetcore-3.1)
* [What's new in ASP.NET Core 5.0](https://docs.microsoft.com/en-us/aspnet/core/release-notes/aspnetcore-5.0)
* [Migrate from ASP.NET Core 2.2 to 3.0](https://docs.microsoft.com/en-us/aspnet/core/migration/22-to-30)
* [Migrate from ASP.NET Core 3.0 to 3.1](https://docs.microsoft.com/en-us/aspnet/core/migration/30-to-31)
* [Migrate from ASP.NET Core 3.1 to 5.0](https://docs.microsoft.com/en-us/aspnet/core/migration/31-to-50)
* [.NET Core Transitive Dependencies and how to block them](https://curia.me/net-core-transitive-references-and-how-to-block-them/)
* [What is a Transitive dependency in .NET Core](https://www.thecodebuzz.com/transitive-dependency-in-net-core/)
* [Framework Reference](https://docs.microsoft.com/en-us/aspnet/core/migration/22-to-30?view=aspnetcore-5.0&tabs=visual-studio#framework-reference)
* [Deep-dive into .NET Core primitives: deps.json, runtimeconfig.json, and dll's](https://natemcmaster.com/blog/2017/12/21/netcore-primitives/)
* [Deep-dive into .NET Core primitives, part 2: the shared framework](https://natemcmaster.com/blog/2018/08/29/netcore-primitives-2/)
* [Deep-dive into .NET Core primitives, part 3: runtimeconfig.json in depth](https://natemcmaster.com/blog/2019/01/09/netcore-primitives-3/)
* [When ASP.NET Core can't find your controller: debugging application parts](https://andrewlock.net/when-asp-net-core-cant-find-your-controller-debugging-application-parts/)
* [Share controllers, views, Razor Pages and more with Application Parts](https://docs.microsoft.com/en-us/aspnet/core/mvc/advanced/app-parts?view=aspnetcore-5.0)
* [Work with the application model in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/mvc/controllers/application-model?view=aspnetcore-5.0)
* [ASP.NET CORE MVC ANATOMY (PART 1) – ADDMVCCORE](https://www.stevejgordon.co.uk/asp-net-core-mvc-anatomy-addmvccore)

</details>

#### 📹 Videos

<details><summary>Links</summary>
	
* [Migrating to .NET Core 3 | ASP.NET Core 2.2 & 3 REST API Tutorial 16](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/watch?v=gYy5XJRJkOo)
* [Upgrading to .NET Core 3.1 (Real Life Project)](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/watch?v=afyCeCkec4c)
* [Upgrading to .NET 5.0 RC w/ C# 9.0](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/watch?v=ufjtuAel538&t=179s)
* [Cleanup Transitive Dependencies in .NET with Snitch- CodeWithStu](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/watch?v=ZdCn6kpGBhI)

</details>

#### 📦 Libraries

<details><summary>Links</summary>
	
* [https://github.com/dotnet/try-convert](https://github.com/dotnet/try-convert)
	> Helping .NET developers port their projects to .NET Core!
</details>

<div align="right">
  <b><a href="#contents">↥ Back To Top</a></b>
</div>

### .Net Standard

#### 📝 Articles

<details><summary>Links</summary>
	
* [.NET Standard - Microsoft](https://docs.microsoft.com/en-us/dotnet/standard/net-standard)

</details>

#### 📹 Videos

<details><summary>Links</summary>
	
* [Big Changes in .NET 5, C# 9, and Visual Studio 2019 - IAmTimCorey](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/watch?v=zjVgQNfAEOs)

</details>

<div align="right">
  <b><a href="#contents">↥ Back To Top</a></b>
</div>


### .Net 5

#### 📝 Articles 

<details><summary>Links</summary>
	
* [Announcing .NET 5.0 - DevBlogs](https://devblogs.microsoft.com/dotnet/announcing-net-5-0/)
* [Announcing ASP.NET Core in .NET 5](https://devblogs.microsoft.com/aspnet/announcing-asp-net-core-in-net-5/)
* [What's new in .NET 5 - Microsoft](https://docs.microsoft.com/en-us/dotnet/core/dotnet-five)
* [Performance Improvements in .NET 5 - DevBlogs](https://devblogs.microsoft.com/dotnet/performance-improvements-in-net-5/)

</details>

#### 📹 Videos

<div align="right">
  <b><a href="#contents">↥ Back To Top</a></b>
</div>

## .Net CLI

### 📝 Articles

<details><summary>Links</summary>
	
* [.NET CLI overview](https://docs.microsoft.com/en-us/dotnet/core/tools/)
* [Custom templates for dotnet new](https://docs.microsoft.com/en-us/dotnet/core/tools/custom-templates)

</details>

<div align="right">
  <b><a href="#contents">↥ Back To Top</a></b>
</div>


## .Net Tools

### 📝 Articles
* [Using .NET Core Tools to Create Reusable and Shareable Tools & Apps](https://weblog.west-wind.com/posts/2020/Aug/05/Using-NET-Core-Tools-to-Create-Reusable-and-Shareable-Tools-Apps)
* [How to manage .NET tools](https://docs.microsoft.com/en-us/dotnet/core/tools/global-tools)
* [dotnet tool search](https://docs.microsoft.com/en-us/dotnet/core/tools/dotnet-tool-search)
* [dotnet tool install](https://docs.microsoft.com/en-us/dotnet/core/tools/dotnet-tool-install)
* [dotnet tool list](https://docs.microsoft.com/en-us/dotnet/core/tools/dotnet-tool-list)
* [Tutorial: Create a .NET tool using the .NET CLI](https://docs.microsoft.com/en-us/dotnet/core/tools/global-tools-how-to-create)
* [Collect diagnostics in containers](https://docs.microsoft.com/en-us/dotnet/core/diagnostics/diagnostics-in-containers)

### 📦 Libraries
* [dotnet-tools](https://github.com/natemcmaster/dotnet-tools)
> A list of tools to extend the .NET Core command line (dotnet)
* [Investigate performance counters (dotnet-counters)](https://docs.microsoft.com/en-us/dotnet/core/diagnostics/dotnet-counters)
> .NET Core Performance Counter Tool


<div align="right">
  <b><a href="#contents">↥ Back To Top</a></b>
</div>

## .Net Core Tips

### 📝 Articles

* [https://github.com/davidfowl/AspNetCoreDiagnosticScenarios/blob/master/AspNetCoreGuidance.md](https://github.com/davidfowl/AspNetCoreDiagnosticScenarios/blob/master/AspNetCoreGuidance.md)

### 🔖 Samples

* [https://github.com/davidfowl/AspNetCoreDiagnosticScenarios](https://github.com/davidfowl/AspNetCoreDiagnosticScenarios)
	> This repository has examples of broken patterns in ASP.NET Core applications

## C#

### C# 7

#### 📝 Articles


### C# 8

#### 📝 Articles


### C# 9

#### 📝 Articles
- [Top-level programs in C# 9.0](https://gunnarpeipman.com/csharp-top-level-programs/) - Gunnar Peipman
- [Explore ideas using top-level statements to build code as you learn](https://docs.microsoft.com/en-us/dotnet/csharp/whats-new/tutorials/top-level-statements) - Microsoft
- [PLAYING WITH C#9 TOP-LEVEL PROGRAMS, RECORDS AND ELASTICSEARCH.NET](https://www.stevejgordon.co.uk/playing-with-csharp-9-top-level-programs-records-and-elasticsearch-dotnet)
- [Using Tuples in C# to Initialize Properties in the Constructor and to Deconstruct Your Object](https://www.thomasclaudiushuber.com/2021/03/25/csharp-using-tuples-to-initialize-properties/)

## MetaPack

### 📝 Articles
* [Microsoft.AspNetCore.App for ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/metapackage-app)
* [Microsoft.AspNetCore.All metapackage for ASP.NET Core 2.0](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/metapackage)
* [Deep-dive into .NET Core primitives, part 2: the shared framework](https://b2n.ir/083540)
* [Framework Reference](https://docs.microsoft.com/en-us/aspnet/core/migration/22-to-30?view=aspnetcore-5.0&tabs=visual-studio#framework-reference)
* [Deep-dive into .NET Core primitives: deps.json, runtimeconfig.json, and dll's](https://natemcmaster.com/blog/2017/12/21/netcore-primitives/)
* [Deep-dive into .NET Core primitives, part 2: the shared framework](https://natemcmaster.com/blog/2018/08/29/netcore-primitives-2/)
* [Deep-dive into .NET Core primitives, part 3: runtimeconfig.json in depth](https://natemcmaster.com/blog/2019/01/09/netcore-primitives-3/)

<div align="right">
  <b><a href="#contents">↥ Back To Top</a></b>
</div>

## MAUI

### 📝 Articles

### Videos
* [A Journey to .NET MAUI](https://channel9.msdn.com/Shows/On-NET/A-Journey-to-NET-MAUI)
<div align="right">
  <b><a href="#contents">↥ Back To Top</a></b>
</div>

## Source Generators

### 📝 Articles
* [Strongly-typed Ids using C# Source Generators - Gérald Barré](https://www.meziantou.net/strongly-typed-ids-with-csharp-source-generators.htm)
* [Introducing C# Source Generators - DevBlogs](https://devblogs.microsoft.com/dotnet/introducing-c-source-generators/)

<div align="right">
  <b><a href="#contents">↥ Back To Top</a></b>
</div>

## Performance

### Resources

* [https://github.com/adamsitnik/awesome-dot-net-performance](https://github.com/adamsitnik/awesome-dot-net-performance)

### 📝 Articles
* [ASP.NET Core Performance Best Practices](https://docs.microsoft.com/en-us/aspnet/core/performance/performance-best-practices)
* [Memory management and garbage collection (GC) in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/performance/memory)
* [ASP.NET Core load/stress testing](https://docs.microsoft.com/en-us/aspnet/core/test/load-tests)

## Serialization

### 📝 Articles
* [How to serialize and deserialize (marshal and unmarshal) JSON in .NET](https://docs.microsoft.com/en-us/dotnet/standard/serialization/system-text-json-how-to)
* [How to migrate from Newtonsoft.Json to System.Text.Json](https://docs.microsoft.com/en-us/dotnet/standard/serialization/system-text-json-migrate-from-newtonsoft-how-to)
* [Polymorphic deserialization with System.Text.Json](https://josef.codes/polymorphic-deserialization-with-system-text-json/)
* [Using MessagePack with ASP.NET Core MVC](https://www.strathweb.com/2017/06/using-messagepack-with-asp-net-core-mvc/)
* [Using MessagePack with ASP.NET Core WebAPI](https://dotnetthoughts.net/using-message-pack-with-asp-net-core/)
### Library
* [MessagePack-CSharp](https://github.com/neuecc/MessagePack-CSharp)
	> Extremely Fast MessagePack Serializer for C#(.NET, .NET Core, Unity, Xamarin). / msgpack.org[C#]
	
* [Utf8Json](https://github.com/neuecc/Utf8Json)
	> Definitely Fastest and Zero Allocation JSON Serializer for C#(NET, .NET Core, Unity, Xamarin).
	
<div align="right">
  <b><a href="#contents">↥ Back To Top</a></b>
</div>


## Generic Host And Web Host

### 📝 Articles
* [ASP.NET Core Web Host](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/host/web-host?view=aspnetcore-5.0)
* [.NET Generic Host in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/host/generic-host?view=aspnetcore-5.0)
* [USING HOSTBUILDER AND THE GENERIC HOST IN .NET CORE MICROSERVICES](https://www.stevejgordon.co.uk/using-generic-host-in-dotnet-core-console-based-microservices)
* [Generic Host Builder in ASP .NET Core 3.1](https://wakeupandcode.com/generic-host-builder-in-asp-net-core-3-1/)
* [The ASP.NET Core Generic Host: namespace clashes and extension methods](https://andrewlock.net/the-asp-net-core-generic-host-namespace-clashes-and-extension-methods/)
* [Avoiding Startup service injection in ASP.NET Core 3](https://andrewlock.net/avoiding-startup-service-injection-in-asp-net-core-3/)
* [IHostingEnvironment vs IHostEnvironment - obsolete types in .NET Core 3.0](https://andrewlock.net/ihostingenvironment-vs-ihost-environment-obsolete-types-in-net-core-3/#asp-net-core-merges-with-the-generic-host)
* [.NET Generic Host](https://docs.microsoft.com/en-us/dotnet/core/extensions/generic-host)
* [Understanding .NET Generic Host Model](https://sahansera.dev/dotnet-core-generic-host/)
* [Exploring the new project file, Program.cs, and the generic host](https://andrewlock.net/exploring-the-new-project-file-program-and-the-generic-host-in-asp-net-core-3/)
* [Introducing IHostLifetime and untangling the Generic Host startup interactions](https://andrewlock.net/introducing-ihostlifetime-and-untangling-the-generic-host-startup-interactions/)
* [Exploring Program.cs, Startup.cs and CreateDefaultBuilder in ASP.NET Core 2 preview 1](https://andrewlock.net/exploring-program-and-startup-in-asp-net-core-2-preview1-2/)
* [WebHostBuilder](https://girishgodage.in/blog/customize-webhostbuilder)
* [Customizing ASP.​NET Core Part 11: WebHostBuilder](https://asp.net-hacker.rocks/2019/01/30/customizing-aspnetcore-11-webhostbuilder.html)

### 🔖 Samples
* [https://github.com/andrewlock/blog-examples/tree/master/updating-test-host-to-3-0](https://github.com/andrewlock/blog-examples/tree/master/updating-test-host-to-3-0)

<div align="right">
  <b><a href="#contents">↥ Back To Top</a></b>
</div>


## DotNet Core Architecture 

### 📝 Articles
* [ASP.NET CORE ANATOMY – HOW DOES USESTARTUP WORK?](https://www.stevejgordon.co.uk/aspnet-core-anatomy-how-does-usestartup-work)
* [ASP.NET CORE ANATOMY (PART 2) – ADDMVC](https://www.stevejgordon.co.uk/asp-net-core-anatomy-part-2-addmvc)
* [ASP.NET CORE ANATOMY (PART 3) – USEMVC](https://www.stevejgordon.co.uk/asp-net-core-anatomy-part-3-addmvc)
* [ASP.NET CORE ANATOMY (PART 4) – INVOKING THE MVC MIDDLEWARE](https://www.stevejgordon.co.uk/invoking-mvc-middleware-asp-net-core-anatomy-part-4)
* [Deep-dive into .NET Core primitives: deps.json, runtimeconfig.json, and dll's](https://natemcmaster.com/blog/2017/12/21/netcore-primitives/)
* [Deep-dive into .NET Core primitives, part 2: the shared framework](https://natemcmaster.com/blog/2018/08/29/netcore-primitives-2/)
* [Deep-dive into .NET Core primitives, part 3: runtimeconfig.json in depth](https://natemcmaster.com/blog/2019/01/09/netcore-primitives-3/)

### 📹 Videos
* [ASP.NET Community Standup - ASP.NET Core Architecture with David Fowler](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/watch?v=d9Bjg31VuHw&feature=emb_title)
* [Munich .NET Meetup: Anatomy of ASP.NET Core Requests by Steve Gordon](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/watch?v=zMU_LGbTsCQ&feature=w7.mul.ir/yo%7cut%7cu.%7cbe)
<div align="right">
  <b><a href="#contents">↥ Back To Top</a></b>
</div>

## Hosting

### 📝 Articles
* [5 ways to set the URLs for an ASP.NET Core app](https://andrewlock.net/5-ways-to-set-the-urls-for-an-aspnetcore-app/)
* [Adding host filtering to Kestrel in ASP.NET Core](https://andrewlock.net/adding-host-filtering-to-kestrel-in-aspnetcore/)
* [ASP. NET Core - Hosting](https://girishgodage.in/blog/customize-hosting)
* [Customizing ASP.NET Core Part 12: Hosting](https://asp.net-hacker.rocks/2019/04/29/customizing-aspnetcore-12-hosting.html)
* [ASP.NET Core Hosting on IIS on Windows](https://procodeguide.com/programming/asp-net-core-hosting-on-iis/)
* [Hosting Two ASP.NET Core Apps In One Host](https://khalidabuhakmeh.com/hosting-two-aspnet-core-apps-in-one-host)

<div align="right">
  <b><a href="#contents">↥ Back To Top</a></b>
</div>

## Kestrel

### 📝 Articles
* [Kestrel web server implementation in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/servers/kestrel?view=aspnetcore-5.0)
* [.NET Core 3.0 AllowSynchronousIO Workaround](https://khalidabuhakmeh.com/dotnet-core-3-dot-0-allowsynchronousio-workaround)

### 📹 Videos
* [Custom HTTPS Dev Environment using .NET Core, Kestrel & certificates](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/watch?v=96KHOaIe19w&list=PLpSmZmoBaROZm0ucoQchgBJJ_SyTZWbC0&index=3&t=2090s)

<div align="right">
  <b><a href="#contents">↥ Back To Top</a></b>
</div>

## Middleware

### 📝 Articles
* [DEEP DIVE: HOW IS THE ASP.NET CORE MIDDLEWARE PIPELINE BUILT?](https://www.stevejgordon.co.uk/how-is-the-asp-net-core-middleware-pipeline-built)
* [ASP.NET Core Middleware](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/middleware/?view=aspnetcore-5.0)
* [Understanding your middleware pipeline with the Middleware Analysis package](https://andrewlock.net/understanding-your-middleware-pipeline-with-the-middleware-analysis-package/)
* [Exploring IStartupFilter in ASP.NET Core](https://andrewlock.net/exploring-istartupfilter-in-asp-net-core/)
* [Creating an endpoint from multiple middleware in ASP.NET Core 3.x](https://andrewlock.net/creating-an-endpoint-from-multiple-middleware-in-aspnetcore-3/)
* [Converting a terminal middleware to endpoint routing in ASP.NET Core 3.0](https://andrewlock.net/converting-a-terminal-middleware-to-endpoint-routing-in-aspnetcore-3/)
* [Middlewares](https://girishgodage.in/blog/customize-middleware)
* [Customizing ASP.​NET Core Part 06: Middlewares](https://asp.net-hacker.rocks/2018/10/08/customizing-aspnetcore-06-middlewares.html)
* [Styles of Writing ASP.NET Core Middleware](http://stevetalkscode.co.uk/middleware-styles)
* [Middleware vs Filters ASP. NET Core](https://www.edgesidesolutions.com/middleware-vs-filters-asp-net-core/)
* [Exploring Middleware as MVC Filters in ASP.NET Core 1.1](https://andrewlock.net/exploring-middleware-as-mvc-filters-in-asp-net-core-1-1/)
### Videos
* [ASP.NET Monsters #91: Middleware vs. Filters](https://channel9.msdn.com/Series/aspnetmonsters/ASPNET-Monsters-91-Middleware-vs-Filters)

<div align="right">
  <b><a href="#contents">↥ Back To Top</a></b>
</div>

## Action Filters

### 📝 Articles
* [Exploring Middleware as MVC Filters in ASP.NET Core 1.1](https://andrewlock.net/exploring-middleware-as-mvc-filters-in-asp-net-core-1-1/)


## Configuration

### 📝 Articles
* [Configure ASP.NET Core MVC](https://www.programmingwithwolfgang.com/configure-asp-net-core-mvc/)
* [Configuration in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/configuration)
* [Configuration providers in .NET](https://docs.microsoft.com/en-us/dotnet/core/extensions/configuration-providers)
* [ASP. NET Core - Customize Configuration](https://girishgodage.in/blog/customize-configuration)
* [Creating a custom ConfigurationProvider in ASP.NET Core to parse YAML](https://andrewlock.net/creating-a-custom-iconfigurationprovider-in-asp-net-core-to-parse-yaml/)
* [Customizing ASP.​NET Core Part 02: Configuration](https://asp.net-hacker.rocks/2018/09/24/customizing-aspnetcore-02-configuration.html)
* [How to use configuration with C# 9 top-level programs](https://daveabrock.com/2021/01/19/config-top-level-programs)
* [The dangers and gotchas of using scoped services in IConfigureOptions](https://andrewlock.net/the-dangers-and-gotchas-of-using-scoped-services-when-configuring-options-in-asp-net-core/)
* [Debugging configuration values in ASP.NET Core](https://andrewlock.net/debugging-configuration-values-in-aspnetcore/)
* [Viewing app configuration using Oakton's Describe command and Spectre.Console](https://andrewlock.net/viewing-application-configuration-using-oaktons-describe-command/)

### 📦 Libraries
* [NetEscapades.Configuration](https://github.com/andrewlock/NetEscapades.Configuration)


### 🔖 Samples
* [https://github.com/WolfgangOfner/MVC-Core-Configure](https://github.com/WolfgangOfner/MVC-Core-Configure)

<div align="right">
  <b><a href="#contents">↥ Back To Top</a></b>
</div>

## Options Pattern

### 📝 Articles
* [Options pattern in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/configuration/options)
* [How to use the IOptions pattern for configuration in ASP.NET Core RC2](https://andrewlock.net/how-to-use-the-ioptions-pattern-for-configuration-in-asp-net-core-rc2/)
* [Access services inside ConfigureServices using IConfigureOptions in ASP.NET Core](https://andrewlock.net/access-services-inside-options-and-startup-using-configureoptions/)
* [ASP.NET Core IOptions Configuration](https://khalidabuhakmeh.com/aspnet-core-ioptions-configuration)
* [Options Pattern in .NET Core](https://codeburst.io/options-pattern-in-net-core-a50285aeb18d)

<div align="right">
  <b><a href="#contents">↥ Back To Top</a></b>
</div>

## Grpc

### Resources
* [gRPC for WCF developers e-book](https://dotnet.microsoft.com/download/e-book/grpc-for-wcf-devs/pdf)

### 📝 Articles
* [Introduction to gRPC on .NET](https://docs.microsoft.com/en-us/aspnet/core/grpc/)
* [gRPC services with C#](https://docs.microsoft.com/en-us/aspnet/core/grpc/basics)
* [Create gRPC services and methods](https://docs.microsoft.com/en-us/aspnet/core/grpc/services)
* [Call gRPC services with the .NET client](https://docs.microsoft.com/en-us/aspnet/core/grpc/client)
* [gRPC client factory integration in .NET Core](https://docs.microsoft.com/en-us/aspnet/core/grpc/clientfactory)
* [gRPC and C# 8 Async stream](https://laurentkempe.com/2019/09/18/gRPC-and-csharp-8-Async-stream/)
* [gRPC and C# 8 Async stream cancellation](https://laurentkempe.com/2019/09/25/gRPC-and-csharp-8-Async-stream-cancellation/)
* [Code first gRPC services and clients with .NET](https://docs.microsoft.com/en-us/aspnet/core/grpc/code-first)
* [Create JSON Web APIs from gRPC](https://docs.microsoft.com/en-us/aspnet/core/grpc/httpapi)
* [gRPC and ASP.NET Core 5 Discover gRPCui the GUI alternative to gRPCurl](https://anthonygiretti.com/2021/01/17/grpc-asp-net-core-5-discover-grpcui-the-gui-alternative-to-grpcurl/) - Anthony Giretti
* [gRPC and ASP.NET Core 5 Add a gRPC service reference from a remote protobuf over Route-To-Code](https://anthonygiretti.com/2021/01/25/grpc-asp-net-core-5-add-a-grpc-service-reference-from-a-remote-protobuf-over-route-to-code/) - Anthony Giretti
* [gRPC and ASP.NET Core 5 Test gRPC endpoints with gRPCurl](https://anthonygiretti.com/2021/01/13/grpc-asp-net-core-5-test-grpc-endpoints-with-grpcurl/) - Anthony Giretti
* [Using gRPC in Microservices for Building a high-performance Interservice Communication with .Net 5](https://medium.com/aspnetrun/using-grpc-in-microservices-for-building-a-high-performance-interservice-communication-with-net-5-11f3e5fa0e9d)

### 📹 Videos
* [Bidirectional Streaming | gRPC in .NET 5](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/watch?v=wY4nMSUF9e0)
* [Client Streaming | gRPC in .NET 5](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/watch?v=DNxdvRQ4qRQ)
* [gRPC Server & Unary Calls | gRPC in .NET 5](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/watch?v=hp5FTB7PI9s&t=0s)
* [Server Streaming | gRPC in .NET 5](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/watch?v=F2T6xNRoa1E&t=0s)
* [Secure .Net Microservices with IdentityServer4 OAuth2,OpenID](https://www.udemy.com/course/secure-net-microservices-with-identityserver4-oauth2openid/?couponCode=2E7C1D32B62DF23A5A7D)

### Samples
* [https://github.com/aspnetrun/run-aspnet-grpc](https://github.com/aspnetrun/run-aspnet-grpc)
	> Using gRPC in Microservices for Building a high-performance Interservice Communication with .Net 5. See gRPC Microservices and Step by Step Implementation on .NET Course w/ discount
	
<div align="right">
  <b><a href="#contents">↥ Back To Top</a></b>
</div>

## WebSockets 

### 📝 Articles
* [Understanding WebSockets with ASP.NET Core](https://sahansera.dev/understanding-websockets-with-aspnetcore-5/)
* [Using Web Sockets with ASP.NET Core](https://www.meziantou.net/using-web-sockets-with-asp-net-core.htm)
* [WebSockets support in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/websockets?view=aspnetcore-5.0)

<div align="right">
  <b><a href="#contents">↥ Back To Top</a></b>
</div>

## SignalR

### 📝 Articles
* [Use streaming in ASP.NET Core SignalR](https://docs.microsoft.com/en-us/aspnet/core/signalr/streaming?view=aspnetcore-5.0)
* [Real-time Web Applications with SignalR in ASP.NET Core 3.1](https://procodeguide.com/programming/real-time-web-with-signalr-in-aspnet-core/)

### 📹 Videos

* [Asp.Net Core WebSockets Vs SignalR. Which should you use?](https://www.youtube.com/watch?v=ycVgXe6v1VQ)

<div align="right">
  <b><a href="#contents">↥ Back To Top</a></b>
</div>

## HttpClient

### 📝 Articles
* [SENDING AND RECEIVING JSON USING HTTPCLIENT WITH SYSTEM.NET.HTTP.JSON](https://www.stevejgordon.co.uk/sending-and-receiving-json-using-httpclient-with-system-net-http-json)
* [.NET 5: Exploring System.Net.Http.Json namespace](https://anthonygiretti.com/2020/10/03/net-5-exploring-system-net-http-json-namespace/)
* [Introducing Strongly Typed HTTP Request Headers for ASP.NET Core](https://stevetalkscode.co.uk/stronglytypedheaders-part1)
* [Tidy up your HttpClient usage](https://josef.codes/tidy-up-your-httpclient-usage/)
* [You're (probably still) using HttpClient wrong and it is destabilizing your software](https://josef.codes/you-are-probably-still-using-httpclient-wrong-and-it-is-destabilizing-your-software/)
* [Using HTTPClient Best Practices and Anti-Patterns](https://www.thecodebuzz.com/using-httpclient-best-practices-and-anti-patterns/)

<div align="right">
  <b><a href="#contents">↥ Back To Top</a></b>
</div>

## WEB API

### Resources
* [https://github.com/oskardudycz/WebApiWith.NETCore](https://github.com/oskardudycz/WebApiWith.NETCore)
	> Samples and resources of how to design WebApi with .NET Core
* [REST API Tutorial](https://restfulapi.net/)
* [Let's Learn .NET - Web API](https://docs.microsoft.com/en-us/users/cloudskillschallenge/collections/o1qrbroy21p7?WT.mc_id=cloudskillschallenge_aa657376-2198-4cc9-9bba-38da7c199620)
* [.NET 5 REST API Tutorial](https://www.youtube.com/playlist?list=PLeD0-5Hw0ZJ_GlY21kfzfQD-N17i8pdTS)
* [Beginner's Series to: Web APIs](https://channel9.msdn.com/Series/Beginners-Series-to-Web-APIs)

### 📝 Articles
* [ASP.NET Core 5 Route to Code: Taking advantage of Microsoft.AspNetCore.Http json extensions](https://anthonygiretti.com/2020/09/29/asp-net-core-5-route-to-code-taking-advantage-of-microsoft-aspnetcore-http-json-extensions/)
* [Nano services with ASP.NET Core or how to build a light API](https://anthonygiretti.com/2020/06/29/nano-services-with-asp-net-core-or-how%20-to-build-a-light-api/)
* [Basic JSON APIs with Route-to-code in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/web-api/route-to-code)
* [Model Binding - ASP.NET Core Demystified](https://exceptionnotfound.net/asp-net-core-demystified-model-binding-in-mvc/)
* [Beautiful and compact Web APIs with C# 9, .NET 5.0 and ASP.NET Core](https://www.strathweb.com/2020/10/beautiful-and-compact-web-apis-with-c-9-net-5-0-and-asp-net-core/)
* [Building microservices with ASP.NET Core (without MVC)](https://www.strathweb.com/2017/01/building-microservices-with-asp-net-core-without-mvc/)
* [Finally the ASP.NET 5 Web API Blog Series!](https://chriswoodruff.com/finally-the-asp-net-5-web-api-blog-series/)
* [ASP.NET Core in .NET 5 – pass parameters to actions](https://www.michalbialecki.com/2020/05/07/asp-net-5-pass-parameters-to-actions/)
* [Model Binding in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/mvc/models/model-binding)
* [Custom Model Binding in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/mvc/advanced/custom-model-binding)
* [Asp.Net Core Model Binding: Controlling The Binding Source](https://hamidmosalla.com/2017/07/06/asp-net-core-model-binding-controlling-the-binding-source/)
* [Use ASP.NET Core route-to-code for simple JSON APIs](https://daveabrock.com/2020/12/04/migrate-mvc-to-route-to-code)
* [Using action results and content negotiation with route-to-code APIs](https://andrewlock.net/using-action-results-and-content-negotiation-with-route-to-code/)
* [Creating Discoverable HTTP APIs with ASP.NET Core 5 Web API](https://devblogs.microsoft.com/aspnet/creating-discoverable-http-apis-with-asp-net-core-5-web-api/?WT.mc_id=DOP-MVP-4025064&_lrsc=d4a12070-16f9-4d79-8171-918b6c254765&utm_campaign=elevate&utm_source=linkedin&utm_medium=social)
* [Open source HTTP API packages and tools](https://devblogs.microsoft.com/aspnet/open-source-http-api-packages-and-tools/) - Microsoft
* [MVC Controllers are Dinosaurs Embrace API Endpoints](https://ardalis.com/mvc-controllers-are-dinosaurs-embrace-api-endpoints/)
* [Moving from Controllers and Actions to Endpoints with MediatR](https://ardalis.com/moving-from-controllers-and-actions-to-endpoints-with-mediatr/) - Steve Smith
* [MVC Controllers are Dinosaurs - Embrace API Endpoints](https://ardalis.com/mvc-controllers-are-dinosaurs-embrace-api-endpoints/) - Steve Smith
* [Feature Slices for ASP.NET Core MVC](https://docs.microsoft.com/en-us/archive/msdn-magazine/2016/september/asp-net-core-feature-slices-for-asp-net-core-mvc) - Steve Smith
* [API Feature Folders](https://ardalis.com/api-feature-folders)
* [What is the difference between a DTO and a POCO (or POJO)](https://ardalis.com/dto-or-poco/?_lrsc=9fbcec7f-f420-4949-8e56-46bc78620801)
* [Give better names to your DTOs](https://cassiomolin.com/2016/02/11/give-better-names-to-your-dtos/)
* [Immutability in DTOs?](https://jimmybogard.com/immutability-in-dtos/)
* [Immutability in C#](https://www.codemag.com/Article/1905041/Immutability-in-C)
* [Trying the REST Client extension for VSCode](https://asp.net-hacker.rocks/2021/03/01/rest-client-vscode.html)
* [ASPNET Core Razor Pages – Worth Checking Out?](https://ardalis.com/aspnet-core-razor-pages-–-worth-checking-out/)
* [How To Build A Basic HTTP API With ASP.NET Core](https://khalidabuhakmeh.com/how-to-build-a-basic-http-api-with-aspnet-core)
* [Web API design](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design)
* [Microsoft REST API Guidelines](https://github.com/Microsoft/api-guidelines/blob/master/Guidelines.md)
* [Richardson Maturity Model](https://martinfowler.com/articles/richardsonMaturityModel.html)
* [RESTful API Design: 13 Best Practices to Make Your Users Happy](https://florimond.dev/blog/articles/2018/08/restful-api-design-13-best-practices-to-make-your-users-happy/)
* [Best Practices for Designing a Pragmatic RESTful API](https://www.vinaysahni.com/best-practices-for-a-pragmatic-restful-api)
* [The Web API Checklist -- 43 Things To Think About When Designing, Testing, and Releasing your API](https://mathieu.fenniak.net/the-api-checklist/)
* [Design Topics](http://apistylebook.com/design/topics/)
* [Design Guidelines](http://apistylebook.com/design/guidelines/)

### 📹 Videos
* [ASP.NET Core Series Route to Code](https://channel9.msdn.com/Shows/On-NET/ASPNET-Core-Series-Route-to-Code)
* [NET Core 3.1 MVC REST API - Full Course](https://www.youtube.com/watch?v=fmvcAzHpsk8)
* [Updating ASP.NET Core ApiEndpoints package and Fixing Dependent Projects](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/watch?v=BycGGcrYok4) - Steve Smith
* [ASP.NET Community Standup Flexible HTTP APIs](https://www.youtube.com/watch?v=xoYkk5jk8d0)
* [Let's Learn .NET - Web API](https://www.youtube.com/watch?v=BEJI2fy8MpA)
* [ASP.NET Community Standup - Building HTTP APIs](https://www.youtube.com/watch?v=Mpf0fCO6NrU)
* [Integrating PowerApps with .NET Web APIs](https://channel9.msdn.com/Shows/On-NET/Integrating-PowerApps-with-NET-Web-APIs)

### 📦 Libraries And Tools

* [framework](https://github.com/featherhttp/framework)
	> A lightweight low ceremony API for web services.
	
* [ApiEndpoints](https://github.com/ardalis/ApiEndpoints) - Steve Smith
	> A project for supporting API Endpoints in ASP.NET Core web applications.
	
* [Carter](https://github.com/CarterCommunity/Carter)
	> Carter is framework that is a thin layer of extension methods and functionality over ASP.NET Core allowing code to be more explicit and most importantly more enjoyable.
	
* [refit](https://github.com/reactiveui/refit)
	> The automatic type-safe REST library for .NET Core, Xamarin and .NET. Heavily inspired by Square's Retrofit library, Refit turns your REST API into a live interface.
	
* [RestEase](https://github.com/canton7/RestEase)
	> Easy-to-use typesafe REST API client library for .NET Standard 1.1 and .NET Framework 4.5 and higher, which is simple and customisable. Inspired by Refit
	
* [HttpRepl](https://github.com/dotnet/HttpRepl)
	> The HTTP Read-Eval-Print Loop (REPL) is a lightweight, cross-platform command-line tool that's supported everywhere .NET Core is supported and is used for making HTTP requests to test ASP.NET Core web APIs and view their results.

* [rest-client](https://marketplace.visualstudio.com/items?itemName=humao.rest-client)
	> REST Client allows you to send HTTP request and view the response in Visual Studio Code directly.
	
* [Swashbuckle.AspNetCore](https://github.com/domaindrivendev/Swashbuckle.AspNetCore)
	> Swagger tools for documenting API's built on ASP.NET Core

* [OpenAPI.NET](https://github.com/microsoft/OpenAPI.NET)
	> The OpenAPI.NET SDK contains a useful object model for OpenAPI documents in .NET along with common serializers to extract raw OpenAPI JSON and YAML documents from the model.

* [NSwag](https://github.com/RicoSuter/NSwag)
	> The Swagger/OpenAPI toolchain for .NET, ASP.NET Core and TypeScript.
	
* [Crunch.vscode-openapi](https://marketplace.visualstudio.com/items?itemName=42Crunch.vscode-openapi)
	> This Visual Studio Code (VS Code) extension adds rich support for the OpenAPI Specification (OAS) (formerly known as Swagger Specification) in JSON or YAML format

### 🔖 Samples
* [https://github.com/featherhttp/tutorial](https://github.com/featherhttp/tutorial)
* [https://github.com/filipw/net50-webapi-samples](https://github.com/filipw/net50-webapi-samples)
* [https://github.com/ardalis/MediatRAspNetCore](https://github.com/ardalis/MediatRAspNetCore) - Steve Smith
* [https://github.com/dotnet-architecture/eShopOnWeb/tree/master/src/PublicApi](https://github.com/dotnet-architecture/eShopOnWeb/tree/master/src/PublicApi)


### Templates

* [https://github.com/proudmonkey/ApiBoilerPlate](https://github.com/proudmonkey/ApiBoilerPlate)
	> A simple yet organized project template for building ASP.NET Core APIs in .NET Core 3.1

* [https://github.com/blazorhero/CleanArchitecture](https://github.com/blazorhero/CleanArchitecture)
	> Clean Architecture Template for Blazor WebAssembly Built with MudBlazor Components.
	
### Books
- [REST API Design Rulebook](http://shop.oreilly.com/product/0636920021575.do)
- [The Design of Web APIs](https://www.manning.com/books/the-design-of-web-apis)

<div align="right">
  <b><a href="#contents">↥ Back To Top</a></b>
</div>


## Background Tasks

### 📝 Articles

* [Background Tasks in .NET](https://codeopinion.com/background-tasks/) - CodeOpinion
* [Mediator Pattern with Hangfire](https://codeopinion.com/mediator-pattern-hangfire/) - CodeOpinion
* [Processing commands with Hangfire and MediatR](http://www.kamilgrzybek.com/design/processing-commands-with-hangfire-and-mediatr/) - Kamil Grzybek
* [Use Quartz.Net for background and recurring jobs within an ASP.NET Core 3.0 applicati](https://blog.vfrz.fr/quartz-asp-net-core-3-0/)
* [How to run Background Tasks in ASP.NET](https://www.hanselman.com/blog/how-to-run-background-tasks-in-aspnet)
* [Using Quartz.NET with ASP.NET Core and worker services](https://andrewlock.net/using-quartz-net-with-asp-net-core-and-worker-services/)
* [Creating a Quartz.NET hosted service with ASP.NET Core](https://andrewlock.net/creating-a-quartz-net-hosted-service-with-asp-net-core/)
* [Using scoped services inside a Quartz.NET hosted service with ASP.NET Core](https://andrewlock.net/using-scoped-services-inside-a-quartz-net-hosted-service-with-asp-net-core/)


## Validation

### 📝 Articles

### Library
 * [GuardClauses](https://github.com/ardalis/GuardClauses)
	> A simple package with guard clause extensions.
	
## Razor Pages

### 📝 Articles
* [Razor Pages for HTML Controllers for APIs](https://odetocode.com/blogs/scott/archive/2019/09/12/net-core-opinion-14-razor-pages-for-html-controllers.aspx) - Scott Allen
* [Separating concerns using Razor Pages](https://jonhilton.net/razor-pages-separation-of-concerns/) - Jon Hilton
* [MVC vs Razor Pages A quick comparison](https://jonhilton.net/razor-pages-or-mvc-a-quick-comparison/) - Jon Hilton
* [Applying the MVC design pattern to Razor Pages](https://andrewlock.net/aspnetcore-in-action-2e-applying-the-mvc-design-pattern-to-razor-pages/) - Andrew Lock
* [MSDN – Feature Slices for ASPNET Core MVC](https://ardalis.com/msdn-–-feature-slices-for-aspnet-core-mvc/) - Steve Smith
* [Feature Slices for ASP.NET Core MVC](https://docs.microsoft.com/en-us/archive/msdn-magazine/2016/september/asp-net-core-feature-slices-for-asp-net-core-mvc) - Steve Smith
* [ASPNET Core Razor Pages – Worth Checking Out?](https://ardalis.com/aspnet-core-razor-pages-–-worth-checking-out/)
* [Simpler ASP.NET MVC Apps with Razor Pages](https://docs.microsoft.com/en-us/archive/msdn-magazine/2017/september/asp-net-core-simpler-asp-net-mvc-apps-with-razor-pages)
### 📹 Videos
* [Introduction to ASP.NET Core Razor Pages](https://www.youtube.com/watch?v=yyBijyCI5Sk) 
* [ASP.NET Core Series MVC and Razor Pages](https://www.youtube.com/watch?v=6GRFDkeCv3k&t=1264s)

### 🔖 Samples
* [https://github.com/ardalis/OrganizingAspNetCore](https://github.com/ardalis/OrganizingAspNetCore) - Steve Smith
* [https://github.com/jbogard/ContosoUniversityDotNetCore-Pages](https://github.com/jbogard/ContosoUniversityDotNetCore-Pages)
## GraphQL

### 📝 Articles
* [Hot Chocolate GraphQL Custom Authentication Series Using Pure Code First Technique - Part1 - User Registration](https://www.learmoreseekmore.com/2021/03/part1-hotchocolate-graphql-custom-authentication-series-using-pure-code-first-technique-user-registration.html)
* [Hot Chocolate GraphQL Custom Authentication Series Using Pure Code First Technique - Part2 - Generating JWT(JSON Web Token) Access Token](https://www.learmoreseekmore.com/2021/03/part-2-hotchocolate-graphql-custom-authentication-series-using-purecodefirst-generating-jwt-access-token.html)
* [Hot Chocolate GraphQL Custom Authentication Series Using Pure Code First Technique - Part4 - Refresh Token](https://www.learmoreseekmore.com/2021/03/part4-hotchocolate-graphql-custom-authentication-series-using-purecodefirst-refresh-token.html)
### 📹 Videos
* [GraphQL API with .NET 5 and Hot Chocolate](https://www.youtube.com/watch?v=HuN94qNwQmM)
* [On .NET Live - Creating GraphQL APIs with a little Hot Chocolate](https://www.youtube.com/watch?v=LfPc0sitoR4)

<div align="right">
  <b><a href="#contents">↥ Back To Top</a></b>
</div>

## NoSQL

### Videos
* [Google I/O 2012 - SQL vs NoSQL: Battle of the Backends](https://www.youtube.com/watch?v=rRoy6I4gKWU)
* [SQL vs NoSQL or MySQL vs MongoDB](https://www.youtube.com/watch?v=ZS_kXvOeQ5Y)
* [GOTO 2012 • Introduction to NoSQL • Martin Fowler](https://www.youtube.com/watch?v=qI_g07C_Q5I)

### Articles
* [NOSQL vs SQL. Key differences and when to choose each](https://pandorafms.com/blog/nosql-vs-sql-key-differences/)

### CosmosDB
* [Azure Cosmos DB - A fully-managed, globally distributed NoSQL database service](https://stackshare.io/azure-cosmos-db) - StackShare

#### Articles
* [An in-depth study of Cosmos DB and the EF Core 3 to 5 database provider](https://www.thereformedprogrammer.net/an-in-depth-study-of-cosmos-db-and-ef-core-3-0-database-provider/)
* [Building a robust CQRS database with EF Core and Cosmos DB](https://www.thereformedprogrammer.net/building-a-robust-cqrs-database-with-ef-core-and-cosmos-db/)
* [Cars Island ASP .NET Core API - integration with Azure Cosmos DB - part 3](https://daniel-krzyczkowski.github.io/Cars-Island-ASP-NET-Core-API-Integration-With-Azure-Cosmos-DB/)

### PostgreSQL
- [PostgreSQL - A powerful, open source object-relational database system](https://stackshare.io/postgresql) - StackShare

#### Articles
- [PostgreSQL Vs. MongoDB](https://blog.panoply.io/postgresql-vs-mongodb)


#### 📹 Videos
* [Integrating ASP.NET Core API with Postgres & OData in Azure](https://www.youtube.com/watch?v=MoDJnEwkYOE) - Hassan Habib
* [ASP.NET Core, C#, EF Core, PostgreSQL, WSL2 - PostreSQL Setup - Tricking Library Ep62](https://www.youtube.com/watch?v=qWfavvrhrfk)
* [Comparison of PostgreSQL and MongoDB](https://www.youtube.com/watch?v=eM7hzKwvTq8)
* [Learn PostgreSQL Tutorial - Full Course for Beginners](https://www.youtube.com/watch?v=qw--VYLpxG4)

### MongoDB
* [MongoDB - The database for giant ideas](https://stackshare.io/mongodb)

### RavenDB
* [RavenDB - A NoSQL Database that's fully transactional](https://stackshare.io/raven-db) - StackShare

## Docker

### 📝 Articles

### 📹 Videos
* [Deploy a .NET Core API with Docker (Step-by-Step)](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/watch?v=f0lMGPB10bM&list=PLpSmZmoBaROZm0ucoQchgBJJ_SyTZWbC0&index=5&t=52s)

## API Versioning

### 📝 Articles
* [Web API Versioning in ASP.NET Core Detailed Guide](https://procodeguide.com/programming/asp-net-core-web-api-versioning/)
* [ASP.NET Core RESTful Web API versioning made easy](https://www.hanselman.com/blog/aspnet-core-restful-web-api-versioning-made-easy) - Sccot Honselman
### 📹 Videos
* [Elegant API Versioning in ASP.NET Core (Web API)](http://w7.mul.ir/yo%7cut%7cu.%7cbe/iVHtKG0eU_s)

<div align="right">
  <b><a href="#contents">↥ Back To Top</a></b>
</div>

## Hosted Service

### 📝 Articles
* [Background tasks with hosted services in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/host/hosted-services)
* [IMPLEMENTING IHOSTEDSERVICE IN ASP.NET CORE 2.0](https://www.stevejgordon.co.uk/asp-net-core-2-ihostedservice)
* [ASP. NET Core - IHostedService and BackgroundService](https://girishgodage.in/blog/customize-hostedservices)
* [Customizing ASP.​NET Core Part 05: HostedServices](https://asp.net-hacker.rocks/2018/10/04/customizing-aspnetcore-05-hostedservices.html)

<div align="right">
  <b><a href="#contents">↥ Back To Top</a></b>
</div>

## Test Host And WebApplicationFactory

### 📝 Articles
* [Converting integration tests to .NET Core 3.0](https://andrewlock.net/converting-integration-tests-to-net-core-3/)
* [Using custom startup class with ASP.NET Core integration tests](https://gunnarpeipman.com/aspnet-core-integration-test-startup/)
* [Using custom appsettings.json with ASP.NET Core integration tests](https://gunnarpeipman.com/aspnet-core-integration-tests-appsettings/)
* [Testing WebAPI with ApprovalTests.NET](https://cezarypiatek.github.io/post/testing-web-api-with-approval-tests/)
<div align="right">
  <b><a href="#contents">↥ Back To Top</a></b>
</div>

## Routing

<div align="right">
  <b><a href="#contents">↥ Back To Top</a></b>
</div>

## Dependency Injection

### 📝 Articles
* [.NET Core Dependency Injection: Everything You Ought To Know](https://www.blog.jamesmichaelhickey.com/NET-Core-Dependency-Injection/)
* [Dependency injection in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/dependency-injection)
* [Inversion of Control Containers and the Dependency Injection pattern](https://martinfowler.com/articles/injection.html)
* [Having Fun with Microsoft IoC Container for .NET Core](https://sahansera.dev/dotnet-core-ioc-container/)
* [ASP. NET Core - Dependency-injection](https://girishgodage.in/blog/customize-dependency-injection)
* [Customizing ASP.​NET Core Part 03: Dependency Injection](https://asp.net-hacker.rocks/2018/09/27/customizing-aspnetcore-03-dependency-injection.html)
* [ASP.NET CORE DEPENDENCY INJECTION – REGISTERING MULTIPLE IMPLEMENTATIONS OF AN INTERFACE](https://www.stevejgordon.co.uk/asp-net-core-dependency-injection-registering-multiple-implementations-interface)
* [ASP.NET CORE DEPENDENCY INJECTION – HOW TO REGISTER GENERIC TYPES](https://www.stevejgordon.co.uk/asp-net-core-dependency-injection-how-to-register-generic-types)
* [ASP.NET CORE DEPENDENCY INJECTION – REGISTERING IMPLEMENTATIONS USING DELEGATES](https://www.stevejgordon.co.uk/asp-net-core-dependency-injection-registering-implementations-using-delegates)
* [Choosing a ServiceLifetime](https://jimmybogard.com/choosing-a-servicelifetime/?utm_source=feedburner&utm_medium=feed&utm_campaign=Feed%3A+GrabBagOfT+%28Jimmy+Bogard%29)
* [ASP.NET Core and the Strategy Pattern](https://adamstorr.azurewebsites.net/blog/aspnetcore-and-the-strategy-pattern)
* [6 Ways To Implement The Strategy Pattern In C# (Basic To Advanced)](https://www.blog.jamesmichaelhickey.com/strategy-pattern-implementations/)
* [Dependency Injection in ASP.NET Core 3.1](https://procodeguide.com/programming/dependency-injection-in-asp-net-core-3/)
* [Understanding Disposables In .NET Dependency Injection – Part 2](http://stevetalkscode.co.uk/disposables-in-di-part-2)
* [Understanding Disposables In .NET Dependency Injection – Part 1](https://stevetalkscode.co.uk/disposables-in-di-part-1)
* [Should I be Checking Injected Dependencies for Null?](http://stevetalkscode.co.uk/null-injection)
* [Getting Dependencies by Name or Key using the .NET Core Container (Part 1)](http://stevetalkscode.co.uk/named-dependencies-part-1#comment-750)
* [ASP.NET CORE DEPENDENCY INJECTION WHAT IS THE ISERVICECOLLECTION?](https://www.stevejgordon.co.uk/aspnet-core-dependency-injection-what-is-the-iservicecollection) - Steve Gordon
* [Avoiding Startup service injection in ASP.NET Core 3](https://andrewlock.net/avoiding-startup-service-injection-in-asp-net-core-3/)
* [What are the costs and possible side effects of calling BuildServiceProvider() in ConfigureServices()](https://stackoverflow.com/questions/56042989/what-are-the-costs-and-possible-side-effects-of-calling-buildserviceprovider-i)
* [Resolve and Initialize the Instances within ConfigServices of ASP.NET Core](https://www.thecodebuzz.com/resolve-instances-within-configservices-method-asp-net-core/)
* [How to Resolve Instance Inside ConfigureServices in ASP.NET Core](https://stackoverflow.com/questions/31863981/how-to-resolve-instance-inside-configureservices-in-asp-net-core)
* [Access services inside ConfigureServices using IConfigureOptions in ASP.NET Core](https://andrewlock.net/access-services-inside-options-and-startup-using-configureoptions/)
* [Using dependency injection while configuring services](https://benjamincollins.com/blog/using-dependency-injection-while-configuring-services/)
* [ASP.NET CORE DEPENDENCY INJECTION: WHAT IS THE ISERVICEPROVIDER AND HOW IS IT BUILT?](https://www.stevejgordon.co.uk/aspnet-core-dependency-injection-what-is-the-iserviceprovider-and-how-is-it-built) - Steve Gordon
* [How to register a service with multiple interfaces in ASP.NET Core DI](https://andrewlock.net/how-to-register-a-service-with-multiple-interfaces-for-in-asp-net-core-di/)
* [A .NET Core ServiceProvider that allows adding of services after it was created](https://siderite.dev/blog/a-net-core-serviceprovider-that-allows.html/)
* [The difference between GetService() and GetRequiredService() in ASP.NET Core](https://andrewlock.net/the-difference-between-getservice-and-getrquiredservice-in-asp-net-core/)
* [Resolve Services In ASP.NET Core Startup](https://khalidabuhakmeh.com/resolve-services-in-aspnet-core-startup)
* [Automatic factory with Microsoft.Extensions.DependencyInjection and Castle DynamicProxy](https://thomaslevesque.com/2020/09/27/automatic-factory-with-microsoft-extensions-dependencyinjection-and-castle-dynamicproxy/)

### Libraries
 * [https://github.com/AnthonyGiretti/calzolari-dependencyinjection-extensions](https://github.com/AnthonyGiretti/calzolari-dependencyinjection-extensions)
	> Extensions for ASP.NET Core dependency injection
	
<div align="right">
  <b><a href="#contents">↥ Back To Top</a></b>
</div>

## Security

### Encryption And Data Protection

#### 📝 Articles
* [Symmetric and Asymmetric Encryption in .NET Core](https://damienbod.com/2020/08/19/symmetric-and-asymmetric-encryption-in-net-core/)
* [ENCRYPTING TEXTS FOR AN IDENTITY IN ASP.NET CORE RAZOR PAGES USING AES AND RSA](https://damienbod.com/2020/08/22/encrypting-texts-for-an-identity-in-asp-net-core-razor-pages-using-aes-and-rsa/)
* [USING DIGITAL SIGNATURES TO CHECK INTEGRITY OF CIPHER TEXTS IN ASP.NET CORE RAZOR PAGES](https://damienbod.com/2020/09/01/using-digital-signatures-to-check-integrity-of-cipher-texts-in-asp-net-core-razor-pages/)
* [Configure ASP.NET Core Data Protection](https://docs.microsoft.com/en-us/aspnet/core/security/data-protection/configuration/overview)
* [An introduction to the Data Protection system in ASP.NET Core](https://andrewlock.net/an-introduction-to-the-data-protection-system-in-asp-net-core/)

<div align="right">
  <b><a href="#contents">↥ Back To Top</a></b>
</div>

### DotNet Core Identity

#### 📝 Articles
* [ASP.NET Core Identity – Getting Started](https://procodeguide.com/programming/asp-net-core-identity/)
* [Overview of ASP.NET Core authentication](https://docs.microsoft.com/en-us/aspnet/core/security/authentication/)
* [Introduction to Identity on ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/security/authentication/identity)
* [Identity model customization in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/security/authentication/customize-identity-model)
* [ASP NET Core Identity Tutorial](https://www.tektutorialshub.com/asp-net-core/asp-net-core-identity-tutorial/)
* [Login and Registration using Identity in ASP.NET Core 3.1](https://www.freecodespot.com/blog/asp-net-core-identity/)
* [Custom User Management in ASP.NET Core MVC with Identity](https://codewithmukesh.com/blog/user-management-in-aspnet-core-mvc/)

#### Samples
* [https://github.com/iammukeshm/CustomUserManagement.MVC](https://github.com/iammukeshm/CustomUserManagement.MVC)
	> Let’s go in-depth and understand the functionalities you can achieve with the help of Microsoft Identity. We will build a small yet practical implementation of Custom User Management in ASP.NET Core MVC with Identity.

* [https://github.com/IdentityManager/IdentityManager2](https://github.com/IdentityManager/IdentityManager2)
	> Development tool for administering users and roles

* [https://github.com/matteofabbri/AspNetCore.Identity.Mongo](https://github.com/matteofabbri/AspNetCore.Identity.Mongo)
	> This is a MongoDB provider for the ASP.NET Core 2 Identity framework
	
* [https://github.com/gustavobigardi/IdentityServer.BlazorAdmin](https://github.com/gustavobigardi/IdentityServer.BlazorAdmin)
	> Identity Server AdminUI using Blazor.

<div align="right">
  <b><a href="#contents">↥ Back To Top</a></b>
</div>

### Authentication 

#### 📝 Articles
* [Introduction to Authentication with ASP.NET Core](https://andrewlock.net/introduction-to-authentication-with-asp-net-core/)
* [Exploring the cookie authentication middleware in ASP.NET Core](https://andrewlock.net/exploring-the-cookieauthenticationmiddleware-in-asp-net-core/)
* [Getting started with Securing APIs using JWT Bearer Authentication - Hands on](https://referbruv.com/blog/posts/getting-started-with-securing-apis-using-jwt-bearer-authentication-hands-on)
* [JWT Authentication In ASP.NET Core](https://www.freecodespot.com/blog/jwt-authentication-in-dotnet-core/)
* [Login Web Application using Cookie Authentication in ASP NET Core](https://www.freecodespot.com/blog/cookie-authentication-in-dotnet-core/)
* [Build Secure ASP.NET Core API with JWT Authentication – Detailed Guide](https://www.codewithmukesh.com/blog/aspnet-core-api-with-jwt-authentication)
* [Canceling JWT tokens in .NET Core](https://piotrgankiewicz.com/2018/04/25/canceling-jwt-tokens-in-net-core/)
* [JWT refresh tokens and .NET Core](https://piotrgankiewicz.com/2017/12/07/jwt-refresh-tokens-and-net-core/)
* [JWT RSA & HMAC + ASP.NET Core](https://piotrgankiewicz.com/2017/07/24/jwt-rsa-hmac-asp-net-core/)
* [An introduction to the Data Protection system in ASP.NET Core](https://andrewlock.net/an-introduction-to-the-data-protection-system-in-asp-net-core/)

#### 📹 Videos
* [ASP.NET Core 3 - Authentication - Ep.1 Basics (Claims/ClaimsIdentity/ClaimsPrincipal/Authorization)](https://www.youtube.com/watch?v=Fhfvbl_KbWo)
* [ASP.NET Core 3 - Authentication - Ep.2 Identity Authentication](https://www.youtube.com/watch?v=IjbtWPXVJGw)
* [Secure a .NET Core API with Bearer Authentication](https://www.youtube.com/watch?v=3PyUjOmuFic)
* [User Registration and Controller Auth | ASP.NET Core 5 REST API Tutorial 10](https://www.youtube.com/watch?v=ARvsBUBioT0)
* [.NET Core - canceling JWT tokens](https://www.youtube.com/watch?v=Y5ZLhxZtww8)
* [Restricting endpoints with Claims | ASP.NET Core 5 REST API Tutorial 17](https://www.youtube.com/watch?v=g_8EHDQO4wI)
* [Setting up ApiKey-based Authentication | ASP.NET Core 5 REST API Tutorial 24](https://www.youtube.com/watch?v=Zo3T_See7iI)
* [User specific content with JWT claims | ASP.NET Core 5 REST API Tutorial 12](https://www.youtube.com/watch?v=o8dwfI7X16E)
* [User Login using JWT (Authentication) | ASP.NET Core 5 REST API Tutorial 11](https://www.youtube.com/watch?v=APLjIrZgxyo)
* [What is a Refresh Token and why your REST API needs it?](https://www.youtube.com/watch?v=-Z57Ss_uiuc)
* [Refreshing JWTs with Refresh Tokens | ASP.NET Core 5 REST API Tutorial 13](https://www.youtube.com/watch?v=AU0TIOZhGqs)
* [Setting up JWT support (Authentication) | ASP.NET Core 5 REST API Tutorial 9](https://www.youtube.com/watch?v=M6AkbBaDGJE)
* [What is a JWT (JSON Web Token) and why your REST API needs it](https://www.youtube.com/watch?v=qDJYgGzmalQ)

#### Samples
* [https://github.com/iammukeshm/JWTAuthentication.WebApi](https://github.com/iammukeshm/JWTAuthentication.WebApi)
	> Security is a vital part of any kind of application. Since APIs can expose highly sensitive data like user details, email adressses , it is highly critical that these API endpoints are secured.In this Guide let's build a Secure ASP.NET Core API with JWT Authentication. Read my detailed blog post for implementation.

* [https://github.com/spetz/jwt-hmac-rsa-aspnet-core-sample](https://github.com/spetz/jwt-hmac-rsa-aspnet-core-sample)

#### Libraries
- [fake-authentication-jwtbearer](https://github.com/webmotions/fake-authentication-jwtbearer)
	> Simple way to fake an authenticated user for integration test with ASP.Net Core framework
	
<div align="right">
  <b><a href="#contents">↥ Back To Top</a></b>
</div>

### Authorization

#### 📝 Articles
* [Create an ASP.NET Core web app with user data protected by authorization](https://docs.microsoft.com/en-us/aspnet/core/security/authorization/secure-data)
* [ASP.NET Core Identity Roles based Authorization](https://procodeguide.com/programming/asp-net-core-identity-roles-authorization/)
* [Role-based authorization in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/security/authorization/roles)
* [Policy-based authorization in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/security/authorization/policies)
* [Claims-based authorization in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/security/authorization/claims)
* [Resource-based authorization in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/security/authorization/resourcebased)
* [ASP.NET Core - Claims Based Authentication: Claims vs Identities vs Principals](https://eddieabbondanz.io/post/aspnet/claims-based-authentication-claims-identities-principals/)
* [Role-based and Claims-based Authorization in ASP.NET Core using Policies - Hands on](https://referbruv.com/blog/posts/role-based-and-claims-based-authorization-in-aspnet-core-using-policies-hands-on)
* [Implementing Policy-Based Authorization in ASP.NET Core - Getting Started](https://referbruv.com/blog/posts/implementing-policy-based-authorization-in-aspnet-core-getting-started)
* [Policy-based Authorization in ASP.NET Core – A Deep Dive](https://www.red-gate.com/simple-talk/dotnet/c-programming/policy-based-authorization-in-asp-net-core-a-deep-dive/)
* [ASP.NET Core Identity Claims based Authorization](https://procodeguide.com/programming/asp-net-core-identity-claims/)
* [Deep dive into policy-based authorization in ASP.NET Core](https://blog.joaograssi.com/posts/2021/asp-net-core-deep-dive-policy-based-authorization/)
#### 📹 Videos
* [ASP.NET Core 3 - Authentication - Ep.3 Authorization (All about Policies and Claims)](https://www.youtube.com/watch?v=RBMO_hruKaI)

<div align="right">
  <b><a href="#contents">↥ Back To Top</a></b>
</div>

## Logging And Auditing

### 📝 Articles
* [TRACING IO IN .NET CORE](https://www.softwarepark.cc/blog/2021/1/29/tracing-io-in-net-core)
* [Setting up Serilog in ASP.NET Core 3](https://nblumhardt.com/2019/10/serilog-in-aspnetcore-3/)
* [Serilog in ASP.NET Core 3.1 – Structured Logging Made Easy](https://codewithmukesh.com/blog/serilog-in-aspnet-core-3-1/)
* [Series: Using Serilog.AspNetCore in ASP.NET Core 3.0](https://andrewlock.net/series/using-serilog-aspnetcore-in-asp-net-core-3/)
* [ASP.NET Core 5 + Serilog](https://jkdev.me/asp-net-core-serilog/)
* [What Is Structured Logging and Why Developers Need It](https://stackify.com/what-is-structured-logging-and-why-developers-need-it/)
* [Structured logging concepts in .NET Series (1)](https://nblumhardt.com/2016/06/structured-logging-concepts-in-net-series-1/)
* [Events and levels structured logging concepts in .NET (2)](https://nblumhardt.com/2016/06/events-and-levels-structured-logging-concepts-in-net-2/)
* [Message templates and properties structured logging concepts in .NET (3)](https://nblumhardt.com/2016/06/message-templates-and-properties-structured-logging-concepts-in-net-3/)
* [Exporting Open Telemetry Data to Jaeger](https://rehansaeed.com/exporting-open-telemetry-data-to-jaeger/)

### 📹 Videos
* [Logging into Elasticsearch using Serilog and viewing logs in Kibana | .NET Core Tutorial](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/watch?v=0acSdHJfk64)
* [Add Simple Distributed Tracing in .NET Libraries](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/watch?v=wjglj4jE18Y) - CodeWithStu

### Libraries
- [https://github.com/thepirat000/Audit.NET](https://github.com/thepirat000/Audit.NET)
	> An extensible framework to audit executing operations in .NET and .NET Core.
	
### 🔖 Samples
* [https://github.com/serilog/serilog-aspnetcore](https://github.com/serilog/serilog-aspnetcore)
* [https://github.com/jernejk/AspNetCoreSerilogExample](https://github.com/jernejk/AspNetCoreSerilogExample)

<div align="right">
  <b><a href="#contents">↥ Back To Top</a></b>
</div>


## Tracing

### 📝 Articles
* [A Step by Step Guide to Logging in ASP.NET Core 5](https://www.ezzylearning.net/tutorial/a-step-by-step-guide-to-logging-in-asp-net-core-5)

<div align="right">
  <b><a href="#contents">↥ Back To Top</a></b>
</div>

## Testing

### TDD

### Articles
* [TDD is dead. Long live testing](https://dhh.dk/2014/tdd-is-dead-long-live-testing.html)
* [Test-induced design damage](https://dhh.dk/2014/test-induced-design-damage.html)

### BDD

#### Articles
* [Behavior-Driven Development from scratch](https://beyondxscratch.com/2019/05/21/behavior-driven-development-from-scratch/)

#### 📹 Videos
* [Getting started with Behavior Driven Development (BDD) in .NET using SpecFlow](https://www.youtube.com/watch?v=EEeVU0z26u0)
* [Getting started with BDD using Specflow .NET Core 3.1 (C#)](https://www.youtube.com/watch?v=O5oHiBD5Lvk)

<div align="right">
  <b><a href="#contents">↥ Back To Top</a></b>
</div>

### Unit Testing

#### 📝 Articles 
* [Keep Tests Short and DRY with Extension Methods](https://ardalis.com/keep-tests-short-and-dry-with-extensions/) - Steve Smith
* [C# – How to unit test code that uses HttpClient](https://makolyte.com/csharp-how-to-unit-test-code-that-uses-httpclient/)
* [How to unit test a class that consumes an HttpClient with IHttpClientFactory in ASP.NET Core?](https://anthonygiretti.com/2018/09/06/how-to-unit-test-a-class-that-consumes-an-httpclient-with-ihttpclientfactory-in-asp-net-core/)
* [ASP.NET Core 2+ best practices and practical tools for testing, part 1](https://anthonygiretti.com/2019/06/15/asp-net-core-2-best-practices-and-practical-tools-for-testing-part-1/)
* [ASP.NET Core 2+ best practices and practical tools for testing, part 2, Use cases](https://anthonygiretti.com/2019/07/18/asp-net-core-2-best-practices-and-practical-tools-for-testing-part-2-use-cases/)
* [You will never give up a unit test anymore with ExpectedObjects in .NET Core](https://anthonygiretti.com/2019/01/21/you-will-never-give-up-a-unit-test-anymore-with-expectedobjects-in-net-core/)
* [How to unit test private methods in .NET Core applications? (even if it’s bad)](https://anthonygiretti.com/2018/08/26/how-to-unit-test-private-methods-in-net-core-applications-even-if-its-bad/)
* [Mock and Unit Test HTTPClient with MessageHandler](https://www.thecodebuzz.com/mock-httpclient-with-messagehandler-unit-test/)
* [Unit Test or Integration Test and Why You Should Care](https://ardalis.com/unit-test-or-integration-test-and-why-you-should-care/) - Steve Smith
* [Unit Test Naming Convention](https://ardalis.com/unit-test-naming-convention/?utm_sq=gkewnaysjn)

#### 📹 Videos
* [C# Unit Test Mocking with Moq](https://www.youtube.com/watch?v=IFN4-YrgBEI) - Raw Coding
* [C# Unit Testing Tutorial](https://www.youtube.com/watch?v=e9q-ocrt4UI) - Raw Coding
* [C# Unit Testing Example](https://www.youtube.com/watch?v=Tc9FUg74ci4) - Raw Coding
* [.NET 5 REST API Tutorial 10 - Unit Testing and TDD](https://www.youtube.com/watch?v=dsD0CMgPjUk&t=0s)

#### Tools

- [https://github.com/BenMorris/NetArchTest](https://github.com/BenMorris/NetArchTest)
	> A fluent API for .Net that can enforce architectural rules in unit tests.
	
<div align="right">
  <b><a href="#contents">↥ Back To Top</a></b>
</div>


### Integration Testing 

#### 📝 Articles 
* [Self-hosted integration tests in ASP.NET by Mark Seemann](https://blog.ploeh.dk/2021/01/25/self-hosted-integration-tests-in-aspnet/)
* [Running Integration Tests in Build Pipelines with a Real Database](https://ardalis.com/running-integration-tests-in-build-pipelines-with-a-real-database/?utm_sq=gk5cykzhad) - Steve Smith
* [Limitations of the EF Core in-memory database providers](https://blog.joaograssi.com/limitations-ef-core-in-memory-database-providers/)
* [Using docker-compose for your ASP.NET + EF Core integration tests](https://blog.joaograssi.com/using-docker-compose-for-your-asp-net-ef-core-integration-tests/)
* [ASP.NET Core integration tests with docker-compose on GitHub Actions](https://blog.joaograssi.com/posts/2020/asp-net-core-integration-tests-with-docker-compose-github-actions/)
* [Testing WebAPI with ApprovalTests.NET](https://cezarypiatek.github.io/post/testing-web-api-with-approval-tests/)

#### 📹 Videos
* [C# Integration Testing Tutorial](https://www.youtube.com/watch?v=OPEC_7J1LOw) - Raw Coding
* [ASP.NET Core C# Integration Testing Tutorial (File Uploads Example)](https://www.youtube.com/watch?v=0PXZMigt01A) - Raw Coding
* [ASP.NET Core C# Integration Testing Example (Mocking Identity)](https://www.youtube.com/watch?v=03y-i4nMou4&t=0s)
* [ASP.NET Core C# Integration Testing - Mocking Cookie Authentication](https://www.youtube.com/watch?v=b1-KG_x-Y5Q)

<div align="right">
  <b><a href="#contents">↥ Back To Top</a></b>
</div>

### End-To-End Testing

#### 📝 Articles
<div align="right">
  <b><a href="#contents">↥ Back To Top</a></b>
</div>

### Load Testing

#### 📝 Articles

#### 📹 Videos
* [Munich .NET Meetup: Massive load testing with NBomber cluster](https://www.youtube.com/watch?v=U2j7NmXZrOc)
* [ASP.NET Core Series: Performance Testing Techniques](https://www.youtube.com/watch?v=jn54CjePzs0)

#### 📦 Libraries

* [bombardier](https://github.com/codesenberg/bombardier)
  > Fast cross-platform HTTP benchmarking tool written in Go

<div align="right">
  <b><a href="#contents">↥ Back To Top</a></b>
</div>

### Architectural Testing

#### 📝 Articles
[Writing ArchUnit style tests for .Net and C# to enforce architecture rules](https://www.ben-morris.com/writing-archunit-style-tests-for-net-and-c-for-self-testing-architectures/)

#### 📦 Libraries
* [https://github.com/BenMorris/NetArchTest](https://github.com/BenMorris/NetArchTest)
	> A fluent API for .Net that can enforce architectural rules in unit tests.
	
* [https://github.com/joelparkerhenderson/architecture_decision_record](https://github.com/joelparkerhenderson/architecture_decision_record)
	> Architecture decision record (ADR) examples for software planning, IT leadership, and template documentation
	
### Mocking

#### 📝 Articles
 * [Effective mocking](https://cezarypiatek.github.io/post/effective-mocking/)

<div align="right">
  <b><a href="#contents">↥ Back To Top</a></b>
</div>


### XUnit

#### 📦 Libraries

* [xunit-logging](https://github.com/martincostello/xunit-logging)
  > Logging extensions for xunit

<div align="right">
  <b><a href="#contents">↥ Back To Top</a></b>
</div>

#### 📹 Videos

<div align="right">
  <b><a href="#contents">↥ Back To Top</a></b>
</div>

## Exception Handling

### 📝 Articles
* [My take on the Result class](https://josef.codes/my-take-on-the-result-class-in-c-sharp/) - Josef Ottosson
* [Functional C# Handling failures, input errors](https://enterprisecraftsmanship.com/posts/functional-c-handling-failures-input-errors/) - Vladimir Khorikov
* [10 Exception handling best practices in C#](https://kumarashwinhubert.com/10-exception-handling-best-practices-in-csharp)
* [Exception handling in C# - throw or throw ex](https://kumarashwinhubert.com/exception-handling-in-csharp-throw-or-throw-ex)
* [Problem Details - The right way to specify errors in Web API responses](https://kumarashwinhubert.com/problem-details-the-right-way-to-specify-errors-in-web-api-responses)
* [Handle Exceptions With ASP.NET Core ExceptionHandlerMiddleware](https://khalidabuhakmeh.com/handling-aspnet-core-exceptions-with-exceptionhandler-middleware)
### 📹 Videos
* [STOP throwing Exceptions! Start being Explicit](http://w7.mul.ir/yo%7cut%7cub%7ce.%7cco%7cm/watch?v=4UEanbBaJy4)

### Libraries
* [https://github.com/proudmonkey/AutoWrapper](https://github.com/proudmonkey/AutoWrapper)
* [Hellang.Middleware.ProblemDetails](https://www.nuget.org/packages/Hellang.Middleware.ProblemDetails/)
* [https://github.com/ardalis/GuardClauses](https://github.com/ardalis/GuardClauses)
## EF Core

### 📝 Articles
* [Announcing the Release of EF Core 5.0](https://devblogs.microsoft.com/dotnet/announcing-the-release-of-ef-core-5-0/)
* [Entity Framework Core 5 free resources](https://erikej.github.io/efcore/2021/01/05/efcore-5-resources.html)
* [What is New in EF Core 5.0](https://docs.microsoft.com/en-us/ef/core/what-is-new/ef-core-5.0/whatsnew?WT.mc_id=DT-MVP-4025156)
* [Calling Stored Procedures with the Entity Framework in .NET 5](https://www.codemag.com/Article/2101031/Calling-Stored-Procedures-with-the-Entity-Framework-in-.NET-5)
* [EF Core 5: Building on the Foundation](https://www.codemag.com/Article/2010042/EF-Core-5-Building-on-the-Foundation)
* [Entity Framework Core 5 Resources I have Created Recently](https://thedatafarm.com/data-access/entity-framework-core-5-resources/)
* [Entity Framework Core 5 vs SQLBulkCopy](https://www.michalbialecki.com/2020/05/03/entity-framework-core-5-vs-sqlbulkcopy-2/)
* [Entity Framework Core health check](https://www.michalbialecki.com/2020/03/13/entity-framework-core-health-check/)
* [Entity Framework Core 3.0: A Foundation for the Future](https://codemag.com/Article/1911062/Entity-Framework-Core-3.0-A-Foundation-for-the-Future)
* [Useful SQL statements when writing EF Core 5 migrations](https://www.michalbialecki.com/2021/01/07/useful-sql-statements-when-writing-ef-core-5-migrations/)
* [Adding Entity Framework Core 5 migrations to .NET 5 project](https://www.michalbialecki.com/2020/07/20/adding-entity-framework-core-5-migrations-to-net-5-project/)
* [Merging migrations in Entity Framework Core 5](https://www.michalbialecki.com/2020/07/24/merging-migrations-in-entity-framework-core-5/)
* [Executing raw SQL with Entity Framework Core 5](https://www.michalbialecki.com/2020/09/14/executing-raw-sql-with-entity-framework-core-5/)
* [PrimeHotel – adding Entity Framework Core 5 in .NET](https://www.michalbialecki.com/2020/07/10/primehotel-adding-entity-framework-core-5/)
* [Working with views in Entity Framework Core 5](https://www.michalbialecki.com/2020/09/09/working-with-views-in-entity-framework-core-5/)
* [Adding an Entity Framework Core 5 to an existing database](https://www.michalbialecki.com/2020/07/17/adding-an-entity-framework-core-5-to-an-existing-database/)
* [How to configure relationships in Entity Framework Core 5](https://www.michalbialecki.com/2020/10/02/how-to-configure-relationships-in-entity-framework-core-5/)
* [Entity Framework Core – is it fast?](https://www.michalbialecki.com/2021/01/10/entity-framework-core-is-it-fast/)
* [Bulk copy with Entity Framework Core 5](https://www.michalbialecki.com/2021/01/21/bulk-copy-with-entity-framework-core-5/)
* [Unit tests in Entity Framework Core 5](https://www.michalbialecki.com/2020/11/28/unit-tests-in-entity-framework-core-5/)
* [How not to pass parameters in Entity Framework Core 5](https://www.michalbialecki.com/2020/09/26/how-not-to-pass-parameters-in-entity-framework-core-5/)
* [Select data with a stored procedure with Entity Framework Core 5](https://www.michalbialecki.com/2020/09/03/select-data-with-a-stored-procedure-with-entity-framework-core-5/)
* [How to call stored procedures with OUTPUT parameters with FromSqlRaw in EF Core](https://erikej.github.io/efcore/2020/08/03/ef-core-call-stored-procedures-out-parameters.html)
* [Query non-table classes using ad-hoc (raw) SQL with EF Core 3.1](https://erikej.github.io/efcore/2020/04/06/query-non-table-classes-raw-sql.html)
* [Execute a stored procedure with Entity Framework Core 5](https://www.michalbialecki.com/2020/08/27/execute-a-stored-procedure-with-entity-framework-core-5/)
* [Mapping and using SQL Server stored procedures with EF Core Power Tools](https://erikej.github.io/efcore/2020/08/10/ef-core-power-tools-stored-procedures.html)
* [Avoiding SQL Server plan cache pollution with EF Core 3 and Enumerable.Contains](https://erikej.github.io/efcore/sqlserver/2020/03/30/ef-core-cache-pollution.html)
* [How to pass a dynamic/variable list of values as SqlParameters with FromSqlRaw in EF Core](https://erikej.github.io/efcore/sqlserver/2020/04/20/use-dynamic-sqlparameters-with-fromsql.html)
* [EF Core Power Tools database reverse engineering: renaming of entities and properties](https://erikej.github.io/efcore/2020/09/07/ef-core-power-tools-renaming-advanced.html)
* [Change Tracking in EF Core](https://docs.microsoft.com/en-us/ef/core/change-tracking/)
* [Entity Framework Core – Projection Performance](https://eliottrobson.me/entity-framework-core-projection-performance/)
* [Expression and Projection Magic for Entity Framework Core](https://benjii.me/2018/01/expression-projection-magic-entity-framework-core/) - Ben Cull
* [Building high performance database queries using Entity Framework Core and AutoMapper](https://www.thereformedprogrammer.net/building-efficient-database-queries-using-entity-framework-core-and-automapper/)
* [Database Providers](https://docs.microsoft.com/en-us/ef/core/providers/?tabs=dotnet-core-cli)
* [Using Database Project and DbUp for database management](http://www.kamilgrzybek.com/database/using-database-project-and-dbup-for-database-management/)
* [Database change management](http://www.kamilgrzybek.com/database/database-change-management/)
* [Converting a Visual Studio database project to use DbUp migrations](https://dasith.me/2020/06/08/database-project-conversion-to-migrations/)
* [Entity Framework Core 5 Value Converters](https://khalidabuhakmeh.com/entity-framework-core-5-value-converters)
* [Designing for Related Data without Foreign Keys](https://ardalis.com/related-data-without-foreign-keys/)
* [Five levels of performance tuning for an EF Core query](https://www.thereformedprogrammer.net/five-levels-of-performance-tuning-for-an-ef-core-query/)
* [Automate Database Deployments](https://www.programmingwithwolfgang.com/automate-database-deployments/)
* [Efficient querying with LINQ, AutoMapper and Future queries](https://lostechies.com/jimmybogard/2014/03/11/efficient-querying-with-linq-automapper-and-future-queries/)
* [CQRS with Entity Framework Core](https://www.edgesidesolutions.com/cqrs-with-entity-framework-core/)
### 📹 Videos
* [Typed Exceptions for Entity Framework Core](https://www.youtube.com/watch?v=aUl5QfswNU4) - Microsoft
* [Entity Framework Community Standup - Performance Tuning an EF Core App](https://www.youtube.com/watch?v=VgNFFEqwZPU)
* [Entity Framework Community Standup - Julie Lerman and EF Core Ask Me Anything (AMA)](https://www.youtube.com/watch?v=oZVsZrFKp48)

### 📦 Libraries 
* [https://github.com/linq2db/linq2db.EntityFrameworkCore](https://github.com/linq2db/linq2db.EntityFrameworkCore)
	> Bring power of Linq To DB to Entity Framework Core projects

* [https://github.com/ErikEJ/EFCorePowerTools](https://github.com/ErikEJ/EFCorePowerTools)
	> reverse engineering, migrations and model visualization for EF Core

* [https://github.com/Giorgi/EntityFramework.Exceptions](https://github.com/Giorgi/EntityFramework.Exceptions)
	> Handle database errors easily when working with Entity Framework Core. Supports SQLServer, PostgreSQL, SQLite, Oracle and MySql

* [https://github.com/thepirat000/Audit.NET](https://github.com/thepirat000/Audit.NET)
	> An extensible framework to audit executing operations in .NET and .NET Core.

<div align="right">
  <b><a href="#contents">↥ Back To Top</a></b>
</div>

## Environment

### 📝 Articles
* [How to set the hosting environment in ASP.NET Core](https://andrewlock.net/how-to-set-the-hosting-environment-in-asp-net-core/)
* [Configuring multiple ASP.NET Core hosting environment](https://procodeguide.com/programming/asp-net-core-hosting-environment/)

<div align="right">
  <b><a href="#contents">↥ Back To Top</a></b>
</div>

## MediatR

### 📝 Articles
* [Using MediatR in ASPNET Core Apps](https://ardalis.com/using-mediatr-in-aspnet-core-apps) - Steve Smith

### 🔖 Samples
* [https://github.com/ardalis/MediatRAspNetCore](https://b2n.ir/j44724) - Steve Smith

## Mapping

### 📝 Articles
* [Implement Automapper in ASP.NET Core 3.1 – Ultimate Guide](https://procodeguide.com/programming/automapper-in-asp-net-core/)
* [Let's talk about mapping objects in c-sharp (C#)](https://josef.codes/lets-talk-about-mapping-objects-in-c-sharp/)

<div align="right">
  <b><a href="#contents">↥ Back To Top</a></b>
</div>

### 📦 Libraries 
* [Mapster](https://github.com/MapsterMapper/Mapster)
  > A fast, fun and stimulating object to object Mapper. 

### 📹 Videos
* [Mapster, the best .NET mapper that you are (probably) not using](https://www.youtube.com/watch?v=UIslFVEHkzA)
* [Domain to Contract mapping with Automapper | ASP.NET Core 5 REST API Tutorial 20](https://www.youtube.com/watch?v=1Dz5Lfo6mqo)

<div align="right">
  <b><a href="#contents">↥ Back To Top</a></b>
</div>


## Benchmarking

### 📦 Libraries

* [BenchmarkDotNet](https://github.com/dotnet/BenchmarkDotNet)
  > Powerful .NET library for benchmarking

### 📹 Videos
* [Benchmarking C# code using BenchmarkDotNet](https://www.youtube.com/watch?v=EWmufbVF2A4)
* [Analyzing performance with BenchmarkDotNet - ASP.NET Core: From 0 to overkill](https://www.youtube.com/watch?v=8JOC8kN_WbU)

<div align="right">
  <b><a href="#contents">↥ Back To Top</a></b>
</div>

## Package Versioning

### 📹 Videos
* [Streamlining package versioning with MinVer](https://www.youtube.com/watch?v=2sFCBJOhWWY)

## Orleans

### 📹 Videos

* [On .NET Live - Deep Dive into Microsoft Orleans](https://www.youtube.com/watch?v=R0ODfwU6MzQ)
* [Introduction to Microsoft Orleans - CodeWithStu](https://www.youtube.com/watch?v=yM-gpuw1uhM)
* [Building real applications with Orleans](https://www.youtube.com/watch?v=8duFuggnj8o)
* [An Introduction to Orleans](https://www.youtube.com/watch?v=9OMXw0CslKE)

## Identity Server

### Articles
- [The OpenID Connect (OIDC) Architecture Map](https://techcommunity.microsoft.com/t5/azure-developer-community-blog/the-openid-connect-oidc-architecture-map/ba-p/1119450)

### Videos
* [Creating your First IdentityServer4 Solution](https://www.youtube.com/watch?v=HJQ2-sJURvA&t=218s)
* [How to add ASP.NET Identity and Entity Framework Support for your IdentityServer4 Solution](https://www.youtube.com/watch?v=Sw1rScI20xM)
* [How to Setup FIDO2 for IdentityServer4](https://www.youtube.com/watch?v=j-QjTvBnEn4)
* [How to Setup FIDO2 for ASP.NET Identity](https://www.youtube.com/watch?v=8rO6c3CLg48)

### 🔖 Samples

* [SettingUpIdentityServer](https://github.com/kevinrjones/SettingUpIdentityServer)

* [dnc-identity-identityserver](https://github.com/kimcu-on-thenet/dnc-identity-identityserver)
	> An example of IdentityServer4 and ASP.NET Identity, Ocelot and Consul

* [run-aspnet-identityserver4](https://github.com/aspnetrun/run-aspnet-identityserver4)
	> Secure microservices with using standalone Identity Server 4 and backing with Ocelot API Gateway. Protect our ASP.NET Web MVC and API applications with using OAuth 2 and OpenID Connect in IdentityServer4. Securing your web application and API with tokens, working with claims, authentication and authorization middlewares and applying policies.
	
* [TheIdServer](https://github.com/Aguafrommars/TheIdServer)
	> OpenID/Connect server based on IdentityServer4
	
* [Identity-Service](https://github.com/INNVTV/Identity-Service) - INNVTV
	> Identity-As-A-Service written from scratch in .Net Core using a CQRS architecture with a CosmosDB/Redis persistence layer and RSA signed JWT Tokens with public key distribution for authentication and claims.

* [AspNet5IdentityServerAngularImplicitFlow](https://github.com/damienbod/AspNet5IdentityServerAngularImplicitFlow)
	> OpenID Connect Code / Implicit Flow with Angular and ASP.NET Core 5 IdentityServer4

* [IdentityServer4AspNetCoreIdentityTemplate](https://github.com/damienbod/IdentityServer4AspNetCoreIdentityTemplate)
	> An ASP.NET Core 3.1 IdentityServer4 Identity Bootstrap 4 template with localization
	
* [JPProject.IdentityServer4.SSO](https://github.com/brunohbrito/JPProject.IdentityServer4.SSO)
	> 🔒 ASP.NET Core 3.1 Open Source SSO. Built within IdentityServer4 🔑

* [JPProject.IdentityServer4.AdminUI](https://github.com/brunohbrito/JPProject.IdentityServer4.AdminUI)
	> 🔧 ASP.NET Core 3 & Angular 8 Administration Panel for 💞IdentityServer4 and ASP.NET Core Identity

* [https://github.com/skoruba/IdentityServer4.Admin](https://github.com/skoruba/IdentityServer4.Admin)
	> The administration for the IdentityServer4 and Asp.Net Core Identity

* [IdentityServer.BlazorAdmin](https://github.com/gustavobigardi/IdentityServer.BlazorAdmin)
	> Identity Server AdminUI using Blazor.
	
* [IdentityManager2](https://github.com/IdentityManager/IdentityManager2)
	> Development tool for administering users and roles

* [Duende.IdentityServer.Admin](https://github.com/skoruba/Duende.IdentityServer.Admin)
  The administration for the Duende IdentityServer and Asp.Net Core Identity ⚡
  
## CI/CD

### Azure Devops

#### 📝 Articles

* [Manage release flow using pipelines in Azure DevOps](https://daniel-krzyczkowski.github.io/Manage-Release-Flow-Using-Pipelines-In-Azure-DevOps/)


### GitHub Actions

#### 📝 Articles
* [Automate Azure AD B2C policies release with GitHub Actions](https://daniel-krzyczkowski.github.io/Automate-Azure-AD-B2C-policies-release-with-GitHub-Actions/)

## PaaS

### Heroku

#### 📝 Articles

#### 📹 Videos
* [Deploy Asp.Net Core Website on Heroku using Docker](https://www.youtube.com/watch?v=gQMT4al2Grg)

### Netlify

#### 📝 Articles

#### 📹 Videos
* [How to host a Blazor C# project for FREE](https://www.youtube.com/watch?v=8NOmadyM1Ao)

## Roslyn

### Articles
* [GETTING STARTED WITH THE ROSLYN APIS: WRITING CODE WITH CODE](https://www.stevejgordon.co.uk/getting-started-with-the-roslyn-apis-writing-code-with-code)

### Tools
* [https://github.com/KirillOsenkov/RoslynQuoter](https://github.com/KirillOsenkov/RoslynQuoter)
	> Roslyn tool that for a given C# program shows syntax tree API calls to construct its syntax tree
	
* [https://github.com/meziantou/Meziantou.Analyzer](https://github.com/meziantou/Meziantou.Analyzer)
	> A Roslyn analyzer to enforce some good practices in C#.
	
## Others

### 📝 Articles
* [Building a social media platform without going bankrupt Part I–Laying the numbers](https://ayende.com/blog/193026-C/building-a-social-media-platform-without-going-bankrupt-part-i-laying-the-numbers)
* [Building a social media platform without going bankrupt Part II–Accepting posts](https://ayende.com/blog/193027-C/building-a-social-media-platform-without-going-bankrupt-part-ii-accepting-posts)
* [Building a social media platform without going bankrupt Part III–Reading posts](https://ayende.com/blog/193028-C/building-a-social-media-platform-without-going-bankrupt-part-iii-reading-posts)
* [Building a social media platform without going bankrupt Part IV–Caching and distribution](https://ayende.com/blog/193029-C/building-a-social-media-platform-without-going-bankrupt-part-iv-caching-and-distribution)
* [Building a social media platform without going bankrupt Part V–Handling the timeline](https://ayende.com/blog/193057-A/building-a-social-media-platform-without-going-bankrupt-part-v-handling-the-timeline)
* [Building a social media platform without going bankrupt Part VI–Dealing with edits and deletions](https://ayende.com/blog/193058-A/building-a-social-media-platform-without-going-bankrupt-part-vi-dealing-with-edits-and-deletions)
* [Building a social media platform without going bankrupt Part VII–Counting views, replies and likes](https://ayende.com/blog/193059-A/building-a-social-media-platform-without-going-bankrupt-part-vii-counting-views-replies-and-likes)
* [Building a social media platform without going bankrupt Part VIII–Tagging and searching](https://ayende.com/blog/193060-A/building-a-social-media-platform-without-going-bankrupt-part-viii-tagging-and-searching)
* [Building a social media platform without going bankrupt Part IX–Dealing with the past](https://ayende.com/blog/193061-A/building-a-social-media-platform-without-going-bankrupt-part-ix-dealing-with-the-past)

<div align="right">
  <b><a href="#contents">↥ Back To Top</a></b>
</div>

## Books

* [Microsoft .Net Ebooks](https://github.com/dotnet-architecture/eBooks/tree/master/current)
