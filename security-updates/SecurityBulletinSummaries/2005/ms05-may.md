---
TOCTitle: 'MS05-MAY'
Title: 'Microsoft 安全公告摘要 (2005 年 5 月)'
ms:assetid: 'ms05-may'
ms:contentKeyID: 61236872
ms:mtpsurl: 'https://technet.microsoft.com/zh-CN/library/ms05-may(v=Security.10)'
---



Microsoft 安全公告摘要 (2005 年 5 月)
=====================================

发布时间: 2005年5月10日

**版本:** 1.0

**发布日期：**2005 年 5 月 10 日
**版本号：**1.0

可通过访问以下[网站](http://www.microsoft.com/security/default.mspx)，获取此信息的最终用户版本。

**保护您的 PC：**Microsoft 在以下位置提供了关于如何帮助保护 PC 的信息：

-   最终用户可以访问[保护您的 PC](http://go.microsoft.com/fwlink/?linkid=21169) 网站。
-   IT 专业人士可以访问[安全指南中心](http://go.microsoft.com/fwlink/?linkid=21171)网站。

**更新管理策略：**[修补程序管理、安全更新和下载](http://go.microsoft.com/fwlink/?linkid=21168)网站提供有关 Microsoft 对应用安全更新的最佳做法建议的详细信息。

**IT 专业人士安全区域社区：**了解如何提高安全性和优化 IT 基础结构，并在 [IT 专业人士安全区域网站](http://go.microsoft.com/fwlink/?linkid=21164)与其他 IT 专业人士一起就安全话题展开讨论。

**Microsoft 安全性通知服务：**要在 Microsoft 安全公告发布时收到自动电子邮件通知，请订阅 [Microsoft 安全性通知服务](http://go.microsoft.com/fwlink/?linkid=21163)。

#### 摘要

此通报中包含新发现漏洞的更新：

重要 (1)
--------

| 公告标识           | Microsoft 安全公告 MS05-024                                                                                  |
|--------------------|--------------------------------------------------------------------------------------------------------------|
| **公告标题**       | [**Web 视图中的漏洞可能允许远程执行代码 (894320)**](http://technet.microsoft.com/security/bulletin/ms05-024) |
| **摘要**           | 处理文件属性时，Web 视图中存在一个脚本注入漏洞。                                                             |
| **最高严重等级**   | [重要](http://go.microsoft.com/fwlink/?linkid=21140)                                                         |
| **安全漏洞的影响** | 远程执行代码                                                                                                 |
| **受影响的软件**   | **Windows**                                                                                                  |

受影响的软件和下载位置
----------------------

**如何使用该表？**

可使用该表了解可能需要安装的安全更新。 您应该查看列出的每个软件程序或组件，了解是否有必须安装的安全更新。 如果列出了一个软件程序或组件，则会列出漏洞的影响，并且还会使用超链接将其链接到可用的软件更新。

**受影响的软件和下载位置**

<p> </p>
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th></th>
<th>详细信息        </th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>公告标识</strong></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/security/bulletin/ms05-024"><strong>MS05-024</strong></a></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><strong>最高严重等级</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>重要</strong></a></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p><strong>受影响的 Windows 软件：</strong></p></td>
<td style="border:1px solid black;"></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;">Windows 2000 Service Pack 3</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=67581d32-743f-44ff-9b53-30277c196923">重要</a></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;">Windows 2000 Service Pack 4</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=67581d32-743f-44ff-9b53-30277c196923">重要</a></td>
</tr>  
</tbody>  
</table>
  
部署  
----
  
  
**Software Update Services:**
  
通过使用 Microsoft Software Update Services (SUS)，管理员可以在基于 Windows 2000 和 Windows Server 2003 的服务器以及运行 Windows 2000 Professional 或 Windows XP Professional 的台式机系统上快速而可靠地部署最新的重要更新和安全更新。
  
有关如何使用软件更新服务部署此安全更新的详细信息，请访问[软件更新服务网站](http://go.microsoft.com/fwlink/?linkid=21133)。
  
**Systems Management Server:**
  
Microsoft Systems Management Server (SMS) 提供了一个用于管理更新且可高度配置的企业解决方案。 通过使用 SMS，管理员可以确定需要安全更新的基于 Windows 的系统，并在整个企业中以可控制的方式执行这些更新的部署，而对最终用户造成的干扰最少。 有关管理员如何使用 SMS 2003 来部署安全更新的详细信息，请参阅 [SMS 2003 安全修补程序管理网站](http://go.microsoft.com/fwlink/?linkid=22939)。 SMS 2.0 用户还可以使用 [Software Updates Service Feature Pack](http://go.microsoft.com/fwlink/?linkid=33340) 帮助部署安全更新。 有关 SMS 的信息，请访问 [SMS 网站](http://go.microsoft.com/fwlink/?linkid=21158)。
  
**注** SMS 使用 Microsoft Baseline Security Analyzer 和 Microsoft Office Detection Tool 提供对安全公告更新检测和部署的广泛支持。 这些工具可能检测不到某些软件更新。 在这些情况下，管理员可以使用 SMS 的清单功能将更新部署到特定系统上。 有关此过程的详细信息，请访问以下[网站](http://go.microsoft.com/fwlink/?linkid=33341)。 某些安全更新在重新启动系统后可能需要管理权限。 管理员可以使用 Elevated Rights Deployment Tool（在 [SMS 2003 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=33387) 和 [SMS 2.0 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=21161) 中提供）安装这些更新。
  
**QChain.exe 和 Update.exe：**
  
Microsoft 已发布了一个名为 QChain.exe 的命令行工具，系统管理员可使用它将安全更新安全地链接在一起。 “*链接*”是指您在安装多个更新时，在两个安装之间不需要重新启动。 此通报中描述的更新所使用的 Update.exe 内置了链接功能。 使用 Windows 2000 Service Pack 2 或更高版本、Windows XP 或 Windows Server 2003 的用户不需要使用 Qchain.exe 来链接这些更新。 Qchain.exe 仍支持将这些 Windows 更新链接在一起，以使管理员在所有平台上创建一致的部署脚本。 有关 Qchain 的详细信息，请访问此[网站](http://go.microsoft.com/fwlink/?linkid=21156)。
  
**Microsoft Baseline Security Analyzer:**
  
管理员可使用 Microsoft Baseline Security Analyzer (MBSA)，在本地和远程系统中扫描缺少的安全更新和常见的安全配置错误。 有关 MBSA 的详细信息，请访问 [Microsoft Baseline Security Analyzer 网站](http://go.microsoft.com/fwlink/?linkid=21134)。
  
#### 其他信息：
  
**获取其他安全更新：**
  
可从以下位置获得针对其他安全问题的更新：
  
-   [Microsoft 下载中心](http://go.microsoft.com/fwlink/?linkid=21129)提供了安全更新。 通过搜索关键字“security\_patch”，可以非常方便地找到这些更新。  
-   可从 [Windows Update 网站](http://go.microsoft.com/fwlink/?linkid=21130)获得适用于客户平台的更新。
  
**支持：**
  
-   美国 和加拿大的客户可拨打电话 1-866-PCSAFETY，从 [Microsoft 产品支持服务](http://go.microsoft.com/fwlink/?linkid=21131)获得技术支持。 与安全更新有关的电话支持服务是免费的。  
-   其他国家（或地区）的客户可从当地的 Microsoft 分公司获得支持。 与安全更新有关的支持服务不收取任何费用。 有关如何就支持问题与 Microsoft 取得联系方面的详细信息，请访问[国际支持网站](http://go.microsoft.com/fwlink/?linkid=21155)。
  
**安全资源：**
  
-   [Microsoft TechNet Security](http://go.microsoft.com/fwlink/?linkid=21132) 网站提供了有关 Microsoft 产品安全的详细信息。  
-   [Microsoft Software Update Services](http://go.microsoft.com/fwlink/?linkid=21133)  
-   [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134) (MBSA)  
-   [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130)  
-   Windows Update 目录：有关 Windows Update 目录的详细信息，请参阅 [Microsoft 知识库文章 323166](http://support.microsoft.com/default.aspx?scid=kb;en-us;323166)。  
-   [Office Update](http://go.microsoft.com/fwlink/?linkid=21135)
  
**免责声明：**
  
Microsoft 知识库中的信息“按原样”提供，没有任何形式的担保。 Microsoft 不作任何明示或暗示保证，包括对适销性和针对特定目的的适用性的保证。 Microsoft Corporation 或其供应商不对任何损害（包括直接的、间接的、偶然的、必然的损害，商业利润损失，或特殊损害）承担任何责任，即使 Microsoft Corporation 或其供应商事先已被告知有可能发生此类损害。 有些州不允许排除或限制必然或偶然损害的赔偿责任，因此上述限制可能不适用。
  
**修订：**
  
-   V1.0（2005 年 5 月 10 日）：已发布公告
  
*Built at 2014-04-18T01:50:00Z-07:00*
