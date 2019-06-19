# 提交闪存信息

* 至少需要已知以下信息

1. 闪存料号
1. 对应的ID
1. 制程
1. 单元类型（TLC/MLC等）

* 对于闪迪五位数料号，则要求更多信息

1. 颗粒是否带锁（解过的不算）
1. CE数以及Die数

# 开始提交你的数据

## 邮件方式

* [发送邮件](mailto:peratx@itxtech.org) 到 `peratx@itxtech.org`

### 模板如下

```text

标题：提交闪存颗粒信息
内容：
品牌：如东芝/美光等
料号：如K9OMGY8S7M-CCK0
ID：ECxxxxxxxxxx（必须为6个字节，可有多个）
制程：3DV3
单元：TLC

```
* 对于闪迪五位数料号

```text

标题：提交闪存颗粒信息
内容：
品牌：闪迪
料号：如05498-128G
ID：453E9AA376D1（必须为6个字节，可有多个）
制程：15nm
单元：TLC
CE：2
Die：8
CODE：无
东芝：7THL

```

## 网页提交

* 到 [fdfdb](https://github.com/iTXTech/fdfdb) 项目提交 [Pull request](https://github.com/iTXTech/fdfdb/pulls)
