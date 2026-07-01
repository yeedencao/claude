<img width="829" height="546" alt="image" src="https://github.com/user-attachments/assets/d6667b8d-bf8a-4970-9136-6282132aed65" /># Claude Code配置教程

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

<img width="484" height="1021" alt="image" src="https://github.com/user-attachments/assets/e15d23b0-549b-4c72-a6df-81faef487fc4" />


## 一、未安装 claude code

## 1.终端版本（这三个版本，三选一即可）

步骤一：确保 [Node.js](https://nodejs.org/en/download) 版本 ≥ 18.0，安装 [Git Bash](https://git-scm.com/install/windows) 。如果未安装，请先安装

步骤二：安装 Claude Code

```Bash
npm install -g @anthropic-ai/claude-code
claude --version
```

成功安装如下后：

<img width="614" height="332" alt="image" src="https://github.com/user-attachments/assets/cb6af157-4340-40f3-8c4c-d67bf51b7a3a" />


## 2.VS Code/Cursor/Trae插件版本

步骤一：安装 [Git Bash](https://git-scm.com/install/windows)

步骤二：然后插件市场（快捷键Ctrl+Shift+X）搜索Claude Code for VS Code安装



## 3.Claude Desktop配置教程：[Claude Desktop配置教程](https://vcnibslwmu5u.feishu.cn/wiki/UAYcwIdEUijmL2k2DxPcvjq1n3b)

## 二、已安装claude code

### 方式1（推荐）

#### 安装并打开一键配置工具 [cc-swtich](https://github.com/farion1231/cc-switch/releases)

国内直连安装包： [Mac](https://1820236347.share.123pan.cn/123pan/7Dsojv-Dszp?pwd=K1xO#) |  [Win](https://1820236347.share.123pan.cn/123pan/7Dsojv-dQQf?pwd=2lAp#) 

第一步：

供应商名称选择Claude ，然后点击右侧“+”号

<img width="827" height="99" alt="image" src="https://github.com/user-attachments/assets/abfa1678-cf1c-43e5-bedc-a6dc0031f4d7" />


第二步（图片可放大）：

预设供应商：选择自定义配置

供应商名称：自拟

API Key：即刚刚创建的令牌，访问获取https://devaicode.dev/console/token

请求地址：https://devaicode.dev

无需填写模型id

<img width="1427" height="752" alt="image" src="https://github.com/user-attachments/assets/fcf52898-a1dc-4dd4-85be-8ac7f82508c1" />


确认之后，检测是否连接成功

<img width="825" height="573" alt="image" src="https://github.com/user-attachments/assets/11105152-558c-414d-b2fe-488e7fd87251" />


<img width="820" height="574" alt="image" src="https://github.com/user-attachments/assets/a438584e-0bae-475d-92d7-7c795ef519eb" />


测试成功后，点击左上角“设置”图标

<img width="824" height="574" alt="image" src="https://github.com/user-attachments/assets/d0d66a6a-b11d-4dd5-ac27-6045734df525" />


开启“跳过 Claude Code 初次安装确认”

<img width="826" height="534" alt="image" src="https://github.com/user-attachments/assets/d8248b7c-4653-42ad-acdb-103ee929136b" />


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

<img width="817" height="459" alt="image" src="https://github.com/user-attachments/assets/95569cfa-59c5-42d1-8429-a412778b5e26" />


如果没有配置成功，请重启终端，重新输入命令

### 插件版本：

点击侧边栏的Claude图标

<img width="38" height="250" alt="image" src="https://github.com/user-attachments/assets/4ae9ebd5-5a71-46ba-ae62-4af95fa82939" />


如图显示则为配置成功

<img width="489" height="444" alt="image" src="https://github.com/user-attachments/assets/0759d450-7b02-4d18-96d7-61b1939afc61" />


如图显示则为配置失败

<img width="228" height="536" alt="image" src="https://github.com/user-attachments/assets/61e37a8c-09a6-47f7-8a33-0b3e42d60cb8" />


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

<img width="502" height="560" alt="image" src="https://github.com/user-attachments/assets/2ae2a31e-24ce-45f4-a556-dd56d0a13a13" />


### 2.codeboddy

提供商：自定义

接口地址：https://devaicode.dev/v1

API KEY：即刚刚创建的令牌，访问获取https://devaicode.dev/console/token

模型名称：claude-sonnet-5

勾选。 工具调用，图片输入，推理模式

<img width="816" height="542" alt="image" src="https://github.com/user-attachments/assets/b27be0f7-ef29-4dc8-98c8-8ac06e039af7" />


### 3.Chatbox

<img width="822" height="615" alt="image" src="https://github.com/user-attachments/assets/5d6e6cfe-1b07-4352-b033-c9cdb5481cc6" />


### 4.OpenClaw

下载新版cc-switch

官方下载链接：

cc-switch 下载地址： https://github.com/farion1231/cc-switch/releases 

国内直连：

cc-switch：[Win](https://1820236347.share.123pan.cn/123pan/7Dsojv-4JTf?pwd=uaXB#)｜[Mac](https://1820236347.share.123pan.cn/123pan/7Dsojv-uA2p?pwd=TE6G#)

<img width="821" height="534" alt="image" src="https://github.com/user-attachments/assets/e0dffaeb-17a8-491a-8dc2-6292c85b61c6" />


下一步

供应商标识：随机填写

供应商名称：随机填写

API协议：Anthropic Messages

API端点：https://devaicode.dev/v1

API Key：即刚刚创建的令牌，访问获取https://devaicode.dev/console/token

<img width="829" height="546" alt="image" src="https://github.com/user-attachments/assets/a0927226-99dd-4af4-b0ea-44145df9d7f0" />


下一步，选择模型

<img width="825" height="543" alt="image" src="https://github.com/user-attachments/assets/1f098377-bae3-4e04-ad72-d15094ad2a0d" />


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

<img width="821" height="33" alt="image" src="https://github.com/user-attachments/assets/590af5bb-6b8b-422c-b077-dd99465f0ea4" />


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
