---
title: "macOS 및 Linux에서 Azure PowerShell 설치 및 구성 | Microsoft Docs"
description: "macOS 및 Linux에서 Azure PowerShell을 처음으로 설치하고 구성하는 방법입니다."
services: azure
author: sdwheeler
ms.author: sewhee
manager: carmonm
ms.product: azure
ms.service: azure-powershell
ms.devlang: powershell
ms.topic: conceptual
ms.date: 09/06/2017
ms.openlocfilehash: 94b39c18acaca7a4b17b5207feed025442665acc
ms.sourcegitcommit: c42c7176276ec4e1cc3360a93e6b15d32083bf9f
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 12/14/2017
---
# <a name="install-and-configure-azure-powershell-on-macos-and-linux"></a><span data-ttu-id="2e21c-103">macOS 및 Linux에서 Azure PowerShell 설치 및 구성</span><span class="sxs-lookup"><span data-stu-id="2e21c-103">Install and configure Azure PowerShell on macOS and Linux</span></span>

<span data-ttu-id="2e21c-104">이제 Windows 이외의 플랫폼에서도 PowerShell 6(베타) 및 Azure PowerShell을 설치할 수 있게 되었습니다.</span><span class="sxs-lookup"><span data-stu-id="2e21c-104">It is now possible to install PowerShell 6 (beta) and Azure PowerShell on non-Windows platforms.</span></span>
<span data-ttu-id="2e21c-105">macOS 및 Linux에 Azure PowerShell 설치 프로세스는 Windows와 다르지 않지만, PowerShell 6(베타)을 먼저 설치해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="2e21c-105">The process of installing Azure PowerShell on macOS and Linux is not that different from Windows, however, you must first install PowerShell 6 (beta).</span></span>

> [!NOTE]

