#各大主流服务器配置httpst贴图教程	#

###Nginx Https 配置###
	server {
	    listen              80;
	    listen              443 ssl;
	    server_name         www.example.com;
	    #配置证书   证书路径
	    ssl_certificate     www.example.com.crt;
	    ssl_certificate_key www.example.com.key;
	    #...
	}

###Apache Https 配置###



###IIS Https 配置###



###Tomcat Https 配置###