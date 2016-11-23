# Multimedia-Project Online Video Play and Chat
多媒体项目的视频播放实时弹幕功能和在线聊天功能

运行的环境要求：
       视频播放部分和弹幕部分：需要配置linux服务器的Nodejs运行环境
       
       在线聊天功能部分：需要同样配置Nodejs运行环境，同时需要在Linux环境下安装Redis，
                       运行这部分功能的时候需要先启动Redis数据服务器然后再启动Nodejs Server
                       
       前端页面Welcome：这个作为一个欢迎页面可以放在Tomcat服务器或者Nginx服务器上就可以，作为服务器启动时候
                       静态页面加载就可以实现到视频播放页面和在线聊天页面的跳转功能，但是需要对html文件中跳转的链接进行修改
       
       配置环境的具体细节，参见各个子目录中的文档
       
