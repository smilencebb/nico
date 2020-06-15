---
description: 在 iOS 设备上使用 Shadowrocket 接入流量中继服务
---

# Shadowrocket\(小火箭\)

| 系统要求： | iOS 9.0及以上  |
| :--- | :--- |
| 设备要求： | iPhone、iPad & iPod touch |

## 配置订阅节点及使用教程

完成以下三个简单配置步骤，即可享用海豚湾云服务。\(阁下可能需要花5~10分钟左右的时间完成教程\)

{% tabs %}
{% tab title="第一步\(软件安装\)" %}
#### 请使用浏览器打开 海豚湾 用户中心 -查看快速添加节点

![](../../.gitbook/assets/image%20%2826%29.png)

1. 此软件已从国区 App Store 下架，请自备账户从非国区下载
2. 复制订阅地址，配置客户端时需使用。

{% hint style="danger" %}
订阅地址包含您的订阅信息，阁下应当把它当做密码一样妥善保管，请勿泄露给他人！
{% endhint %}

#### 完成以上步骤后，进行第二步。
{% endtab %}

{% tab title="第二步\(节点配置\)" %}
> 打开 Shadowrocket 点击右上角的 加号。

![](../../.gitbook/assets/image%20%288%29.png)

> 类型选择「Subscribe」，在 URL 里粘贴刚刚复制的链接，点击右上角「完成」 。

![](../../.gitbook/assets/image%20%2822%29.png)

> 返回首页后向左滑动点击「更新」，更新节点列表。

![](../../.gitbook/assets/image%20%2836%29.png)

> 此时显示更新中，这可能需要一小段时间，具体根据网络情况而定。等待更新完成后回到首页即可看见您的所有节点。

![](../../.gitbook/assets/image%20%2824%29.png)

#### 完成以上步骤后，进行第三步。
{% endtab %}

{% tab title="第三步\(客户端配置\)" %}
> 节点前有黄色小点表示选中状态。

> 因为 iOS 设备无法提供分应用代理类似的设定，我们需要进行以下步骤实现国内外流量分流。
>
> 点击最下方的配置项

![](../../.gitbook/assets/image%20%2828%29.png)

> 点击「远程文件」下方的「添加配置」。

```text
海豚湾 提供下列配置文件，请长按或者右键复制链接。
```

\*\*\*\*[**https://config.hitun.life/lhie1/Rules/master/Shadowrocket/Complete.conf**](https://config.hitun.life/lhie1/Rules/master/Shadowrocket/Complete.conf) ****

粘贴配置文件地址到客户端中，点击下载。

![](../../.gitbook/assets/image%20%2844%29.png)

> 点击远程文件下面我们刚刚添加的配置，选择 **使用配置** ，配置文件会进行更新，更新完成显示成功即可。

![](../../.gitbook/assets/image%20%2860%29.png)

![](../../.gitbook/assets/image%20%2831%29.png)

> 选择适合您的接入点后，点击最上面的「开关」启动服务，首次启动会出现下面的提示，点击「Allow」并输入您的 Apple ID 指纹或者密、码确定添加 Shadowrocket 为 VPN 应用即可。

![](../../.gitbook/assets/image%20%2823%29.png)

![](../../.gitbook/assets/image%20%2854%29.png)

> 最后为了您的节点保持最新状态，我们推荐您打开 Shadowrocket 的 设置 - 服务器订阅

![](../../.gitbook/assets/image%20%281%29.png)

> 打开「打开时更新」的选项。

![](../../.gitbook/assets/image%20%2850%29.png)

> 现在您可以享受 海豚湾云服务 接入点带来的全新国际网络访问体验。
{% endtab %}
{% endtabs %}



