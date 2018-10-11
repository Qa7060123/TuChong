# TuChong
这是一个图虫项目 
团队开发离不开版本控制器，而现今最好用的免费版本控制就是git，这里教会大家使用git，献上一个干货 
前言 
自从git这个版本控制器问世以后，它便代替SVN成为最好用的免费控制器，会不会使用它关系着每个开发者的开发便利与否的问题，这么说：如果你不会用git===你不会团队开发，而GitHub 
是一个面向开源及私有软件项目的托管平台，因为只支持 Git 
作为唯一的版本库格式进行托管，故名 GitHub，除了 Git 代码仓库托管及基本的 
Web 
管理界面以外，还提供了订阅、讨论组、文本渲染、在线文件编辑器、协作图谱（报表）、代码片段分享（Gist）等功能。目前，其注册用户已经超过350万，托管版本数量也是非常之多，其中不乏知名开源项目 
Ruby on Rails、jQuery、python 等。 
很多没有工作过的同学，一般很少接触到它，或者说甚至不了解，我也曾经在网上找了很多的教程，都是说了各种命令行，却很少有手把手的教你怎么做的。于是决定出一个关于git+github的手把手教程。 
提示：默认教程是linux环境下的，如果你是window环境下请安装git软件，安装后，在教程输入git命令行时，请使用右键Git 
bBash Here打开git自带的命令行。 创建github项目 
首先我们进入github官网：github，注册一个用户Sign 
up，这里就不教大家怎么注册了，你自己起个用户名（得是英文），再用你的邮箱地址作为账号，密码一设，注册结束，然后Sign 
in登录，登录后如图： 点击start a project（开始一个项目），如图： 
进行相关信息的填写信息，由于是英语这里简单说说： Repository 
name（库名称）:填写你要创建的git项目的名字 Description (optional) 
:填写你的项目的规范
Public Initialize this repository with a 
README：初始化本库，可选择可不选择，这里分为两种演示方式，先演示不选择的。 
git本地化 本地化方式一 点击Create 
repository，创建库，如果不选中Initialize this repository with a 
README，创建后如图： 
不了解的人看到这个就不能理解了，这是什么？不急，按照下面的教程，你的疑问会慢慢进行解答 
新建文件夹存放git 
其实这就到了命令初始化git了，如果你是window用户的话，自行创建一个文件夹，然后shift+右键，选中"在这里打开命令行"，然后跳过linux建目录的过程。 
如果你是linux的话，要么自行定义文件夹，要么按照流程跟我走，我们打开命令行，linux如下： 
cd ~ mkdir githubproject（文件夹名） cd githubproject/ 
首先到达home目录，创建一个文件夹名叫githubproject，再进入到文件夹里面。 
作者：言墨儿 链接：https://www.jianshu.com/p/deb5eddbffb8 來源：简书
简书著作权归作者所有，任何形式的转载都请联系作者获得授权并注明出处。
