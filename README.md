### Markdown外链图片格式
对Markdown外链图片的语法进行进行测试，效果如下。

- 图片居中
	- 貌似标签前后不能同时有空行？（HTML渲染及Github渲染都显示的是插入图片的整个语法内容）
<center>
![matlab](https://github.com/hustmzp/external_link_images/raw/master/test/matlab.png)
</center>

- 设置大小
	- 原图大小
	
		![](https://github.com/hustmzp/external_link_images/raw/master/test/27c54652d8426dc9.jpg)
	- 缩放50%（宽高都缩放50%）

		<img src="https://github.com/hustmzp/external_link_images/raw/master/test/27c54652d8426dc9.jpg" width="50%" height="50%" />

- 缩放后居中
	- 注意：center内部的图片链接使用该语法时需缩进一个制表符（这个时候center标签前后有空行时HTML渲染又没问题了。。。）

<center>
	<img src="https://github.com/hustmzp/external_link_images/raw/master/test/27c54652d8426dc9.jpg" width="50%" height="50%" />
</center>

- github外链格式
	- png格式（整体缩放50%）

		<img src="https://github.com/hustmzp/external_link_images/raw/master/test/%E5%8D%8E%E4%B8%AD%E7%A7%91%E6%8A%80%E5%A4%A7%E5%AD%A6%E6%A0%A1%E5%BE%BD%E9%AB%98%E6%B8%85.png" width="50%" height="50%" />

	- gif格式

		![monitorsize](https://github.com/hustmzp/external_link_images/raw/master/test/monitorsize.gif)

	- svg格式

		![CPCflag](https://github.com/hustmzp/external_link_images/raw/master/test/CPCflag.svg)