> <span data-ttu-id="2e21c-106">이때 PowerShell 6(베타)과 .NET Core용 Azure PowerShell은 아직 베타 버전입니다.</span><span class="sxs-lookup"><span data-stu-id="2e21c-106">At this time, both PowerShell 6 (beta) and Azure PowerShell for .NET Core are still in beta.</span></span>
> <span data-ttu-id="2e21c-107">이러한 제품에 대한 지원은 제한됩니다.</span><span class="sxs-lookup"><span data-stu-id="2e21c-107">Support for these products is limited.</span></span> <span data-ttu-id="2e21c-108">문제가 있거나 버그를 발견한 경우 GitHub에서 문제를 제출하십시오.</span><span class="sxs-lookup"><span data-stu-id="2e21c-108">If you have problems or discover bugs, please file Issues in GitHub.</span></span>
>
> * [<span data-ttu-id="2e21c-109">PowerShell 6(베타)에 대한 문제</span><span class="sxs-lookup"><span data-stu-id="2e21c-109">Issues for PowerShell 6 (beta)</span></span>](https://github.com/PowerShell/PowerShell/issues)
> * [<span data-ttu-id="2e21c-110">Azure PowerShell에 대한 문제</span><span class="sxs-lookup"><span data-stu-id="2e21c-110">Issues for Azure PowerShell</span></span>](https://github.com/azure/azure-docs-powershell/issues)

## <a name="step-1-install-powershell-6-beta"></a><span data-ttu-id="2e21c-111">1단계: PowerShell 6(베타) 설치</span><span class="sxs-lookup"><span data-stu-id="2e21c-111">Step 1: Install PowerShell 6 (beta)</span></span>

<span data-ttu-id="2e21c-112">PowerShell 6(베타) 설치 프로세스는 대상 운영 체제에 따라 달라집니다.</span><span class="sxs-lookup"><span data-stu-id="2e21c-112">The process of installing PowerShell 6 (beta) on varies depending on the target operating system.</span></span>
<span data-ttu-id="2e21c-113">Windows에 PowerShell 6(베타)를 설치할 수 있지만 이 문서에서는 macOS 및 Linux에 설치하는 것에 초점을 둡니다.</span><span class="sxs-lookup"><span data-stu-id="2e21c-113">While it is possible to install PowerShell 6 (beta) on Windows, this article focuses on macOS and Linux.</span></span> <span data-ttu-id="2e21c-114">Windows에서 Azure PowerShell을 사용하려는 경우 Windows용 [설치](./install-azurerm-ps.md) 문서를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="2e21c-114">If you want to use Azure PowerShell on Windows, see the [install](./install-azurerm-ps.md) article for Windows.</span></span>

<span data-ttu-id="2e21c-115">Linux 또는 macOS에 **PowerShell 6**(베타)를 설치하려면 경우 다음을 수행해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="2e21c-115">To install **PowerShell 6** (beta) on Linux or macOS, you need to:</span></span>

1. <span data-ttu-id="2e21c-116">[GitHub](https://github.com/powershell/powershell#get-powershell)에서 특정 운영 체제 및 버전용 PowerShell을 가져옵니다.</span><span class="sxs-lookup"><span data-stu-id="2e21c-116">Get PowerShell for the specific OS and version, from [GitHub](https://github.com/powershell/powershell#get-powershell)</span></span>
2. <span data-ttu-id="2e21c-117">설치 지침을 따릅니다.</span><span class="sxs-lookup"><span data-stu-id="2e21c-117">Follow the installation instructions</span></span>
   - [<span data-ttu-id="2e21c-118">Linux</span><span class="sxs-lookup"><span data-stu-id="2e21c-118">Linux</span></span>](https://github.com/PowerShell/PowerShell/blob/master/docs/installation/linux.md)
   - [<span data-ttu-id="2e21c-119">macOS</span><span class="sxs-lookup"><span data-stu-id="2e21c-119">macOS</span></span>](https://github.com/PowerShell/PowerShell/blob/master/docs/installation/linux.md#macos-1012)

## <a name="step-2-install-azure-powershell-for-net-core"></a><span data-ttu-id="2e21c-120">2단계: .NET Core용 Azure PowerShell 설치</span><span class="sxs-lookup"><span data-stu-id="2e21c-120">Step 2: Install Azure PowerShell for .NET Core</span></span>

<span data-ttu-id="2e21c-121">PowerShell 6(베타)은 PowerShellGet 모듈이 이미 설치되어 제공됩니다.</span><span class="sxs-lookup"><span data-stu-id="2e21c-121">PowerShell 6 (beta) comes with the PowerShellGet module already installed.</span></span> <span data-ttu-id="2e21c-122">따라서 PowerShell 갤러리에 게시된 어떤 모듈도 쉽게 설치할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2e21c-122">This makes it easy to install any module that is published to the PowerShell Gallery.</span></span> <span data-ttu-id="2e21c-123">Azure PowerShell을 설치하려면 새 PowerShell 세션을 열고 다음 명령을 실행합니다.</span><span class="sxs-lookup"><span data-stu-id="2e21c-123">To install Azure PowerShell, open a new PowerShell session and run the following command:</span></span>

```powershell
Install-Module AzureRM.NetCore
```

## <a name="step-3-load-the-azurermnetcore-module"></a><span data-ttu-id="2e21c-124">3단계: AzureRM.Netcore 모듈 로드</span><span class="sxs-lookup"><span data-stu-id="2e21c-124">Step 3: Load the AzureRM.Netcore module</span></span>

<span data-ttu-id="2e21c-125">모듈이 설치되면 PowerShell 세션에 모듈을 로드해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="2e21c-125">Once the module is installed, you need to load the module into your PowerShell session.</span></span> <span data-ttu-id="2e21c-126">모듈은 다음과 같이 `Import-Module` cmdlet을 사용하여 로드됩니다.</span><span class="sxs-lookup"><span data-stu-id="2e21c-126">Modules are loaded using the `Import-Module` cmdlet, as follows:</span></span>

```powershell
Import-Module AzureRM.Netcore
```

<span data-ttu-id="2e21c-127">가져오기가 완료되면 다음 명령을 사용하여 Azure에 로그인을 시도하여 새로 설치한 모듈을 테스트할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="2e21c-127">After the import completes, you can test your newly installed and module by attempting to sign into Azure using the following command:</span></span>

```powershell
Login-AzureRMAccount
```

<span data-ttu-id="2e21c-128">위의 명령을 실행하면 `https://aka.ms/devicelogin`으로 이동하여 제공된 코드를 입력하라는 메시지가 나타납니다.</span><span class="sxs-lookup"><span data-stu-id="2e21c-128">The above command should prompt you to go to `https://aka.ms/devicelogin` and enter the provided code.</span></span>

## <a name="available-cmdlets"></a><span data-ttu-id="2e21c-129">사용할 수 있는 cmdlet</span><span class="sxs-lookup"><span data-stu-id="2e21c-129">Available cmdlets</span></span>

<span data-ttu-id="2e21c-130">.NET 표준용 Azure PowerShell 모듈은 아직 개발 중입니다.</span><span class="sxs-lookup"><span data-stu-id="2e21c-130">The Azure PowerShell modules for .NET Standard are still in development.</span></span> <span data-ttu-id="2e21c-131">이러한 모듈은 모듈의 Windows 버전에 대해 사용할 수 있는 cmdlet의 집합을 모두 제공하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="2e21c-131">These modules do not provide the full set of cmdlets that are available for the Windows version of the modules.</span></span> <span data-ttu-id="2e21c-132">다음 함수는 AzureRM.Netcore 모듈에서 구현됩니다.</span><span class="sxs-lookup"><span data-stu-id="2e21c-132">The following functions are implemented in AzureRM.Netcore modules:</span></span>

* <span data-ttu-id="2e21c-133">계정 관리</span><span class="sxs-lookup"><span data-stu-id="2e21c-133">Account management</span></span>
  - <span data-ttu-id="2e21c-134">Microsoft 계정, 조직 계정 또는 Azure Active Directory를 통해 서비스 사용자로 로그인</span><span class="sxs-lookup"><span data-stu-id="2e21c-134">Login with Microsoft account, Organizational account, or Service Principal through Microsoft Azure Active Directory</span></span>
  - <span data-ttu-id="2e21c-135">Save-AzureRmContext로 자격 증명을 디스크에 저장하고 Import-AzureRmContext를 사용하여 저장된 자격 증명 로드</span><span class="sxs-lookup"><span data-stu-id="2e21c-135">Save Credentials to disk with Save-AzureRmContext and load saved credentials using Import-AzureRmContext</span></span>
* <span data-ttu-id="2e21c-136">Environment</span><span class="sxs-lookup"><span data-stu-id="2e21c-136">Environment</span></span>
  - <span data-ttu-id="2e21c-137">다른 기본 Microsoft Azure 환경 가져오기</span><span class="sxs-lookup"><span data-stu-id="2e21c-137">Get the different out-of-box Microsoft Azure environments</span></span>
  - <span data-ttu-id="2e21c-138">사용자 지정 환경 추가/설정/제거(예: Azure Stack 또는 Windows Azure 팩 환경)</span><span class="sxs-lookup"><span data-stu-id="2e21c-138">Add/Set/Remove customized environments (like your Azure Stack or Windows Azure Pack environments)</span></span>
* <span data-ttu-id="2e21c-139">리소스 관리자 및 서비스 관리 인터페이스를 사용하여 Azure 서비스용 평면 cmdlet 관리</span><span class="sxs-lookup"><span data-stu-id="2e21c-139">Management plane cmdlets for Azure services using Resource Manager and Service Management interfaces.</span></span>
  - <span data-ttu-id="2e21c-140">가상 컴퓨터</span><span class="sxs-lookup"><span data-stu-id="2e21c-140">Virtual Machine</span></span>
  - <span data-ttu-id="2e21c-141">App Service(웹 사이트)</span><span class="sxs-lookup"><span data-stu-id="2e21c-141">App Service (Websites)</span></span>
  - <span data-ttu-id="2e21c-142">SQL Database</span><span class="sxs-lookup"><span data-stu-id="2e21c-142">SQL Database</span></span>
  - <span data-ttu-id="2e21c-143">Storage</span><span class="sxs-lookup"><span data-stu-id="2e21c-143">Storage</span></span>
  - <span data-ttu-id="2e21c-144">네트워크</span><span class="sxs-lookup"><span data-stu-id="2e21c-144">Network</span></span>

## <a name="next-steps"></a><span data-ttu-id="2e21c-145">다음 단계</span><span class="sxs-lookup"><span data-stu-id="2e21c-145">Next Steps</span></span>

<span data-ttu-id="2e21c-146">Azure PowerShell 사용에 대한 자세한 내용은 [Azure PowerShell 시작](get-started-azureps.md) 문서를 참조하세요.</span><span class="sxs-lookup"><span data-stu-id="2e21c-146">For more information about using Azure PowerShell, see the [Get started with Azure PowerShell](get-started-azureps.md) article.</span></span>