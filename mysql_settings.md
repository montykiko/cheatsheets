```
@title :mysql terminal settings in mac
Created on 2017-08-18
@author :jixue
```
## 方法：alias命令简化相对路径
```
$ vim ~/.bash_profile
#MySQL
alias mysql='/usr/local/mysql/bin/mysql'; (退出保存 :wq)
$ source ~/.bash_profile
$ mysql -u root -p
Enter password:
```

## 修改mysql密码
```
mysqladmin -uroot -p password 123456
```

## 忘记mysql密码的解决方案
[如果忘记mysql密码](http://fgyong.cn/2016/01/28/MAC-重置MySQL-root-密码/)

## 登入mysql
```
mysql -h127.0.0.1 -uroot -p 123456
```
