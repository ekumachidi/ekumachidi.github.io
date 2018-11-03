---
layout: post
title: Understanding the dotNET (.NET) ecosystem
date: 2018-10-02 07:07:07 +0100
img: 5.jpg
tags: [Xamarin, Dotnet, CoreAspnet, MvcAspnetAspnetcore]
author: Ekuma Chidi
---

.NET is a confusing term nowadays. The framework was developed in 2002 by Microsoft and is continually maintained or upgraded to keep up with modern dev trends in web, mobile and the cloud. Because of this evolution, the ecosystem has become large and somewhat confusing.

![](https://cdn-images-1.medium.com/max/1600/1*R8mBIZo2BhbjUowwmm2bcA.png)

You probably already know about the .**NET framework**, the Base/Framework Class Library (**BCL/FCL**) and Portable Class Library (**PCL**). In 2016, .**NET core** was released. Now you may be thinking; “what is that?”, “How is it different from the .NET framework?”; “What about .NET standard?” How is it different from .NET core? Is it another framework? All these questions make it a bit complex choosing what type of project your new application should be or what tools to use.

> **.NET framework, .NET Core and Mono/Xamarin are all runtimes. They all implement the .NET standard specification.**

What then is .NET standard?

> **.NET Standard** is a base set of APIs that are common to all .NET implementations.

1.  **.NET Framework:** I think this is where the confusion started from. Here’s why I think so…_it was the only runtime for a long time and so it became analogous to the .NET ecosystem_. Even though it’s called a framework it’s a runtime and has other frameworks and workloads as do all the other runtimes. It supports websites, services, desktop apps, and more on Windows. The .NET Framework is partly open-source; “partly” because though some of the source code is available on GitHub, you cannot submit pull-requests
2.  **.NET Core** is a cross-platform .NET implementation for websites, servers, and console apps on macOS, Windows, and Linux. The .NET Core is open source and the entire code is available on GitHub.
3.  **Mono/Xamarin** is a .NET implementation for running apps on all the major mobile operating systems.

Let us compare these runtimes side by side

![](https://cdn-images-1.medium.com/max/1600/1*pgjTb4cHHI_kFZhbnQNo2g.png)


**So which of the runtimes should you use when?**

**I’d recommend you use .NET Core** for ASP.NET development, especially when you **want high performant apps** with a small fingerprint that can **run cross-platform.**

**.NET Framework:** Consider this when you’re specifically targeting Windows platforms or you need packages not yet available on .NET Core.

**Mono/Xamarin:** This is your best bet when you’re developing mobile apps that utilize native features and run cross-platform.

**How about the self-contained and framework dependent apps?**

If you’re asking this question then clearly you chose .NET Core.

For the framework dependent, these are the benefits;

1.  Small deployment package
2.  You don’t have to specify the target OS

The major drawback here is that you must have .NET Core already installed on the target.

For the self-contained app, the major benefits are that .NET Core doesn’t need to be installed on the target beforehand, you just bundle all your dependencies and versions with the package, however, this results in larger deployments and you’d have to explicitly specify the target OS.
