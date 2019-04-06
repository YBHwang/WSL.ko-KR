---
title: Linux 명령 참조에 대 한 Windows 하위 시스템
description: Linux 용 Windows 하위 시스템을 관리 하는 명령 목록
keywords: BashOnWindows, bash, wsl, windows, linux, windowssubsystem ubuntu 용 windows 하위 시스템
author: scooley
ms.author: scooley
ms.date: 07/31/2017
ms.topic: article
ms.assetid: 82908295-a6bd-483c-a995-613674c2677e
ms.custom: seodec18
ms.openlocfilehash: 978a35d593e37877949c24cbd833a519888d54bf
ms.sourcegitcommit: ca08a78925880ed3eccf88edb30def16c83f2543
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/04/2019
ms.locfileid: "59063581"
---
# <a name="command-reference-for-windows-subsystem-for-linux"></a><span data-ttu-id="e4c05-104">Linux 용 Windows 하위 시스템에 대 한 명령 참조</span><span class="sxs-lookup"><span data-stu-id="e4c05-104">Command Reference for Windows Subsystem for Linux</span></span>

> `lxrun.exe` <span data-ttu-id="e4c05-105">Windows 10 1803부터 사용 되지 않는 이상 됩니다.</span><span class="sxs-lookup"><span data-stu-id="e4c05-105">is deprecated as of Windows 10 1803 and later.</span></span>

