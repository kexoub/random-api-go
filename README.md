<center style="font-size: 50px"><b>random-api-go</b></center>
<h1> 介绍</h1>

<p align="center">
  <img src="https://count.moeyy.cn/get/@:random-api-go alt=":random-api-go" />
<p>random-api-go 是一个基于 Golang 的随机图片API。</p>
<h1> 安装</h1>
从<a href="https://github.com/wuliya336/random-api-go/releases">发布页面</a>下载对应平台的压缩包并上传至服务器，解压后运行即可。
<h1> 使用</h1>

<h2> Windows</h2>

<h3>方式一</h3>
切换到解压后的目录，输入以下命令：

```
random-api-go.exe
```
<h3>方式二</h3>
切换到解压后的目录,双击打开`.exe`文件。
<h2> Linux</h2>
切换到解压后的目录，输入以下命令：

```
random-api-go.exe
```
<h1>用法</h1>
API配置在config/api.json中
修改端口需要在启动的时候指定-port参数，如：

```
random-api-go.exe -port=8080
```
API参数
id: 随机图片ID
naem；随机图片的名称
alias: 随机图片的别名
这个三选一
type: 随机图片的类型，可选值有：img|json ,默认为img
num: 随机图片数量，默认为1,仅在`type=json`时有效
<h1>示例</h1>

```
http://localhost:33699/api?id=1
```