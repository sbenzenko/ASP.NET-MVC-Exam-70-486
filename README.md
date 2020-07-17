# Microsoft Exam 70-486 Topics

### 1. Design the application architecture (15-20%)

**1.1 Plan the application layers**
- [Common web application architectures](https://docs.microsoft.com/en-us/dotnet/architecture/modern-web-apps-azure/common-web-application-architectures)

*1.1.1 Plan data access*
 - [Exam Ref 70-486 Developing ASP.NET MVC 4 Web](https://www.amazon.com/Exam-70-486-Developing-ASP-NET-Applications/dp/1509300929/) pages 2-6

*1.1.2 plan for separation of concerns, appropriate use of models, views, controllers, view components, and service dependency injection*
 - [Exam Ref 70-486 Developing ASP.NET MVC 4 Web](https://www.amazon.com/Exam-70-486-Developing-ASP-NET-Applications/dp/1509300929/) pages 6-15
 
*1.1.3 choose between client-side and server-side processing*
 - [Exam Ref 70-486 Developing ASP.NET MVC 4 Web](https://www.amazon.com/Exam-70-486-Developing-ASP-NET-Applications/dp/1509300929/) pages 15-16

*1.1.4 design for scalability*
 - [Exam Ref 70-486 Developing ASP.NET MVC 4 Web](https://www.amazon.com/Exam-70-486-Developing-ASP-NET-Applications/dp/1509300929/) pages 16-17

*1.1.5 choose between ASP.NET Core and ASP.NET*
 - [Choose between ASP.NET 4.x and ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/choose-aspnet-framework?view=aspnetcore-3.1)

*1.1.6 choose when to use .NET standard libraries*
 - [What is the difference between .NET Core and .NET Standard Class Library project types?](https://stackoverflow.com/questions/42939454/what-is-the-difference-between-net-core-and-net-standard-class-library-project#:~:text=Use%20a%20.,Use%20a%20)
 - [Demystifying .NET Core and .NET Standard](https://docs.microsoft.com/en-us/archive/msdn-magazine/2017/september/net-standard-demystifying-net-core-and-net-standard)

**1.2 Design a distributed application**
 - [Design Distributed Application](https://examref.com/MCSD/70-486/DesignDistApp)
 - [Design a distributed application](http://failedturing.blogspot.com/2014/06/microsoft-70-486-design-distributed.html)
 - [Exam Ref 70-486 Developing ASP.NET MVC 4 Web](https://www.amazon.com/Exam-70-486-Developing-ASP-NET-Applications/dp/1509300929/) pages 21-24

*1.2.1 Design a hybrid application*
 - [Building Hybrid Applications in the Cloud on Microsoft Azure](https://docs.microsoft.com/en-us/previous-versions/msp-n-p/hh871440(v=pandp.10)?redirectedfrom=MSDN)
 - [Exam Ref 70-486 Developing ASP.NET MVC 4 Web](https://www.amazon.com/Exam-70-486-Developing-ASP-NET-Applications/dp/1509300929/) pages 24-26

*1.2.2 plan for session management in a distributed environment*
 - [Exam Ref 70-486 Developing ASP.NET MVC 4 Web](https://www.amazon.com/Exam-70-486-Developing-ASP-NET-Applications/dp/1509300929/) pages 26-27
 - [Sticky and NON-Sticky sessions](https://stackoverflow.com/questions/10494431/sticky-and-non-sticky-sessions)

*1.2.3 plan web farms*
 - [Exam Ref 70-486 Developing ASP.NET MVC 4 Web](https://www.amazon.com/Exam-70-486-Developing-ASP-NET-Applications/dp/1509300929/) pages 27-28

*1.2.4 run Microsoft Azure services on-premises with Azure Pack*

*1.2.5 enable deferred processing through Azure features including queues, scheduled and on-demand jobs, Azure Functions, Azure Web Jobs*

**1.3 Design and implement the Azure Web Apps life cycle**

*1.3.1 Identify and implement Start, Run, and Stop events*

*1.3.2 code against application events in application*

*1.3.3 configure startup tasks, including IIS, app pool configuration, and third-party tools*

**1.4 Configure state management**

*1.4.1 Choose a state management mechanism including in-process, out of process, and Redis based state management*

*1.4.2 plan for scalability*

*1.4.3 use cookies or local storage to maintain state*

*1.4.4 apply configuration settings in web.config file*

*1.4.5 implement sessionless state including for example, query strings*

*1.4.6 configure middleware to enable session and application state in ASP.NET Core*

**1.5 Design a caching strategy**

*1.5.1 Implement page output caching and data caching*

*1.5.2 create cache profiles*

*1.5.3 implement HTTP caching*

*1.5.4 implement Azure Redis caching*

*1.5.5 plan a content delivery network (CDN) strategy, for example, Azure CDN*

**1.6 Design and implement a Web Socket strategy**

*1.6.1 Read and write string and binary data asynchronously*

*1.6.2 choose a connection loss strategy*

*1.6.3 decide when to use Web Sockets*

*1.6.4 implement SignalR*

*1.6.5 enable web socket features in an Azure Web App instance*

**1.7 Design a configuration management solution**

*1.7.1 Manage configuration sources, including XML, JSON, and INI files*

*1.7.2 manage environment variables*

*1.7.3 implement Option objects*

*1.7.4 implement multiple environments using files and hierarchical structure*

*1.7.5 manage sensitive configuration*

*1.7.6 react to runtime configuration changes*

*1.7.7 implement a custom configuration source*

*1.7.8 secure configuration by using Azure Key Vault*

*1.7.9 use the Secret Manager tool in development to keep secrets out of your code for configuration values*

**1.8 Interact with the host environment**

*1.8.1 Work with file system using file providers*

*1.8.2 work with environment variables*

*1.8.3 determine hosting environment capabilities*

*1.8.4 implement native components, including PInvoke and native dependencies for hosts including Linux and Windows*

*1.8.5 use ASP.NET hosting on an Open Web Interface for .NET (OWIN)-based server*

**1.9 Compose an application by using the framework pipeline**

*1.9.1 Add custom request processing modules to the pipeline*

*1.9.2 add, remove, and configure services used in the application*

*1.9.3 design and implement middleware*

*1.9.4 design for kestrel, Http.sys web server and IIS*

*1.9.5 design and implement startup filters*

### 2. Design the build and deployment architecture (10-15%)

**2.1 Design a browser artifact build strategy**

*2.1.1 Design a JavaScript build pipeline using Gulp, Grunt, npm and Bower*

*2.1.2 design an artifact build strategy using Less, Sass and Font Awesome*

*2.1.3 design and implement a bundling and minification strategy for broswer artifacts, including JavaScript, CSS and images*

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

*3.1.2 structure and lay out the user interface by using HTML*

*3.1.3 implement dynamic page content based on a design*

**3.2 Design and implement UI behavior**

*3.2.1 Implement client-side validation*

*3.2.2 use JavaScript to manipulate the DOM*

*3.2.3 extend objects by using prototypal inheritance*

*3.2.4 use AJAX to make partial page updates*

**3.3 Design the UI layout of an application**

*3.3.1 Implement partial views and view components for reuse in different areas of the application*

*3.3.2 design and implement pages by using Razor Pages*

*3.3.3 design and implement layouts to provide visual structure*

*3.3.4 define and render optional and required page sections*

*3.3.5 create and use tag and HTML helpers to simplify markup*

**3.4 Plan a responsive UI layout**

*3.4.1 Plan for applications that run on multiple devices and screen resolutions*

*3.4.2 use media queries and Bootstrap's responsive grid*

*3.4.3 detect browser features and capabilities*

*3.4.4 create a web application that runs across multiple browsers and mobile devices*

*3.4.5 enable consistent cross-browser experiences with polyfills*

**3.5 Plan mobile UI strategy**

*3.5.1 Implement mobile specific UI elements such as touch input, low bandwidth situations, and device orientation changes*

*3.5.2 define and implement a strategy for working with mobile browsers*

### 4. Develop the User Experience (15-20%)

**4.1 Plan for search engine optimization and accessibility**

*4.1.1 Use analytical tools to parse HTML*

*4.1.2 provide an xml sitemap and robots.txt file to improve scraping*

*4.1.3 write semantic markup for accessibility, for example, screen readers*

*4.1.4 use rich snippets to increase content visibility*

**4.2 Plan and implement globalization and localization**

*4.2.1. Plan a localization strategy*

*4.2.2. create and apply resources to UI including JavaScript resources*

*4.2.3. set cultures*

*4.2.4. implement server side localization and globalization*

**4.3 Design and implement MVC controllers and actions**

*4.3.1 Apply authorization attributes, filters including global, authentication, and overriddable filters*

*4.3.2 choose and implement custom HTTP status codes and responses*

*4.3.3 implement action results*

*4.3.4 implement MVC areas*

*4.3.5 implement Dependency Injection for services in controllers*

**4.4 Design and implement routes**

*4.4.1 Define a route to handle a URL pattern*

*4.4.2 apply route constraints*

*4.4.3 ignore URL patterns*

*4.4.4 add custom route parameters*

*4.4.5 define areas*

*4.4.6 define routes that interoperate with Single Page Application frameworks such as Angular*

**4.5 Control application behavior by using MVC extensibility points**

*4.5.1 Create custom middleware and inject it into the pipeline*

*4.5.2 implement MVC filters and controller factories*

*4.5.3 control application behavior by using action results, model binders, and route handlers*

*4.5.4 inject services into a view*

**4.6 Design and implement serialization and model binding**

*4.6.1 Serialize models and data using supported serialization formats, including JSON, XML, protobuf, and WCF/SOAP*

*4.6.2 implement model and property binding, including custom binding and model validation; implement web socket communication in MVC; implement file uploading and multipart data; use AutoRest to build clients*

### 5 Troubleshoot and Debug Web Applications (20-25%)

**5.1 Prevent and troubleshoot runtime issues**

*5.1.1 Troubleshoot performance, security, and errors*

*5.1.2 implement tracing, logging, and debugging including IntelliTrace*

*5.1.3 enable and configure health monitoring including Performance Monitor*

*5.1.4 configure and use App Insights runtime telemetry*

**5.2 Design an exception handling strategy**

*5.2.1 Handle exceptions across multiple layers*

*5.2.2 use MVC middleware to configure error handling*

*5.2.3 use different exception handling strategies for different environments*

*5.2.4 create and display custom error pages*

*5.2.5 configure a custom pipeline for error handling*

*5.2.6 handle first chance exceptions*

*5.2.7 configure and use App Insights*

*5.2.8 log application exceptions*

**5.3 Test a web application**

*5.3.1 Create and run unit tests, for example, use the Assert class, create mocks and stubs*

*5.3.2 create and run web tests including using Browser Link*

*5.3.3 debug a web application in multiple browsers and mobile emulators*

*5.3.4 use Azure DevTest Labs*

*5.3.5 use Visual Studio Team Services*

**5.4 Debug an Azure application**

*5.4.1 Collect diagnostic information by using Azure App Insights*

*5.4.2 choose log types, for example, event logs, performance counters, and crash dumps*

*5.4.3 stream logs directly to Visual Studio from a deployed site*

*5.4.4 debug an Azure application by using Visual Studio and remote debugging*

*5.4.5 interact directly with remote Azure websites using Server Explorer*

### 6 Design and Implement Security (15-20%)

**6.1 Configure authentication**

*6.1.1 Authenticate users*

*6.1.2 enforce authentication settings*

*6.1.3 implement ASP.NET Core Identity*

*6.1.4 enable Facebook, Google and other external providers*

*6.1.5 implement account confirmation, password recovery, and multi-factor authentication*

*6.1.6 perform authentication using Azure Active Directory, Azure Active Directory B2C, Azure Active Directory B2B, and Microsoft Identity*

*6.1.7 manage user session by using cookies*

*6.1.8 acquire access tokens using the Microsoft Authentication Library (MSAL)*

**6.2 Configure and apply authorization**

*6.2.1 Create roles*

*6.2.2 authorize roles programmatically*

*6.2.3 configure and work with custom UserStores using middleware*

*6.2.4 configure controllers and actions to participate in authorization*

**6.3 Design and implement claims-based authentication**

*6.3.1 perform authentication and authorization using tokens including OpenID, OAuth, JWT, SAML, bearer tokens, etc.*

**6.4 Manage data integrity**

*6.4.1 Apply encryption to application data*

*6.4.2 apply encryption to the configuration sections of an application*

*6.4.3 sign application data to prevent tampering*

*6.4.4 secure data using Azure Key Vault*

*6.4.5 implement encryption for data protection using the data protection APIs in transit and at rest*

**6.5 Implement a secure site**

*6.5.1 Secure communication by applying SSL certificates*

*6.5.2 require SSL for all requests*

*6.5.3 enable SSL hosting in the development environment*

*6.5.4 implement SSL using Azure Load Balancers*

*6.5.5 salt and hash passwords for storage*

*6.5.6 use HTML encoding to prevent cross-site scripting attacks (ANTI-XSS Library)*

*6.5.7 implement deferred validation and handle unvalidated requests, for example, form, querystring, and URL*

*6.5.8 prevent SQL injection attacks by parameterizing queries*

*6.5.9 prevent cross-site request forgeries (XSRF)*

*6.5.10 use Azure Security Center to monitor Azure resources*

*6.5.11 implement Cross Origin Resource Sharing (CORS)*

*6.5.12 implement protection against open redirect attacks*