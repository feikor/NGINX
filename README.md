# NGINX

http://www.pcre.org/

rpm -qa | grep pcre

http://nginx.org/

yum install pcre pcre-devel -y

http://nginx.org/en/download.html

http://nginx.org/download/nginx-1.14.2.tar.gz


ls -lh

tar xf nginx-1.14.2.tar.gz

 ./configure --user=www --group=www --with-http_stub_status_module --with-http_ssl_module --prefix=/application/nginx-1.14.2/
 
 yum install openssl-devel -y
 
 
 useradd www -s /sbin/nologin/ -M


rpm -qa pcre pcre-devel
rpm -qa | grep pcre

rpm -qa pcre
pcre-8.32-15.el7_2.1.x86_64
pcre-8.32-15.el7_2.1.i686

yum remove pcre-8.32-15.el7_2.1.i686

tar xf nginx-1.14.2.tar.gz

yum list|grep nginx

 ./configure --user=www --group=www --with-http_stub_status_module --with-http_ssl_module --prefix=/application/nginx-1.14.2/
./configure: error: C compiler cc is not found

yum install gcc -y
 yum install openssl-devel -y
 
 
./configure: error: SSL modules require the OpenSSL library.
 yum install openssl-devel -y


 useradd www -s /sbin/nologin/ -M
 
 ln -s /application/nginx-1.14.2/ /application/nginx

http://www.runoob.com/linux/linux-yum.html

yum -y install 包名（支持*） ：自动选择y，全自动
yum install 包名（支持*） ：手动选择y or n
yum remove 包名（不支持*）
rpm -ivh 包名（支持*）：安装rpm包
rpm -e 包名（不支持*）：卸载rpm包


 



