# Using Webpack in XbimWebUI<br>在XbimWebUI中使用Webpack

## Required Extension<br>必需的扩展名

Since this project uses webpack to generate the output bundles, the Visual Studio
[WebPack Task Runner Extension](https://marketplace.visualstudio.com/items?itemName=MadsKristensen.WebPackTaskRunner)
extension should be installed.<br>由于此项目使用webpack生成输出包，因此Visual Studio应该安装扩展[WebPack任务运行器扩展]

## Debugging<br>调试

The `webpack.config.js` file has a binding defined that launches the `Watch - Development` task after the solution has been loaded.
This keeps track of changes to the TypeScript files and rebuilds the `Build/xbim.bundle.js` and the `Build/xbim.browser.css` output files.
A refresh of the page in the browser will load the new bundle.<br>`webpack.config.js`文件定义了一个绑定，在加载解决方案后启动`Watch - Development`任务。这将跟踪TypeScript文件的更改并重建`Build / xbim.bundle.js`和`Build / xbim.browser.css`输出文件。在浏览器中刷新页面将加载新的包。

``` Javascript
/// <binding ProjectOpened='Watch - Development' />
var webpack = require('webpack');
...
```

Tasks can be manually started in the `Task Runner Explorer` window:

![Webpack Task Runner](./docs/WebpackTaskRunner.png)

## Publishing

When building the solution in the `Release` configuration, the `build.bat` script is being executed. It generates all JavaScript outputs
(complete bundle and separate Viewer and Browser bundles) as well as the documentation.
