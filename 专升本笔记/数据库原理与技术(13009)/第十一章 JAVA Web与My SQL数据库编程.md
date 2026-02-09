Tomcat目录及主要文件说明
	bin目录
		bin目录主要是用来存放Tomcat命令的
	conf目录
		catalina 目录：用于存储自定义部署 Web的应用程序文件。
		文件 server.xml：可以设置端口号，设置域名或IP，默认加载的项目，请求编码。
		文件tomcat-users.xml：用来配置管理Tomcat的用户与权限。
	lib目录
		lib目录用于存放Tomcat运行需要的库文件
	logs目录
	temp目录
		temp目录主要存放Tomcat在运行过程中产生的临时文件
	webapps目录
		webapps目录用来存放应用程序，当Tomcat 启动时会加载webapps目录下的应用程序。
	work目录
		work目录用来存放Tomcat在运行时编译后的文件，如JSP编译后的文件。清空work目录，然后重启Tomcat，可以达到清除缓存的目的。
servlet/JSP的工作原理
	Servlet是一种独立于平台和协议、在服务器端运行的Java应用程序，可以生成动态Web 页 面，其名称来自于Service+Applet，表示小服务程序。
	JSP是对 Servlet的补充，JSP源程序编译后就是一个 Servlet。
	