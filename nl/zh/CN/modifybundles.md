---

copyright:
  years: 2015, 2017
lastupdated: "2017-07-19"


---

{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen:.screen}
{:codeblock:.codeblock}

# 修改束详细信息
{: #modifybundles}

打开束时，可以查看有关该束的所有详细信息。该束中的所有目标语言都会列出，同时还包括每一种语言的当前翻译状态。

![束详细信息页面显示束及其翻译的相关信息。](images/bundleDetails.png)

束中每一种语言的状态可以是“进行中”、“已失败”或“已翻译”：

| 状态| 描述|
|--------|-------------|
| 进行中| 机器翻译仍在进行中。|
| 已失败| 在将资源文件翻译为目标语言时发生错误。|
| 已翻译| 到目标语言的翻译已完成。|

您可以更新束所使用的资源文件、向束中添加目标语言、从束中删除目标语言，以及下载已生成的目标语言翻译。

## 更新束所使用的资源文件

1. 在源语言的旁边，单击“操作”列中的**上传资源**图标 ![选择此图标以上传新资源文件](images/uploadIcon.png)。
2. 单击**浏览**并选择要上传的新资源文件。
3. 选择要上传的资源文件类型
 * Java 属性文件
 * AMD I18N
 * JSON
4. 单击**更新**，以上传新资源文件。

新的或更新的资源文件中的键值对会与已上传的值同步。只会翻译新的或更改的内容。

## 向束中添加目标语言

1. 单击**添加语言**按钮。
2. 此时将显示所有可用的目标语言。选择要添加到束的语言。

此时将立即开始所选择语言的翻译。

## 从束中删除目标语言

当您从束中删除目标语言时，您会从项目移除目标语言及所有相关联的翻译。在要移除的目标语言的“操作”列中，单击**移除此目标语言**图示 ![选择“移除此目标语言”废纸箱图标](images/trashIcon.png)。

## 下载生成的目标语言翻译

{{site.data.keyword.GlobalizationPipeline_short}} 提供多种方法，可将目标语言的翻译引入到您的应用程序中。您可以将翻译下载为资源文件，并在您的应用程序构建中包含该资源文件。您还可以通过 {{site.data.keyword.GlobalizationPipeline_short}}，使用其中一个开放式源代码 [SDK](https://github.com/IBM-Bluemix/gp-common)，动态地参考翻译。 

<!-- For information on {{site.data.keyword.GlobalizationPipeline_full}} SDKs, see <link>. -->

要将翻译下载为资源文件： 

1. 在要下载的目标或源语言的**操作**列中，单击**下载翻译**图标 ![选择下载图标以下载目标语言的源键或翻译](images/downloadIcon.png)。
2. 选择文件格式。
3. 单击**下载**。