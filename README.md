## Tips:1
这个版本适用于搭载"Debian 11.11 x64"系统使用
如需Windows版请前往:https://github.com/ssqls666/CS-GO_1155Server
## Tips:2
如有技术支援需求，请添加我的QQ:3148912176 或发送Mail给我的邮箱:ssqls@foxmail.com
## Tips:3
由于Linux问题，开服包不包含Steamcmd,仅包含开服所用到的"插件包" "Server.cfg" "Start.sh"
## Tips:4
开服包下载:
我的个人网盘:http://download.imqfy.qpon/linux/Linux_kaifu.zip
123盘:https://www.123684.com/s/UzIVVv-BNpY

## 配置需求
最低需求:1v核心2GB内存 40Gb可用空间 10Mbps网络带宽 Ipv4公网ip一个 UDP端口正常开放
推荐需求:4v核心8GB内存 60Gb可用空间 50Mbps网络带宽 Ipv4公网ip一个 UDP端口正常开放

## 开始搭建
首先，我们先输入 "sudo apt update" 后回车

<img width="1920" height="1080" alt="7e17dff4809e3a558fc0f3fcd377ff99" src="https://github.com/user-attachments/assets/b6a63ac6-c8e2-4b8d-9a3a-04e60cc72a17" />

然后输入 "sudo apt install software-properties-common" 后回车

<img width="1920" height="1080" alt="8f85ef51b2a14df09739c0a436461f15" src="https://github.com/user-attachments/assets/f5f86c15-d7de-4e41-ab89-5de21e484994" />

然后输入 "sudo apt-add-repository non-free; sudo dpkg --add-architecture i386" 后回车

<img width="1920" height="1080" alt="432dd1a00f66178754085411e7e27d8d" src="https://github.com/user-attachments/assets/ab2c90d7-7193-4901-ab51-8355a824093c" />

接着输入 "sudo apt update" 后回车

<img width="1920" height="1080" alt="f599fec0b479e57a8cf98197e5735507" src="https://github.com/user-attachments/assets/bf54e301-dd5b-448c-869f-3bd5c6b2249d" />

最后我们输入 "sudo apt install steamcmd" 安装SteamCmd

<img width="1920" height="1080" alt="101aa107075023e06c04455733957cc0" src="https://github.com/user-attachments/assets/b6979e8f-f01b-4fc7-b617-ef3499cdd866" />

当提示我们 “您希望继续执行吗？” 的时候输入 "y" 后回车

<img width="1920" height="1080" alt="b4602c5ef142a12977287c752aa7ae24" src="https://github.com/user-attachments/assets/45c4be9b-d5ef-4e15-8c32-45bfb64ad53f" />

当弹出这个界面后，用方向键选择下面的 "<确定>" 后回车

<img width="1920" height="1080" alt="9f6f6d26a77b16324657ea60c134a2dd" src="https://github.com/user-attachments/assets/b075aa89-1663-45d4-8dfe-d62c77f63893" />

当出现这个界面，用方向键选择下面的 "I AGREE" 后回车

<img width="1920" height="1080" alt="c6b7716e602dfa75bfdbd2cd4eb6db96" src="https://github.com/user-attachments/assets/ba8fdd5c-7797-4df7-9b98-44f4510f3045" />

执行完后我们输入 "/usr/lib/games/steam/steamcmd" 后回车

<img width="1920" height="1080" alt="b139b9df3583cd50eefa7613c266997c" src="https://github.com/user-attachments/assets/90d9e347-f6c0-4889-9146-0103326075cf" />

当这个任务执行完后，我们输入 "cd /usr/lib/games" 后回车

<img width="1920" height="1080" alt="8ec30fe4-5747-42c8-9eb1-aa3529561423" src="https://github.com/user-attachments/assets/efb869d1-9bae-4bf8-95f5-e7e4d537009a" />

然后输入 "./steamcmd.sh" 后回车

<img width="1920" height="1080" alt="72fe0ea7-05f7-4e8e-a98a-8dd099d82b46" src="https://github.com/user-attachments/assets/4959d06d-50b8-4d1c-813c-31cfbf5b69f2" />

当前面变成 "Steamcmd>" 的时候，我们输入 "login anonymous"

<img width="1920" height="1080" alt="11308ab1-9ff7-4911-bd63-23ad97a70715" src="https://github.com/user-attachments/assets/1c154a2c-96c3-4d25-a03e-da9e78bb9231" />

等匿名登录完后，我们输入 "app_update 740 validate" 安装CSGO服务端

<img width="1920" height="1080" alt="f0500aee-5735-4ab8-9910-593137255ea7" src="https://github.com/user-attachments/assets/3b574098-2fa5-4452-9188-272e39a4f73d" />

安装完成后 我们输入 "quit" 退出SteamCmd

<img width="1920" height="1080" alt="d578bfa35e44d403dc488b9a33165b99" src="https://github.com/user-attachments/assets/d6110dfe-f005-458c-9ec9-7471ead4a3fb" />

然后输入 "cd /root/Steam/steamapps/common/Counter-Strike\ Global\ Offensive\ Beta\ -\ Dedicated\ Server/"

<img width="1920" height="1080" alt="2c5e311b-9cba-46f3-9b3f-2858fe5e3368" src="https://github.com/user-attachments/assets/c9d68820-23c3-44b8-bb74-f362a305c8a8" />

将插件包中的 "start.sh" 上传到当前目录

<img width="1920" height="1080" alt="8bd366a2-a118-46b5-84fa-18c8d92e17a9" src="https://github.com/user-attachments/assets/2d9bb9d5-26f8-4d22-b17e-cb86e9a4e484" />

使用FinalShell下方的文件管理，打开 "/csgo/cfg" 将 "server.cfg" 放置当前目录

<img width="1920" height="1080" alt="63bd4f59-7691-4d89-b063-515ba9f471b8" src="https://github.com/user-attachments/assets/6debea09-ca1e-47c8-8f36-1fa3f588d962" />

返回到 "/csgo" 将开服包里面的插件包解压,然后把里面的 "addone" 和 "cfg" 文件夹上传到当前目录

<img width="1920" height="1080" alt="443f6653-0204-4791-ba6d-91b30fa2e32b" src="https://github.com/user-attachments/assets/10794475-bbbe-4c87-8689-1d29f666c655" />

最后输入 "cd /root/Steam/steamapps/common/Counter-Strike\ Global\ Offensive\ Beta\ -\ Dedicated\ Server/" 后再执行 "start.sh" 就可以游玩了

<img width="1920" height="1080" alt="9c9901ee-f511-43b3-a4ed-6bf6574bba66" src="https://github.com/user-attachments/assets/16ae810b-7c94-4282-8d04-877b49b3995d" />
<img width="1920" height="1080" alt="d6c8487d-012d-4b1e-9439-b19fff3702e3" src="https://github.com/user-attachments/assets/dbd401ba-0782-48e3-a1a2-1d408ad12b0b" />
<img width="1920" height="1080" alt="b8066075-ba30-4371-8473-4a8f86455da7" src="https://github.com/user-attachments/assets/e940a306-a06e-4901-af3a-8af11be6a8f8" />

## 添加Admin/更改服务器密码/更改服务器名字 Windows那篇教程有

## 结尾

如果你觉得本期教程超级有用，那不妨施舍一点吧QwQ (bushi 
<img width="1037" height="1037" alt="1" src="https://github.com/user-attachments/assets/5af16773-1426-4e8a-b642-81f0d12c272d" />
