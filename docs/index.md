<h1>Getting started with React in Meteor</h1>

Using Meteor and React together is awesome. Meteor gives you a fast, easy to use solution for data management across client and server, and React gives you a way to structure your app's UI from reusable components.

Meteor和React配合使用起来非常棒！Meteor提供了跨客户端和服务器端的数据管理解决方案，性能高效，易于使用，而React则通过可复用的组件的方式来结构化你的应用UI。

We are still making improvements and investigating the best ways to use Meteor and React together, but these packages are already usable and you can download them now. Try them out and let us know what you think [on GitHub](https://github.com/meteor/react-packages/issues)!

我们依然在改进和探索使用Meteor和React的最佳实践，但是这些包现在已经可以被下载使用了。来尝试一下吧，让我们知道你的[想法](https://github.com/meteor/react-packages/issues)。

## Quick start

If you want to get going as fast as possible, you just need to add the `react` package that bundles together everything you need:

如果你迫不及待想要开始，只需要添加`react`包就可以得到所需要的一切：

```
meteor add react
```

### What's in the box? 

The `react` meta-package comes with everything you need to build your Meteor app with React. You can also add any of the parts individually:

`react`这个meta-package已经包含了构建Meteor和React应用所需的所有东西，你也可以单独添加任何一部分：

1. `react-runtime`: The React library itself
2. `jsx`: A compiler that automatically transforms `.jsx` files into JavaScript, and lets you use some ES6 features
3. `react-meteor-data`: A React mixin called `ReactMeteorData` that lets you easily use data from Meteor collections and other reactive sources in your components

1. `react-runtime`: React包本身
2. `jsx`: 一个可以自动将`.jsx`文件转换成标准JavaScript的编译器，可以让你使用ES6的一些特性
3. `react-meteor-data`: 一个叫做`ReactMeteorData`的React mixin，可以在组件中轻松得使用从Meteor collections和其他reactive资源中得到的数据

### Additional available packages

1. `react-template-helper`: Include React components anywhere in your Meteor Blaze templates. [Read the guide here.](react-template-helper.md)

1. `react-template-helper`: 在Meteor的Blaze模板中加载React组件，[阅读指南](react-template-helper.md)。

### Next steps

Now that you have created an app and added everything you need, do these next:

现在你可以构建应用，添加任何你需要的东西：

1. Follow the [tutorial](tutorial.md)
2. Check out the [example apps](https://github.com/meteor/react-packages/tree/master/examples)

1. 查看[教程](tutorial.md)
2. 查看[示例应用](https://github.com/meteor/react-packages/tree/master/examples)

## Contributing and filing bugs

[See the repository on GitHub.](https://github.com/meteor/react-packages)

## 协助翻译

[GitHub地址](https://github.com/JimmyLv/Reactjs-in-meteor-doc-zh)
