---
title: 搭建网站的必备要素
tags: 张驰

---
1.域名 
    
   (1).不需要解析域名(直接转发) 
      
       https://www.site.ac/ 
       
  （2).需要解析域名 
       
       https://customer.l53.net/ (无用） https://www.namesilo.com/ 
       
   (3).检测域名是否有效

       https://whois.west.cn/
2.域名解析 

    https://dash.cloudflare.com/login 

3.ssl证书获取 

   （1）证书获取  
   
        https://ohttps.com/monitor/dashboard 
   
   （2）Tomcat 实现 HTTPS 访问(开放443端口) 
   
     https://www.cnblogs.com/54chensongxia/p/13754839.html 
       
   （3）tomcat的ssl证书格式为JKS 或 PFX(推荐使用) 
       需要将PEM转换为PFX 
       
       https://myssl.com/cert_convert.html 

4.云服务器 

（1）国内阿里云或腾讯云都可以但需要备案 

（2）国外

     https://linuxone.cloud.marist.edu/#/index 



---

