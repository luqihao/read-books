ES6 标准入门 - 阮一峰

javascript 设计模式与开发实践 - 曽探

SVG 精髓（第二版）

HTML5 canvas核心技术 图形、动画与游戏开发

node.js实战




### vim操作手记

命令模式
	左右 h l
	上下 k j
	dd	删除一行,剪切一行(ndd)
	dG 从当前行删除到最后一行 
	dw 删除一个单词
	d^ 从当前字符删除到行首
	d$ 从当前字符删除到行末
	dnG从当前行删除到第n行
	G  最后一行
	nG 到达第n行
	yy 复制当前行
	nyy 复制n行
	p  粘贴到下一行
	2p 重复粘贴两次
	P  粘贴到上一行
	u  撤销
	ctrl+y 恢复
	/hello 查找hello单词，查找多个n(next)键 
	v  按v键再按上下左右进行视图选中，进行快速缩进(tab右，shift+tab左)
	x  删除当前字符,nx删除n个字符

末行模式
	:wq 保存退出
	:x	保存退出
	:q	不保存退出
	:w 	保存不退出
	:q! 强制不保存退出
	:%s/hello/world/g 	  把hello替换成world
	:1,10s/hello/world/g  从第1行到第10行把hello替换成world
