# Markdown入门 

（仅仅是对自己的使用做个记录）

---

正文开始啦&ensp;	:exclamation:  :question:  
&ensp;	:smile:  :smiley:  :smirk:  :worried:  :expressionless:  
&ensp;	:weary:  :sweat_smile:  :disappointed_relieved:  :sob:  :joy:  
&ensp;	:scream:  :angry:  :triumph:  :sunglasses:  :smiling_imp:  
&ensp;	:thumbsup:  :-1:  :punch:  :fist:  :pray:  :muscle:  
&ensp;	:rocket:  :arrow_left:  :arrow_right:  :sunny:  :bug:  

***

## 简介  
　　Markdown是什么？相信很多小伙伴对于Markdown会很陌生，简要来说，Markdown是一种排版语法。排版？我们不是有Word吗？What？我们可是21世纪的"程序猿"了，怎么还能这么low(没有贬低word的意思 真的)。网站小编、码农、排版编辑高呼：“要有光！” 于是乎Markdown诞生了。  
　　你可以认为Markdown是一种排版语法，提供了一些特殊的符号来替换成对应的格式，我们在word中点击鼠标来达到加粗、倾斜、增大字体的目的，在Markdown中被相应的特殊符号替代。Markdown用于解放鼠标，仅仅使用键盘就能排版出非常漂亮的文字、博客等（比如本文就是用Markdown编写的）。

---

