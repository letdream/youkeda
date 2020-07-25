我们使用git init命令将一个文件夹初始化为一个git仓库
我们可以使用git remote -v命令来查看当前git仓库绑定的远程仓库,显示是空白，即无绑定，我们才可以进行远程仓库的绑定，否则就会提示冲突
我们使用下面的命令来绑定远程仓库：git remote add origin 仓库地址
如果绑定错误，我们可以执行git remote remove origin来移除我们的绑定