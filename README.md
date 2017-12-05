一、登录知乎      

这里用的是手机端登录的，[知乎登录的链接](https://www.zhihu.com/signin?next=/)      
post请求：           
![image](https://github.com/xiangge93/zhihu_login/raw/master/知乎登录.png)
      
post请求的参数：      
_xsrf：据说是防跨站请求的；      
password：密码       
email：登录邮箱        
captcha：验证码       
        
在登录页定位到这些参数，用post在登录时传入这些参数，就可以登录了；      