## 准备  
- 安装[HBuilder](http://www.dcloud.io/)  
- 安装GFM Viewer
  - 打开HBuilder
  - 工具
  - 插件安装
  - 浏览eclipse插件市场
  - 搜索GFM Viewer
  - install
- GFM使用
  - 右击XXX.md
  - show in GFM View

___

## 语法

1. 标题  
    - 字符`#`作为关键字  
    - `#`后面加上一个`空格`
    - 类似于html中的`h1 ~ h6`  

2. 列表
    - 无序列表
      - 格式：`*`&ensp;`-`&ensp;`+` 后`空一格`  
      - 多级：下一级开头`空两格`
  
    - 有序列表  
      - 格式：`1.`&emsp;`2.`&emsp;`3.`  后`空一格`  
      - 多级：下一级开头`空四格`  

3. 倾斜  
    - 格式：`*倾斜文字*`  `_倾斜文字_`
    - 示例：*倾斜文字*  _倾斜文字_

4. 粗体  
    - 格式：`**粗体文字**` `__粗体文字__`
    - 示例：**粗体文字**  __粗体文字__

5. 加粗倾斜  
    - 格式：`***倾斜加粗文字***` `___倾斜加粗___`
    - 示例：***倾斜加粗文字*** ___倾斜加粗___
    
6. 删除线  
    - 格式：`~~删除文字~~ `
    - 示例：~~删除文字~~  
    
7. 链接  
    - 格式:`[链接描述](url地址 "提示文字可不写与url空一格")`
	- 内嵌式链接
    	- 示例：
    	```
    	[刘坤磊的github](https://github.com/liukunlei)  
    	[README.md](README.md)  
    	[Markdown小技巧](#小技巧 )  
    	```
    	[刘坤磊的github](https://github.com/liukunlei)  
    	[README.md](README.md)  
    	[Markdown小技巧](#小技巧)  
    - 引用式链接
        - 示例：
        ```
        [刘坤磊github]  
		[回到顶部]  
		
		[刘坤磊github]: https://github.com/liukunlei  
    	[回到顶部]: #准备 
        ```
        
		[刘坤磊github]  
		[回到顶部]  
		
		[刘坤磊github]: https://github.com/liukunlei  
    	[回到顶部]: #准备

8. 图片  
    - 格式：
    ```
    下面是外部图片
	![林宥嘉图片不存在](https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1504330182151&di=903d1b8efba12cdfc68aa15183e448ea&imgtype=0&src=http%3A%2F%2Fimg22.mtime.cn%2Fup%2F2010%2F11%2F30%2F092058.43271090_o.jpg "成全")
	下面是仓库内图片
	![林宥嘉](images/timg.jpg)
	下面是图片引用式链接  
	![yoga][宥嘉]  
	![yogalin][linyoujia]  
	
	[宥嘉]:https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1504330182151&di=903d1b8efba12cdfc68aa15183e448ea&imgtype=0&src=http%3A%2F%2Fimg22.mtime.cn%2Fup%2F2010%2F11%2F30%2F092058.43271090_o.jpg  
	[linyoujia]:images/timg.jpg  
	下面是图片链接  
	[![youji](images/timg.jpg)](http://www.baidu.com)
    ```
	- 示例：  
	下面是外部图片
	![林宥嘉图片不存在](https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1504330182151&di=903d1b8efba12cdfc68aa15183e448ea&imgtype=0&src=http%3A%2F%2Fimg22.mtime.cn%2Fup%2F2010%2F11%2F30%2F092058.43271090_o.jpg "成全")
	下面是仓库内图片
	![林宥嘉](images/timg.jpg)
	下面是图片引用式链接  
	![yoga][宥嘉]  
	![yogalin][linyoujia]  
	
	[宥嘉]:https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1504330182151&di=903d1b8efba12cdfc68aa15183e448ea&imgtype=0&src=http%3A%2F%2Fimg22.mtime.cn%2Fup%2F2010%2F11%2F30%2F092058.43271090_o.jpg  
	[linyoujia]:images/timg.jpg  
	下面是图片链接  
	[![youji](images/timg.jpg)](http://www.baidu.com)
	
9. 引用  
    - 格式：`>(大于号)引用内容`
    >这里是引用的内容 

10. 行内代码  
    - 格式：\`行内代码\`（Tab上面的&ensp;\`）
    - 示例：git `push` origin master  
    
11. 代码块  
    - 格式：\`\`\`代码\`\`\`
    - 示例：
    ```php
 	//时间差值
	$cha = mktime(0,0,0,8,3,2017)-time();
	$cha = mktime(0,0,0,2,16,2018)-time();
	$daynum = 24*60*60;
	$day = floor($cha/$daynum);
	$hour = floor(($cha%$daynum)/3600);
	$minute = floor((($cha%$daynum)%3600)/60);
	$second = (($cha%$daynum)%3600)%60;
	echo "距离过年还剩".$day."天".$hour."小时".$minute."分钟".$second."秒";
    ```
    
12. 表格  
    ```
    |名称|值|备注|
	|:---|:---:|---:|
	|1|2|31|
	|2|1|3|
    ```

	|名称|值|备注|
	|:---|:---:|---:|
	|1|2|31|
	|2|1|3|

13. 复选框  
	任务列表
	- [ ] 任务1
	- [x] 任务2
	- [ ] 任务3
	```
	任务列表
	- [ ] 任务1
	- [x] 任务2
	- [ ] 任务3
	```

14. 分割线  
    - 格式：三个或以上`*`&ensp;`-`&ensp;`_`

***

## 小技巧

1. 换行  
    - 空一行  
      - 在想要换行的地方`Enter两次`
    - 加两个空格  
      - 在想要换行的地方`空两格`

2. 首行缩进  
    - 输入法切换为`全角（shift+space）`  
      - 全角占用了一个汉字的位置，半角则占用了一个英文的位置
    - 段首`空两格`

3. 字体、字号、颜色 
    - Markdown是兼容html的  
    - `<font size=5 face="黑体" color=red>字号</font> ` 

4. 字符转义  
    - 格式：`\*`
    - 反斜杠连接要转义的字符
    
5. 缩进、空格  
    - \&emsp;是一个中文字符
    - \&ensp;是半个中文字符
    - \&nbsp;是1/4中文字符
    
___

## Markdown学习  
- [果冻虾仁Markdown]  
- [表情符号]
- [Markdown练习]

[果冻虾仁Markdown]:https://github.com/guodongxiaren/README/blob/master/README.md#文本
[表情符号]:https://github.com/guodongxiaren/README/blob/master/emoji.md  
[Markdown练习]: https://www.markdowntutorial.com/
***

## 关于我
:smile: 963114591@qq.com  
:smiley:刘坤磊  

[回到顶部]
