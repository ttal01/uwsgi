# uwsgi
kedazikong
#如何安装GeoServer
http://blog.csdn.net/lin00kun11/article/details/39581777
#nginx 和 GeoServer 部署研究
http://www.docin.com/p-1298769706.html

/etc/profile

export JAVA_HOME=/usr/local/java/jdk1.8.0_144
export JRE_HOME=$JAVA_HOME/jre
export JAVA_BIN=$JAVA_HOME/bin
export CLASSPATH=.:$JAVA_HOME/lib/dt.jar:$JAVA_HOME/lib/tools.jar:$JRE_HOME/lib
export PATH=$PATH:$JAVA_HOME/bin:$JRE_HOME/bin

source /etc/profile
