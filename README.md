# personal-VSCode-configuration
配了一下自己觉得比较舒服的设置

**注意：** C/C++部分还未完全配置完，makefile和cmake的路径需要根据自己的电脑路径进行配置

## 需要安装的插件





## markdown部分配置
使用`Markdown All In One`和`Markdown Preview Github Styling`插件
### 操作方法
在vscode中，`Ctrl+Shift+P`输入`user snippets`,接着输入`markdown`,打开`markdown.json`文件后，将内容进行替换

在`setting.json`中,添加如下代码，此段代码目的是使得`markdown.json`中设置的快捷键可以被使用
```
"[markdown]": {
        "editor.formatOnSave": true,
        "editor.renderWhitespace": "all",
        "editor.quickSuggestions": {
            "other": "on",
            "comments": "on",
            "strings": "on"
        },
        "editor.acceptSuggestionOnEnter": "on",
        "editor.defaultFormatter": "yzhang.markdown-all-in-one"
    },
```

## 未完
后续可能会对其他语言的配置进行补充更新
