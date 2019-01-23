# Apache-kylin_resume
use python resume about failed jobs
需要写配置文件，修改相关参数
[host]
#主机名，默认本机
host = localhost
[port]
#端口号，默认7070
port = 7070
[sleep]
#获取失败jobid等待时长，默认10秒
resquest_time =10
#job 提交时间间隔，默认30秒
job_time=30
[path]
#$KYLIN_HIOM替换成kylin的实例路径
#如果在$KYLIN_HIOM没有retry目录，则新建。
kylin_home = $KYLIN_HOME/retry/
[user]
#登陆用户名，默认ADMIN
user = ADMIN
[password]
#登陆密码，默认KYLIN
pass =KYLIN
[Naenvvar]
#Name of environment variable
#是否开启自动批量刷新功能，需要设置，详见readme
AUTO=AUTO_RESUME
[count]
#设置刷新失败job的次数，默认情况下3次
count=3
