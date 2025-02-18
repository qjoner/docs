---
title: 关于组织的资料
intro: 组织的资料页面显示组织的基本信息。
redirect_from:
  - /articles/about-your-organization-s-profile
  - /articles/about-your-organizations-profile
  - /github/setting-up-and-managing-your-github-profile/about-your-organizations-profile
  - /github/setting-up-and-managing-your-github-profile/customizing-your-profile/about-your-organizations-profile
versions:
  fpt: '*'
  ghes: '*'
  ghae: '*'
  ghec: '*'
topics:
  - Profiles
shortTitle: Organization's profile
ms.openlocfilehash: d5500e34a9996f8d5cae216972ef0289569d53f2
ms.sourcegitcommit: 47bd0e48c7dba1dde49baff60bc1eddc91ab10c5
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/05/2022
ms.locfileid: '147066512'
---
可以选择为组织添加描述、位置、网站和电子邮件地址，以及固定重要存储库。{% ifversion fpt or ghec or ghes > 3.3 or ghae-issue-4749 %} 可以通过添加 README.md 文件来自定义组织的公共资料。 有关详细信息，请参阅“[自定义组织的资料](/organizations/collaborating-with-groups-in-organizations/customizing-your-organizations-profile)”。{% endif %}

{% ifversion fpt %} 使用{% data variables.product.prodname_ghe_cloud %} 的组织可以通过 {% data variables.product.product_name %} 验证组织的域来确认其组织的标识并在组织资料页面显示“已验证”徽章。 有关详细信息，请参阅 {% data variables.product.prodname_ghe_cloud %} 文档中的“[验证或批准组织的域](/organizations/managing-organization-settings/verifying-or-approving-a-domain-for-your-organization)”。
{% elsif ghec or ghes %} 要确认组织标识并在组织资料页面显示“已验证”徽章，可以向 {% data variables.product.prodname_dotcom %} 验证组织的域。 有关详细信息，请参阅“[验证或批准组织的域](/organizations/managing-organization-settings/verifying-or-approving-a-domain-for-your-organization)”。
{% endif %}

{% ifversion fpt or ghes > 3.2 or ghec %} ![示例组织资料页](/assets/images/help/organizations/org_profile_with_overview.png) {% else %} ![示例组织资料页](/assets/images/help/profile/org_profile.png) {% endif %}

## 延伸阅读

- “[关于组织](/organizations/collaborating-with-groups-in-organizations/about-organizations)”
