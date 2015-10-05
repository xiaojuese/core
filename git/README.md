#git 常用命令
##配置相关
- 查看配置
	- 显示全部：git config  --list	
	- 显示全局：git config --global --list 如果本地没有则使用全局的
	- 显示本地（具体）：git config --local --list 
- 修改配置
	-	修改本地 git config user.name xiaojuese
	-	修改全局 git config --global user.name xiaojuese