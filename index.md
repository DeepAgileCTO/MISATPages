---
layout: default
---

# 说明

*   感谢您使用数字病理切片图像标注软件。
*   本产品说明手册是苏州深捷信息科技有限公司数字病理切片图像标注软件产品说明手册，将向您介绍软件安装、日常使用、维护保养等方面内容。
*   为安全正确使用本产品，在操作前，请务必仔细阅读本手册内容，使用人员经培训合格后上机操作。
*   为了获得最好效果，在进行临床使用前，您必须熟悉本产品操作。
*   阅读后请妥善保存本产品说明手册，以便需要的时候可以随时查阅。
*   有任何问题可以与您的经销商联系。

* * *

# 1 数字病理切片图像标注概述

## 1.1 产品简介

数字病理切片图像标注软件是基于WPF开发的病理图像分析软件。本软件可为用户提供数字病理切片图像的浏览与标注服务。用户需配备独立的客户端主机，安装软件后，可实现基本的数字病理切片图像的管理、浏览、标注与复核等任务。

本产品提供用户友好的使用界面，支持多种病理切片扫描仪的图像数据格式，包括.zyp、.tiff等。本产品主要功能包括：用户登录、病理图像管理、病理图像显示与交互、病理图像标注以及病理图像标注数据复核，具有高灵活性、扩展性、容错性和稳定性。

## 1.2 产品适用范围

数字病理切片图像标注软件是一款病理图像分析软件，支持.zyp、.tiff格式的病理切片扫描数据，使用人员包括但不限于病理科医生和科研人员。本产品通过提供一系列标注工具，帮助用户标注感兴趣区域。

## 1.3 操作界面

数字病理切片图像标注软件采用可视化图形用户界面、并支持各类鼠标交互。用户需具备基础的计算机硬件、Windows操作知识以及基本的病理知识，基本了解病理图像的数据标注流程，经过本公司授权人员培训后即可轻松使用本产品。为保证安全与正确的功能，用户需按照本手册中的功能规范进行操作。为防止用户误操作，本产品通过在操作界面中置灰按钮、弹出提示框提醒用户。本产品主要操作界面如图1所示，主要包括六个部分。

#### (1) 菜单栏
可进行病理图像数据的导入，系统设置等功能。

#### (2) 病理图像缩略图显示区
可查看本地数字病理切片图像，进行多文档管理。

#### (3) 病理切片图像显示区
可进行数字切片病理图像的显示，实现缩放、平移交互。

#### (4) 病理图像导航区
显示当前显示区域的导航图信息，进行快速定位显示区域。

#### (5) 标注列表管理区
进行病理图像标注、标注管理以及标注结果保存。

#### (6) 复核列表管理区
显示待复核标注信息，进行复核标注选择与导入。

