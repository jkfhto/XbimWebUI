XbimWebUI
=========

Web components for xBIM Toolkit. [Documentation on GitHub Pages.](http://xbimteam.github.io/XbimWebUI/)

Build Status (master branch): [ ![Build Status](http://xbimbuilds.cloudapp.net/app/rest/builds/buildType:(id:Xbim_XbimWebUi_XbimWebUi),branch:(name:master)/statusIcon "Build Status") ](http://xbimbuilds.cloudapp.net/project.html?projectId=Xbim_XbimWebUi&tab=projectOverview "Build Status")

Build Status (develop branch): [ ![Build Status](http://xbimbuilds.cloudapp.net/app/rest/builds/buildType:(id:Xbim_XbimWebUi_XbimWebUi),branch:(name:develop)/statusIcon "Build Status") ](http://xbimbuilds.cloudapp.net/project.html?projectId=Xbim_XbimWebUi&tab=projectOverview "Build Status")

# XBIM - the eXtensible Building Information Modelling (BIM) Toolkit<br>XBIM - 可扩展建筑信息模型（BIM）工具包

## What is it?

The xBIM Tookit (eXtensible Building Information Modelling) is an open-source, software development BIM toolkit that 
supports the BuildingSmart Data Model (aka the [Industry Foundation Classes IFC](http://en.wikipedia.org/wiki/Industry_Foundation_Classes)).<br>xBIM Tookit（可扩展建筑信息模型）是一个开源的软件开发BIM工具包，支持BuildingSmart数据模型（又名工业基础类IFC）

xBIM allows developers to read, create and view [Building Information (BIM)](http://en.wikipedia.org/wiki/Building_information_modeling) Models in the IFC format. 
There is full support for geometric, topological operations and visualisation. In addition xBIM supports 
bi-directional translation between IFC and COBie formats<br>xBIM允许开发人员以IFC格式读取，创建和查看建筑信息（BIM）模型。完全支持几何，拓扑操作和可视化。此外，xBIM支持IFC和COBie格式之间的双向转换

## Getting Started

You will need Visual Studio 2015 Update 3 or newer to compile the Solution. The web components are created in [TypeScript](http://www.typescriptlang.org).
[npm](https://www.npmjs.com/) and [webpack](https://webpack.github.io) are used to compile the client side JavaScript libraries.
Since TypeScript compilation in the Visual Studio solution is enabled, the [TypeScript for Visual Studio 2015](http://www.typescriptlang.org/#download-links)
extension must be installed at least in version 2.0. Information how to debug and build the solution using webpack [is located here](WEBPACK.md).
All solutions target .NET 4.0. The 4.0 Client profile may be supported for some projects.<br>您将需要Visual Studio 2015 Update 3或更高版本来编译解决方案。 Web组件是在TypeScript中创建的。 npm和webpack用于编译客户端JavaScript库。由于启用了Visual Studio解决方案中的TypeScript编译，因此必须至少在2.0版中安装TypeScript for Visual Studio 2015扩展。有关如何使用webpack调试和构建解决方案的信息位于此处。所有解决方案都针对.NET 4.0。某些项目可能支持4.0客户端配置文件


Xbim is a software library, and is currently deployed with a number of sample applications to demonstrate its capabilities<br>Xbim是一个软件库，目前部署了许多示例应用程序来展示其功能

* XbimXplorer - a Windows WPF sample application that can open and render 3D IFC models (and native XBIM models ) as well as displaying semantic data.<br>bimXplorer - 一个Windows WPF示例应用程序，可以打开和呈现3D IFC模型（和本机XBIM模型）以及显示语义数据
* Xbim.SceneJSWebViewer - a MVC web application that can open and render 3D IFC models (previously converted to XBIM) using a WebGL compatible browser. <br>Xbim.SceneJSWebViewer - 一个MVC Web应用程序，可以使用兼容WebGL的浏览器打开和渲染3D IFC模型（以前转换为XBIM）
* XbimConvert - a sample console application to generate native XBIM model and geometry files from an IFC file.<br>XbimConvert - 一个示例控制台应用程序，用于从IFC文件生成本机XBIM模型和几何文件
* Xbim.COBie.Client - A sample windows application demonstrating how a COBie spreadsheet can be generated from an IFC model.<br>Xbim.COBie.Client - 一个示例Windows应用程序，演示如何从IFC模型生成COBie电子表格
* CodeExamples - a sample console application demonstrating how to undertake a number of BIM processes using XBIM<br>CodeExamples - 一个示例控制台应用程序，演示如何使用XBIM进行多个BIM进程

Please note: all the samples in this solution are examples of how to use the Xbim library, and not intended to be used in a 
production environment without further development.<br>请注意：此解决方案中的所有示例都是如何使用Xbim库的示例，并且不打算在没有进一步开发的情况下在生产环境中使用

## Licence

The XBIM library is made available under the CDDL Open Source licence.  See the licences folder for a full text.

All licences should support the commercial usage of the XBIM system within a 'Larger Work', as long as you honour 
the licence agreements.

## Third Party Licences

The core XBIM library makes use of the following 3rd party software packages, under their associated licences:

* 'OpenCASCADE' Geometry Engine : http://www.opencascade.org/ - OPEN CASCADE Public License 
* 'Gardens Point Parser Generator' http://gppg.codeplex.com/ - New BSD Licence
* Elements of '3D Tools' WPF library http://3dtools.codeplex.com/ - MS Permissive Licence
* Log4net : http://logging.apache.org/log4net/ - Apache 2.0 Licence
* NPOI : http://npoi.codeplex.com - Apache 2.0 Licence
* NewtonSoft JSON : http://json.codeplex.com/ - MIT Licence

Additionally the Samples also make use of the following libraries

* SceneJS: https://github.com/xeolabs/scenejs - joint MIT and GPL Licence
* SignalR : https://github.com/SignalR/SignalR - Apache 2.0 Licence

All licences are included in full under the Licences\3rd Party solution folder. 

## Support & Help

Please use [GitHub issues](https://github.com/xBimTeam/XbimWebUI/issues) to ask any questions.

## Getting Involved

If you'd like to get involved and contribute to this project, please contact the Project Coordinator, [Steve Lockley](https://github.com/SteveLockley).
