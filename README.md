# Claude Code配置教程

售后无忧，量大优惠

适配VS Code For Claude Code（包含Trae，Trae CN，Vs code，Cursor），Claude Code CLI，[Claude Desktop](https://vcnibslwmu5u.feishu.cn/wiki/UAYcwIdEUijmL2k2DxPcvjq1n3b)

## 零、获取令牌（即API Key）

第一步：访问 [https://devaicode.dev](https://devaicode.dev/)

第二步：注册

第三步：登陆

第四步：点击钱包管理（https://devaicode.dev/console/topup）

第五步：输入发货的激活码

第六步：创建api key，api key分组选择default（https://devaicode.dev/console/token）

**不用开启模型限制**

![img](https://vcnibslwmu5u.feishu.cn/space/api/box/stream/download/asynccode/?code=ZDFkNWQwZmQzMjA4NWJlNTMxNWVjOTZjNDgxOGMzMGZfU1EwOWdPTVo0bXdGQkVLRW5iM1lSZGNCd1F1ODc5WGVfVG9rZW46WEtSWGJFUnNUb09QVlF4NkR5Z2N3RFc2bnhmXzE3ODI5MDI2NTI6MTc4MjkwNjI1Ml9WNA&add_watermark=true&scene_type=CCM)

## 一、未安装 claude code

## 1.终端版本（这三个版本，三选一即可）

步骤一：确保 [Node.js](https://nodejs.org/en/download) 版本 ≥ 18.0，安装 [Git Bash](https://git-scm.com/install/windows) 。如果未安装，请先安装

步骤二：安装 Claude Code

```Bash
npm install -g @anthropic-ai/claude-code
claude --version
```

成功安装如下后：

![img](https://vcnibslwmu5u.feishu.cn/space/api/box/stream/download/asynccode/?code=OGU0MWU0NGNkZWRlN2UyNDBjMTgzYmU4YzIzZDQ0OTFfZ3Z6RXhjamNld3l2WkVGdEc3N3lVQW9jZXFFeVJrazdfVG9rZW46SFR6amJuQkRGb3Zjczd4alNOWWNOaU1ObnRoXzE3ODI5MDI2NTI6MTc4MjkwNjI1Ml9WNA&add_watermark=true&scene_type=CCM)

## 2.VS Code/Cursor/Trae插件版本

步骤一：安装 [Git Bash](https://git-scm.com/install/windows)

步骤二：然后插件市场（快捷键Ctrl+Shift+X）搜索Claude Code for VS Code安装

![img](https://vcnibslwmu5u.feishu.cn/space/api/box/stream/download/asynccode/?code=ZjI1YmM1OWM4YjIwYzMxMGJkOTg4ODQ1ZGU3ZWUzZGZfWDBsU3dQZGNIbnJBV3BVV29NbW9NZG5DSElLU29OMzFfVG9rZW46UUM0T2JHdFpHb1FZRnB4VDJOcWNLU1dBbnViXzE3ODI5MDI2NTI6MTc4MjkwNjI1Ml9WNA&add_watermark=true&scene_type=CCM)

## 3.Claude Desktop配置教程：[Claude Desktop配置教程](https://vcnibslwmu5u.feishu.cn/wiki/UAYcwIdEUijmL2k2DxPcvjq1n3b)

## 二、已安装claude code

### 方式1（推荐）

#### 安装并打开一键配置工具 [cc-swtich](https://github.com/farion1231/cc-switch/releases)

国内直连安装包： [Mac](https://1820236347.share.123pan.cn/123pan/7Dsojv-Dszp?pwd=K1xO#) |  [Win](https://1820236347.share.123pan.cn/123pan/7Dsojv-dQQf?pwd=2lAp#) 

第一步：

供应商名称选择Claude ，然后点击右侧“+”号

![img](https://vcnibslwmu5u.feishu.cn/space/api/box/stream/download/asynccode/?code=NjA1MzNiYTkzOGQ3NzhhOTc2MDBmOTQxYjIxOWIyNWFfN3lKTVVyYmFpaXh0NXdRa1ZpT3J5bzNxRFBMR0F2S1FfVG9rZW46TGN5RGIyNzVkb0lHN1N4S2l2bGN5cndEbndkXzE3ODI5MDI2NTI6MTc4MjkwNjI1Ml9WNA&add_watermark=true&scene_type=CCM)

第二步（图片可放大）：

预设供应商：选择自定义配置

供应商名称：自拟

API Key：即刚刚创建的令牌，访问获取https://devaicode.dev/console/token

请求地址：https://devaicode.dev

无需填写模型id

![img](https://vcnibslwmu5u.feishu.cn/space/api/box/stream/download/asynccode/?code=ZTY1ZjJlMTlhMmQzZGNjNWE1YzYzYTcxYmNlMWYzMThfWnVpaE9VUFdpenRGYVk4dWYzVmZ3NEtYZVEwcEJVT2dfVG9rZW46U0swaGJKWEJDb2k1S0h4YThpcGNjcTRkbjlmXzE3ODI5MDI2NTI6MTc4MjkwNjI1Ml9WNA&add_watermark=true&scene_type=CCM)

确认之后，检测是否连接成功

![img](https://vcnibslwmu5u.feishu.cn/space/api/box/stream/download/asynccode/?code=MTMxZjhmMGYyNTg0YTQ0ZjEzZDI3NDZhMzNiNmVjZDRfZFJiUFZmYkR6ckhNU0xKYXp2WGdSbXZXanFSN0kxb0ZfVG9rZW46Q3hoRWJVSjJDb3pvc1l4ZTVHbWNseVJUbkdkXzE3ODI5MDI2NTI6MTc4MjkwNjI1Ml9WNA&add_watermark=true&scene_type=CCM)

![img](https://vcnibslwmu5u.feishu.cn/space/api/box/stream/download/asynccode/?code=MmYxNjBlMDBjNTZlZWViMzM5MjM3YzllZmRkMjNmNTdfUFhUVXduRE1IczRRRkU2ZW1HbnFza2dhOTZNV1JrYWZfVG9rZW46QlFWQWJUQ0VWb3B1NmF4aEwxamNzSFlGbk9nXzE3ODI5MDI2NTI6MTc4MjkwNjI1Ml9WNA&add_watermark=true&scene_type=CCM)

测试成功后，点击左上角“设置”图标

![img](https://vcnibslwmu5u.feishu.cn/space/api/box/stream/download/asynccode/?code=OGE1OWRkNzcxMGExM2VkZDY3NWExODFhZjNhNzRlZWZfZ0J0NmxOaHdORDlCTjMxWWs5czRJd25tMkhmRmlTandfVG9rZW46TXdJUWJNRUUwbzdVVTd4VTBMQWNldlFnbmdmXzE3ODI5MDI2NTI6MTc4MjkwNjI1Ml9WNA&add_watermark=true&scene_type=CCM)

开启“跳过 Claude Code 初次安装确认”

![img](https://vcnibslwmu5u.feishu.cn/space/api/box/stream/download/asynccode/?code=MjE3NjJkOWM0YzdiZGQxNTM5ODMwMDkwMzg4YzAzNzRfUTZoM0t0ZmZuRlI1c0VDNTJJWW11QjVUTEp0bWZqR0hfVG9rZW46QXlQb2I5cjhUb1A0M1N4UEJoM2NSNHhkblJmXzE3ODI5MDI2NTI6MTc4MjkwNjI1Ml9WNA&add_watermark=true&scene_type=CCM)

### 方式2

#### Windows

#### 把 `ANTHROPIC_AUTH_TOKEN` 换成你刚刚创建的KEY（密钥） 

##### Powershell

```JSON
$dir = "$env:USERPROFILE\.claude"
New-Item -ItemType Directory -Force -Path $dir | Out-Null
@'
{
  "env": {
    "ANTHROPIC_BASE_URL": "https://devaicode.dev",
    "ANTHROPIC_AUTH_TOKEN": "替换这里"
  }
}
'@ | Set-Content -Path "$dir\settings.json" -Encoding utf8
```

##### CMD

```Bash
mkdir "%USERPROFILE%\.claude" 2>nul & (
echo {
echo   "env": {
echo     "ANTHROPIC_BASE_URL": "https://devaicode.dev",
echo     "ANTHROPIC_AUTH_TOKEN": "替换这里"
echo   }
echo }
) > "%USERPROFILE%\.claude\settings.json"
```

#### Mac/Linux（适用于服务器）

把 `ANTHROPIC_AUTH_TOKEN` 换成你刚刚创建的KEY（密钥）

```Bash
mkdir -p ~/.claude && cat > ~/.claude/settings.json << 'EOF'
{
  "env": {
    "ANTHROPIC_BASE_URL": "https://devaicode.dev",
    "ANTHROPIC_AUTH_TOKEN": "替换这里"
  }
}
EOF
```

## 三、启动claude code

### 终端版本：

在终端或者cmd输入claude ，回车启动。

```Bash
claude
```

如图显示则为配置成功

![img](https://vcnibslwmu5u.feishu.cn/space/api/box/stream/download/asynccode/?code=NjE1NWY3ZWFjYTYyN2ZkYmIyNGFjNTkyYWRkNDA5OWZfQkM1WlNZd1ZZRVFBc01MNG5JSkhlcE5keWlqZFdvdTJfVG9rZW46SlkwQWJ2aTJZb2RpZUF4aElseGNhT1pqbjhJXzE3ODI5MDI2NTI6MTc4MjkwNjI1Ml9WNA&add_watermark=true&scene_type=CCM)

如果没有配置成功，请重启终端，重新输入命令

### 插件版本：

点击侧边栏的Claude图标

![img](https://vcnibslwmu5u.feishu.cn/space/api/box/stream/download/asynccode/?code=YzkxYzM2MWMzYjBiYmFhNTUwYWNkYTY3NmY3MDAzMGJfbmdxRmlxRUtRRlpvQm5YQWlVZ1pWc2hSWnZxeTlPeHhfVG9rZW46VnNoRmJ6Z2w2b2xjNlF4a1p6dWNSZmVhbnprXzE3ODI5MDI2NTI6MTc4MjkwNjI1Ml9WNA&add_watermark=true&scene_type=CCM)

如图显示则为配置成功

![img](https://vcnibslwmu5u.feishu.cn/space/api/box/stream/download/asynccode/?code=NWJlYzZjMjIwMjdmMDg3YzllOGYxNGY3ZDk1MDM1NDlfNVVjbHpLbGVtT2ZtQXhqSjYzZ2JWRHVIbE1pM25XbUhfVG9rZW46VnhQR2JIZmhqbzk4cnZ4ODdvbWN5ZGhrbm1vXzE3ODI5MDI2NTI6MTc4MjkwNjI1Ml9WNA&add_watermark=true&scene_type=CCM)

如图显示则为配置失败

![img](https://vcnibslwmu5u.feishu.cn/space/api/box/stream/download/asynccode/?code=MTNjNmZmMzAzNjRmNDg3YjNjNGMxMjliZmM1YTA2MjlfdVcyVzJzQXhMcDYyNEF0SEoyempOTHNHVmhSamZ0dHdfVG9rZW46UkZKUGJjS0hvb0ExbW14c1hYa2NhQUtlbnpoXzE3ODI5MDI2NTI6MTc4MjkwNjI1Ml9WNA&add_watermark=true&scene_type=CCM)

如果配置失败

找到 ~/.claude 目录，在目录下创建config.json，路径为~/.claude/config.json

```Bash
{
    "primaryApiKey": "api"
}
```

然后 重启VScode/Cursor/Trae，重试

## 四、其他软件适配

### 1.Trae

选择自定义配置，然后如图所示配置

API格式：Anthropic Messages 格式

自定义请求地址：https://devaicode.dev

模型ID ：claude-sonnet-5

API密钥：即刚刚创建的令牌，访问获取https://devaicode.dev/console/token

![img](https://vcnibslwmu5u.feishu.cn/space/api/box/stream/download/asynccode/?code=NTAyMWU5OWY1OGU4ZTljN2JlMTMyZDEwYzI5ZmM0YWJfNkJaTUxFbkh2eWpzNGVzdXV4WTgxMHk4UkprMzF3a3ZfVG9rZW46SmxwTGJkTll0b2N1R1h4R21OVmNHcmRqbmtnXzE3ODI5MDI2NTI6MTc4MjkwNjI1Ml9WNA&add_watermark=true&scene_type=CCM)

### 2.codeboddy

提供商：自定义

接口地址：https://devaicode.dev/v1

API KEY：即刚刚创建的令牌，访问获取https://devaicode.dev/console/token

模型名称：claude-sonnet-5

勾选。 工具调用，图片输入，推理模式

![img](https://vcnibslwmu5u.feishu.cn/space/api/box/stream/download/asynccode/?code=ZDE5NjQ5ZDA1NzBiMDQ5ODY5MGYwMTE5NjA3MmNmMDZfMkxLSFJHalpDd3h5dzJVc1Izd3g2b1B2V0hHaEFraDBfVG9rZW46WGJIZGJiN2M3b0NIdFV4VWliSGNUWlI4bkJmXzE3ODI5MDI2NTI6MTc4MjkwNjI1Ml9WNA&add_watermark=true&scene_type=CCM)

### 3.Chatbox

![img](https://vcnibslwmu5u.feishu.cn/space/api/box/stream/download/asynccode/?code=YzcwMTZmOWMwNDllNTRmZmUxYzMwN2E3NjI0M2IyNThfcXY3NE45dWdDc3lMOEFaZ2cyTDVpclJWZmtnWTNWbVBfVG9rZW46QjNWcGJUVG9ob2tGSDJ4WFNxeWMySjM1bk1kXzE3ODI5MDI2NTI6MTc4MjkwNjI1Ml9WNA&add_watermark=true&scene_type=CCM)

### 4.OpenClaw

下载新版cc-switch

官方下载链接：

cc-switch 下载地址： https://github.com/farion1231/cc-switch/releases 

国内直连：

cc-switch：[Win](https://1820236347.share.123pan.cn/123pan/7Dsojv-4JTf?pwd=uaXB#)｜[Mac](https://1820236347.share.123pan.cn/123pan/7Dsojv-uA2p?pwd=TE6G#)

![img](https://vcnibslwmu5u.feishu.cn/space/api/box/stream/download/asynccode/?code=NjI4M2YxZGQ4NmFlOTRiOTM5OTJlYjhmOWY4NmFiNWJfQVJtREJiMnRUcDVHTVdWalJKNjJmcjI3aE83V0FtQmNfVG9rZW46WjE2WGJBbk5vb2x3WFp4ajBIZGNPWjlkbnViXzE3ODI5MDI2NTI6MTc4MjkwNjI1Ml9WNA&add_watermark=true&scene_type=CCM)

下一步

供应商标识：随机填写

供应商名称：随机填写

API协议：Anthropic Messages

API端点：https://devaicode.dev/v1

API Key：即刚刚创建的令牌，访问获取https://devaicode.dev/console/token

![img](https://vcnibslwmu5u.feishu.cn/space/api/box/stream/download/asynccode/?code=ZTI2ODRjZDRjMTc4ODFjMTU1NGFmMjZjM2Q5NWQ5MWRfMWpaMXozdkloMnd2b2tTQ1JadnBYZmFIN2xaQlo3N3NfVG9rZW46WkxMVmJ1VnF4b1J4aEZ4SzB0TmMzbDdsbkZkXzE3ODI5MDI2NTI6MTc4MjkwNjI1Ml9WNA&add_watermark=true&scene_type=CCM)

下一步，选择模型

![img](https://vcnibslwmu5u.feishu.cn/space/api/box/stream/download/asynccode/?code=MTA0ZTMyYmE0ZGViNDE4ZGRhODQ1ZTUxNjIyYTkxZDRfMDB5MDZIOHV3c0RISm91NVFRTVVIM1JWZ1ZLWkoxMnpfVG9rZW46SEg2RGJ0WDRnbzFPTHF4THFxQWN1djRkbnliXzE3ODI5MDI2NTI6MTc4MjkwNjI1Ml9WNA&add_watermark=true&scene_type=CCM)

保存

## 五、其他地方调用（通用调用）

Anthropic协议

URL：https://devaicode.dev/v1/messages 或 https://devaicode.dev 或 https://devaicode.dev/v1

（需根据自己软件判断）

Key：填自己的（"sk-"开头）

Model：claude-opus-4-8 或 claude-sonnet-5

## 六、常见问题（FAQ）

### 1.如何选择模型？

对话框输入“/model”，可以选择模型。

```Bash
/model
```

### 2.为什么我选择了sonnet/opus，还是调用了haiku？

**主模型（你选的 Sonnet/Opus）**：负责核心代码生成、复杂推理、长对话

**辅助模型（固定 Haiku）**：专门做**文件扫描、代码摘要、会话总结、状态检查、快速工具调用**等轻量后台任务

### 3.遇到504报错如何解决？

关闭VPN，直连使用即可恢复

### 4.遇到400报错如何解决？

#### 类型一

错误例如：status_code=400, invalid params, function name or parameters is empty (2013)

![img](https://vcnibslwmu5u.feishu.cn/space/api/box/stream/download/asynccode/?code=ZDBiNWZhNDcyYTFhYzM3ODk5YTlhYzRiMjkwYjg3ZDNfQ1JodFpNTFpUZUZvbGxhYzk1aTk2SzRsMWJDYllHTVRfVG9rZW46T2NiTGJhZTFsb29UbUJ4YU9LRGNxVVB2bmJlXzE3ODI5MDI2NTI6MTc4MjkwNjI1Ml9WNA&add_watermark=true&scene_type=CCM)

答：新建一个窗口重新进行对话并减少websarch调用

因：因Claude Code 调用了 websearch，但是本店主打性价比，低价渠道供应商暂不支持websarch，即使缺失这个功能，不影响正常使用。

#### 类型二

status_code=400, invalid params, context window exceeds limit (2013)

对话框输入“/compact”，压缩上下文即可

```Bash
/compact
```

### **5.是否会售卖客户聊天数据？**

本店承诺永不保存，永不售卖客户聊天数据，永远尊重个人隐私！！！