![数字病理切片图像标注软件界面](https://deepagilecto.github.io/MISATPages/assets/images/数字病理切片图像标注软件界面.png)

图1. 数字病理切片图像标注软件界面

## 1.4 产品运行环境与兼容性

### 1.4.1 硬件运行环境

数字病理切片图像标注软件安装所需最小磁盘空间为5G，硬件运行环境如下表所示：

表1-1. 客户端硬件运行环境

|主要硬件       |配置信息                                     |
|:--------------|:--------------------------------------------|
| 处理器        | 英特尔® 酷睿™ i7-8700 处理器（12核 3.2GHz） |
| 内存          | 8 GB                                        |
| 显卡          | NVIDIA® GeForce GTX 1060显卡（6GB显存）     |
| 硬盘          | 1TB硬盘                                     |
| 显示器分辨率  | 2560×1440                                   |

### 1.4.2 软件运行环境

软件运行环境:

*   Microsoft Windows 10 64位家庭中文版操作系统；
*   Microsoft.Net Framework 4.5.2及以上版本软件库的支持；
*   Nvidia显卡驱动456.71及以上版本；

### 1.4.3 兼容性

本软件兼容的数据类型为多厂商病理切片扫描数据格式，如zyp、tiff。部署本软件及其运行环境后，本软件与杀毒软件兼容。本软件使用计算机xml格式读取与保存标注信息。

## 1.5 使用限制

本软件处理的图像数据需为病理切片扫描数据，包含多层金字塔结构的tiff或zyp格式数据。

## 1.6 警告

本产品仅用于本文档中列出的应用，不得用于存在固有危险或可能造成人身伤害的应用。如果您在危险的应用中使用本产品，应采取所有必要的故障安全、备份、冗余和其他措施，确保安全使用本产品。对于在危险应用中使用本产品所造成的任何损害，中科院苏州医工所不承担任何责任。

## 1.7 注意事项

### 1.7.1 注意细则

*   本产品说明已排除内部的不一致。
*   使用本产品的用户要求具有正常视力及键盘操作能力，能够正确识别简体中文，且红绿色盲不可使用本产品。
*   当使用该产品时，为保证安全和正确的功能，应采用使用说明书所描述的正确的操作方法。
*   使用该系统前，认真阅读和理解说明书内容，确保明白其描述的内容。
*   操作该系统时将说明书放置于您易于拿到的位置。
*   当您不阅读该说明书时，请将其放在您不会弄丢或损坏的地方。
*   当您转卖或移交此系统时，请将说明书移交新的所有者。

### 1.7.2 免费维护

*   本软件提供另存为功能，用户可将数据另存到本地文件夹进行备份，并通过读取该文件夹进行恢复。
*   本产品在宕机或异常退出时，重新启动本产品后，能正常运行并且数据不会丢失。
*   本产品出现严重故障或损坏时，请联系授权的专业人员进行故障排查与数据恢复。

## 1.8 产品维护方法

### 1.8.1 免费维护

*   本公司对产品运行提供支持，用户在使用过程中遇到任何维护服务相关的问题均可通过售后联系方式与本公司联系。
*   本产品升级与初次安装由本公司授权的专业人员进行。用户电脑由专业人员配置运行环境后，用户可进行本产品的安装与卸载。
*   本产品免费维护期限为1年，免费维护期从安装验收合格之日起计算。
*   免费维护有效期内，产品在符合要求的环境条件和使用条件下，按本说明书要求操作出现的产品故障，属于免费维护范围。维护服务将由本公司授权的专业人员进行。
*   本产品提供日志记录软件运行事件，以便服务工程师进行维护；本产品提供日志记录AI模型运行事件，以便服务工程师进行维护。
*   病毒感染计算机系统导致无法正常工作不属于免费维护范围。

### 1.8.2 日常保养

*   U盘放置应尽量避免落上灰尘并远离磁场，日常保存，请放入包装盒内。
*   有污垢时，请用软棉布（或眼镜布）轻轻擦拭，请勿用清水、超声波清洗剂（器）、含有酒精或任何市面上出售的各种珠宝清洁剂清洗，以免造成永不磨灭的印迹。
*   请勿与硬物，尖锐物品摆放一起，以免磨损，造成无法读取的后果。

## 1.9 寿命期限

生产日期：见标签。

寿命期期： 5年。

## 1.10 技术参数

使用1.4.1章节硬件运行环境，本产品主要技术参数如下：

*   单个.zyp文件读取速度≤2000ms。
*   单个tiff文件读取速度≤1000ms。

## 1.11 版权保护

本产品通过License序列号文件的方式控制版权，单个序列号有效期为1年。当产品有效期＜30天时，软件将弹出提示框。

## 1.12 储存环境

<dl>
<dt>温度：</dt>
<dd>15℃～40℃</dd>
<dt>湿度：</dt>
<dd>≤80％RH</dd>
<dt>周围环境：</dt>
<dd>应无酸性、碱性和无其他有害气体</dd>
<dt>特殊储存：</dt>
<dd>周围无强磁场</dd>
</dl>

* * *

# 2 安装与卸载

## 2.1 产品安装

满足1.4章节所述配置与运行环境的电脑均可安装本产品。本产品初次安装将由本公司授权的专业人员进行，他们将在第一次使用之前安装和检查所有系统组件。

若用户电脑已由本公司授权的专业人员配置运行环境，则用户可自行安装本产品，安装与运行步骤如下：

1.  将本产品存储U盘插入电脑USB接口端；
2.  在U盘Setup目录下，点击运行“Setup.exe”安装本产品；
3.  在电脑桌面点击“数字病理切片图像标注软件”快捷方式启动本产品。

## 2.2 产品卸载

用户可自行卸载本产品，卸载步骤如下：

1.  退出“数字病理切片图像标注软件”后，打开“控制面板”。
2.  进入“添加/删除程序”，找到“数字病理切片图像标注软件”，点击“更改/删除”按钮。
3.  弹出“解除安装”提示页面，点击“是”，直接卸载完毕。

* * *

# 3 启动客户端

## 3.1 用户欢迎界面

请在操作系统桌面，双击本产品客户端的快捷图标启动系统，进入用户欢迎界面，如图3-1所示，在欢迎界面中，用户可选择标注模式进行标注，也可以选择复核模式对已标注数据进行复核。选择模式后，输入用户信息，选择用户级别，确认后进入主界面。

![用户欢迎界面](https://deepagilecto.github.io/MISATPages/assets/images/用户欢迎界面.png)

图3-1 用户欢迎界面

* * *

# 4 数字病理切片图像浏览与标注

## 4.1 数字病理切片图像管理

### 4.1.1 数据导入

点击菜单栏的文件-打开文件弹出“文件浏览”对话框，选择单张病理切片图像，点击确定后导入该图像，如下图4-1-1所示；或者打开文件夹，弹出“文件夹浏览”对话框，选择包含多张病理切片图像的文件夹，点击“确定”按钮，导入该文件夹下的所有病理图像。如下图4-1-2所示：

![病理图像文件导入-1](https://deepagilecto.github.io/MISATPages/assets/images/病理图像文件导入-1.png)

![病理图像文件导入-2](https://deepagilecto.github.io/MISATPages/assets/images/病理图像文件导入-2.png)

图4-1-1 病理图像文件导入

![病理图像文件夹导入](https://deepagilecto.github.io/MISATPages/assets/images/病理图像文件夹导入.png)

图4-1-2 病理图像文件夹导入

### 4.1.2 病理图像缩略图显示

在病理图像数据导入解析完成后，文件管理面板将显示病理图像缩略图。“单击”任意病理图像后，可切换当前激活显示的图像，按住Ctrl键可以打开多张图像，如下图4-1-3所示：

![病理图像缩略图显示功能](https://deepagilecto.github.io/MISATPages/assets/images/病理图像缩略图显示功能.png)

图4-1-3病理图像缩略图显示功能

## 4.2 病理图像显示与交互

### 4.2.1 病理图像显示

导入病理图像后，软件主显示区域显示当前激活的病理图像。界面左上角显示当前病理图像的缩放倍率，左下角显示比例尺信息，如下图4-2-1所示：

![影像显示功能](https://deepagilecto.github.io/MISATPages/assets/images/影像显示功能.png)

图4-2-1 影像显示功能

### 4.2.2 病理图像交互

用户在激活病理图像显示的情况下，在图像显示区域中按下鼠标左键并进行移动来平移图像显示区域，通过鼠标滚轮前后滚动来缩放图像显示区域，如下图4-2-2所示：

* * *

Text can be **bold**, _italic_, or ~~strikethrough~~.

[Link to another page](./another-page.html).

There should be whitespace between paragraphs.

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

# Header 1

This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

## Header 2

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
