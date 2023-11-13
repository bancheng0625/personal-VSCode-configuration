# personal-VSCode-configuration
配了一下自己觉得比较舒服的设置

**注意：** C/C++部分还未完全配置完，makefile和cmake的路径需要根据自己的电脑路径进行配置
## 需要字体
 Github Monaspace
[字体详情](https://monaspace.githubnext.com)

个人选用MonaspaceXenon

## 需要安装的软件
1. VSCode
2. mingw64
3. cmake
4. cmake-format
## 需要安装的插件
1. Monokai Pro
2. vscode-icons
3. Fluent-Icons
4. C/C++
5. CMake
6. CMake Tools
7. cmake-format
8. Code Runner
9.  Cpp Reference
10. Makefile Tools
11. Markdown All in One
12. Markdown Preview Github Styling
13. Gitlens-Git supercharged
14. Error Lens
15. Doxygen Documentation Generator
16. Color Highlight
17. Better Comments

## markdown部分配置
使用`Markdown All in One`和`Markdown Preview Github Styling`插件
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
