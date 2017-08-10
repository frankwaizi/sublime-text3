# sublime-text3
我的常用SublimeText3个人设置与插件

# 用户设置
```javascript
{
    "color_scheme": "Packages/Babel/Monokai Phoenix.tmTheme",// 主题
    "font_size": 16,
    "ignored_packages":
    [
        "Vintage"
    ],
    "word_separators": "./\\()\"':,.;<>~!@#$%^&*|+=[]{}`~?", //这些字符会在鼠标双击时隔断,可自行删除不必要的,例如这个被我修改过删除了'-'符号
    "word_wrap": true, //一行内容太长了,自动换行(如果你够'自信'的话,又喜欢拖动X轴滚动条请无视我)
    "highlight_line": true, //高亮显示当前编辑的行,有时自动折行看不清,这个就把一整块显示出来,清晰一些
    "show_encoding": true, //编辑器底部显示编码信息,用GBK编码的偶尔出现乱码,看看这个能查一下,虽然作用不大,放在下面也不占地方,无所谓了
    "save_on_focus_lost": true, //当焦点从当前编辑文档中丢失,会自动保存,看个人喜好咯
    "highlight_modified_tabs": true, //高亮TAB显示被修改过的文档,如果上一条为关闭,修改过的文件看起来更清晰
    "highlight_modified_tabs": true,//高亮未保存文件。
    "draw_minimap_border": true, //在编辑器右侧小代码地图上为当前区加个边框,视力不好可以加上,比如我
    "always_show_minimap_viewport": true, //总是显示这个迷你地图窗口,还是视力不好
    "tab_size": 2, // tab空格大小
    "translate_tabs_to_spaces": true, //很明白就是把代码 tab 对齐转换为空格对齐，tab_size 配合设置空格数
    "trim_trailing_white_space_on_save": true, //自动移除行尾多余空格
    "ensure_newline_at_eof_on_save": true, //文件末尾自动保留一个空行
    "fade_fold_buttons": false, //默认显示行号右侧的代码段闭合展开三角号
    "bold_folder_labels": true, //侧边栏文件夹显示加粗，区别于文件
    "default_line_ending": "unix", //使用 unix 风格的换行符
    "scroll_past_end": true, //滚动能否超过结尾
    "show_full_path": true //在你的窗口title上显示当前编辑的文件的全路径
}

```

# 插件安装
```
- Package Control
- Babel //for React
- CSS3
- Autoprefixer
- CSSComb || CSSOrder
- ColorHighlighter
- BracketHighlighter
- SideBarEnhancements
- HTML-CSS-JS Prettify
- SublimeCodeIntel
- DocBlockr
- TrailingSpaces
- SideBarFolders
- WordCount
- ConvertToUTF8
- All Autocomplete
- GitGutter
```

#主题推荐
另外，推荐一款新主题：  
[Material Theme](https://github.com/equinusocio/material-theme)  
![Material Theme](http://i.imgur.com/9PyxJMN.gif)  
和对应的AppBar:  
[Material Theme Appbar](https://github.com/equinusocio/material-theme-appbar)  
![Material Theme App Bar](http://i.imgur.com/LVhR9jq.png)