<span data-ttu-id="e4c05-106">명령을 `lxrun.exe` 상호 작용에 사용할 수는 [Windows 하위 시스템에 대 한 WSL (Linux)](https://msdn.microsoft.com/en-us/commandline/wsl/faq#what-windows-subsystem-for-linux-wsl-) 직접.</span><span class="sxs-lookup"><span data-stu-id="e4c05-106">The command `lxrun.exe` can be used to interact with the [Windows Subsystem for Linux (WSL)](https://msdn.microsoft.com/en-us/commandline/wsl/faq#what-windows-subsystem-for-linux-wsl-) directly.</span></span>  <span data-ttu-id="e4c05-107">이러한 명령에 설치 되는 `\Windows\System32` 디렉터리 및 Windows 명령 프롬프트 내에서 또는 PowerShell에서 실행할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e4c05-107">These commands are installed into the `\Windows\System32` directory and may be run within a Windows command prompt or in PowerShell.</span></span>

* `lxrun.exe` <span data-ttu-id="e4c05-108">WSL를 관리에 사용 됩니다.</span><span class="sxs-lookup"><span data-stu-id="e4c05-108">is used to manage WSL.</span></span>  <span data-ttu-id="e4c05-109">설치 또는 Ubuntu 이미지를 제거 하려면이 명령을 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e4c05-109">This command can be used to install or uninstall the Ubuntu image.</span></span>


| <span data-ttu-id="e4c05-110">Command</span><span class="sxs-lookup"><span data-stu-id="e4c05-110">Command</span></span>                     | <span data-ttu-id="e4c05-111">설명</span><span class="sxs-lookup"><span data-stu-id="e4c05-111">Description</span></span>                     |
|:----------------------------|:---------------------------|
| `bash`                      | <span data-ttu-id="e4c05-112">현재 디렉터리에서 Bash 셸을 시작합니다.</span><span class="sxs-lookup"><span data-stu-id="e4c05-112">Launches the Bash shell in the current directory.</span></span>  <span data-ttu-id="e4c05-113">Bash 셸 자동으로 설치 되지 않은 경우 실행</span><span class="sxs-lookup"><span data-stu-id="e4c05-113">If the Bash shell is not installed automatically runs</span></span> `lxrun /install` |
| `bash ~`                    | <span data-ttu-id="e4c05-114">사용자의 Ubuntu에 대 한 홈 디렉터리에 bash 셸을 시작합니다.</span><span class="sxs-lookup"><span data-stu-id="e4c05-114">Launches the bash shell into the user's Ubuntu home directory.</span></span>  <span data-ttu-id="e4c05-115">Cd 실행 비슷합니다 ~</span><span class="sxs-lookup"><span data-stu-id="e4c05-115">Similar to running cd ~</span></span>            |
| `bash -c "<command>"`       | <span data-ttu-id="e4c05-116">명령을 실행 하 고 출력에 인쇄 다시 Windows 명령 프롬프트를 종료 합니다.</span><span class="sxs-lookup"><span data-stu-id="e4c05-116">Runs the command, prints the output and exits back to the Windows command prompt.</span></span> <br/> <br/> <span data-ttu-id="e4c05-117">예: **-c "ls"의 bash**</span><span class="sxs-lookup"><span data-stu-id="e4c05-117">Example:  **bash -c "ls"**</span></span> |

<p>

| <span data-ttu-id="e4c05-118">Command</span><span class="sxs-lookup"><span data-stu-id="e4c05-118">Command</span></span>                     | <span data-ttu-id="e4c05-119">설명</span><span class="sxs-lookup"><span data-stu-id="e4c05-119">Description</span></span>                     |
|:----------------------------|:---------------------------|
| `lxrun`                     | <span data-ttu-id="e4c05-120">Lxrun 명령은 WSL 인스턴스 관리에 사용 됩니다.</span><span class="sxs-lookup"><span data-stu-id="e4c05-120">The lxrun command is used to manage the WSL instance.</span></span> |
| `lxrun /install`            | <span data-ttu-id="e4c05-121">다운로드를 시작 하 고 프로세스를 설치 합니다.</span><span class="sxs-lookup"><span data-stu-id="e4c05-121">Starts the download and install process.</span></span> <br/> <span data-ttu-id="e4c05-122">**/y** 모든 메시지를 표시 하지 않으려면 추가할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="e4c05-122">**/y** may be added to bypass all prompts.</span></span>  <span data-ttu-id="e4c05-123">확인 프롬프트를 자동으로 적용 및 기본 사용자가 루트으로 설정 합니다.</span><span class="sxs-lookup"><span data-stu-id="e4c05-123">The confirmation prompt is automatically accepted and the default user is set to root.</span></span>          |
| `lxrun /uninstall`          | <span data-ttu-id="e4c05-124">제거 되 고 Ubuntu 이미지를 삭제 합니다.</span><span class="sxs-lookup"><span data-stu-id="e4c05-124">Uninstalls and deletes the Ubuntu image.</span></span>  <span data-ttu-id="e4c05-125">기본적으로이 사용자의 Ubuntu에 대 한 홈 디렉터리를 제거 되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="e4c05-125">By default this does not remove the user's Ubuntu home directory.</span></span> <br/> <span data-ttu-id="e4c05-126">**/y** 확인 프롬프트를 자동으로 적용할 추가할 수 있습니다</span><span class="sxs-lookup"><span data-stu-id="e4c05-126">**/y** may be added to automatically accept the confirmation prompt</span></span> <br/><span data-ttu-id="e4c05-127">**전체/** 제거 되 고 사용자의 Ubuntu에 대 한 홈 디렉터리를 삭제 합니다.</span><span class="sxs-lookup"><span data-stu-id="e4c05-127">**/full** uninstalls and deletes the user's Ubuntu home directory</span></span>         |
| `lxrun /setdefaultuser <userName>`     | <span data-ttu-id="e4c05-128">Ubuntu 사용자의 기본 Bash를 설정합니다.</span><span class="sxs-lookup"><span data-stu-id="e4c05-128">Sets the default Bash on Ubuntu user.</span></span> <span data-ttu-id="e4c05-129">지정된 된 사용자가 없으면 암호를 묻는 됩니다.</span><span class="sxs-lookup"><span data-stu-id="e4c05-129">Will prompt for a password if the specified user does not exist.</span></span>  <span data-ttu-id="e4c05-130">자세한 내용은 참조: https://aka.ms/wslusers합니다.</span><span class="sxs-lookup"><span data-stu-id="e4c05-130">For more information visit: https://aka.ms/wslusers.</span></span> <br/> <span data-ttu-id="e4c05-131">**/y** 암호 바이패스 promping 합니다.</span><span class="sxs-lookup"><span data-stu-id="e4c05-131">**/y** Bypasses promping for the password.</span></span>  <span data-ttu-id="e4c05-132">사용자는 암호 없이 생성 됩니다.</span><span class="sxs-lookup"><span data-stu-id="e4c05-132">The user will be created without a password.</span></span>|
| `lxrun /update`            | <span data-ttu-id="e4c05-133">하위 시스템의 패키지 인덱스 업데이트</span><span class="sxs-lookup"><span data-stu-id="e4c05-133">Updates the subsystem's package index</span></span>          |
