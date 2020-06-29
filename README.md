####################################################################
flaskboot功能说明：
本项目为熟悉springboot的程序员提供一个类似的python框架，毕竟springboot已经深入人心。
实现了控制器、拦截器、服务实现、数据模块和Dao操作
flask更简洁，但如果把功能都堆到一个模块中，不易于后续维护，为此设计了该项目。
windows、Linux部署方便。


####################################################################
flaskboot目录结构：
config：配置文件，包括端口号、mysql等
logs：运行日志
src：实现主要代码
src.controller: 控制器
src.interceptor: 拦截器
src.repository: 数据库操作实体和接口
src.service: 服务逻辑实现
src.utitl: 通用基础模块
application.py 进程入口模块
start.sh 启动脚本
stop.sh 关闭脚本

####################################################################
查看操作系统版本：
cat /etc/redhat-release


安装依赖包：

pip install flask-sqlalchemy

pip install pymysql


####################################################################
联系方式： czhijun@sina.com


