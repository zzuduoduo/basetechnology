# 总体架构
初创互联网公司几个特点决定了总体架构：
  1. 刚成立，急需将产品推出去，迭代优化。
  2. 技术人员偏少和偏弱，特别是目前竞争激烈的社会，好的技术人才更是一将难求，因此必须在技术架构从实际出发。
  3. 人员流动性高，能够干满一年的都是老员工了。
    
基于以上三个特点，设计移动互联网公司的原则如下：  

  1. 主体采用成熟技术方案，这里成熟技术方案是指大多数互联网公司在使用的方案，开源软件尽量采用公司开源的而不是个人开源的，主要考虑是后期维护性。
  2. 部分采用最新的技术方案，一方面最新的技术方案一般都是为了解决现有问题，提高开发效率的，部分采用可以提升技术水平，另一方面提高人员对技术的兴趣，提高整体技术水平。  

目前我们使用的技术栈为：
* 前端为AngularJS、Nodejs、ExpressJS、bootstrap、requireJS、grunt、underscore、JQuery等，
* iOS开发采用swift语言，Android使用Android Studio，使用MVC架构，正在转向MVP架构，统计信息采用友盟和百度统计，友盟在iOS错误统计上有问题，目前已转向百度统计。
* 服务器端采用Spring 4.0，架构正在由单体应用转向到微服务架构，Mysql数据库，基础运维环境是阿里云。
* 运维正在采用Docker，准备搭建基于Docker和Jenkis，Git的持续集成平台，减轻运维压力
* 日志监控和性能监控。采用ELK开源日志平台，实时分析日志，对错误和性能进行及时报警。
* 代码版本管理采用SVN和GitLab，目前正在从SVN迁移到GitLab上，svn在分支管理上远远落后于git，并且code review可以在gitlab很好的完成，无须再搭建新的代码评审系统。




