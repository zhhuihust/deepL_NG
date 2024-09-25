

## github windows 设置

1. windows 上的ssh genkey and public key设置https://www.cnblogs.com/mymhj/p/7263991.html
2. github setting->ssh中new ssh key
3. ssh git@github.com 连接测试出错时，设置host. https://stackoverflow.com/questions/72971645/ssh-connect-to-host-github-com-port-22-connection-timed-out-fatal-could-not-r
4. 本地可以使用git extension管理分支，git extension 不用特殊设置email和密码
5. 下载github仓库使用ssh链接，不适用https

### git set user name and email
在某个仓库目录下设置：
git config user.name ""
git config user.email ""

# anaconda pytorch 安装

1. [查看cuda版本](https://blog.csdn.net/Gabriel_wei/article/details/112595642)
   1. hp zbook 15: cuda 11.7.9
2. 



## conda environment

conda commands:

| conda -V                     |            |
| ---------------------------- | ---------- |
| conda create --name <my-env> | create env |
| conda activate myenv         |            |
| conda env list               |            |
| conda                        |            |
|                              |            |
|                              |            |
|                              |            |
|                              |            |
|                              |            |


## python program guideline

whenever possible, avoid explicit for-loops
