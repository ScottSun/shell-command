# shell-command
常用的shell命令

mac下的sed命令的-i参数，需要带一个备份文件名，如果不需要备份用空字符串替换
* grep -lr AAA ./* | xargs sed -i "" 's|AAA|BBB|g'
