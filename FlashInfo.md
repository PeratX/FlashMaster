# 提交闪存信息

* [English](#user-content-submit-flash-info)

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

# Submit Flash Info

* At least the following information needs to be known

1. Flash Part Number
1. Flash Id
1. Manufacturing Process
1. Cell type (TLC/MLC, etc.)

* For the SanDisk five-digit Part Number, more information is required

1. Whether the NAND Flash is CODEd (not unlocked)
1. CE number and Die number

# Start submitting your data

## E-Mail

* [Send](mailto:peratx@itxtech.org) to `peratx@itxtech.org`

### Template is as follows

```text

Title: Submit NAND Flash Information
content:
Vendor: such as Toshiba / Micron, etc.
Part number: such as K9OMGY8S7M-CCK0
ID: ECxxxxxxxxxx (must be 6 bytes, there can be more than one)
Process: 3DV3
Cell: TLC

```
* For SanDisk five-digit item number

```text

Title: Submit NAND Flash Information
content:
Vendor: SanDisk
Part number: such as 05498-128G
ID: 453E9AA376D1 (must be 6 bytes, there can be more than one)
Process: 15nm
Cell: TLC
CE: 2
Die: 8
CODE: None
Toshiba: 7THL

```

## Web

* Go to [fdfdb](https://github.com/iTXTech/fdfdb) and submit a [Pull request](https://github.com/iTXTech/fdfdb/pulls)