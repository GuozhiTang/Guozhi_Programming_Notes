# 1.6 Node.js Installation

## For Windows \(.msi\):

### 1. Installation

* Node.js 安装包及源码下载地址为：

{% embed url="https://nodejs.org/en/download/" %}

*  双击下载后的安装包，如下所示：

![](../../.gitbook/assets/1%20%281%29.png)

*  点击以上的Run\(运行\)，将出现如下界面：

![](../../.gitbook/assets/install-node-msi-version-on-windows-step2.png)

*  勾选接受协议选项，点击 next（下一步） 按钮 :

![](../../.gitbook/assets/install-node-msi-version-on-windows-step3.png)

*  Node.js默认安装目录为 "C:\Program Files\nodejs\" , 你可以修改目录，并点击 next（下一步）：

![](../../.gitbook/assets/install-node-msi-version-on-windows-step4.png)

*  点击树形图标来选择你需要的安装模式 , 然后点击下一步 next（下一步）：

![](../../.gitbook/assets/install-node-msi-version-on-windows-step5.png)

*  点击 Install（安装） 开始安装Node.js。你也可以点击 Back（返回）来修改先前的配置。 然后并点击 next（下一步）：

![](../../.gitbook/assets/install-node-msi-version-on-windows-step6.png)

*  安装过程：

![](../../.gitbook/assets/install-node-msi-version-on-windows-step7.png)

*  点击 Finish（完成）按钮退出安装向导：

![](../../.gitbook/assets/install-node-msi-version-on-windows-step8.png)

### 2. PATH Configuration

 检测PATH环境变量是否配置了Node.js，点击开始=》运行=》输入"cmd" =&gt; 输入命令"path"，输出如下结果：

```bash
PATH=C:\oraclexe\app\oracle\product\10.2.0\server\bin;C:\Windows\system32;
C:\Windows;C:\Windows\System32\Wbem;C:\Windows\System32\WindowsPowerShell\v1.0\;
c:\python32\python;C:\MinGW\bin;C:\Program Files\GTK2-Runtime\lib;
C:\Program Files\MySQL\MySQL Server 5.5\bin;C:\Program Files\nodejs\;
C:\Users\rg\AppData\Roaming\npm
```

![](../../.gitbook/assets/image%20%2815%29.png)

### 3. Version

![](../../.gitbook/assets/image%20%2867%29.png)

## For MacOS：

### 1. Use .pkg to Install

* 通过官网下载

{% embed url="https://nodejs.org/en/download/" %}

### 2. Use brew to Install

```bash
brew install node
```

