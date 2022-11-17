# Vscode-Plug-In 全网最全 -weiShaoY


## 林檎的旅行笔记

` 代码补全`

## 别名路径跳转
` 路径跳转`


``` js
路径映射
例如{'@':'/Src','components':'/src/components'}，/表示项目根目录
```
``` js
Jsconfig.json
   {
  "Compileroptions": {
    "Experimentaldecorators": True,
    "Baseurl": "./",
    "Paths": {
      "@/*": ["Src/*"],
      "Components/*": ["Src/components/*"],
      "Assets/*": ["Src/assets/*"],
      "Views/*": ["Src/views/*"],
      "Common/*": ["Src/common/*"],
    }
  },
  "Exclude": ["Node_modules", "Dist"]
}
```


##
` `

```

```

## 掘金
` 摸鱼`

```
快捷键
      沸点  Ctrl + J + J
      文章  Ctrl + P + P
```
## 小程序开发助手
`小程序`


## A-super-comprehensive
` 代码片段`

## Auto Close Tag
` Html`

```
自动关闭标签
当我们输入 <Div/ 时，它会自动把后面的括号补充好
```
## Auto Rename Tag
`Html `

```
自动完成另一侧标签的同步修改
```

 Vscode内置方案    <img src="../img/1668717715929.jpg" style="zoom: 67%;" />

​								点击设置，搜索Link，把这个勾选上，就可以左右重命名标签了

​								在Html中是支持的，而vue中则是要安装volar，vetur是不行的。volar可以配置vue2的。并且jsx也是不支持的，图方便的话，还是保留着吧。

## Bco-translate
` 翻译`

```
一款快速生成英文变量名的插件,支持驼峰,需配置百度翻译
```
## Better Comments
` 注释`

代码注释设置成不同颜色

```
///
//!
//?
////
//Todo
//*
```
## Bookmarks
` 提示`

```
书签
```
## Chinese (Simplified)
`官方简体中文包 `

## ClassTree
` Css`

Class Tree 基于 Ast 分析提取Class 快速提取Class 输出对应结构

解决在前端主流Vue，react框架开发中定义初始 Dom Class 命名后仍需要去编写 Scss/less 样式结构，该插件可自动快速生成定义好Class 树状结构增快业务开发速度原理

```
快捷键
      Windows：ctrl+1 （React） | Ctrl+2 （Vue）
      Mac:     Cmd+1  （react） | Cmd+2（vue）
```
## Code Runner
`调试 `

支持用多种语言立即执行代码 Alt + Q
```
键盘快捷键 Ctrl+alt+n
快捷键 F1 调出 命令面板, 然后输入 Run Code
在编辑区，右键选择 Run Code
在左侧的文件管理器，右键选择 Run Code
右上角的运行小三角按钮
一键执行各种语言代码（常用于测试）
```

## Code Translate
` 翻译`

```
一款纯粹的 Vscode 滑词翻译插件
```
## Color Highlight
`颜色 `

扩展样式可以在您的文档中找到 Css/web 颜色
<img src="C:\Users\16047\Desktop\Vscode插件-全网最全\img\3daeba1480b29c602d5c915b10896b71d91c9a4c045d4a2fc2217364e3701d2c.png" style="zoom:50%;" />

## css-class-intellisense
` 提示` ` Html`

目前只支持Html文件

实时监测 Html 文件，对引入的 Css 文件进行智能提示，包括本地和远程文件。并对内嵌的 Css 提示 Html 标签内的 Class


## Debug Visualizer
` 调试`

用于在调试时可视化数据结构的 Vs Code 扩展

与 Vs Code 的观察视图类似，但具有丰富的观察值可视化

## Dot Env
` 调试`

不管是前端项目还是后端项目，大多都会使用 .Env 文件来保存环境变量

这款插件可以对 .Env 文件进行高亮
## Easy LESS
`Css `
.Css每次保存文件时生成一个.less文件。例如styles.less-->styles.css

创建一个.Less文件

按 Ctrl/cmd+s 保存文件

.Css会自动生成一个文件

您应该会在状态栏中看到一条临时的“Less Compiled In X Ms”消息
``` js
Settings.json
"Less.compile": {
    //Less插件配置生成文件保存位置
    "Out": "../Css/"
  },
```
## Element UI Snippets
`代码片段 ` `Ui `

Element Ui 的代码片段


## Element-ui-helper
` 代码片段`

鼠标放到Element组件标签上面,提示相应的组件属性和方法


## Emoji
`注释 `

彩色表情
```
打开命令面板Command/ctrl + P 类型>选择Emoji: Insert Emoji
通过点击并选择要在光标处插入的表情符号来运行Emoji: Insert Emoji或emoji: Insert Emoji Unicode在命令面板中。enter
```

## Error Lens
` 规则`

Errorlens 通过使诊断更加突出来增强语言诊断功能，在语言生成诊断的任何地方突出显示整行，并内联打印消息


## ES7+ React/Redux/React-Native snippets
`代码片段 `

Es7+ 中的 Javascript 和 React/redux 片段

```
可以快速创建模板代码，提高我们的开发效率。
比如使用 React 的 Usestate Hook，它可以自动转换 Setxxx 的驼峰命名法，以及自动跳转光标位置
```

## ESLint
`规则 ` `提示 `

文档  <Https://eslint.org/docs/latest/>



## ESLint Chinese Rules
` 提示` ` 代码片段`  ` 注释`

Github Copilot 使用 Openai Codex 从您的编辑器中实时建议代码和整个功能


## GitHub Pull Requests and Issues
`Git `

此扩展允许您在 Visual Studio Code 中查看和管理 Github 拉取请求和问题

```
验证 Vs Code 并将其连接到 Github。github Enterprise 受社区支持，请参阅此Pr了解如何设置。
从 Vs Code 中列出和浏览 Pr。
在 Vs Code 中使用编辑器内评论来审查 Pr。
从 Vs Code 中通过简单的检出验证 Pr。
使 Ui 和 Cli 共存的终端集成。
从 Vs Code 中列出和浏览问题。
“@”提到的用户和问题的悬停卡。
对用户和问题的完成建议。
可以为您创建分支的“开始处理问题”操作。
从“待办事项”注释中创建问题的代码操作。
```
## Htmltagwrap
` Html`

快速包裹Dom标签

我们可以选择一段 Dom 标签，然后按住 Options+w / Alt+w，就可以在外层创建一个标签了。

```
快捷键
      Windows：Options+w
      Mac:     Alt+w
```
```
冲突
      和翻译插件 Wisen Translate 自带快捷键冲突
      解决方法: 把Wisen Translate 快捷方式删除
```
## Image preview

` 图片`

在装订线和悬停时显示图像预览

当引入路径为图片时，可以预览当前图片

## Javascript console utils
` 注释`

将Console.log 改为彩色


## Live Server
` 调试`

为静态和动态页面启动具有实时重新加载功能的本地开发服务器

## Markdown All in One
`Markdown `

Markdown 所需的一切（键盘快捷键、目录、自动预览等
## Markdown Preview VS Code Highlighting
` Markdown`

Markdown 预览 Vs 代码高亮

在 Vs Code 的内置 Markdown 预览中使用Shiki进行代码高亮

使得预览的颜色更好地匹配您在 Vs Code 文本编辑器中看到的颜色


##
` `

```

```

##
` `

```

```

##
` `

```

```

##
` `

```

```
##
` `

```

```

##
` `

```

```