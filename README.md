# Dynamic-IP-Log

微醺

联系我：d2UxeDRuQHFxLmNvbQo=

配合crontab进行轮回检测

```shell
crontab -e
```
修改crontab的配置文件

```shell
*/30 * * * * /usr/bin/python /usr/weixun/Dynamic-IP-Log.py
```
使用前将`Dynamic-IP-Log.py`里面IP.log文件修改成绝对路径


------------


PS:如果不能执行的话，就写一个shell脚本，让crontab每次都执行sh文件就好了
