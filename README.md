一.环境搭建
	1.安装eclipse、maven
	2.eclipse配置maven
二.创建Maven项目
	1.打开eclipse，点击: File->new->other 选择创建maven project，点击next
	2.创建项目->点击finish
		Group Id:com.zds  		  //所属组
		Artiface Id:TestProject    //项目名称
		Packaging:war              //选择war
		注：其他的可以默认
	3.右键点击项目，选择properties->Project Facets->Dynamic Web Module 勾去掉，点击Apply
	4.Dynamic Web Module勾上，出现【!Further config...】
	5.在弹框中，修改以下内容，保存
		Content directory： src/main/webapp
		点击完成后：（这里已经把webContent删除了，该文件夹在src下面）
	6.右键点击项目，properties->Deployment Assembly
三. 搭建框架
	1.pom.xml中添加依赖
	2.web.xml中填加servlet
	3.创建spring配置文件，指定注入依赖配置
	4.创建controller
四.配置tomcat，测试项目
===================================================================================

	