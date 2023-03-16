# verilog_fingertext
notepad++的fingerText插件，编写Verilog的利器，可以将常用定义，计数器等模板化。

安装notepad++后，配置该插件后，可以配置模板，解放生产力！

如设置一个模板关键字： **w8**，内容如下：

	wire           （预留空格） 		[7:0]	（预留空格）      

在notepad++敲代码时，只要输入 **w8+"tab"**键，可按预定格式自动补全如下代码:

	wire            		[7:0]	      |(光标)

如上，可以设置多个关键字，wx(x为位宽)，也可以设置复杂的模板如：计数器，状态机等。


一定程度可以替代GVIM

效果如下：

![](https://github.com/fivexxxxx/verilog_fingertext/blob/master/fingerText.gif)
