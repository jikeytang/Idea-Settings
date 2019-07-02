## Plugins
插件有很多，但不建议全部都安装，用到那个安装那个，安装过多，由于插件质量良莠不齐，会使软件本身不稳定，经常挂掉。

- Vim  
不好用系列
File -> Settings -> Plugins
搜索vim，对它点右键install，然后重启IDE就行了。

- Eslint  
没VsCode好用系列

  - [有关eslint与webstrom格式化的冲突](https://segmentfault.com/q/1010000014002641)

- React snippets   
安装完之后在此处看规则Preferences -> Editor -> Live Templates -> React Group.

- [vant - webstorm插件](http://plugins.jetbrains.com/plugin/11148-vant-plugin)
- [element - idea plugin for develop vue with element ui](https://github.com/jiaolong1021/ElementPlugin)

- [miaozhang9 - WebStorm下配置微信小程序代码提醒jar](https://github.com/miaozhang9/wecharCodejar)

## Settings
- 主题

  - [修改IDEA代码左侧折叠线颜色](https://blog.csdn.net/FocusAgain/article/details/69257625)   
  - [phpstorm 主题](http://www.phpstorm-themes.com/)   
  - 去掉css行号颜色块显示  
  settings -> Editor -> Appearance -> show css color preview icon in gutter
  - 去掉波浪线  
  file - settings - Editor - Colors & Fonts - General
  - 去除烦人的波浪线+灰色变量名，原因 - 没用过的标签  
  file - settings - Editor - Colors & Fonts - General - Unused sumbol，然后取消选中Effects和Foreground

- Java - IntelliJ IDEA

  - [IntelliJ IDEA 的热部署](https://zyjustin9.iteye.com/blog/2173112)
  - [IntelliJ IDEA12 怎么热部署，每次修改java文件就得重启tomcat](https://www.oschina.net/question/194770_91781)
  - [从Eclipse转移到IntelliJ IDEA一点心得](http://www.ituring.com.cn/article/37792)
  - [Intellij idea 使用配置](https://hwy1782.iteye.com/blog/1917988)
  - [解决intellij idea中使用live edit插件不能在chrome即时显示css变化的方法（html可以）](https://www.cnblogs.com/nova-/p/3761698.html)

- PHP - PHPStorm

  - [使用phpstorm来做github的git操作](https://jingyan.baidu.com/article/27fa7326fc009e46f9271f47.html)
  - [膘叔 - phpstorm设置ftp上传的时间问题](http://www.neatstudio.com/show-2057-1.shtml)

- React

  - [React snippets](https://plugins.jetbrains.com/plugin/10113-react-snippets)
  - [WebStorm中使用reactjs语法报错](https://segmentfault.com/q/1010000004125560)
  - [WebStorm中添加自定义模板](https://github.com/jakwuh/webtip/tree/master/tips/02-08-2017)
  - [WebStorm中React详细规则](https://github.com/Drapegnik/env/tree/master/jetbrains/templates)
  - [Useful Javascript & React live-templates for WebStorm](https://medium.com/@drapegnik/useful-javascript-react-live-templates-for-webstorm-8a6c70aee207)
  
- Vue

  - [Vue 设置 Script 标签首层不缩进](https://www.jianshu.com/p/622c463ff925)  
  
  
- 微信小程序

  - [配置webstorm开发微信小程序](https://www.jianshu.com/p/e2b45d96301e)     
  
- Git

  - [英杰王 - IDEA修改git账号及密码的方法](https://blog.csdn.net/dalinsi/article/details/77989840)  
  - [曹梦龙 - WebStorm与Git使用指南](https://www.kancloud.cn/caomenglong/webstorm_guide/49494)  
  
- SVN

  - [Windows下WebStorm使用SVN（转）](https://www.cnblogs.com/Deasel-s-magic-box/p/3492941.html)  
  - [cannot load supported formats intellij 解决办法](https://blog.csdn.net/ameryzhu/article/details/24269841)  
  
- FTP

  - [FTP自动同步功能](https://www.jianshu.com/p/59692367e528)   
  点击导航栏tools->deployment->automatic upload （always）  

- 请教如何让光标只能在最后一个字符后面  
file -> settings -> ide settings ->editor
allow ... after end of line

- 显示右下角垃圾回收进度  
file - settings - Appearance - show memory indicator

- 关闭标签自动提示，比如输入i会有iframe,ie7等提示  
File -> Settings -> Editor -> Code Completion -> Autopopup code completion

- jsp页面提示插件   
Application Servers View打勾

- 版本控制，文件以及所在的文件夹都会出现一个颜色表示   
version control -> show directories with changed descendants
Settings > Editor > Colors & Fonts > File Status

- 取消多余参数显示  
Settings -> Editor -> General -> Appearance -> Show parameter name hints 
取消打勾

- [设置 Script 标签首层不缩进](https://www.jianshu.com/p/622c463ff925)
- 取消html中间空格  
Setting -> Editor -> code Style -> HTML -> Keep line breaks in text
勾不选

- [如何取消Webstorm的分号检查 - How to disable WebStorm semicolon check?](https://stackoverflow.com/questions/31583771/how-to-disable-webstorm-semicolon-check-in-node-js)
- [通过调试工具将 JS 运行过程可视化可以做到吗?](https://segmentfault.com/q/1010000000592521)


## Default Keymap

    1. ctrl + shift + n: 打开工程中的文件
    2. ctrl + j: 输出模板
    3. ctrl + b: 跳到变量申明处
    4. ctrl + alt + T: 围绕包裹代码(包括zencoding的Wrap with Abbreviation), ctrl + shift + del: 删除包裹
    5. ctrl + []: 匹配 {}[]
    6. ctrl + F12: 可以显示当前文件的结构，快速跳转到目标函数
    7. ctrl + x: 剪切行
    8. alt + left/right:标签切换
    9. ctrl + r: 替换 ctrl + shift + r: 全局替换
    10. ctrl + shift + up: 行移动
    11. shift + alt + up: 块移动
    12. ctrl + d: 行复制
    13. ctrl + shift + ]/[: 选中块代码    <table>....</table>
    14. ctrl + / : 单行注释
    15. ctrl + shift + / : 块注释
    16. ctrl + shift + i : 显示当前class,function的详细信息
    17. ctrl + p: 显示默认参数
    18. ctrl + shift + v: 可以复制多个文本
    19. shift + enter: 智能跳到下一行 ctrl + alt + enter: 在上一行添加空白行vb
    20. ctrl + k: svn 提交
    21. ctrl + shift + u: 大小写
    22. ctrl + ~ : 切换主题
    23. ctrl + F11: 添加标签 ctrl + shift + 大键盘数字键, F11:添加空标签, shift+F11:显示标签列表，方便快捷跳转
    24. ctrl + alt + F12: file path
    25. ctrl + alt + a: search keymap
    26. shift + F6: 重构标签名，焦点在编辑区时可以修改当前文件的变量名
    27. Ctrl+delete  删除光标后面的单词
    28. Ctrl+BackSpace  删除光标前面的单词
    29. Ctrl+小键盘+/-  折叠/展开代码
    30. Ctrl + Alt + V 快速引进一个变量
    31. Ctrl+Alt + I 自动对齐格式
    32. alt+j: //选中下一个同样的词 Shift + Ctrl + Alt + J //选中所有同样的词
    33. ctrl+alt+m: 重构函数
    34. ctrl+shift+alt+j: 向下选词
    35. ctrl+w: Main menu -> Edit -> Extend Selection 扩展选中
    
### 自定义

    1. alt + d :show in explorer
    2. alt + c: 删除单行
    3. alt + w: 注释单行
    4. alt + b: open in browser
    5. shift + space: suggest path
    6. 全屏的快捷键是 ` ，就是esc下面的那个键
    7. F1: project
    8. split line: ctrl+alt+enter, before current:ctrl+enter
    9. new line: shift + enter, before current : ctrl + enter
    10. alt + F11: 焦点从编辑区到工具区 Jump to last tool window 再跳回来: ESC
    11. alt + p: surround with
    12. alt+1: hide active tool window, Tool window -> Project
    13. alt+U: upload file to ftp
    14. alt+T: show toolbar
    15. alt + L : show history 查看本地历史记录 

## Document
- [emmet.io - 内置emmet文档](https://docs.emmet.io/cheat-sheet/)

## Skill
- 在出现横向滚动条的文件中，按住 shift 键滚动滚轮，可以横向移动编辑区

## Guide
- [judasn - IntelliJ IDEA 简体中文专题教程](https://github.com/judasn/IntelliJ-IDEA-Tutorial)

## Other
- [关于Webstorm webpack经常不能自动热更新问题](https://segmentfault.com/q/1010000007796140)  
webstrom settings的system settings默认勾选‘safewrite’,勾选去掉就可以了

