经过本次的错误，经过两天的折腾，现记录如下：
1.下载github的wndow版本使用https://git-scm.com/
2.使用命令登陆win + R 输入 sysdm.cpl选择高级 -- 环境变量
系统变量 -- path，打开git的 bin文件夹，复制bin文件夹的绝对路径例 D:\Git\bin将该路径添加至环境变量
输入 git  --version测试是否调整好变量
在base中登陆
输入git config --global user.name “your name”
输入 git config --global user.email “email@email.com“
3.最后让git走代理
clash代理开启之后在cmd中执行git config --global http.proxy http://127.0.0.1:7890
4.之后在vscode中进行clone
