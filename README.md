# shell-command
常用的shell命令

mac下的sed命令的-i参数，需要带一个备份文件名，如果不需要备份用空字符串替换
* grep -lr AAA ./* | xargs sed -i "" 's|AAA|BBB|g'

sudo权限重定向
* sudo sh -c ">access.log"

vim删除空白行
* g/^$/d

awk求和
awk 'BEGIN{total=0}{total+=$1}END{print total}'
