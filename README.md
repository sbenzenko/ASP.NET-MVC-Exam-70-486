# Microsoft Exam 70-486 Topics

### 1. Design the application architecture (15-20%)

**1.1 Plan the application layers**
- [Common web application architectures](https://docs.microsoft.com/en-us/dotnet/architecture/modern-web-apps-azure/common-web-application-architectures)

*1.1.1 Plan data access*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 2-6

*1.1.2 plan for separation of concerns, appropriate use of models, views, controllers, view components, and service dependency injection*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 6-15
 - [Dependency injection in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/dependency-injection?view=aspnetcore-3.1)
 - [Dependency injection in ASP.NET Core](https://app.pluralsight.com/library/courses/aspdotnet-core-dependency-injection) [$][video]
 
*1.1.3 choose between client-side and server-side processing*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 15-16

*1.1.4 design for scalability*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 16-17

*1.1.5 choose between ASP.NET Core and ASP.NET*
 - [Choose between ASP.NET 4.x and ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/choose-aspnet-framework?view=aspnetcore-3.1)
 - [.NET Core vs. .NET Framework for server apps](https://docs.microsoft.com/en-us/dotnet/standard/choosing-core-framework-server)

*1.1.6 choose when to use .NET standard libraries*
 - [What is the difference between .NET Core and .NET Standard Class Library project types?](https://stackoverflow.com/questions/42939454/what-is-the-difference-between-net-core-and-net-standard-class-library-project#:~:text=Use%20a%20.,Use%20a%20)
 - [Demystifying .NET Core and .NET Standard](https://docs.microsoft.com/en-us/archive/msdn-magazine/2017/september/net-standard-demystifying-net-core-and-net-standard)
 - [.NET Standard versions](https://dotnet.microsoft.com/platform/dotnet-standard)

**1.2 Design a distributed application**
 - [Design Distributed Application](https://examref.com/MCSD/70-486/DesignDistApp)
 - [Design a distributed application](http://failedturing.blogspot.com/2014/06/microsoft-70-486-design-distributed.html)
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 21-24

*1.2.1 Design a hybrid application*
 - [Building Hybrid Applications in the Cloud on Microsoft Azure](https://docs.microsoft.com/en-us/previous-versions/msp-n-p/hh871440(v=pandp.10)?redirectedfrom=MSDN)
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 24-26

*1.2.2 plan for session management in a distributed environment*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 26-27
 - [Sticky and NON-Sticky sessions](https://stackoverflow.com/questions/10494431/sticky-and-non-sticky-sessions)

*1.2.3 plan web farms*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 27-28
 - [Host ASP.NET Core in a web farm](https://docs.microsoft.com/en-us/aspnet/core/host-and-deploy/web-farm?view=aspnetcore-3.1)

*1.2.4 run Microsoft Azure services on-premises with Azure Pack*
 - [Windows Azure Pack — что за зверь и с чем его есть?](https://habr.com/ru/company/microsoft/blog/209918/)
 - [Windows Azure Pack for Windows Server](https://docs.microsoft.com/en-us/previous-versions/azure/windows-server-azure-pack/dn296435(v=technet.10))

*1.2.5 enable deferred processing through Azure features including queues, scheduled and on-demand jobs, Azure Functions, Azure Web Jobs*
 - [An introduction to Azure Functions](https://docs.microsoft.com/en-us/azure/azure-functions/functions-overview)
 - [Run background tasks with WebJobs in Azure App Service](https://docs.microsoft.com/en-us/azure/app-service/webjobs-create)

**1.3 Design and implement the Azure Web Apps life cycle**
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 31-40
 - [Background tasks with hosted services in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/host/hosted-services)
 - [Building ASP.NET Core Hosted Services and .NET Core Worker Services](https://app.pluralsight.com/library/courses/building-aspnet-core-hosted-services-net-core-worker-services) [$][video]

*1.3.1 Identify and implement Start, Run, and Stop events*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 35-38
 - [Customize the Lifecycle of a Web or Worker role in .NET](https://docs.microsoft.com/en-us/azure/cloud-services/cloud-services-role-lifecycle-dotnet)

*1.3.2 code against application events in application*
 - [ASP.NET Core 3.0: The MVC Request Life Cycle](https://app.pluralsight.com/library/courses/aspnet-core-3-mvc-request-life-cycle) [$][video]

*1.3.3 configure startup tasks, including IIS, app pool configuration, and third-party tools*
 - [Running async tasks on app startup in ASP.NET Core](https://andrewlock.net/running-async-tasks-on-app-startup-in-asp-net-core-part-1/)
 - [How to configure and run startup tasks for a cloud service](https://docs.microsoft.com/en-us/azure/cloud-services/cloud-services-startup-tasks)
 - [Setting Application Pool Idle and Recycle Timeout Period Using Startup Tasks - Windows Azure](https://www.c-sharpcorner.com/UploadFile/aravindbenator/setting-application-pool-idle-and-recycle-timeout-period-usi/)

**1.4 Configure state management**
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 40-51
 - [Session and state management in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/app-state?view=aspnetcore-3.1)

*1.4.1 Choose a state management mechanism including in-process, out of process, and Redis based state management*
 - [ASP.NET Session State Provider for Azure Cache for Redis](https://docs.microsoft.com/en-us/azure/azure-cache-for-redis/cache-aspnet-session-state-provider)
 - [ASP.NET Session State Management With Redis](https://www.c-sharpcorner.com/UploadFile/826da2/Asp-Net-session-state-management-with-redis-local-server-fa/)

*1.4.2 plan for scalability*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 44-45

*1.4.3 use cookies or local storage to maintain state*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 45-46

*1.4.4 apply configuration settings in web.config file*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> page 47

*1.4.5 implement sessionless state including for example, query strings*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 48-49

*1.4.6 configure middleware to enable session and application state in ASP.NET Core*
 - [Configure session state](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/app-state?view=aspnetcore-3.1#configure-session-state)

**1.5 Design a caching strategy**
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 51-59
 - [Cache in-memory in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/performance/caching/memory?view=aspnetcore-3.1)
 - [Distributed caching in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/performance/caching/distributed?view=aspnetcore-3.1)

*1.5.1 Implement page output caching and data caching*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 51-57

*1.5.2 create cache profiles*
 - [Cache profiles](https://docs.microsoft.com/en-us/aspnet/core/performance/caching/response?view=aspnetcore-3.1#cache-profiles)

*1.5.3 implement HTTP caching*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> page 57
 - [HTTP-based response caching](https://docs.microsoft.com/en-us/aspnet/core/performance/caching/response?view=aspnetcore-3.1#http-based-response-caching)

*1.5.4 implement Azure Redis caching*
 - [Quickstart: Use Azure Cache for Redis with an ASP.NET web app](https://docs.microsoft.com/en-us/azure/azure-cache-for-redis/cache-web-app-howto)
 - [Improve session scalability in a .NET Framework ASP.NET web application by using Azure Cache for Redis](https://docs.microsoft.com/en-us/learn/modules/aspnet-session/)

*1.5.5 plan a content delivery network (CDN) strategy, for example, Azure CDN*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> page 202
 - [Quickstart: Create an Azure CDN profile and endpoint](https://docs.microsoft.com/en-us/azure/cdn/cdn-create-new-endpoint)

**1.6 Design and implement a Web Socket strategy**
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 60-67
 - [WebSockets support in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/websockets?view=aspnetcore-3.1)

*1.6.1 Read and write string and binary data asynchronously*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 60-63

*1.6.2 choose a connection loss strategy*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> page 64

*1.6.3 decide when to use Web Sockets*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 64-65

*1.6.4 implement SignalR*
 - [Introduction to ASP.NET Core SignalR](https://docs.microsoft.com/en-us/aspnet/core/signalr/introduction?view=aspnetcore-3.1)
 - [Tutorial: Get started with ASP.NET Core SignalR](https://docs.microsoft.com/en-us/aspnet/core/tutorials/signalr?tabs=visual-studio&view=aspnetcore-3.1)
 - [Getting started with ASP.NET Core SignalR](https://app.pluralsight.com/library/courses/aspdotnet-core-signalr-getting-started) [$][video]

*1.6.5 enable web socket features in an Azure Web App instance*
 - [Introduction to WebSockets on Windows Azure Web Sites](https://azure.microsoft.com/ru-ru/blog/introduction-to-websockets-on-windows-azure-web-sites/)

**1.7 Design a configuration management solution**

*1.7.1 Manage configuration sources, including XML, JSON, and INI files*
 - [Configuration in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/configuration/?view=aspnetcore-3.1)
 - [Эволюция конфигурации .NET](https://habr.com/ru/company/arcadia/blog/514652/)

*1.7.2 manage environment variables*
 - [Environment variables](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/configuration/?view=aspnetcore-3.1#environment-variables)

*1.7.3 implement Option objects*
 - [Options pattern in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/configuration/options?view=aspnetcore-3.1)
 - [Using Configuration and Options in .NET Core and ASP.NET Core Apps](https://app.pluralsight.com/library/courses/dotnet-core-aspnet-core-configuration-options) [$][video]

*1.7.4 implement multiple environments using files and hierarchical structure*
 - [Hierarchical configuration data](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/configuration/?view=aspnetcore-3.1#hierarchical-configuration-data)
 - [Use multiple environments in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/environments?view=aspnetcore-3.1)

*1.7.5 manage sensitive configuration*
 - [Safe storage of app secrets in development in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/security/app-secrets)

*1.7.6 react to runtime configuration changes*
 - [Auto Refresh Settings Changes in ASP.NET Core Runtime](https://edi.wang/post/2019/1/5/auto-refresh-settings-changes-in-aspnet-core-runtime)

*1.7.7 implement a custom configuration source*
 - [Custom configuration provider](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/configuration/?view=aspnetcore-3.1#custom-configuration-provider)

*1.7.8 secure configuration by using Azure Key Vault*
 - [Azure Key Vault Configuration Provider in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/security/key-vault-configuration?view=aspnetcore-3.1)

*1.7.9 use the Secret Manager tool in development to keep secrets out of your code for configuration values*
 - [Secret Manager](https://docs.microsoft.com/en-us/aspnet/core/security/app-secrets?view=aspnetcore-3.1&tabs=windows#secret-manager)

**1.8 Interact with the host environment**
 - [ASP.NET Core Web Host](https://docs.microsoft.com/en-my/aspnet/core/fundamentals/host/web-host?view=aspnetcore-3.1)

*1.8.1 Work with file system using file providers*
 - [File Providers in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/file-providers?view=aspnetcore-3.1)

*1.8.2 work with environment variables*
 - [Environment variables](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/configuration/?view=aspnetcore-3.1#environment-variables)

*1.8.3 determine hosting environment capabilities*
 - [Use multiple environments in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/environments?view=aspnetcore-3.1)

*1.8.4 implement native components, including PInvoke and native dependencies for hosts including Linux and Windows*
 - [Platform Invoke (P/Invoke)](https://docs.microsoft.com/en-us/dotnet/standard/native-interop/pinvoke)

*1.8.5 use ASP.NET hosting on an Open Web Interface for .NET (OWIN)-based server*
 - [Open Web Interface for .NET (OWIN) with ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/owin?view=aspnetcore-3.1)
 - [OWIN и Katana: первый взгляд](https://habr.com/ru/post/202018/)

**1.9 Compose an application by using the framework pipeline**
 - [ASP.NET Core 3.0: The MVC Request Life Cycle](https://app.pluralsight.com/library/courses/aspnet-core-3-mvc-request-life-cycle) [$][video]
 - [ASP.NET Core Middleware](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/middleware/?view=aspnetcore-3.1)
 - "ASP.NET Core in Action"<sup>[3]</sup> pages 61-92

*1.9.1 Add custom request processing modules to the pipeline*
 - [Adding Custom Processing to Requests in ASP.NET](https://visualstudiomagazine.com/articles/2018/10/01/adding-custom-processing.aspx)

*1.9.2 add, remove, and configure services used in the application*
 - [App startup in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/startup?view=aspnetcore-3.1)

*1.9.3 design and implement middleware*
 - [Write custom ASP.NET Core middleware](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/middleware/write?view=aspnetcore-3.1)

*1.9.4 design for kestrel, Http.sys web server and IIS*
 - [Web server implementations in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/servers/?view=aspnetcore-3.1&tabs=windows)
 - [Kestrel in ASP.NET Core apps](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/servers/?view=aspnetcore-3.1&tabs=windows)
 - [How to use HTTP.sys](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/servers/httpsys?view=aspnetcore-3.1#how-to-use-httpsys)
 - [Enable the IISIntegration components](https://docs.microsoft.com/en-us/aspnet/core/host-and-deploy/iis/?view=aspnetcore-3.1#enable-the-iisintegration-components)

*1.9.5 design and implement startup filters*
 - [Extend Startup with startup filters](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/startup?view=aspnetcore-3.1#extend-startup-with-startup-filters)
 - [Exploring IStartupFilter in ASP.NET Core](https://andrewlock.net/exploring-istartupfilter-in-asp-net-core/)

### 2. Design the build and deployment architecture (10-15%)

**2.1 Design a browser artifact build strategy**

*2.1.1 Design a JavaScript build pipeline using Gulp, Grunt, npm and Bower*
 - [Introduction to Bower, Grunt, and Gulp in Visual Studio](https://www.red-gate.com/simple-talk/dotnet/asp-net/introduction-to-bower-grunt-and-gulp-in-visual-studio/)
 - [Use Grunt in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/client-side/using-grunt?view=aspnetcore-3.1)
 - [Client-side library acquisition in ASP.NET Core with LibMan](https://docs.microsoft.com/en-us/aspnet/core/client-side/libman/?view=aspnetcore-3.1)

*2.1.2 design an artifact build strategy using Less, Sass and Font Awesome*
 - [Стилизация приложений с помощью Less, Sass и Font Awesome](https://dotnet.today/ru/aspnet5-vnext/client-side/less-sass-fa.html)
 - [Styling Applications with Less, Sass, and Font Awesome](https://jakeydocs.readthedocs.io/en/latest/client-side/less-sass-fa.html)

*2.1.3 design and implement a bundling and minification strategy for broswer artifacts, including JavaScript, CSS and images*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 197-202
 - [Bundle and minify static assets in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/client-side/bundling-and-minification?view=aspnetcore-3.1)
 - [Объединение и минификация файлов на примере ASP.NET Core MVC. Bundling and Minification](https://alekseev74.ru/lessons/show/aspnet-core-mvc/bundling-and-minification)

**2.2 Design a server build strategy**

*2.2.1 Manage NuGet dependencies*
 - Install and manage packages in
   - [Visual Studio](https://docs.microsoft.com/en-us/nuget/consume-packages/install-use-packages-visual-studio)
   - [dotnet CLI](https://docs.microsoft.com/en-us/nuget/consume-packages/install-use-packages-dotnet-cli)
   - [Package Manager Console](https://docs.microsoft.com/en-us/nuget/consume-packages/install-use-packages-powershell)

*2.2.2 target runtimes, including the full .NET Framework, .NET core, and .NET standard*
 - [Target frameworks in SDK-style projects](https://docs.microsoft.com/en-us/dotnet/standard/frameworks)

*2.2.3 manage debug and release configurations, including compilation and optimization options*
 - [C# Debug vs. Release builds](https://benhall.io/c-debug-vs-release-builds-and-debugging-in-visual-studio-from-novice-to-expert-in-one-blog-article/)
 - [Set debug and release configurations in Visual Studio](https://docs.microsoft.com/en-us/visualstudio/debugger/how-to-set-debug-and-release-configurations?view=vs-2019)
 - [Project settings for C# debug configurations](https://docs.microsoft.com/en-us/visualstudio/debugger/project-settings-for-csharp-debug-configurations?view=vs-2019)

*2.2.4 include or exclude files from build*
 - [Excluding Files and Folders in Visual Studio Web Site Project](https://weblog.west-wind.com/posts/2020/Jul/25/Excluding-Files-and-Folders-in-Visual-Studio-Web-Site-Project)
 - [How to: Select the files to build](https://docs.microsoft.com/en-us/visualstudio/msbuild/how-to-select-the-files-to-build?view=vs-2019)
 - [How to: Exclude files from the build](https://docs.microsoft.com/en-us/visualstudio/msbuild/how-to-exclude-files-from-the-build?view=vs-2019)
 - [Excluding Files and Folders from Deployment](https://docs.microsoft.com/en-us/aspnet/web-forms/overview/deployment/advanced-enterprise-web-deployment/excluding-files-and-folders-from-deployment)

*2.2.5 manage build sources, including content, resources, and shared files*
- [Project file "files" section](https://docs.microsoft.com/en-us/dotnet/core/tools/project-json-to-csproj#files)

*2.2.6 implement metadata for projects, including version, release notes, and descriptions*
 - [A mapping between project.json and csproj properties](https://docs.microsoft.com/en-us/dotnet/core/tools/project-json-to-csproj)

*2.2.7 define other build options, including xmlDoc and warningsAsErrors*
 - [Some cool Project.json features with ASP.NET Core](https://www.talkingdotnet.com/cool-project-json-features-with-asp-net-core/)

*2.2.8 work with static files in ASP.NET core*
 - [Static files in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/static-files?view=aspnetcore-3.1)

**2.3 Design a publishing strategy**
 - [Overview of deployment in Visual Studio](https://docs.microsoft.com/en-us/visualstudio/deployment/deploying-applications-services-and-components-resources?view=vs-2019)
 - [Visual Studio publish profiles (.pubxml) for ASP.NET Core app deployment](https://docs.microsoft.com/en-us/aspnet/core/host-and-deploy/visual-studio-publish-profiles?view=aspnetcore-3.1)
 - [How Web Publishing In Visual Studio Works](https://aspnetcore.readthedocs.io/en/stable/publishing/web-publishing-vs.html)

*2.3.1 Implement application publishing using dotnet.exe*
 - [Basic command-line publishing](https://docs.microsoft.com/en-us/aspnet/core/host-and-deploy/visual-studio-publish-profiles?view=aspnetcore-3.1#basic-command-line-publishing)
 - [dotnet publish](https://docs.microsoft.com/en-us/dotnet/core/tools/dotnet-publish)

*2.3.2 manage publishing options in csproj*
 - [Visual Studio publish profiles (.pubxml) for ASP.NET Core app deployment](https://docs.microsoft.com/en-us/aspnet/core/host-and-deploy/visual-studio-publish-profiles?view=aspnetcore-3.1)

*2.3.3 implement additional tooling*

*2.3.4 implement pre-publish and post-publish scripts*
 - [Running Scripts Pre and Post Publish in ASP.NET Core RC2](https://www.jamessturtevant.com/posts/Running-scripts-pre-and-post-publish-in-ASPNET-Core-RC2/)
 - [Run a target before or after publishing](https://docs.microsoft.com/en-us/aspnet/core/host-and-deploy/visual-studio-publish-profiles?view=aspnetcore-3.1#run-a-target-before-or-after-publishing)

*2.3.5 implement native compilation*

*2.3.6 publish to Docker container image*
 - [Deploy an ASP.NET container to a container registry using Visual Studio](https://docs.microsoft.com/ru-ru/visualstudio/containers/hosting-web-apps-in-docker?view=vs-2019)
 - [Docker Cheat Sheet](https://dev.to/hasone/docker-cheat-sheet-27po)
 - [Administer containers in Azure](https://docs.microsoft.com/en-us/learn/paths/administer-containers-in-azure/)

**2.4 Implement an Azure deployment strategy**

*2.4.1 Deploy Azure Web App using supported deployment models including FTP, Kudu, Web Deploy, and Visual Studio Publishing Wizard*
 - [Deploy your app to Azure App Service using FTP](https://docs.microsoft.com/en-us/azure/app-service/deploy-ftp)
 - [Deploy your app to Azure App Service with a ZIP or WAR file](https://docs.microsoft.com/en-us/azure/app-service/deploy-zip)
 - [Publish an ASP.NET Core app to Azure with Visual Studio](https://docs.microsoft.com/en-us/aspnet/core/tutorials/publish-to-azure-webapp-using-vs?view=aspnetcore-3.1)
 - [Publish a web app to Azure with Visual Studio](https://docs.microsoft.com/en-us/learn/modules/publish-azure-web-app-with-visual-studio/)

*2.4.2 provision ARM based resources while deploying application*
 - [Deploy resources with ARM templates and Azure portal](https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/deploy-portal)
 - [Creating and deploying Azure resource groups through Visual Studio](https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/create-visual-studio-deployment-project)

*2.4.3 implement deployment environments, including dev, test, and prod in Azure*
 - [Create and target an environment](https://docs.microsoft.com/en-us/azure/devops/pipelines/process/environments?view=azure-devops)

*2.4.4 use deployment slots for staging sites*
 - [Stage a web app deployment for testing and rollback by using App Service deployment slots](https://docs.microsoft.com/en-us/learn/modules/stage-deploy-app-service-deployment-slots/)

*2.4.5 deploy to Azure Stack*
 - [Deploy a C# ASP.NET web app to a VM in Azure Stack Hub](https://docs.microsoft.com/en-us/azure-stack/user/azure-stack-dev-start-howto-vm-dotnet?view=azs-2002)

**2.5 Implement a on-premises deployment strategy**

*2.5.1 Deploy application to IIS using Web Deploy, xcopy, and Visual Studio Publishing Wizard*
 - [Introduction to Web Deploy](https://docs.microsoft.com/en-us/iis/publish/using-web-deploy/introduction-to-web-deploy)

*2.5.2 deploy application to Windows Nano Server, deploy application to IIS Hosted Web Core, deploy application to HTTP.sys web server*
 - [How to use HTTP.sys](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/servers/httpsys?view=aspnetcore-3.1#how-to-use-httpsys)

*2.5.3 deploy application to Kestrel on Windows and Linux*
 - [Kestrel in ASP.NET Core apps](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/servers/?view=aspnetcore-3.1&tabs=windows)

*2.5.4 implement reverse proxying to Kestrel using IIS and Nginx*
 - [When to use Kestrel with a reverse proxy](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/servers/kestrel?view=aspnetcore-3.1#when-to-use-kestrel-with-a-reverse-proxy)

### 3. Design the User Experience (Interface) (15-20%)

**3.1 Create elements of the user interface for a web application**

*3.1.1 Create and apply styles by using CSS*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 86-89
 - [CSS3](https://html5book.ru/css-css3/)

*3.1.2 structure and lay out the user interface by using HTML*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 90-92
 - [HTML5](https://html5book.ru/html-html5/)

*3.1.3 implement dynamic page content based on a design*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 92-95

**3.2 Design and implement UI behavior**
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 97-113

*3.2.1 Implement client-side validation*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 98-103
 - [Client-side validation](https://docs.microsoft.com/en-us/aspnet/core/mvc/models/validation?view=aspnetcore-2.1#client-side-validation-1)
 - [ASP.NET Core and ASP.NET Input Validation](https://app.pluralsight.com/library/courses/using-validation-best-practices-secure-aspdotnet-core-applications/) [$][video]

*3.2.2 use JavaScript to manipulate the DOM*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> page 103
 - [How to Manipulate HTML (An Intro to the JS DOM)](https://medium.com/@pdlozano/how-to-manipulate-html-an-intro-to-the-js-dom-276784df6d61)
 - [Манипуляции HTML-элементами](https://html5book.ru/jquery-manipulyacii)

*3.2.3 extend objects by using prototypal inheritance*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 103-105
 - [Prototypal inheritance](https://javascript.info/prototype-inheritance)

*3.2.4 use AJAX to make partial page updates*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 105-108

**3.3 Design the UI layout of an application**
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 114-123
 - [Layout in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/mvc/views/layout?view=aspnetcore-3.1)

*3.3.1 Implement partial views and view components for reuse in different areas of the application*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 114-116
 - "Pro ASP.NET Core MVC 2"<sup>[2]</sup> cтр. 680-685
 - "Pro ASP.NET Core MVC 2"<sup>[2]</sup> cтр. 700-722
 - [View components in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/mvc/views/view-components?view=aspnetcore-3.1)
 - [ASP.NET Core Tag Helpers and View Components](https://app.pluralsight.com/library/courses/aspdotnet-core-tag-helpers) [$][video]

*3.3.2 design and implement pages by using Razor Pages*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> page 117
 - [Introduction to Razor Pages in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/razor-pages/?view=aspnetcore-3.1&tabs=visual-studio)

*3.3.3 design and implement layouts to provide visual structure*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 117-118

*3.3.4 define and render optional and required page sections*
- [Sections](https://docs.microsoft.com/en-us/aspnet/core/mvc/views/layout?view=aspnetcore-3.1#sections)

*3.3.5 create and use tag and HTML helpers to simplify markup*
 - "Pro ASP.NET Core MVC 2"<sup>[2]</sup> cтр. 723-754
 - [Tag Helpers in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/mvc/views/tag-helpers/intro?view=aspnetcore-3.1)
 - [ASP.NET Core Tag Helpers and View Components](https://app.pluralsight.com/library/courses/aspdotnet-core-tag-helpers) [$][video]

**3.4 Plan a responsive UI layout**

*3.4.1 Plan for applications that run on multiple devices and screen resolutions*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 132-134

*3.4.2 use media queries and Bootstrap's responsive grid*
 - [CSS Media Queries](https://www.w3schools.com/css/css3_mediaqueries.asp)
 - [Grid system](https://getbootstrap.com/docs/4.1/layout/grid/)

*3.4.3 detect browser features and capabilities*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 124-126
 - [Implementing feature detection](https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Cross_browser_testing/Feature_detection)

*3.4.4 create a web application that runs across multiple browsers and mobile devices*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 126-128

*3.4.5 enable consistent cross-browser experiences with polyfills*
 - [A Beginner's Guide to HTML5 Cross-Browser Polyfills](https://www.sitepoint.com/html5-cross-browser-polyfills/)
 - [How Polyfills Remove Browser Compatibility](https://medium.com/valtech-ch/how-polyfills-remove-browser-compatibility-d601dbfab4b8)

**3.5 Plan mobile UI strategy**

*3.5.1 Implement mobile specific UI elements such as touch input, low bandwidth situations, and device orientation changes*
 - [Hybrid Mobile Apps with ASP.NET MVC](https://www.infoq.com/articles/Hybrid-Mobile-Apps-MVC/) [?]

*3.5.2 define and implement a strategy for working with mobile browsers*
 - [Making your existing ASP.NET MVC Web Site Mobile Friendly](https://www.dotnetcurry.com/aspnet-mvc/877/mobile-friendly-aspnet-mvc-website) [?]

### 4. Develop the User Experience (15-20%)

**4.1 Plan for search engine optimization and accessibility**
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 145-156
 - [Plan for search engine optimization and accessibility](http://failedturing.blogspot.com/2015/03/microsoft-70-486-plan-for-search-engine.html)
 - [Search Engine Optimization with ASP.NET](https://www.pluralsight.com/courses/seo-with-aspdotnet) [$][video]

*4.1.1 Use analytical tools to parse HTML*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 146-149

*4.1.2 provide an xml sitemap and robots.txt file to improve scraping*
 - [Managing Robots.txt and Sitemap Files](https://docs.microsoft.com/en-us/iis/extensions/iis-search-engine-optimization-toolkit/managing-robotstxt-and-sitemap-files)
 - [Serving sitemap.xml and robots.txt with ASP.Net core MVC](https://dev.to/estyc/serving-sitemap-xml-and-robots-txt-with-asp-net-core-mvc-10f1)

*4.1.3 write semantic markup for accessibility, for example, screen readers*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 151-153

*4.1.4 use rich snippets to increase content visibility*
 - [What Is Structured Data And How To Add It Using JSON-LD, Schema.NET And Asp.Net MVC](https://quoracreative.com/article/Implement-Structured-Data-in-Jason-LD-format-using-Schema-Net-and-Asp-Net-MVC)

**4.2 Plan and implement globalization and localization**
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 156-163
 - [Globalization and localization in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/localization?view=aspnetcore-3.1) - Docs
 - [Globalization and Localization in ASP.NET Core](https://www.codewithmukesh.com/blog/globalization-and-localization-in-aspnet-core/) - Blog Post

*4.2.1. Plan a localization strategy*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 156-158

*4.2.2. create and apply resources to UI including JavaScript resources*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 158-160

*4.2.3. set cultures*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 160-161

*4.2.4. implement server side localization and globalization*
 - [Globalization and localization in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/localization?view=aspnetcore-3.1)

**4.3 Design and implement MVC controllers and actions**
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 163-175

*4.3.1 Apply authorization attributes, filters including global, authentication, and overriddable filters*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 164-167
 - "Pro ASP.NET Core MVC 2"<sup>[2]</sup> cтр. 589-626
 - [Filters in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/mvc/controllers/filters?view=aspnetcore-3.1)

*4.3.2 choose and implement custom HTTP status codes and responses*
 - "Pro ASP.NET Core MVC 2"<sup>[2]</sup> cтр. 548-555

*4.3.3 implement action results*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 168-170
 - "Pro ASP.NET Core MVC 2"<sup>[2]</sup> cтр. 529-548
 - [ActionResult In ASP.NET Core MVC](https://www.c-sharpcorner.com/article/actionresult-in-asp-net-core-mvc/)

*4.3.4 implement MVC areas*
 - [Areas in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/mvc/controllers/areas?view=aspnetcore-3.1)

*4.3.5 implement Dependency Injection for services in controllers*
 - [Dependency injection into controllers in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/mvc/controllers/dependency-injection?view=aspnetcore-3.1)

**4.4 Design and implement routes**
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 175-185
 - [Routing in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/routing?view=aspnetcore-2.1)
 - [Routing to controller actions in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/mvc/controllers/routing?view=aspnetcore-2.1)
 - [Routing in ASP.NET Core 3.1 - Endpoints](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/routing?view=aspnetcore-3.1)

*4.4.1 Define a route to handle a URL pattern*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 176-178
 - "Pro ASP.NET Core MVC 2"<sup>[2]</sup> cтр. 443-459
 - [Route template reference](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/routing?view=aspnetcore-2.1#route-template-reference-2)

*4.4.2 apply route constraints*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 178-179
 - "Pro ASP.NET Core MVC 2"<sup>[2]</sup> cтр. 460-470
 - [Route constraint reference](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/routing?view=aspnetcore-2.1#route-constraint-reference-2)

*4.4.3 ignore URL patterns*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 179-180
 - [How to ignore routes in ASP.NET Core?](https://stackoverflow.com/questions/39517816/how-to-ignore-routes-in-asp-net-core)

*4.4.4 add custom route parameters*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> page 180
 - "Pro ASP.NET Core MVC 2"<sup>[2]</sup> cтр. 452-459

*4.4.5 define areas*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 181-182
 - "Pro ASP.NET Core MVC 2"<sup>[2]</sup> cтр. 505-510
 - [Routing - Areas](https://docs.microsoft.com/en-us/aspnet/core/mvc/controllers/routing?view=aspnetcore-2.1)

*4.4.6 define routes that interoperate with Single Page Application frameworks such as Angular*
 - [Совмещение маршрутизации Angular и ASP.NET Core](https://metanit.com/sharp/aspnetcore/2.2.php)

**4.5 Control application behavior by using MVC extensibility points**
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 186-197
 - [ASP.NET Core 3.0: The MVC Request Life Cycle](https://app.pluralsight.com/library/courses/aspnet-core-3-mvc-request-life-cycle) [$][video]
 - [Improving .NET Core MVC Apps Using Extension Points](https://app.pluralsight.com/library/courses/dotnet-core-mvc-apps-extensions/table-of-contents) [$][video]

*4.5.1 Create custom middleware and inject it into the pipeline*
 - [ASP.NET Core Middleware](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/middleware/?view=aspnetcore-3.1)

*4.5.2 implement MVC filters and controller factories*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 186-188
 - [Filters in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/mvc/controllers/filters?view=aspnetcore-3.1)

*4.5.3 control application behavior by using action results, model binders, and route handlers*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 188-194
 - [How to write custom actionResult in asp.net core](https://stackoverflow.com/questions/42594356/how-to-write-custom-actionresult-in-asp-net-core/42594823)
 - [Custom Model Binding In ASP.NET Core MVC](https://www.c-sharpcorner.com/article/custom-model-binding-in-asp-net-core-mvc/)
 - [Routing Middleware — Route Handler](https://medium.com/@lucaslra/asp-net-core-mvc-pipeline-routing-middleware-route-handler-6432229fe706)

*4.5.4 inject services into a view*
 - [Dependency injection into views in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/mvc/views/dependency-injection?view=aspnetcore-3.1)

**4.6 Design and implement serialization and model binding**

*4.6.1 Serialize models and data using supported serialization formats, including JSON, XML, protobuf, and WCF/SOAP*
 - [JSON and XML Serialization in ASP.NET Web API](https://docs.microsoft.com/en-us/aspnet/web-api/overview/formats-and-model-binding/json-and-xml-serialization)
 - [Protocol Buffer Basics: C#](https://developers.google.com/protocol-buffers/docs/csharptutorial)

*4.6.2 implement model and property binding, including custom binding and model validation*
 - "Pro ASP.NET Core MVC 2"<sup>[2]</sup> cтр. 809-876
 - [Custom Model Binding in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/mvc/advanced/custom-model-binding?view=aspnetcore-3.1)
 - [Validation - Custom attributes](https://docs.microsoft.com/en-us/aspnet/core/mvc/models/validation?view=aspnetcore-2.1#custom-attributes-1)

*4.6.3 implement web socket communication in MVC*
 - [WebSockets support in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/websockets?view=aspnetcore-3.1)

*4.6.4 implement file uploading and multipart data*
 - [Upload files in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/mvc/models/file-uploads?view=aspnetcore-3.1)

*4.6.5 use AutoRest to build clients*
 - [Generating clients for your APIs with AutoRest](https://dzimchuk.net/generating-clients-for-your-apis-with-autorest/)

### 5. Troubleshoot and Debug Web Applications (20-25%)

**5.1 Prevent and troubleshoot runtime issues**
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 215-234

*5.1.1 Troubleshoot performance, security, and errors*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 216-223
 - [First look at profiling tools](https://docs.microsoft.com/en-us/visualstudio/profiling/profiling-feature-tour?view=vs-2019)
 - [Measure application performance by analyzing CPU usage](https://docs.microsoft.com/en-us/visualstudio/profiling/beginners-guide-to-performance-profiling?view=vs-2019)
 - [Measure memory usage in Visual Studio](https://docs.microsoft.com/en-us/visualstudio/profiling/memory-usage?view=vs-2019)
 - [Performance Testing Techniques](https://channel9.msdn.com/Shows/On-NET/ASPNET-Core-Series-Performance-Testing-Techniques) [video]

*5.1.2 implement tracing, logging, and debugging including IntelliTrace*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 223-227
 - [IntelliTrace for Visual Studio Enterprise](https://docs.microsoft.com/en-us/visualstudio/debugger/intellitrace?view=vs-2019)
 - [First look at the Visual Studio Debugger](https://docs.microsoft.com/en-us/visualstudio/debugger/debugger-feature-tour?view=vs-2019)
 - [Effective Logging in ASP.NET Core](https://app.pluralsight.com/library/courses/asp-dotnet-core-effective-logging) [$][video]

*5.1.3 enable and configure health monitoring including Performance Monitor*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 230-232
 - [Windows Performance Monitor Overview](https://techcommunity.microsoft.com/t5/ask-the-performance-team/windows-performance-monitor-overview/ba-p/375481)
 - [ASP.NET Core Health Checks](https://app.pluralsight.com/library/courses/asp-dot-net-core-health-checks/table-of-contents) [$][video]

*5.1.4 configure and use App Insights runtime telemetry*
 - [What is Application Insights?](https://docs.microsoft.com/en-us/azure/azure-monitor/app/app-insights-overview)
 - [Application Insights for ASP.NET Core applications](https://docs.microsoft.com/en-us/azure/azure-monitor/app/asp-net-core)

**5.2 Design an exception handling strategy**
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 234-243

*5.2.1 Handle exceptions across multiple layers*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 235-236
 - [Handle errors in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/error-handling?view=aspnetcore-3.1)

*5.2.2 use MVC middleware to configure error handling*
 - "ASP.NET Core in Action"<sup>[3]</sup> pages 78-92

*5.2.3 use different exception handling strategies for different environments*
 - "ASP.NET Core in Action"<sup>[3]</sup> pages 80-86
 
*5.2.4 create and display custom error pages*
 - [Exception handler page](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/error-handling?view=aspnetcore-3.1#exception-handler-page)

*5.2.5 configure a custom pipeline for error handling*
 - [Global Exception Handling in ASP.NET Core Web API](https://blog.jonblankenship.com/2020/04/12/global-exception-handling-in-aspnet-core-api/)
 - [Creating a custom ErrorHandlerMiddleware function](https://andrewlock.net/creating-a-custom-error-handler-middleware-function/)

*5.2.6 handle first chance exceptions*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 238-240
 - [How to: Receive First-Chance Exception Notifications](https://docs.microsoft.com/en-us/dotnet/framework/app-domains/how-to-receive-first-chance-exception-notifications)

*5.2.7 configure and use App Insights*
 - [Application Insights for ASP.NET Core applications](https://docs.microsoft.com/en-us/azure/azure-monitor/app/asp-net-core)

*5.2.8 log application exceptions*
 - [Global Error Handling In ASP.NET Core App Using NLog](https://www.c-sharpcorner.com/article/global-error-handling-in-asp-net-core-app-using-nlog/)
 - [Log exceptions](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/logging/?view=aspnetcore-3.1#log-exceptions)

**5.3 Test a web application**
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 243-255

*5.3.1 Create and run unit tests, for example, use the Assert class, create mocks and stubs*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 244-250
 - [Walkthrough: Create and run unit tests for managed code](https://docs.microsoft.com/en-us/visualstudio/test/walkthrough-creating-and-running-unit-tests-for-managed-code?view=vs-2019)
 - [Unit testing best practices](https://docs.microsoft.com/en-us/dotnet/core/testing/unit-testing-best-practices)
 - [Unit test controller logic in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/mvc/controllers/testing?view=aspnetcore-3.1)
 - [Test ASP.NET Core middleware](https://docs.microsoft.com/en-us/aspnet/core/test/middleware?view=aspnetcore-3.1)
 - [Integration tests in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/test/integration-tests?view=aspnetcore-3.1)
 - [Microsoft Azure Developer: Performing Unit Testing & Integration Testing](https://app.pluralsight.com/course-player?clipId=862dd10e-4860-4e7b-8dca-84bcfd83f743) [$][video]

*5.3.2 create and run web tests including using Browser Link*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 250-252
 - [Browser Link in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/client-side/using-browserlink?view=aspnetcore-3.1)

*5.3.3 debug a web application in multiple browsers and mobile emulators*

*5.3.4 use Azure DevTest Labs*
 - [About Azure DevTest Labs](https://docs.microsoft.com/en-us/azure/devtest-labs/devtest-lab-overview)

*5.3.5 use Visual Studio Team Services*
 - [What is Azure DevOps](https://docs.microsoft.com/en-us/azure/devops/user-guide/what-is-azure-devops?view=azure-devops)
 - [Хабр: Visual Studio Team Services](https://habr.com/ru/post/325906/) [*устар.]

**5.4 Debug an Azure application**
 - [Troubleshoot an app in Azure App Service using Visual Studio](https://docs.microsoft.com/en-us/azure/app-service/troubleshoot-dotnet-visual-studio)

*5.4.1 Collect diagnostic information by using Azure App Insights*
 - [Instrument Application with Azure Monitor Application Insights](https://app.pluralsight.com/library/courses/microsoft-azure-application-insights-web-application-instrument) [$][video]
 - [Microsoft Azure Developer: Troubleshooting Using Microsoft Azure Portal](https://app.pluralsight.com/library/courses/microsoft-azure-portal-troubleshooting-using) [$][video]

*5.4.2 choose log types, for example, event logs, performance counters, and crash dumps*
 - [Microsoft Azure Developer: Implementing Application Logging with App Service Logs](https://app.pluralsight.com/library/courses/microsoft-azure-application-logging-diagnostic-logs-implementing) [$][video]

*5.4.3 stream logs directly to Visual Studio from a deployed site*
 - [Diagnostic logs overview](https://docs.microsoft.com/en-us/azure/app-service/troubleshoot-dotnet-visual-studio#logsoverview)

*5.4.4 debug an Azure application by using Visual Studio and remote debugging*
 - [Remote Debug ASP.NET Core on IIS in Azure in Visual Studio](https://docs.microsoft.com/en-us/visualstudio/debugger/remote-debugging-azure?view=vs-2019)
 - [Debug live ASP.NET Azure apps using the Snapshot Debugger](https://docs.microsoft.com/en-us/visualstudio/debugger/debug-live-azure-applications?view=vs-2019)

*5.4.5 interact directly with remote Azure websites using Server Explorer*
 - [Access app files in Server Explorer](https://docs.microsoft.com/en-us/azure/app-service/troubleshoot-dotnet-visual-studio#remoteview)

### 6 Design and Implement Security (15-20%)

**6.1 Configure authentication**
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 271-293
 - [ASP.NET Core - Authentication & Authorization Tutorial](https://www.youtube.com/playlist?list=PLOeFnOV9YBa7dnrjpOG6lMpcyd7Wn7E8V) [video]
 - [Authentication and Authorization in ASP.NET Core](https://app.pluralsight.com/library/courses/authentication-authorization-aspnet-core/table-of-contents) [$][video]

*6.1.1 Authenticate users*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 272-280
 - [Overview of ASP.NET Core authentication](https://docs.microsoft.com/en-us/aspnet/core/security/authentication/?view=aspnetcore-3.1)

*6.1.2 enforce authentication settings*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 280-282

*6.1.3 implement ASP.NET Core Identity*
 - "Pro ASP.NET Core MVC 2"<sup>[2]</sup> cтр. 877-972
 - [Introduction to Identity on ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/security/authentication/identity)
 - [ASP.NET Core 3 - Authentication - Ep.2 Identity Authentication](https://www.youtube.com/watch?v=IjbtWPXVJGw) [video]
 - [ASP.NET Core MVC Login and Registration with Identity](http://www.codaffection.com/asp-net-core-article/asp-net-core-mvc-login-and-registration-with-identity/)

*6.1.4 enable Facebook, Google and other external providers*
 - [Google](https://docs.microsoft.com/en-us/aspnet/core/security/authentication/social/google-logins?view=aspnetcore-3.1)
 - [Facebook](https://docs.microsoft.com/en-us/aspnet/core/security/authentication/social/facebook-logins?view=aspnetcore-3.1)
 - [Microsoft Account](https://docs.microsoft.com/en-us/aspnet/core/security/authentication/social/microsoft-logins?view=aspnetcore-3.1)
 - [Twitter](https://docs.microsoft.com/en-us/aspnet/core/security/authentication/social/twitter-logins?view=aspnetcore-3.1)
 - [External OAuth](https://docs.microsoft.com/en-us/aspnet/core/security/authentication/social/other-logins?view=aspnetcore-3.1)
 - [ASP.NET Core 3 - Authentication - Ep.2 Identity Authentication](https://www.youtube.com/watch?v=IjbtWPXVJGw) [video]

*6.1.5 implement account confirmation, password recovery, and multi-factor authentication*
 - [Account confirmation and password recovery in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/security/authentication/accconfirm)
 - [Account Confirmation and Password Recovery](https://jakeydocs.readthedocs.io/en/latest/security/authentication/accconfirm.html)
 - [Two-factor authentication with SMS in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/security/authentication/2fa)
 - [Enable QR Code generation for TOTP authenticator apps in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/security/authentication/identity-enable-qrcodes)
 - [ASP.NET Core 3 - Identity - Ep.2.1 Email Verification](https://www.youtube.com/watch?v=Vj7iCb7wDs0) [video]

*6.1.6 perform authentication using Azure Active Directory, Azure Active Directory B2C, Azure Active Directory B2B, and Microsoft Identity*
 - [Protect a web API backend in Azure API Management by using OAuth 2.0 authorization with Azure AD](https://docs.microsoft.com/en-us/azure/api-management/api-management-howto-protect-backend-with-aad)
 - [Secure your RESTful services (B2C)](https://docs.microsoft.com/en-us/azure/active-directory-b2c/secure-rest-api)
 - [Tutorial: Enable authentication in a web application using Azure Active Directory B2C](https://docs.microsoft.com/en-us/azure/active-directory-b2c/tutorial-web-app-dotnet?tabs=app-reg-ga)
 - [Using Azure Active Directory B2C with ASP.NET Core](https://csharp.christiannagel.com/2018/08/01/azureadb2c/)

*6.1.7 manage user session by using cookies*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 283-285
 - [Use cookie authentication without ASP.NET Core Identity](https://docs.microsoft.com/en-us/aspnet/core/security/authentication/cookie?view=aspnetcore-3.1)

*6.1.8 acquire access tokens using the Microsoft Authentication Library (MSAL)*
 - [Overview of Microsoft Authentication Library (MSAL)](https://docs.microsoft.com/en-us/azure/active-directory/develop/msal-overview)

**6.2 Configure and apply authorization**
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 294-303
 - [Create an ASP.NET Core web app with user data protected by authorization](https://docs.microsoft.com/en-us/aspnet/core/security/authorization/secure-data)

*6.2.1 Create roles*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 294-296
 - [Adding Role Authorization to a ASP.NET MVC Core Application](https://www.c-sharpcorner.com/article/adding-role-authorization-to-a-asp-net-mvc-core-application/)
 - [Local Users with ASP.NET Core – ASP.NET Core Identity](https://csharp.christiannagel.com/2020/07/07/aspnetcoreroles/)
 - [Управление ролями](https://metanit.com/sharp/aspnet5/16.13.php)

*6.2.2 authorize roles programmatically*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 296-298
 - [Role-based authorization in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/security/authorization/roles?view=aspnetcore-3.1)

*6.2.3 configure and work with custom UserStores using middleware*
 - [Customize the user store](https://docs.microsoft.com/en-us/aspnet/core/security/authentication/identity-custom-storage-providers?view=aspnetcore-3.1#customize-the-user-store)

*6.2.4 configure controllers and actions to participate in authorization*
 - [Авторизация](https://metanit.com/sharp/aspnet5/15.3.php)

**6.3 Design and implement claims-based authentication**
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 303-314
 - [Claims-based authorization in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/security/authorization/claims?view=aspnetcore-3.1)
 - [ASP.NET Core 3 - Authentication - Ep.3 Authorization (All about Policies and Claims)](https://www.youtube.com/watch?v=RBMO_hruKaI) [video]
 - [ASP.NET Core - Roles vs Claims vs Policy](https://www.youtube.com/watch?v=cbtK3U2aOlg) [video]

*6.3.1 perform authentication and authorization using tokens including OpenID, OAuth, JWT, SAML, bearer tokens, etc.*
 - [Google](https://docs.microsoft.com/en-us/aspnet/core/security/authentication/social/google-logins?view=aspnetcore-3.1)
 - [Facebook](https://docs.microsoft.com/en-us/aspnet/core/security/authentication/social/facebook-logins?view=aspnetcore-3.1)
 - [Microsoft Account](https://docs.microsoft.com/en-us/aspnet/core/security/authentication/social/microsoft-logins?view=aspnetcore-3.1)
 - [Twitter](https://docs.microsoft.com/en-us/aspnet/core/security/authentication/social/twitter-logins?view=aspnetcore-3.1)
 - [External OAuth](https://docs.microsoft.com/en-us/aspnet/core/security/authentication/social/other-logins?view=aspnetcore-3.1)
 - [ASP.NET Core 3 - OAuth - Ep.5 JWT Bearer](https://www.youtube.com/watch?v=YC4ewe7Rbl4) [video]
 - [ASP.NET Core 3 - OAuth - Ep.6 OAuth Client](https://www.youtube.com/watch?v=0oBIgPaFYOg) [video]
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 310-313

**6.4 Manage data integrity**
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 314-324

*6.4.1 Apply encryption to application data*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 316-318
 - [Cryptography in .NET](https://www.meziantou.net/cryptography-in-dotnet.htm)

*6.4.2 apply encryption to the configuration sections of an application*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 319-320
 - [Encrypting and Decrypting Configuration Sections](https://docs.microsoft.com/en-us/previous-versions/aspnet/zhhddkxy(v=vs.100))

*6.4.3 sign application data to prevent tampering*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 321-322

*6.4.4 secure data using Azure Key Vault*
 - [About Azure Key Vault](https://docs.microsoft.com/en-us/azure/key-vault/general/overview)

*6.4.5 implement encryption for data protection using the data protection APIs in transit and at rest*
 - [ASP.NET Core Data Protection](https://docs.microsoft.com/en-us/aspnet/core/security/data-protection/introduction?view=aspnetcore-3.1)
 - [Configure ASP.NET Core Data Protection](https://docs.microsoft.com/en-us/aspnet/core/security/data-protection/configuration/overview?view=aspnetcore-3.1)

**6.5 Implement a secure site**
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 324-338
 - [Securing ASP.NET and ASP.NET Core Applications](https://app.pluralsight.com/paths/skills/securing-aspnet-and-aspnet-core-applications) [$][video]

*6.5.1 Secure communication by applying SSL certificates*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 325-328
 - [Configuring HTTPS in ASP.NET Core across different platforms](https://devblogs.microsoft.com/aspnet/configuring-https-in-asp-net-core-across-different-platforms/)

*6.5.2 require SSL for all requests*
 - [Enforce HTTPS in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/security/enforcing-ssl?view=aspnetcore-3.1&tabs=visual-studio)
 - [Implementing HTTPS in ASP.NET and ASP.NET Core](https://app.pluralsight.com/library/courses/https-aspnet-and-aspnet-core)

*6.5.3 enable SSL hosting in the development environment*
 - [Developing locally with ASP.NET Core under HTTPS, SSL, and Self-Signed Certs](https://www.hanselman.com/blog/DevelopingLocallyWithASPNETCoreUnderHTTPSSSLAndSelfSignedCerts.aspx)

*6.5.4 implement SSL using Azure Load Balancers*
 - [Understanding Azure Load Balancing Solutions - Azure Load Balancer, Azure Application Gateway and Azure Traffic Manager](https://www.codeproject.com/Articles/1254411/Understanding-Azure-Load-Balancing-Solutions-Azure)
 - [Open port 443 in the Azure load balancer](https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-tutorial-dotnet-app-enable-https-endpoint#open-port-443-in-the-azure-load-balancer)

*6.5.5 salt and hash passwords for storage*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 328-331
 - [Hash passwords in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/security/data-protection/consumer-apis/password-hashing?view=aspnetcore-3.1)

*6.5.6 use HTML encoding to prevent cross-site scripting attacks (ANTI-XSS Library)*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 331-332
 - [Prevent Cross-Site Scripting (XSS) in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/security/cross-site-scripting?view=aspnetcore-3.1)
 - [Cross Site Scripting (XSS) Prevention for ASP.NET Core and ASP.NET Applications](https://app.pluralsight.com/library/courses/cross-site-scripting-xss-prevention-asp-dot-net-core-applications) [$][video]

*6.5.7 implement deferred validation and handle unvalidated requests, for example, form, querystring, and URL*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 332-333
 - [ASP.NET Core and ASP.NET Input Validation](https://app.pluralsight.com/library/courses/using-validation-best-practices-secure-aspdotnet-core-applications) [$][video]

*6.5.8 prevent SQL injection attacks by parameterizing queries*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 333-335
 - [Defeating Injection Attacks in ASP.NET and ASP.NET Core](https://app.pluralsight.com/library/courses/defeating-injection-attacks-aspnet-aspnet-core) [$][video]

*6.5.9 prevent cross-site request forgeries (XSRF)*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 335-336
 - [Prevent Cross-Site Request Forgery (XSRF/CSRF) attacks in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/security/anti-request-forgery?view=aspnetcore-3.1)
 - [Cross Site Request Forgery (CSRF) Prevention for ASP.NET Core and ASP.NET Applications](https://app.pluralsight.com/library/courses/cross-site-request-forgery-csrf-prevention-asp-dot-net-core-applications) [$][video]

*6.5.10 use Azure Security Center to monitor Azure resources*
 - [Tutorial: Protect your resources with Azure Security Center](https://docs.microsoft.com/en-us/azure/security-center/tutorial-protect-resources)

*6.5.11 implement Cross Origin Resource Sharing (CORS)*
 - [Enable Cross-Origin Requests (CORS) in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/security/cors?view=aspnetcore-3.1)
 - [Configuring CORS in ASP.NET and ASP.NET Core](https://app.pluralsight.com/library/courses/configuring-cors-in-aspnet-and-aspnet-core) [$][video]

*6.5.12 implement protection against open redirect attacks*
 - [Prevent open redirect attacks in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/security/preventing-open-redirects?view=aspnetcore-3.1)


## Books:
[1] [Exam Ref 70-486 Developing ASP.NET MVC 4 Web](https://www.amazon.com/Exam-70-486-Developing-ASP-NET-Applications/dp/1509300929/)

[2] [Адам Фримен “Pro ASP.NET Core MVC 2”. – Диалектика, 2019.](https://www.ozon.ru/context/detail/id/148161571/)

[3] [Andrew Lock "ASP.NET Core in Action". - Manning, 2018.](https://www.manning.com/books/asp-net-core-in-action)


