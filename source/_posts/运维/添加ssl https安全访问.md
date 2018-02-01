---
title: 添加ssl https安全访问
categories: 运维
tags:
  - ssl
---
# 参考文章

- ["Let's Encrypt" 全程配置使用指南](https://www.williamyao.com/index.php/archives/1438/)
- [Linux CentOS 7 下 Nginx 安装使用 Let’ s Encrypt 证书的完整过程](http://blog.csdn.net/andylau00j/article/details/54604415)

1.CentOS使用yum安装源

2.推荐使用TLS-SNI方式申请

3.下面/home/wwwroot/www.williamyao.com 这一端的意思是 nginx conf文件里面的root行
~~~
# certbot certonly -w /home/wwwroot/www.williamyao.com -d williamyao.com -d www.williamyao.com
~~~

-[可以免费申请的中文网站，其实也是上面网站提供的](https://freessl.org/)