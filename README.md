# Microsoft Exam 70-486 Topics

### 1. Design the application architecture (15-20%)

**1.1 Plan the application layers**
- [Common web application architectures](https://docs.microsoft.com/en-us/dotnet/architecture/modern-web-apps-azure/common-web-application-architectures)

*1.1.1 Plan data access*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 2-6

*1.1.2 plan for separation of concerns, appropriate use of models, views, controllers, view components, and service dependency injection*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 6-15
 
*1.1.3 choose between client-side and server-side processing*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 15-16

*1.1.4 design for scalability*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 16-17

*1.1.5 choose between ASP.NET Core and ASP.NET*
 - [Choose between ASP.NET 4.x and ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/choose-aspnet-framework?view=aspnetcore-3.1)

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

*1.3.1 Identify and implement Start, Run, and Stop events*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 35-38
 - [Customize the Lifecycle of a Web or Worker role in .NET](https://docs.microsoft.com/en-us/azure/cloud-services/cloud-services-role-lifecycle-dotnet)

*1.3.2 code against application events in application*
 - [HOW TO CREATE CUSTOM EVENTS, METRICS, TRACES IN AZURE APPLICATION INSIGHTS USING C#](https://carldesouza.com/how-to-create-custom-events-metrics-traces-in-azure-application-insights-using-c/)

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

*1.6.5 enable web socket features in an Azure Web App instance*
 - [Introduction to WebSockets on Windows Azure Web Sites](https://azure.microsoft.com/ru-ru/blog/introduction-to-websockets-on-windows-azure-web-sites/)

**1.7 Design a configuration management solution**

*1.7.1 Manage configuration sources, including XML, JSON, and INI files*
- [Configuration in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/configuration/?view=aspnetcore-3.1)

*1.7.2 manage environment variables*
 - [Environment variables](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/environments?view=aspnetcore-3.1)

*1.7.3 implement Option objects*
 - [Options pattern in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/configuration/options?view=aspnetcore-3.1)

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
 - [Environment variables](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/environments?view=aspnetcore-3.1)

*1.8.3 determine hosting environment capabilities*
 - [Use multiple environments in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/environments?view=aspnetcore-3.1)

*1.8.4 implement native components, including PInvoke and native dependencies for hosts including Linux and Windows*
 - [Platform Invoke (P/Invoke)](https://docs.microsoft.com/en-us/dotnet/standard/native-interop/pinvoke)

*1.8.5 use ASP.NET hosting on an Open Web Interface for .NET (OWIN)-based server*
 - [Open Web Interface for .NET (OWIN) with ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/owin?view=aspnetcore-3.1)

**1.9 Compose an application by using the framework pipeline**
 - [ASP.NET Core Middleware](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/middleware/?view=aspnetcore-3.1)

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
 - [Exploring IStartupFilter in ASP.NET Core](https://andrewlock.net/exploring-istartupfilter-in-asp-net-core/)

### 2. Design the build and deployment architecture (10-15%)

**2.1 Design a browser artifact build strategy**

*2.1.1 Design a JavaScript build pipeline using Gulp, Grunt, npm and Bower*

*2.1.2 design an artifact build strategy using Less, Sass and Font Awesome*

*2.1.3 design and implement a bundling and minification strategy for broswer artifacts, including JavaScript, CSS and images*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 197-202

**2.2 Design a server build strategy**

*2.2.1 Manage NuGet dependencies*

*2.2.2 target runtimes, including the full .NET Framework, .NET core, and .NET standard*

*2.2.3 manage debug and release configurations, including compilation and optimization options*

*2.2.4 include or exclude files from build*

*2.2.5 manage build sources, including content, resources, and shared files*

*2.2.6 implement metadata for projects, including version, release notes, and descriptions*

*2.2.7 define other build options, including xmlDoc and warningsAsErrors*

*2.2.8 work with static files in ASP.NET core*

**2.3 Design a publishing strategy**

*2.3.1 Implement application publishing using dotnet.exe*

*2.3.2 manage publishing options in csproj*

*2.3.3 implement additional tooling*

*2.3.4 implement pre-publish and post-publish scripts*

*2.3.5 implement native compilation*

*2.3.6 publish to Docker container image*

**2.4 Implement an Azure deployment strategy**

*2.4.1 Deploy Azure Web App using supported deployment models including FTP, Kudu, Web Deploy, and Visual Studio Publishing Wizard*

*2.4.2 provision ARM based resources while deploying application*

*2.4.3 implement deployment environments, including dev, test, and prod in Azure*

*2.4.4 use deployment slots for staging sites*

*2.4.5 deploy to Azure Stack*

**2.5 Implement a on-premises deployment strategy**

*2.5.1 Deploy application to IIS using Web Deploy, xcopy, and Visual Studio Publishing Wizard*

*2.5.2 deploy application to Windows Nano Server, deploy application to IIS Hosted Web Core, deploy application to HTTP.sys web server*

*2.5.3 deploy application to Kestrel on Windows and Linux*

*2.5.4 implement reverse proxying to Kestrel using IIS and Nginx*

### 3. Design the User Experience (15-20%)

**3.1 Create elements of the user interface for a web application**

*3.1.1 Create and apply styles by using CSS*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 86-89

*3.1.2 structure and lay out the user interface by using HTML*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 90-92

*3.1.3 implement dynamic page content based on a design*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 92-95

**3.2 Design and implement UI behavior**
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 97-113

*3.2.1 Implement client-side validation*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 98-103

*3.2.2 use JavaScript to manipulate the DOM*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> page 103

*3.2.3 extend objects by using prototypal inheritance*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 103-105

*3.2.4 use AJAX to make partial page updates*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 105-108

**3.3 Design the UI layout of an application**
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 114-123

*3.3.1 Implement partial views and view components for reuse in different areas of the application*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 114-116

*3.3.2 design and implement pages by using Razor Pages*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> page 117

*3.3.3 design and implement layouts to provide visual structure*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 117-118

*3.3.4 define and render optional and required page sections*

*3.3.5 create and use tag and HTML helpers to simplify markup*

**3.4 Plan a responsive UI layout**

*3.4.1 Plan for applications that run on multiple devices and screen resolutions*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 132-134


*3.4.2 use media queries and Bootstrap's responsive grid*

*3.4.3 detect browser features and capabilities*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 124-126

*3.4.4 create a web application that runs across multiple browsers and mobile devices*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 126-128

*3.4.5 enable consistent cross-browser experiences with polyfills*

**3.5 Plan mobile UI strategy**

*3.5.1 Implement mobile specific UI elements such as touch input, low bandwidth situations, and device orientation changes*

*3.5.2 define and implement a strategy for working with mobile browsers*

### 4. Develop the User Experience (15-20%)

**4.1 Plan for search engine optimization and accessibility**
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 145-156

*4.1.1 Use analytical tools to parse HTML*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 146-149

*4.1.2 provide an xml sitemap and robots.txt file to improve scraping*

*4.1.3 write semantic markup for accessibility, for example, screen readers*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 151-153

*4.1.4 use rich snippets to increase content visibility*

**4.2 Plan and implement globalization and localization**
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 156-163
 - [Globalization and Localization in ASP.NET Core](https://www.codewithmukesh.com/blog/globalization-and-localization-in-aspnet-core/)

*4.2.1. Plan a localization strategy*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 156-158

*4.2.2. create and apply resources to UI including JavaScript resources*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 158-160

*4.2.3. set cultures*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 160-161

*4.2.4. implement server side localization and globalization*

**4.3 Design and implement MVC controllers and actions**
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 163-175

*4.3.1 Apply authorization attributes, filters including global, authentication, and overriddable filters*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 164-167

*4.3.2 choose and implement custom HTTP status codes and responses*

*4.3.3 implement action results*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 168-170

*4.3.4 implement MVC areas*

*4.3.5 implement Dependency Injection for services in controllers*

**4.4 Design and implement routes**
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 175-185

*4.4.1 Define a route to handle a URL pattern*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 176-178

*4.4.2 apply route constraints*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 178-179

*4.4.3 ignore URL patterns*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 179-180

*4.4.4 add custom route parameters*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> page 180

*4.4.5 define areas*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 181-182

*4.4.6 define routes that interoperate with Single Page Application frameworks such as Angular*

**4.5 Control application behavior by using MVC extensibility points**
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 186-197

*4.5.1 Create custom middleware and inject it into the pipeline*

*4.5.2 implement MVC filters and controller factories*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 186-188

*4.5.3 control application behavior by using action results, model binders, and route handlers*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 188-194

*4.5.4 inject services into a view*

**4.6 Design and implement serialization and model binding**

*4.6.1 Serialize models and data using supported serialization formats, including JSON, XML, protobuf, and WCF/SOAP*

*4.6.2 implement model and property binding, including custom binding and model validation; implement web socket communication in MVC; implement file uploading and multipart data; use AutoRest to build clients*

### 5 Troubleshoot and Debug Web Applications (20-25%)

**5.1 Prevent and troubleshoot runtime issues**
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 215-234

*5.1.1 Troubleshoot performance, security, and errors*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 216-223

*5.1.2 implement tracing, logging, and debugging including IntelliTrace*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 223-227

*5.1.3 enable and configure health monitoring including Performance Monitor*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 230-232

*5.1.4 configure and use App Insights runtime telemetry*

**5.2 Design an exception handling strategy**
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 234-243
 - [Global Exception Handling in ASP.NET Core Web API](https://blog.jonblankenship.com/2020/04/12/global-exception-handling-in-aspnet-core-api/)

*5.2.1 Handle exceptions across multiple layers*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 235-236

*5.2.2 use MVC middleware to configure error handling*

*5.2.3 use different exception handling strategies for different environments*

*5.2.4 create and display custom error pages*

*5.2.5 configure a custom pipeline for error handling*

*5.2.6 handle first chance exceptions*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 238-240

*5.2.7 configure and use App Insights*

*5.2.8 log application exceptions*

**5.3 Test a web application**
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 243-255

*5.3.1 Create and run unit tests, for example, use the Assert class, create mocks and stubs*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 244-250

*5.3.2 create and run web tests including using Browser Link*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 250-252

*5.3.3 debug a web application in multiple browsers and mobile emulators*

*5.3.4 use Azure DevTest Labs*

*5.3.5 use Visual Studio Team Services*

**5.4 Debug an Azure application**
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 255-263

*5.4.1 Collect diagnostic information by using Azure App Insights*

*5.4.2 choose log types, for example, event logs, performance counters, and crash dumps*

*5.4.3 stream logs directly to Visual Studio from a deployed site*

*5.4.4 debug an Azure application by using Visual Studio and remote debugging*

*5.4.5 interact directly with remote Azure websites using Server Explorer*

### 6 Design and Implement Security (15-20%)

**6.1 Configure authentication**
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 271-293
 - [ASP.NET Core - Authentication & Authorization Tutorial](https://www.youtube.com/playlist?list=PLOeFnOV9YBa7dnrjpOG6lMpcyd7Wn7E8V)

*6.1.1 Authenticate users*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 272-280

*6.1.2 enforce authentication settings*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 280-282

*6.1.3 implement ASP.NET Core Identity*
 - [ASP.NET Core 3 - Authentication - Ep.2 Identity Authentication](https://www.youtube.com/watch?v=IjbtWPXVJGw)

*6.1.4 enable Facebook, Google and other external providers*
 - [ASP.NET Core 3 - Authentication - Ep.2 Identity Authentication](https://www.youtube.com/watch?v=IjbtWPXVJGw)

*6.1.5 implement account confirmation, password recovery, and multi-factor authentication*
 - [ASP.NET Core 3 - Identity - Ep.2.1 Email Verification](https://www.youtube.com/watch?v=Vj7iCb7wDs0)

*6.1.6 perform authentication using Azure Active Directory, Azure Active Directory B2C, Azure Active Directory B2B, and Microsoft Identity*

*6.1.7 manage user session by using cookies*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 283-285

*6.1.8 acquire access tokens using the Microsoft Authentication Library (MSAL)*

**6.2 Configure and apply authorization**
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 294-303

*6.2.1 Create roles*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 294-296

*6.2.2 authorize roles programmatically*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 296-298

*6.2.3 configure and work with custom UserStores using middleware*

*6.2.4 configure controllers and actions to participate in authorization*

**6.3 Design and implement claims-based authentication**
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 303-314
 - [ASP.NET Core 3 - Authentication - Ep.3 Authorization (All about Policies and Claims)](https://www.youtube.com/watch?v=RBMO_hruKaI)

*6.3.1 perform authentication and authorization using tokens including OpenID, OAuth, JWT, SAML, bearer tokens, etc.*
 - [ASP.NET Core 3 - OAuth - Ep.5 JWT Bearer](https://www.youtube.com/watch?v=YC4ewe7Rbl4)
 - [ASP.NET Core 3 - OAuth - Ep.6 OAuth Client](https://www.youtube.com/watch?v=0oBIgPaFYOg)
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 310-313


**6.4 Manage data integrity**
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 314-324

*6.4.1 Apply encryption to application data*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 316-318

*6.4.2 apply encryption to the configuration sections of an application*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 319-320

*6.4.3 sign application data to prevent tampering*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 321-322

*6.4.4 secure data using Azure Key Vault*

*6.4.5 implement encryption for data protection using the data protection APIs in transit and at rest*

**6.5 Implement a secure site**
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 324-338

*6.5.1 Secure communication by applying SSL certificates*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 325-328

*6.5.2 require SSL for all requests*

*6.5.3 enable SSL hosting in the development environment*

*6.5.4 implement SSL using Azure Load Balancers*

*6.5.5 salt and hash passwords for storage*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 328-331

*6.5.6 use HTML encoding to prevent cross-site scripting attacks (ANTI-XSS Library)*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 331-332

*6.5.7 implement deferred validation and handle unvalidated requests, for example, form, querystring, and URL*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 332-333

*6.5.8 prevent SQL injection attacks by parameterizing queries*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 333-335

*6.5.9 prevent cross-site request forgeries (XSRF)*
 - "Exam Ref 70-486 Developing ASP.NET MVC 4 Web"<sup>[1]</sup> pages 335-336

*6.5.10 use Azure Security Center to monitor Azure resources*

*6.5.11 implement Cross Origin Resource Sharing (CORS)*

*6.5.12 implement protection against open redirect attacks*


## Books:
[1] [Exam Ref 70-486 Developing ASP.NET MVC 4 Web](https://www.amazon.com/Exam-70-486-Developing-ASP-NET-Applications/dp/1509300929/) 
 