---
title: "Azure PowerShell 개요 | Microsoft Docs"
description: "설치 및 구성에 대한 링크를 포함한 Azure PowerShell 개요입니다."
author: sdwheeler
ms.author: sewhee
manager: carmonm
ms.product: azure
ms.service: azure-powershell
ms.devlang: powershell
ms.topic: conceptual
ms.manager: carmonm
ms.date: 05/15/2017
ms.openlocfilehash: f26b204604018449584c1fd2ff199728487b1515
ms.sourcegitcommit: 226527be7cb647acfe2ea9ab151185053ab3c6db
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 06/29/2017
---
# <span data-ttu-id="0fe20-103">Azure PowerShell 개요</span><span class="sxs-lookup"><span data-stu-id="0fe20-103">Overview of Azure PowerShell</span></span>
<a id="overview-of-azure-powershell" class="xliff"></a>

<span data-ttu-id="0fe20-104">Azure PowerShell은 Azure 리소스를 관리하기 위해 [Azure Resource Manager](/azure/azure-resource-manager/resource-group-overview) 모델을 사용하는 cmdlet 집합을 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="0fe20-104">Azure PowerShell provides a set of cmdlets that use the [Azure Resource Manager](/azure/azure-resource-manager/resource-group-overview) model for managing your Azure resources.</span></span>

<span data-ttu-id="0fe20-105">시스템에서 Azure PowerShell을 실행하는 방법은 [설치](install-azurerm-ps.md) 문서를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="0fe20-105">Review the [Install](install-azurerm-ps.md) article to get Azure PowerShell up and running on your system.</span></span> <span data-ttu-id="0fe20-106">그런 다음 [시작](get-started-azureps.md) 문서를 읽고 사용을 시작해 보세요.</span><span class="sxs-lookup"><span data-stu-id="0fe20-106">Then read the [Get Started](get-started-azureps.md) article to begin using it.</span></span> <span data-ttu-id="0fe20-107">최신 릴리스에 대한 자세한 내용은 [릴리스 정보](release-notes-azureps.md)를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="0fe20-107">For information about the latest release, see the [release notes](release-notes-azureps.md).</span></span>

<span data-ttu-id="0fe20-108">다음 샘플을 통해 Azure PowerShell로 일반 시나리오를 수행하는 방법을 배울 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="0fe20-108">The following samples can help you learn how to perform common scenarios with Azure PowerShell:</span></span>

* [<span data-ttu-id="0fe20-109">Linux 가상 컴퓨터</span><span class="sxs-lookup"><span data-stu-id="0fe20-109">Linux Virtual Machines</span></span>](/azure/virtual-machines/virtual-machines-linux-powershell-samples?toc=/powershell/azure/toc.json)
* [<span data-ttu-id="0fe20-110">Windows 가상 컴퓨터</span><span class="sxs-lookup"><span data-stu-id="0fe20-110">Windows Virtual Machines</span></span>](/azure/virtual-machines/virtual-machines-windows-powershell-samples?toc=/powershell/azure/toc.json)
* [<span data-ttu-id="0fe20-111">Web Apps</span><span class="sxs-lookup"><span data-stu-id="0fe20-111">Web Apps</span></span>](/azure/app-service-web/app-service-powershell-samples?toc=/powershell/azure/toc.json)
* [<span data-ttu-id="0fe20-112">SQL Databases</span><span class="sxs-lookup"><span data-stu-id="0fe20-112">SQL Databases</span></span>](/azure/sql-database/sql-database-powershell-samples?toc=/powershell/azure/toc.json)

> [!NOTE]
> <span data-ttu-id="0fe20-113">변환할 수 없는 클래식 배포 모델을 사용하는 배포가 있는 경우 Azure PowerShell의 Service Management 버전을 설치할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="0fe20-113">If you have deployments that use the classic deployment model that cannot be converted, you can install the Service Management version of Azure PowerShell.</span></span> <span data-ttu-id="0fe20-114">자세한 내용은 다음을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="0fe20-114">For more information, see</span></span>

<span data-ttu-id="0fe20-115">[Azure PowerShell Service Management 모듈 설치](/powershell/azure/servicemanagement/install-azure-ps).</span><span class="sxs-lookup"><span data-stu-id="0fe20-115">[Install the Azure PowerShell Service Management module](/powershell/azure/servicemanagement/install-azure-ps).</span></span>


### <span data-ttu-id="0fe20-116">PowerShell에 대한 도움말이 필요하십니까?</span><span class="sxs-lookup"><span data-stu-id="0fe20-116">Need help with PowerShell?</span></span>
<a id="need-help-with-powershell" class="xliff"></a>

<span data-ttu-id="0fe20-117">PowerShell에 대해 잘 모른다면 PowerShell에 대한 소개가 유용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="0fe20-117">If you are unfamiliar with PowerShell, you may find an introduction to PowerShell helpful.</span></span> <span data-ttu-id="0fe20-118">PowerShell을 시작하려면 [PowerShell을 사용하여 스크립팅](https://technet.microsoft.com/library/bb978526.aspx)을 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="0fe20-118">To get started with PowerShell, see [Scripting with PowerShell](https://technet.microsoft.com/library/bb978526.aspx).</span></span>

<span data-ttu-id="0fe20-119">[PowerShell 기본 사항: (1부) PowerShell 시작](https://channel9.msdn.com/Blogs/Taste-of-Premier/PowerShellBasicsPart1) 비디오를 시청할 수도 있습니다.</span><span class="sxs-lookup"><span data-stu-id="0fe20-119">You can also watch this video: [PowerShell Basics: (Part 1) Getting Started with PowerShell](https://channel9.msdn.com/Blogs/Taste-of-Premier/PowerShellBasicsPart1).</span></span>

## <span data-ttu-id="0fe20-120">다른 Azure PowerShell 모듈</span><span class="sxs-lookup"><span data-stu-id="0fe20-120">Other Azure PowerShell modules</span></span>
<a id="other-azure-powershell-modules" class="xliff"></a>

* [<span data-ttu-id="0fe20-121">Azure Active Directory</span><span class="sxs-lookup"><span data-stu-id="0fe20-121">Azure Active Directory</span></span>](/powershell/azure/active-directory/)
* [<span data-ttu-id="0fe20-122">Azure Information Protection</span><span class="sxs-lookup"><span data-stu-id="0fe20-122">Azure Information Protection</span></span>](/powershell/azure/aip/)
* [<span data-ttu-id="0fe20-123">Azure Service Fabric</span><span class="sxs-lookup"><span data-stu-id="0fe20-123">Azure Service Fabric</span></span>](/powershell/azure/oservice-fabric/)
* [<span data-ttu-id="0fe20-124">Azure ElasticDB</span><span class="sxs-lookup"><span data-stu-id="0fe20-124">Azure ElasticDB</span></span>](/powershell/azure/elasticdbjobs/)