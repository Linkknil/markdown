# 1、关于Markdown #

介绍链接地址：
[http://itmyhome.com/markdown/article/about/readme.html](http://itmyhome.com/markdown/article/about/readme.html "mark讲解")

# 2、基本语法 #
1. 段落和换行  
	段落内如何加入换行呢？  
	加br或者两个空格

2. 标题  
	可以使用 # #来使用

3. 引用    
	>在段落或者其他内容前使用>符号  
	具体多行链接可以查看:
	[http://itmyhome.com/markdown/article/syntax/blockquotes.html](http://itmyhome.com/markdown/article/syntax/blockquotes.html "引用")

4. 列表  
	有序列表展示  
	1.  记得.开始
	2.  并且要有个空格
	
	无序列表  
	- -可以  
	+ +也可以  
	* *也可以  
  
5. 代码   

```
printf("hello world");
```
  
  
6. 分割线  
	
	---
	***

7. 超链接  

	格式 `[link text](URL 'title text')`
	
	- 普通链接  
	[Google](http://www.google.com/)  

	- 本地文件链接  
	[icon.png](./imgs/tu.png)  

8. 插入图片  
	插入图片的语法和插入超链接的语法基本一致，只是在最前面多一个 !。

	- 插入一个原始图片  
	![GitHub](./imgs/tu.png "test")  

	- 插入一个指定大小图片<img标签  
	<img src="./imgs/tu.png" title="test"  width="100" height="100"/> 

9. 强调  
	- 加粗  
	  **怎么加粗**  
	- 斜体  
		*怎么斜体*

10. 字符转义  
	反斜线（\）用于插入在 Markdown 语法中有特殊作用的字符。

	\*显示一些特殊字符\*  
	
	**特殊字符有：**  

	`
		\ _ * {} () # + - . !
	`

# 3、扩展语法 #
1. 删除线   
    markdownpad ~~做删除线无效~~  
	要用del语法  
	比如:  
	<del>我是删除线</del>		

2. 语法高亮  
	**如果没有在工具中进行设置，那么没法显示语法高亮**  
	设置路径为：  
	工具->选项->markdown->markdown处理器->github风格

```objc
	self.window = [[UIWindow alloc] initWithFrame:[UIScreen mainScreen] bounds]];
	[self.window makeKeyAndVisible];
	return YES;

	if (int i=0; i<100; i++)
	{
		NSLog("i=%d",i);
	}
```

3. 表格  
  - 单元格和表头   
	
|    name    | age |
| ---------- | --- |
| LearnShare |  12 |
| Mike       |  32 |

   - 对齐方式   
		
| left | center | right |
| :--- | :----: | ----: |
| aaaa | bbbbbb | ccccc |
| a    | b      | c     |

# 4、编辑器和一些扩展介绍 #

[编辑器介绍](http://itmyhome.com/markdown/article/tools/readme.html "编辑器和扩展介绍")

# 5、问题 #
- 目前很多markdown编辑器的一些语法不一致
- github和 http://git.oschina.net 上传上去展示的不一致

	
	
	
