---
description: 在 Android 设备上使用 ShadowsocksR(R) App 接入流量中继服务
---

# ShadowsocksR for Android

| 系统要求： | Android 4.4 及以上 |
| :--- | :--- |
| 软件版本： | ShadowsocksR 最新版 |
| 设备要求： | Android Phone & Tablet |

## 配置订阅节点及使用教程

完成以下三个简单配置步骤，即可享用海豚湾云服务。\(阁下可能需要花5~10分钟左右的时间完成教程\)

{% tabs %}
{% tab title="第一步\(软件安装\)" %}
#### **请使用浏览器打开 海豚湾 用户中心 -查看快速添加节点**

![](../.gitbook/assets/image%20%2823%29.png)

1. 点击下载 Android apk 并安装。
2. 复制订阅地址，配置客户端时需使用。

{% hint style="danger" %}
订阅地址包含您的订阅信息，阁下应当把它当做密码一样妥善保管，请勿泄露给他人！
{% endhint %}

#### 完成以上步骤后，进行第二步。
{% endtab %}

{% tab title="第二步\(节点配置\)" %}
> 打开安装的 ShadowsocksR 应用程序

![](../.gitbook/assets/image%20%288%29.png)

> 然后点击顶部的「ShadowsocksR」区域进入接入点列表。

![](../.gitbook/assets/image%20%2822%29.png)

> 默认有一个「Android SSR Default」的无效连接信息，建议向右滑动将其去除。在接入点列表页面点击底部的「+」按钮，并选择「添加/升级 SSR 订阅」

![](../.gitbook/assets/image%20%2836%29.png)

> 订阅列表中默认有一个「FreeSSR-public」订阅，建议向右滑动将其去除。在弹出的对话框中点击「与节点一起删除」。

![](../.gitbook/assets/image%20%2828%29.png)

> 再次点击接入点列表页面底部的「+」按钮，选择「添加/升级 SSR 订阅」，在订阅列表中点击「添加订阅地址」。

![](../.gitbook/assets/image%20%2838%29.png)

> 长按文本框空白区域，选择「粘贴」，将第一步复制的订阅地址粘贴到文本框中。点击「确定」

![](../.gitbook/assets/image%20%2832%29.png)

> ShadowsocksR 应用程序显示「处理中」。这可能需要一小段时间，具体根据网络情况而定。

{% hint style="warning" %}
更新失败与网络环境有关，多次失败建议 4G、WIFI 环境都尝试更新一下。
{% endhint %}

![](../.gitbook/assets/image%20%2826%29.png)

> 点击「确定并升级」就可以导入最新的 海豚湾 接入点信息并自动更新了。
>
> 建议勾选自动更新。

![](../.gitbook/assets/image%20%2815%29.png)

> ShadowsocksR 应用程序显示「处理中」。下载客户端配置可能需要一小段时间，具体根据网络情况而定。

#### 完成以上步骤后，进行第三步。
{% endtab %}

{% tab title="第三步\(客户端配置\)" %}
#### 在接入中继节点之前，您还需要对客户端进行一些配置。

> 导入接入点信息后，返回到主页面，然后下滑到「功能设置」功能区，打开「UDP 转发」和「IPv6 路由」，并设置「路由」为「绕过局域网和中国大陆地址」。

![](../.gitbook/assets/image%20%2842%29.png)

> 滑动页面到顶部，点击纸飞机图标连接，如果是首次连接，则系统会弹出如下的提示框，请点击「是」

![](../.gitbook/assets/image%20%284%29.png)
{% endtab %}
{% endtabs %}

​



