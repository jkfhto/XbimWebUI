XbimWebUI
=========

Web components for xBIM Toolkit. [Documentation on GitHub Pages.](http://xbimteam.github.io/XbimWebUI/)
<br>xBIM Toolkit的Web组件

Build Status (master branch): [ ![Build Status](http://xbimbuilds.cloudapp.net/app/rest/builds/buildType:(id:Xbim_XbimWebUi_XbimWebUi),branch:(name:master)/statusIcon "Build Status") ](http://xbimbuilds.cloudapp.net/project.html?projectId=Xbim_XbimWebUi&tab=projectOverview "Build Status")

Build Status (develop branch): [ ![Build Status](http://xbimbuilds.cloudapp.net/app/rest/builds/buildType:(id:Xbim_XbimWebUi_XbimWebUi),branch:(name:develop)/statusIcon "Build Status") ](http://xbimbuilds.cloudapp.net/project.html?projectId=Xbim_XbimWebUi&tab=projectOverview "Build Status")

# XBIM - the eXtensible Building Information Modelling (BIM) Toolkit<br>XBIM - 可扩展建筑信息模型（BIM）工具包

## What is it?

The xBIM Tookit (eXtensible Building Information Modelling) is an open-source, software development BIM toolkit that 
supports the BuildingSmart Data Model (aka the [Industry Foundation Classes IFC](http://en.wikipedia.org/wiki/Industry_Foundation_Classes)).<br>xBIM Tookit（可扩展建筑信息模型）是一个开源的软件开发BIM工具包，支持BuildingSmart数据模型（又名工业基础类IFC）

xBIM allows developers to read, create and view [Building Information (BIM)](http://en.wikipedia.org/wiki/Building_information_modeling) Models in the IFC format. 
There is full support for geometric, topological operations and visualisation. In addition xBIM supports 
bi-directional translation between IFC and COBie formats.<br>xBIM允许开发人员以IFC格式读取，创建和查看建筑信息（BIM）模型。 完全支持几何，拓扑操作和可视化。 此外，xBIM支持IFC和COBie格式之间的双向转换。

XbimWebUI is a Javascript library which can be used for web presentation of BIM models. It uses WebGL and is independent of any third party WebGL framework. We did use SceneJS and other frameworks in past but this is independent of any of them. The viewer takes WexBIM data format as its input. This is our custom binary data format which can be [produced using core xBIM Libraries](http://docs.xbim.net/examples/creating-wexbim-file.html). Detailed documentation is available [**here**](http://docs.xbim.net/XbimWebUI/).<br>XbimWebUI是一个Javascript库，可用于在Web端展示BIM模型。 它使用WebGL并且独立于任何第三方WebGL框架。 我们之前确实使用过SceneJS和其他框架，但这与任何框架无关。 查看器将WexBIM数据格式作为输入。 这是我们的自定义二进制数据格式，可以使用核心xBIM库生成。 详细文档可在此处获得。

## Getting Started

You will need Visual Studio 2010 SP1 or newer to compile the Solution. All solutions target .NET 4.0. The 4.0 Client profile
may be supported for some projects.<br>您将需要Visual Studio 2010 SP1或更高版本来编译解决方案。所有解决方案都针对.NET 4.0。某些项目可能支持4.0客户端配置文件

Xbim is a software library, and is currently deployed with a number of sample applications to demonstrate its capabilities.<br>Xbim是一个软件库，目前部署了许多示例应用程序来展示其功能

Please note: all the samples in this solution are examples of how to use the Xbim library, and not intended to be used in a 
production environment without further development.<br>请注意：此解决方案中的所有示例都是如何使用Xbim库的示例，并不打算在没有进一步开发的情况下在生产环境中使用

## Licence

The XBIM library is made available under the CDDL Open Source licence.  See the licences folder for a full text.

All licences should support the commercial usage of the XBIM system within a 'Larger Work', as long as you honour 
the licence agreements.

## Support & Help

Please use [GitHub issues](https://github.com/xBimTeam/XbimWebUI/issues) to ask any questions.

## Getting Involved

If you'd like to get involved and contribute to this project, please contact the Project Coordinator, [Steve Lockley](https://github.com/SteveLockley).
