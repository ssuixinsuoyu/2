网站时这个：https://github.com/先注册
![[Pasted image 20260605154215.png]]
登陆到这个网站

点击注册
![[Pasted image 20260605154257.png]]

注册完之后

注意：后续如果你是用：
谷歌账号或者苹果账号登录的

注册/登录的，那么这个邮箱只是绑定身份。

 GitHub 登录框里的：

**Username or email address**  
**Password**

这里的 **Password** 指的是：

> GitHub 账号自己的密码  
> 不是 Google 密码，也不是 Apple ID 密码

![[Pasted image 20260605154838.png]]


进入到这个界面：
![[Pasted image 20260605154955.png]]



你的新仓库将会被创建为 `-`。仓库名只能包含 **ASCII 英文字母、数字，以及 `. - _` 这几个符号**。
![[Pasted image 20260605160519.png]]

它通常用于显示你的 GitHub 个人主页介绍。也就是别人打开你的 GitHub 主页时，可能会看到这个仓库里 内容。
![[Pasted image 20260605160918.png]]
![[Pasted image 20260605164046.png]]




Its `README.md` will appear on your public profile.

![[Pasted image 20260605161305.png]]

|            |     |                  |
| ---------- | --- | ---------------- |
| **public** | 公开  | 互联网上任何人都可以看到这个仓库 |
|            |     |                  |

|   |   |   |
|---|---|---|
|**Private**|私密|只有你自己，或者你邀请的人能看到|

**Add README** 的意思是：

> **添加一个 README 文件。**

这个仓库的说明书 / 首页介绍文件
展示这个仓库是用来干嘛的？

|选择|结果|
|---|---|
|勾选 **Add README**|GitHub 会自动帮你创建一个 `README.md` 文件|
|不勾选|仓库创建后是空的，需要你自己再添加文件|
建议勾选。





![[Pasted image 20260605162222.png]]
`.gitignore` 可以理解成：

> **告诉 GitHub：哪些文件不要记录、不要上传。**

|文件类型|为什么不上传|
|---|---|
|临时文件|没价值|
|缓存文件|自动生成，没必要|
|密码配置文件|有安全风险|
|系统文件|和项目无关|
|大量依赖文件|太多、太乱|
保持就行了


**![[Pasted image 20260605162828.png]]
**Add license** 的意思是：

> **添加开源许可证。**
把代码或项目内容公开出来，让别人可以查看、学习、使用、修改，甚至参与改进。


| 情况                     | 意思                        |
| ---------------------- | ------------------------- |
| **No license**         | 没有明确授权，别人不能随便拿去用          |
| **MIT License**        | 很宽松，别人可以使用、修改、传播，但要保留版权说明 |
| **Apache License 2.0** | 也比较宽松，常用于代码项目             |
| **GPL License**        | 别人可以用，但改了之后也要开源           |
|                        |                           |

![[Pasted image 20260605164535.png]]![[Pasted image 20260605164725.png]]

|页面内容|中文意思|作用|
|---|---|---|
|**ssuixinsuoyu / 2**|用户名 / 仓库名|说明你现在在 `2` 这个仓库里|
|**Public**|公开|这个仓库现在别人可以看到|
|**main**|主分支|正式版本|
|**README.md**|说明文件|你刚才创建仓库时自动生成的文件|
|**Initial commit**|初始提交|创建仓库时 GitHub 自动保存的第一次记录|
|**Code**|代码/文件按钮|以后下载、复制仓库会用到|
|**+**|添加文件|可以新建文件或上传文件|

| 部分         | 意思            |
| ---------- | ------------- |
| **README** | 读我 / 说明文档     |
| **.md**    | Markdown 文件格式 |
**Markdown** 是一种很简单的**写作格式**。

它的作用是：

> 用普通文字，加上一些简单符号，让文字变成有标题、列表、加粗、链接等格式。

![[Pasted image 20260605165056.png]]

![[Pasted image 20260605170230.png]]

|英文|中文|
|---|---|
|**Create new file**|创建新文件|
|**Upload files**|上传文件|


![[Pasted image 20260605170315.png]]


|位置|英文|中文|作用|
|---|---|---|---|
|上方输入框|**Name your file...**|给文件命名|这里写文件名|
|中间大白框|**Enter file contents here**|输入文件内容|这里写正文|
|右上角绿色按钮|**Commit changes...**|提交更改|保存这个新文件|


这里的 `.md` 表示 Markdown 文件，适合写日记、笔记、文章。

![[Pasted image 20260605171330.png]]

|按钮|中文|结果|
|---|---|---|
|**Cancel changes**|取消更改|放弃，不保存|
|**Commit changes...**|提交更改|正式保存到 GitHub|

![[Pasted image 20260605171543.png]]![[Pasted image 20260605171618.png]]

创建仓库 → 创建文件 → 写内容 → Commit 保存


![[Pasted image 20260605172000.png]]

|英文|中文|作用|
|---|---|---|
|**Preview**|预览|用排版后的样子看 Markdown 文件|
|**Code**|代码/源码|看原始 Markdown 写法|
|**Blame**|追踪修改记录|看每一行是谁、什么时候改的|


![[Pasted image 20260605172338.png]]
![[Pasted image 20260605172401.png]]
![[Pasted image 20260605173526.png]]

![[Pasted image 20260605173857.png]]

| 图标 / 英文   | 中文                     | 作用           |
| --------- | ---------------------- | ------------ |
| 文件夹/箭头图标  | 打开相关编辑环境               | 进阶功能，新手先不用   |
| 小机器人/头像图标 | GitHub AI / Copilot 相关 | AI 辅助功能，先不用  |
| **Raw**   | 原始内容                   | 用纯文本形式打开这个文件 |
| 两个方框图标    | 复制                     | 复制文件内容       |
| 向下箭头      | 下载                     | 把这个文件下载到电脑   |
| **铅笔图标**  | 编辑                     | 修改这个文件       |
| 小三角       | 更多操作                   | 其他高级操作       |


|英文|中文|作用|
|---|---|---|
|**Edit file...**|编辑文件|修改这个文件|
|**In place**|在当前网页里编辑|最适合你现在用|
|**Open with github.dev**|用 GitHub 网页版 VS Code 打开|进阶，不用|
|**GitHub Desktop**|用 GitHub 桌面软件打开|进阶，不用|
![[Pasted image 20260605174004.png]]**Indent mode**  
= **缩进模式**

它控制的是：

> 你按 **Tab** 键时，编辑器用什么方式来缩进。

## 缩进是什么？

缩进就是一行文字前面空出来的距离。

比如：

```
- 第一层  - 第二层
```

第二层前面多了两个空格，这就叫**缩进**。

## Indent mode 一般有两种

|英文|中文|意思|
|---|---|---|
|**Spaces**|空格缩进|用几个空格来缩进|
|**Tabs**|Tab 缩进|用 Tab 符号来缩进|

你之前看到的：

**Spaces 2**

意思是：

> 缩进模式是空格，每次缩进用 2 个空格

![[Pasted image 20260605174531.png]]

|英文|中文|作用|
|---|---|---|
|**Commit changes**|提交更改|保存这次修改|
|**Commit message**|提交说明|简单写这次改了什么|
|**Add new line about creating another video**|添加了一行关于创建另一个视频的内容|GitHub/Copilot 自动生成的提交说明|
|**Extended description**|详细说明|可选，不用填|
|**Commit directly to the main branch**|直接提交到 main 主分支|直接保存到正式版本|
|**Create a new branch for this commit and start a pull request**|创建新分支并发起合并请求|进阶操作，新手不用|
|**Cancel**|取消|不提交，返回|
|**Commit changes**|提交更改|确认保存|


![[Pasted image 20260605181651.png]]现在你点中间的仓库名：

> **2**

或者点上方左侧的：

> **Code**

都可以回到仓库主页。


![[Pasted image 20260605182121.png]]## 上半部分：选择要上传的文件

这里写着：

**Drag files here to add them to your repository**  
= 把文件拖到这里，添加到你的仓库

**Or choose your files**  
= 或者选择你的文件

你现在有两种方式：

|方法|怎么做|
|---|---|
|拖拽上传|把电脑里的文件直接拖到这个大框里|
|选择上传|点蓝色的 **choose your files**，从电脑里选文件|

## 你现在先做这一步

点：

> **choose your files**

然后从电脑里随便选一个测试文件，比如：

```
test.txt
```

或者一个 Markdown 文件：

```
second-diary.md
```


![[Pasted image 20260605182339.png]]**Commit changes**  
= 提交更改 / 保存上传

这里默认会写：

**Add files via upload**  
= 通过上传添加文件

你可以不改。

下面保持默认：

**Commit directly to the main branch**  
= 直接提交到 main 主分支

然后点左下角绿色按钮：

**Commit changes**

这一步的意思是：

> 把你刚刚选的电脑文件，正式保存到 GitHub 仓库里。