---
title: Linux 용 Windows 하위 시스템에 대 한 릴리스 정보
description: Linux 용 Windows 하위 시스템에 대 한 릴리스 정보입니다.  매주 업데이트 합니다.
keywords: BashOnWindows, bash, wsl, windows, linux, windowssubsystem ubuntu 용 windows 하위 시스템
author: benhillis
ms.date: 07/31/2017
ms.topic: article
ms.assetid: 36ea641e-4d49-4881-84eb-a9ca85b1cdf4
ms.custom: seodec18
ms.openlocfilehash: 3eee7ff6d1f8302e98cde84fccabf5d9113c83f2
ms.sourcegitcommit: ca08a78925880ed3eccf88edb30def16c83f2543
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 04/04/2019
ms.locfileid: "59063631"
---
# <a name="release-notes-for-windows-subsystem-for-linux"></a><span data-ttu-id="6f9d2-105">Linux 용 Windows 하위 시스템에 대 한 릴리스 정보</span><span class="sxs-lookup"><span data-stu-id="6f9d2-105">Release Notes for Windows Subsystem for Linux</span></span>

## <a name="build-18342"></a><span data-ttu-id="6f9d2-106">18342 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-106">Build 18342</span></span>
<span data-ttu-id="6f9d2-107">일반 Windows에 대 한 18342 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2019/02/20/announcing-windows-10-insider-preview-build-18342/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-107">For general Windows information on build 18342 visit the [Windows blog](https://blogs.windows.com/windowsexperience/2019/02/20/announcing-windows-10-insider-preview-build-18342/).</span></span>

### <a name="wsl"></a><span data-ttu-id="6f9d2-108">WSL</span><span class="sxs-lookup"><span data-stu-id="6f9d2-108">WSL</span></span>
* <span data-ttu-id="6f9d2-109">Windows에서 Linux 파일 WSL 배포판에 액세스 하려면 사용자가 기능을 추가 했습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-109">We've added the ability for users to access Linux files in a WSL distro from Windows.</span></span> <span data-ttu-id="6f9d2-110">명령줄 및 또한 파일 탐색기와 VSCode Windows 앱을 통해 이러한 파일에 액세스할 수 있습니다, 그리고 등 이러한 파일을 사용 하 여 상호 작용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-110">These files can be accessed through the command line, and also Windows apps, like file explorer, VSCode, etc. can interact with these files.</span></span> <span data-ttu-id="6f9d2-111">로 이동 하 여 파일에 액세스할 \\ \\wsl$\\< distro_name >로 이동 하 여 배포를 실행 중인 목록을 보거나 \\ \\wsl$</span><span class="sxs-lookup"><span data-stu-id="6f9d2-111">Access your files by navigating to \\\\wsl$\\<distro_name>, or see a list of running distributions by navigating to \\\\wsl$</span></span>
* <span data-ttu-id="6f9d2-112">CPU 정보 태그를 추가 하 고 [GH 2234] Cpus_allowed [목록 (_l)] 값 수정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-112">Add additional CPU info tags and fix Cpus_allowed[_list] values [GH 2234]</span></span>
* <span data-ttu-id="6f9d2-113">[GH 3800] 리더가 아닌 스레드에서 exec를 지원 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-113">Support exec from non-leader thread [GH 3800]</span></span>
* <span data-ttu-id="6f9d2-114">치명적이 지 않은 [GH 3785]으로 구성 업데이트 오류 처리</span><span class="sxs-lookup"><span data-stu-id="6f9d2-114">Treat configuration update failures as non-fatal [GH 3785]</span></span>
* <span data-ttu-id="6f9d2-115">오프셋 [GH 3768]를 적절히 처리할 binfmt 업데이트</span><span class="sxs-lookup"><span data-stu-id="6f9d2-115">Update binfmt to properly handle offsets [GH 3768]</span></span>
* <span data-ttu-id="6f9d2-116">계획 9 [GH 3854]에 대 한 매핑 네트워크 드라이브를 사용 하도록 설정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-116">Enable mapping network drives for Plan 9 [GH 3854]</span></span>
* <span data-ttu-id="6f9d2-117">지원 Windows Linux 및 Linux에 바인드 바 운 트에서 대 한 Windows 경로 번역-></span><span class="sxs-lookup"><span data-stu-id="6f9d2-117">Support Windows -> Linux and Linux -> Windows path translation for bind mounts</span></span>
* <span data-ttu-id="6f9d2-118">읽기 전용으로 열려 있는 파일의 매핑에 대 한 읽기 전용 섹션 만들기</span><span class="sxs-lookup"><span data-stu-id="6f9d2-118">Create read-only sections for mappings on files opened read-only</span></span>

## <a name="build-18334"></a><span data-ttu-id="6f9d2-119">18334 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-119">Build 18334</span></span>
<span data-ttu-id="6f9d2-120">일반 Windows에 대 한 18334 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2019/02/08/announcing-windows-10-insider-preview-build-18334/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-120">For general Windows information on build 18334 visit the [Windows blog](https://blogs.windows.com/windowsexperience/2019/02/08/announcing-windows-10-insider-preview-build-18334/).</span></span>

### <a name="wsl"></a><span data-ttu-id="6f9d2-121">WSL</span><span class="sxs-lookup"><span data-stu-id="6f9d2-121">WSL</span></span>
* <span data-ttu-id="6f9d2-122">Windows 표준 시간대 [GH 3747] Linux 표준 시간대로 매핑되는 방식을 다시 디자인</span><span class="sxs-lookup"><span data-stu-id="6f9d2-122">Redesign the way that Windows time zone is mapped to a  Linux time zone [GH 3747]</span></span>
* <span data-ttu-id="6f9d2-123">메모리 누수를 해결 하 고 새로운 문자열 변환 함수 [GH 3746]를 추가 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-123">Fix memory leaks and add new string translation functions [GH 3746]</span></span>
* <span data-ttu-id="6f9d2-124">threadgroup이 없는 스레드를 사용 하 여에서 SIGCONT가 no-op [GH 3741]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-124">SIGCONT on a threadgroup with no threads is a no-op [GH 3741]</span></span> 
* <span data-ttu-id="6f9d2-125">/Proc/self/fd에서 소켓 및 epoll 파일 설명자를 올바르게 표시</span><span class="sxs-lookup"><span data-stu-id="6f9d2-125">Correctly display socket and epoll file descriptors in /proc/self/fd</span></span>

## <a name="build-18305"></a><span data-ttu-id="6f9d2-126">18305 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-126">Build 18305</span></span>
<span data-ttu-id="6f9d2-127">일반 Windows에 대 한 18305 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2018/12/19/announcing-windows-10-insider-preview-build-18305/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-127">For general Windows information on build 18305 visit the [Windows blog](https://blogs.windows.com/windowsexperience/2018/12/19/announcing-windows-10-insider-preview-build-18305/).</span></span>

### <a name="wsl"></a><span data-ttu-id="6f9d2-128">WSL</span><span class="sxs-lookup"><span data-stu-id="6f9d2-128">WSL</span></span>
* <span data-ttu-id="6f9d2-129">주 스레드가 종료 [GH 3589] pthread 파일에 대 한 액세스 권한을 상실합니다</span><span class="sxs-lookup"><span data-stu-id="6f9d2-129">pthreads lose access to files when the primary thread exits [GH 3589]</span></span>
* <span data-ttu-id="6f9d2-130">필요한 경우에 TIOCSCTTY "force" 매개 변수를 무시 해야 [GH 3652]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-130">TIOCSCTTY should ignore the “force” parameter unless it is required [GH 3652]</span></span>
* <span data-ttu-id="6f9d2-131">wsl.exe 명령줄 향상 된 기능 및 추가 가져오기/내보내기 기능.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-131">wsl.exe command line improvements and addition of import / export functionality.</span></span>
```
Usage: wsl.exe [Argument] [Options...] [CommandLine]

Arguments to run Linux binaries:

    If no command line is provided, wsl.exe launches the default shell.

    --exec, -e <CommandLine>
        Execute the specified command without using the default Linux shell.

    --
        Pass the remaining command line as is.

Options:
    --distribution, -d <DistributionName>
        Run the specified distribution.

    --user, -u <UserName>
        Run as the specified user.

Arguments to manage Windows Subsystem for Linux:

    --export <DistributionName> <FileName>
        Exports the distribution to a tar file.
        The filename can be - for standard output.

    --import <DistributionName> <InstallLocation> <FileName>
        Imports the specified tar file as a new distribution.
        The filename can be - for standard input.

    --list, -l [Options]
        Lists distributions.

        Options:
            --all
                List all distributions, including distributions that are currently
                being installed or uninstalled.

            --running
                List only distributions that are currently running.

    -setdefault, -s <DistributionName>
        Sets the distribution as the default.

    --terminate, -t <DistributionName>
        Terminates the distribution.

    --unregister <DistributionName>
        Unregisters the distribution.

    --upgrade <DistributionName>
        Upgrades the distribution to the WslFs file system format.

    --help
        Display usage information.
```

## <a name="build-18277"></a><span data-ttu-id="6f9d2-132">18277 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-132">Build 18277</span></span>
<span data-ttu-id="6f9d2-133">일반 Windows에 대 한 18277 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2018/11/07/announcing-windows-10-insider-preview-build-18277/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-133">For general Windows information on build 18277 visit the [Windows blog](https://blogs.windows.com/windowsexperience/2018/11/07/announcing-windows-10-insider-preview-build-18277/).</span></span>

### <a name="wsl"></a><span data-ttu-id="6f9d2-134">WSL</span><span class="sxs-lookup"><span data-stu-id="6f9d2-134">WSL</span></span>
* <span data-ttu-id="6f9d2-135">빌드 [GH 3645] 18272에에서 도입 된 "인터페이스" 오류 해결</span><span class="sxs-lookup"><span data-stu-id="6f9d2-135">Fix "no such interface supported" error introduced in build 18272 [GH 3645]</span></span>
* <span data-ttu-id="6f9d2-136">Umount syscall [GH 3605]에 대 한 MNT_FORCE 플래그를 무시 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-136">Ignore the MNT_FORCE flag for umount syscall [GH 3605]</span></span>
* <span data-ttu-id="6f9d2-137">WSL 공식 CreatePseudoConsole API를 사용 하는 interop 전환</span><span class="sxs-lookup"><span data-stu-id="6f9d2-137">Switch WSL interop to use the official CreatePseudoConsole API</span></span>
* <span data-ttu-id="6f9d2-138">FUTEX_WAIT 다시 시작 될 때 시간 제한 값을 유지 관리</span><span class="sxs-lookup"><span data-stu-id="6f9d2-138">Maintain no timeout value when FUTEX_WAIT restarts</span></span>

## <a name="build-18272"></a><span data-ttu-id="6f9d2-139">18272 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-139">Build 18272</span></span>
<span data-ttu-id="6f9d2-140">일반 Windows에 대 한 18272 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2018/10/31/announcing-windows-10-insider-preview-build-18272/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-140">For general Windows information on build 18272 visit the [Windows blog](https://blogs.windows.com/windowsexperience/2018/10/31/announcing-windows-10-insider-preview-build-18272/).</span></span>

### <a name="wsl"></a><span data-ttu-id="6f9d2-141">WSL</span><span class="sxs-lookup"><span data-stu-id="6f9d2-141">WSL</span></span>
* <span data-ttu-id="6f9d2-142">**경고:** WSL 작동 하지 않습니다는이 빌드에는 문제가 없습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-142">**WARNING:** There is an issue in this build that makes WSL inoperable.</span></span> <span data-ttu-id="6f9d2-143">배포를 시작 하려고 할 때 "인터페이스" 오류가 표시 됩니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-143">When trying to launch your distribution you will see a “No such interface supported” error.</span></span> <span data-ttu-id="6f9d2-144">문제가 해결 되었습니다 및 다음 주 Insider 빠른 빌드에 포함 됩니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-144">The issue has been fixed and will be in next week's Insider Fast build.</span></span> <span data-ttu-id="6f9d2-145">이전에 설치한 경우 롤백할 수 있습니다 "이전 버전의 Windows 10으로 다시 이동"을 사용 하 여 이전 Windows 빌드 설정에서이 빌드에는 업데이트-> & 보안 복구-> 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-145">If you've installed this build you can roll back to the previous Windows build using “Go back to the previous version of Windows 10” in Settings->Update & Security->Recovery.</span></span>

## <a name="build-18267"></a><span data-ttu-id="6f9d2-146">18267 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-146">Build 18267</span></span>
<span data-ttu-id="6f9d2-147">일반 Windows에 대 한 18267 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2018/10/24/announcing-windows-10-insider-preview-build-18267/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-147">For general Windows information on build 18267 visit the [Windows blog](https://blogs.windows.com/windowsexperience/2018/10/24/announcing-windows-10-insider-preview-build-18267/).</span></span>

### <a name="wsl"></a><span data-ttu-id="6f9d2-148">WSL</span><span class="sxs-lookup"><span data-stu-id="6f9d2-148">WSL</span></span>
* <span data-ttu-id="6f9d2-149">좀비 프로세스 수 없습니다 수 했지만 누릴 수 있었습니다 않았고 무기한으로 문제를 해결 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-149">Fix issue where zombie process may not be reaped and remain indefinitely.</span></span>
* <span data-ttu-id="6f9d2-150">WslRegisterDistribution 오류 메시지 [GH 3592]는 최대 길이 초과 하는 경우 중단 됩니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-150">WslRegisterDistribution hangs if error message exceeds max length [GH 3592]</span></span>
* <span data-ttu-id="6f9d2-151">읽기 전용 파일 DrvFs [GH 3556]에 대 한 성공 하려면 fsync 허용</span><span class="sxs-lookup"><span data-stu-id="6f9d2-151">Allow fsync to succeed for read-only files on DrvFs [GH 3556]</span></span>
* <span data-ttu-id="6f9d2-152">[GH 3584] 내부 symlink를 만들기 전에 /bin 및 /sbin 디렉터리가 존재 하는지 확인</span><span class="sxs-lookup"><span data-stu-id="6f9d2-152">Ensure that /bin and /sbin directories exist before creating symlinks inside [GH 3584]</span></span>
* <span data-ttu-id="6f9d2-153">WSL 인스턴스에 대 한 인스턴스 종료 제한 시간 메커니즘을 추가 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-153">Added an instance termination timeout mechanism for WSL instances.</span></span> <span data-ttu-id="6f9d2-154">제한 시간을 15 초로, 인스턴스가 15 초 마지막 WSL 프로세스가 종료 된 후 종료 됩니다 즉 현재 설정 됩니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-154">The timeout is currently set to 15 seconds, meaning the instance will terminate 15 seconds after the last WSL process exits.</span></span> <span data-ttu-id="6f9d2-155">배포를 즉시 종료 하려면 다음을 사용 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-155">To terminate a distribution immediately, use:</span></span>
```
wslconfig.exe /terminate <DistributionName>
```

## <a name="build-17763-1809"></a><span data-ttu-id="6f9d2-156">17763 빌드 (1809)</span><span class="sxs-lookup"><span data-stu-id="6f9d2-156">Build 17763 (1809)</span></span>
<span data-ttu-id="6f9d2-157">일반 Windows에 대 한 17763 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2018/10/02/how-to-get-the-windows-10-october-2018-update/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-157">For general Windows information on build 17763 visit the [Windows blog](https://blogs.windows.com/windowsexperience/2018/10/02/how-to-get-the-windows-10-october-2018-update/).</span></span>

### <a name="wsl"></a><span data-ttu-id="6f9d2-158">WSL</span><span class="sxs-lookup"><span data-stu-id="6f9d2-158">WSL</span></span>
* <span data-ttu-id="6f9d2-159">동일한 스레드 우선 순위 [GH 1838] 변경에 대 한 너무 엄격한 Setpriority syscall 권한 확인</span><span class="sxs-lookup"><span data-stu-id="6f9d2-159">Setpriority syscall permission check too strict for changing same thread priority [GH 1838]</span></span>
* <span data-ttu-id="6f9d2-160">Clock_gettime(CLOCK_BOOTTIME) [GH 3434]에 대해 음수 값을 반환 하지 않으려면 비편향된 인터럽트 시간 비율 부팅 시간에 사용 되는지 확인</span><span class="sxs-lookup"><span data-stu-id="6f9d2-160">Ensure that unbiased interrupt time is used for boot time to avoid returning negative values for clock_gettime(CLOCK_BOOTTIME) [GH 3434]</span></span>
* <span data-ttu-id="6f9d2-161">WSL binfmt 인터프리터 [GH 3424]에서 symlink를 처리 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-161">Handle symlinks in the WSL binfmt interpreter [GH 3424]</span></span>
* <span data-ttu-id="6f9d2-162">Threadgroup이 리더 파일 설명자 정리 보다 효율적으로 처리 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-162">Better handling of threadgroup leader file descriptor cleanup.</span></span>
* <span data-ttu-id="6f9d2-163">WSL 데 KeQueryInterruptTimePrecise KeQueryPerformanceCounter 대신 [GH 3252] 오버플로가 발생 하지 않도록 전환</span><span class="sxs-lookup"><span data-stu-id="6f9d2-163">Switch WSL to use KeQueryInterruptTimePrecise instead of KeQueryPerformanceCounter to avoid overflow [GH 3252]</span></span>
* <span data-ttu-id="6f9d2-164">Ptrace 연결 월 [GH 1731] 시스템 호출에서 잘못 된 반환 값이 발생</span><span class="sxs-lookup"><span data-stu-id="6f9d2-164">Ptrace attach may cause bad return value from system calls [GH 1731]</span></span>
* <span data-ttu-id="6f9d2-165">여러 AF_UNIX 관련 된 수정 사항을 문제 [GH 3371]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-165">Fix several AF_UNIX related issues [GH 3371]</span></span>
* <span data-ttu-id="6f9d2-166">WSL interop 현재 작업 디렉터리를 5 대 미만의 자 [GH 3379] 이면 실패를 일으킬 수 있는 문제 해결</span><span class="sxs-lookup"><span data-stu-id="6f9d2-166">Fix issue that could cause WSL interop to fail if the current working directory is less than 5 characters long [GH 3379]</span></span>
* <span data-ttu-id="6f9d2-167">존재 하지 않는 포트 [GH 3286]에 대 한 루프백 연결 실패 한 두 번째 지연을 방지합니다</span><span class="sxs-lookup"><span data-stu-id="6f9d2-167">Avoid one second delay failing loopback connections to non-existent ports [GH 3286]</span></span>
* <span data-ttu-id="6f9d2-168">/Proc/sys/fs/file-max 스텁 파일 [GH 2893]를 추가 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-168">Add /proc/sys/fs/file-max stub file [GH 2893]</span></span>
* <span data-ttu-id="6f9d2-169">보다 정확 하 게 IPV6 범위 정보입니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-169">More accurate IPV6 scope information.</span></span>
* <span data-ttu-id="6f9d2-170">PR_SET_PTRACER 지원 [GH 3053]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-170">PR_SET_PTRACER support [GH 3053]</span></span>
* <span data-ttu-id="6f9d2-171">실수로 epoll edge 트리거 이벤트 [GH 3276]의 선택을 취소 하는 파이프 파일 시스템</span><span class="sxs-lookup"><span data-stu-id="6f9d2-171">Pipe filesystem inadvertently clearing edge-triggered epoll event [GH 3276]</span></span>
* <span data-ttu-id="6f9d2-172">Win32 실행 파일은 NTFS symlink를 통해 시작 symlink 이름 [GH 2909]을 따르지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-172">Win32 executable launched via NTFS symlink doesn't respect symlink name [GH 2909]</span></span>
* <span data-ttu-id="6f9d2-173">향상 된 좀비 지원 [GH 1353]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-173">Improved zombie support [GH 1353]</span></span>
* <span data-ttu-id="6f9d2-174">[GH 1493] Windows interop 동작을 제어 하기 위한 wsl.conf 항목 추가</span><span class="sxs-lookup"><span data-stu-id="6f9d2-174">Add wsl.conf entries for controlling Windows interop behavior [GH 1493]</span></span>
  ```
    [interop]

    enabled=false # enable launch of Windows binaries; default is true

    appendWindowsPath=false # append Windows path to $PATH variable; default is true
  ```
* <span data-ttu-id="6f9d2-175">항상 그렇지는 않음 UNIX 소켓 패밀리 형식을 [GH 1774]를 반환 하는 getsockname에 대 한 수정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-175">Fix for getsockname not always returning UNIX socket family type [GH 1774]</span></span>
* <span data-ttu-id="6f9d2-176">TIOCSTI [GH 1863]에 대 한 지원 추가</span><span class="sxs-lookup"><span data-stu-id="6f9d2-176">Add support for TIOCSTI [GH 1863]</span></span>
* <span data-ttu-id="6f9d2-177">비블로킹 소켓 연결 중 쓰기 시도 [GH 2846] EAGAIN 반환할지</span><span class="sxs-lookup"><span data-stu-id="6f9d2-177">Non-blocking sockets in the process of connecting should return EAGAIN for write attempts [GH 2846]</span></span>
* <span data-ttu-id="6f9d2-178">탑재 된 Vhd [GH 3246에 3291]에서 interop를 지원 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-178">Support interop on mounted VHDs [GH 3246, 3291]</span></span>
* <span data-ttu-id="6f9d2-179">루트 폴더 [GH 3304]에서 문제를 확인 하는 사용 권한 수정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-179">Fix permission checking issue on root folder [GH 3304]</span></span>
* <span data-ttu-id="6f9d2-180">TTY 키보드 ioctl KDGKBTYPE, KDGKBMODE 및 KDSKBMODE 제한적으로 지원 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-180">Limited support for TTY keyboard ioctls KDGKBTYPE, KDGKBMODE and KDSKBMODE.</span></span>
* <span data-ttu-id="6f9d2-181">Windows UI 응용 프로그램은 백그라운드에서 시작 하는 경우에 실행 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-181">Windows UI apps should execute even when launched in the background.</span></span>
* <span data-ttu-id="6f9d2-182">Wsl-u 또는--사용자 옵션 [GH 1203] 추가</span><span class="sxs-lookup"><span data-stu-id="6f9d2-182">Add wsl -u or --user option [GH 1203]</span></span>
* <span data-ttu-id="6f9d2-183">빠른 시작을 사용 하는 경우 WSL 시작 문제 해결 [GH 2576]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-183">Fix WSL launch issues when fast startup is enabled [GH 2576]</span></span>
* <span data-ttu-id="6f9d2-184">Unix 소켓 연결이 끊긴된 피어 자격 증명 [GH 3183]를 유지 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-184">Unix sockets need to retain disconnected peer credentials [GH 3183]</span></span>
* <span data-ttu-id="6f9d2-185">EAGAIN [GH 3191]를 사용 하 여 무기한 실패 무중단 Unix 소켓</span><span class="sxs-lookup"><span data-stu-id="6f9d2-185">Non-blocking Unix sockets failing indefinitely with EAGAIN [GH 3191]</span></span>
* <span data-ttu-id="6f9d2-186">대/소문자 = off는 새 기본 drvfs 탑재 [GH 2937, 3212, 3328] 형식</span><span class="sxs-lookup"><span data-stu-id="6f9d2-186">case=off is the new default drvfs mount type [GH 2937, 3212, 3328]</span></span>
    * <span data-ttu-id="6f9d2-187">참조 [블로그](https://blogs.msdn.microsoft.com/commandline/2018/06/14/improved-per-directory-case-sensitivity-support-in-wsl/) 자세한 내용은 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-187">See [blog](https://blogs.msdn.microsoft.com/commandline/2018/06/14/improved-per-directory-case-sensitivity-support-in-wsl/) for more information.</span></span>
* <span data-ttu-id="6f9d2-188">배포 실행을 중지 하려면 종료/wslconfig를 추가 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-188">Add wslconfig /terminate to stop running distributions.</span></span>
* <span data-ttu-id="6f9d2-189">공간을 사용 하 여 경로 올바르게 처리 하지 않는 메뉴 항목 WSL 셸 컨텍스트를 사용 하 여 문제를 해결 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-189">Fix issue with the WSL shell context menu entries that do not correctly handle paths with spaces.</span></span>
* <span data-ttu-id="6f9d2-190">확장된 특성으로 단위 디렉터리에 대/소문자 구분. 노출</span><span class="sxs-lookup"><span data-stu-id="6f9d2-190">Expose per-directory case sensitivity as an extended attribute</span></span>
* <span data-ttu-id="6f9d2-191">ARM64: 캐시 유지 관리 작업을 에뮬레이트하십시오.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-191">ARM64: Emulate cache maintenance operations.</span></span> <span data-ttu-id="6f9d2-192">확인할 [dotnet 문제](https://github.com/dotnet/core/issues/1561)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-192">Resolve [dotnet issue](https://github.com/dotnet/core/issues/1561).</span></span>
* <span data-ttu-id="6f9d2-193">DrvFs: 개인 범위에 해당 하는 문자는 이스케이프 된 문자는 이스케이프을 해제 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-193">DrvFs: only unescape characters in the private range that correspond to an escaped character.</span></span>
* <span data-ttu-id="6f9d2-194">ELF 파서 인터프리터 길이 유효성 검사 [GH 3154]에서 해제-오류 해결</span><span class="sxs-lookup"><span data-stu-id="6f9d2-194">Fix off-by-one error in ELF parser interpreter length validation [GH 3154]</span></span>
* <span data-ttu-id="6f9d2-195">과거의 시간을 사용 하 여 WSL 절대 타이머 [GH 3091] 실행 안 함</span><span class="sxs-lookup"><span data-stu-id="6f9d2-195">WSL absolute timers with a time in the past do not fire [GH 3091]</span></span>
* <span data-ttu-id="6f9d2-196">새로 만든된 재분석 지점을 부모 디렉터리에 따라서 나와 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-196">Ensure newly created reparse points are listed as such in the parent directory.</span></span>
* <span data-ttu-id="6f9d2-197">원자 단위로 DrvFs에서 대/소문자 구분 디렉터리를 만듭니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-197">Atomically create case sensitive directories in DrvFs.</span></span>
* <span data-ttu-id="6f9d2-198">추가 문제를 해결 하 고 다중 스레드 작업 파일에 있는 경우에 ENOENT를 반환할 수 키를 누릅니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-198">Fixed an additional issue where multithreaded operations could return ENOENT even though the file exists.</span></span> <span data-ttu-id="6f9d2-199">[GH 2712]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-199">[GH 2712]</span></span>
* <span data-ttu-id="6f9d2-200">고정된 WSL UMCI을 사용 하는 경우 오류를 시작 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-200">Fixed WSL launch failure when UMCI is enabled.</span></span> <span data-ttu-id="6f9d2-201">[GH 3020]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-201">[GH 3020]</span></span>
* <span data-ttu-id="6f9d2-202">WSL [GH 437 603, 1836]를 시작 하려면 탐색기 상황에 맞는 메뉴를 추가 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-202">Add explorer context menu to launch WSL [GH 437, 603, 1836].</span></span> <span data-ttu-id="6f9d2-203">를 사용 하려면 shift 키를 누르고 및 탐색기 창에서 마우스 오른쪽 단추로 클릭 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-203">To use, hold shift and right-click when in an explorer window.</span></span>
* <span data-ttu-id="6f9d2-204">Unix 소켓 비차단 동작 [GH 2822, 3100] 수정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-204">Fix Unix socket non-blocking behavior [GH 2822, 3100]</span></span>
* <span data-ttu-id="6f9d2-205">GH 2026에 보고 된 NETLINK 명령을 중지를 수정 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-205">Fix hanging NETLINK command as reported in GH 2026.</span></span>
* <span data-ttu-id="6f9d2-206">탑재 전파 플래그 [GH 2911]에 대 한 지원을 추가 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-206">Add support for mount propagation flags [GH 2911].</span></span>
* <span data-ttu-id="6f9d2-207">자르기 유발 하지 inotify 이벤트 [GH 2978]를 사용 하 여 문제를 해결 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-207">Fix issue with truncate not causing inotify events [GH 2978].</span></span>
* <span data-ttu-id="6f9d2-208">추가-셸 없이 단일 바이너리를 호출 하는 wsl.exe exec 옵션입니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-208">Add --exec option for wsl.exe to invoke a single binary without a shell.</span></span>
* <span data-ttu-id="6f9d2-209">추가-특정 배포판을 선택 하려면 wsl.exe에 대 한 배포 옵션입니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-209">Add --distribution option for wsl.exe to select a specific distro.</span></span>
* <span data-ttu-id="6f9d2-210">Dmesg 제한적으로 지원 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-210">Limited support for dmesg.</span></span> <span data-ttu-id="6f9d2-211">응용 프로그램 dmesg를 로깅할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-211">Applications can now log to dmesg.</span></span> <span data-ttu-id="6f9d2-212">WSL 드라이버 dmesg를 제한 된 정보를 기록합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-212">WSL driver logs limited information to dmesg.</span></span> <span data-ttu-id="6f9d2-213">나중에이 드라이버에서 다른 정보/진단 전달할 확장할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-213">In future, this can be extended to carry other information/diagnostics from the driver.</span></span>
    * <span data-ttu-id="6f9d2-214">참고: dmesg를 통해 현재 지원 되는 `/dev/kmsg` 장치 인터페이스입니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-214">Note: dmesg is currently supported through the `/dev/kmsg` device interface.</span></span> `syslog` <span data-ttu-id="6f9d2-215">syscall 인터페이스 아직 지원 되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-215">syscall interface is not yet supported.</span></span> <span data-ttu-id="6f9d2-216">따라서 몇 가지는 `dmesg` 명령줄 옵션 등 `-S`, `-C` 작동 하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-216">And, so, some of the `dmesg` command line options such as `-S`, `-C` don't work.</span></span>
* <span data-ttu-id="6f9d2-217">기본 gid 및 네이티브 [GH 3042]에 맞게 직렬 장치 모드 변경</span><span class="sxs-lookup"><span data-stu-id="6f9d2-217">Change default gid and mode of serial devices to match native [GH 3042]</span></span>
* <span data-ttu-id="6f9d2-218">이제 DrvFs 확장 된 특성을 지원합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-218">DrvFs now supports extended attributes.</span></span>
    * <span data-ttu-id="6f9d2-219">참고: DrvFs 확장 된 특성의 이름에 몇 가지 제한 사항이 있습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-219">Note: DrvFs has some limitations on the name of extended attributes.</span></span> <span data-ttu-id="6f9d2-220">일부 문자 (같은 '/', ':' 및 '\*') 허용 되지 않습니다 되며 확장 특성 이름은 대/소문자 구분 DrvFs에서 하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-220">Some characters (like '/', ':' and '\*') are not allowed, and extended attribute names are not case sensitive on DrvFs</span></span>

## <a name="build-18252-skip-ahead"></a><span data-ttu-id="6f9d2-221">빌드 18252 미리 건너 뛰 세요.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-221">Build 18252 (Skip Ahead)</span></span>
<span data-ttu-id="6f9d2-222">일반 Windows에 대 한 18252 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2018/10/03/announcing-windows-10-insider-preview-build-18252/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-222">For general Windows information on build 18252 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2018/10/03/announcing-windows-10-insider-preview-build-18252/).</span></span>

### <a name="wsl"></a><span data-ttu-id="6f9d2-223">WSL</span><span class="sxs-lookup"><span data-stu-id="6f9d2-223">WSL</span></span>
* <span data-ttu-id="6f9d2-224">Init 및 bsdtar 바이너리 lxssmanager dll를 별도 도구 폴더로 이동 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-224">Move init and bsdtar binaries out of lxssmanager dll and into a separate tools folder</span></span>
* <span data-ttu-id="6f9d2-225">경합 CLONE_FILES를 사용 하는 경우 파일 설명자를 닫기 주위를 수정 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-225">Fix race around closing file descriptor when using CLONE_FILES</span></span>
* <span data-ttu-id="6f9d2-226">DrvFs 경로 변환할 때 /proc/pid/mountinfo에 선택적 필드를 처리 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-226">Handle optional fields in /proc/pid/mountinfo when translating DrvFs paths</span></span>
* <span data-ttu-id="6f9d2-227">S_IFREG에 대 한 메타 데이터 지원은 되려면 DrvFs mknod 허용</span><span class="sxs-lookup"><span data-stu-id="6f9d2-227">Allow DrvFs mknod to succeed without metadata support for S_IFREG</span></span>
* <span data-ttu-id="6f9d2-228">DrvFs에 만들어진 읽기 전용 파일 [GH 3411]를 설정 하는 읽기 전용 특성이 있어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-228">Readonly files created on DrvFs should have the readonly attribute set [GH 3411]</span></span>
* <span data-ttu-id="6f9d2-229">/Sbin/mount.drvfs DrvFs 탑재를 처리 하는 도우미를 추가 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-229">Add /sbin/mount.drvfs helper to handle DrvFs mounting</span></span>
* <span data-ttu-id="6f9d2-230">DrvFs의 POSIX 이름을 사용 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-230">Use POSIX rename in DrvFs.</span></span>
* <span data-ttu-id="6f9d2-231">볼륨 GUID 없는 볼륨에서 경로 번역을 허용 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-231">Allow path translation on volumes without a volume GUID.</span></span>

## <a name="build-17738-fast"></a><span data-ttu-id="6f9d2-232">17738 (Fast) 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-232">Build 17738 (Fast)</span></span>
<span data-ttu-id="6f9d2-233">일반 Windows에 대 한 17738 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2018/08/14/announcing-windows-10-insider-preview-build-17738/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-233">For general Windows information on build 17738 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2018/08/14/announcing-windows-10-insider-preview-build-17738/).</span></span>

### <a name="wsl"></a><span data-ttu-id="6f9d2-234">WSL</span><span class="sxs-lookup"><span data-stu-id="6f9d2-234">WSL</span></span>
* <span data-ttu-id="6f9d2-235">동일한 스레드 우선 순위 [GH 1838] 변경에 대 한 너무 엄격한 Setpriority syscall 권한 확인</span><span class="sxs-lookup"><span data-stu-id="6f9d2-235">Setpriority syscall permission check too strict for changing same thread priority [GH 1838]</span></span>
* <span data-ttu-id="6f9d2-236">Clock_gettime(CLOCK_BOOTTIME) [GH 3434]에 대해 음수 값을 반환 하지 않으려면 비편향된 인터럽트 시간 비율 부팅 시간에 사용 되는지 확인</span><span class="sxs-lookup"><span data-stu-id="6f9d2-236">Ensure that unbiased interrupt time is used for boot time to avoid returning negative values for clock_gettime(CLOCK_BOOTTIME) [GH 3434]</span></span>
* <span data-ttu-id="6f9d2-237">WSL binfmt 인터프리터 [GH 3424]에서 symlink를 처리 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-237">Handle symlinks in the WSL binfmt interpreter [GH 3424]</span></span>
* <span data-ttu-id="6f9d2-238">Threadgroup이 리더 파일 설명자 정리 보다 효율적으로 처리 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-238">Better handling of threadgroup leader file descriptor cleanup.</span></span>

## <a name="build-17728-fast"></a><span data-ttu-id="6f9d2-239">17728 (Fast) 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-239">Build 17728 (Fast)</span></span>
<span data-ttu-id="6f9d2-240">일반 Windows에 대 한 17728 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2018/07/31/announcing-windows-10-insider-preview-build-17728/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-240">For general Windows information on build 17728 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2018/07/31/announcing-windows-10-insider-preview-build-17728/).</span></span>

### <a name="wsl"></a><span data-ttu-id="6f9d2-241">WSL</span><span class="sxs-lookup"><span data-stu-id="6f9d2-241">WSL</span></span>
* <span data-ttu-id="6f9d2-242">WSL 데 KeQueryInterruptTimePrecise KeQueryPerformanceCounter 대신 [GH 3252] 오버플로가 발생 하지 않도록 전환</span><span class="sxs-lookup"><span data-stu-id="6f9d2-242">Switch WSL to use KeQueryInterruptTimePrecise instead of KeQueryPerformanceCounter to avoid overflow [GH 3252]</span></span>
* <span data-ttu-id="6f9d2-243">Ptrace 연결 월 [GH 1731] 시스템 호출에서 잘못 된 반환 값이 발생</span><span class="sxs-lookup"><span data-stu-id="6f9d2-243">Ptrace attach may cause bad return value from system calls [GH 1731]</span></span>
* <span data-ttu-id="6f9d2-244">다양 한 AF_UNIX 관련 된 수정 사항을 문제 [GH 3371]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-244">Fix a number of AF_UNIX related issues [GH 3371]</span></span>
* <span data-ttu-id="6f9d2-245">WSL interop 현재 작업 디렉터리를 5 대 미만의 자 [GH 3379] 이면 실패를 일으킬 수 있는 문제 해결</span><span class="sxs-lookup"><span data-stu-id="6f9d2-245">Fix issue that could cause WSL interop to fail if the current working directory is less than 5 characters long [GH 3379]</span></span>

## <a name="build-18204-skip-ahead"></a><span data-ttu-id="6f9d2-246">빌드 18204 미리 건너 뛰 세요.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-246">Build 18204 (Skip Ahead)</span></span>
<span data-ttu-id="6f9d2-247">일반 Windows에 대 한 18204 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2018/07/25/announcing-windows-10-insider-preview-build-17723-and-build-18204/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-247">For general Windows information on build 18204 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2018/07/25/announcing-windows-10-insider-preview-build-17723-and-build-18204/).</span></span>

### <a name="wsl"></a><span data-ttu-id="6f9d2-248">WSL</span><span class="sxs-lookup"><span data-stu-id="6f9d2-248">WSL</span></span>
* <span data-ttu-id="6f9d2-249">Edge 트리거 epoll 이벤트 [GH 3276]의 선택을 취소 하는 파일 시스템 inadvertenly을 파이프</span><span class="sxs-lookup"><span data-stu-id="6f9d2-249">Pipe filesystem inadvertenly clearing edge-triggered epoll event [GH 3276]</span></span>
* <span data-ttu-id="6f9d2-250">Win32 실행 파일은 NTFS symlink를 통해 시작 symlink 이름 [GH 2909]을 따르지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-250">Win32 executable launched via NTFS symlink doesn't respect symlink name [GH 2909]</span></span>

## <a name="build-17723-fast"></a><span data-ttu-id="6f9d2-251">17723 (Fast) 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-251">Build 17723 (Fast)</span></span>
<span data-ttu-id="6f9d2-252">일반 Windows에 대 한 17723 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2018/07/25/announcing-windows-10-insider-preview-build-17723-and-build-18204/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-252">For general Windows information on build 17723 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2018/07/25/announcing-windows-10-insider-preview-build-17723-and-build-18204/).</span></span>

### <a name="wsl"></a><span data-ttu-id="6f9d2-253">WSL</span><span class="sxs-lookup"><span data-stu-id="6f9d2-253">WSL</span></span>
* <span data-ttu-id="6f9d2-254">존재 하지 않는 포트 [GH 3286]에 대 한 루프백 연결 실패 한 두 번째 지연을 방지합니다</span><span class="sxs-lookup"><span data-stu-id="6f9d2-254">Avoid one second delay failing loopback connections to non-existent ports [GH 3286]</span></span>
* <span data-ttu-id="6f9d2-255">/Proc/sys/fs/file-max 스텁 파일 [GH 2893]를 추가 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-255">Add /proc/sys/fs/file-max stub file [GH 2893]</span></span>
* <span data-ttu-id="6f9d2-256">보다 정확 하 게 IPV6 범위 정보입니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-256">More accurate IPV6 scope information.</span></span>
* <span data-ttu-id="6f9d2-257">PR_SET_PTRACER 지원 [GH 3053]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-257">PR_SET_PTRACER support [GH 3053]</span></span>
* <span data-ttu-id="6f9d2-258">Edge 트리거 epoll 이벤트 [GH 3276]의 선택을 취소 하는 파일 시스템 inadvertenly을 파이프</span><span class="sxs-lookup"><span data-stu-id="6f9d2-258">Pipe filesystem inadvertenly clearing edge-triggered epoll event [GH 3276]</span></span>
* <span data-ttu-id="6f9d2-259">Win32 실행 파일은 NTFS symlink를 통해 시작 symlink 이름 [GH 2909]을 따르지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-259">Win32 executable launched via NTFS symlink doesn't respect symlink name [GH 2909]</span></span>

## <a name="build-17713"></a><span data-ttu-id="6f9d2-260">17713 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-260">Build 17713</span></span>
<span data-ttu-id="6f9d2-261">일반 Windows에 대 한 17713 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2018/07/11/announcing-windows-10-insider-preview-build-17713/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-261">For general Windows information on build 17713 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2018/07/11/announcing-windows-10-insider-preview-build-17713/).</span></span>

### <a name="wsl"></a><span data-ttu-id="6f9d2-262">WSL</span><span class="sxs-lookup"><span data-stu-id="6f9d2-262">WSL</span></span>
* <span data-ttu-id="6f9d2-263">향상 된 좀비 지원 [GH 1353]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-263">Improved zombie support [GH 1353]</span></span>
* <span data-ttu-id="6f9d2-264">[GH 1493] Windows interop 동작을 제어 하기 위한 wsl.conf 항목 추가</span><span class="sxs-lookup"><span data-stu-id="6f9d2-264">Add wsl.conf entries for controlling Windows interop behavior [GH 1493]</span></span>
  ```
    [interop]

    enabled=false # enable launch of Windows binaries; default is true

    appendWindowsPath=false # append Windows path to $PATH variable; default is true
  ```
* <span data-ttu-id="6f9d2-265">항상 그렇지는 않음 UNIX 소켓 패밀리 형식을 [GH 1774]를 반환 하는 getsockname에 대 한 수정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-265">Fix for getsockname not always returning UNIX socket family type [GH 1774]</span></span>
* <span data-ttu-id="6f9d2-266">TIOCSTI [GH 1863]에 대 한 지원 추가</span><span class="sxs-lookup"><span data-stu-id="6f9d2-266">Add support for TIOCSTI [GH 1863]</span></span>
* <span data-ttu-id="6f9d2-267">비블로킹 소켓 연결 중 쓰기 시도 [GH 2846] EAGAIN 반환할지</span><span class="sxs-lookup"><span data-stu-id="6f9d2-267">Non-blocking sockets in the process of connecting should return EAGAIN for write attempts [GH 2846]</span></span>
* <span data-ttu-id="6f9d2-268">탑재 된 Vhd [GH 3246에 3291]에서 interop를 지원 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-268">Support interop on mounted VHDs [GH 3246, 3291]</span></span>
* <span data-ttu-id="6f9d2-269">루트 폴더 [GH 3304]에서 문제를 확인 하는 사용 권한 수정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-269">Fix permission checking issue on root folder [GH 3304]</span></span>
* <span data-ttu-id="6f9d2-270">TTY 키보드 ioctl KDGKBTYPE, KDGKBMODE 및 KDSKBMODE 제한적으로 지원 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-270">Limited support for TTY keyboard ioctls KDGKBTYPE, KDGKBMODE and KDSKBMODE.</span></span>
* <span data-ttu-id="6f9d2-271">Windows UI 응용 프로그램은 백그라운드에서 시작 하는 경우에 실행 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-271">Windows UI apps should execute even when launched in the background.</span></span>

## <a name="build-17704"></a><span data-ttu-id="6f9d2-272">17704 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-272">Build 17704</span></span>
<span data-ttu-id="6f9d2-273">일반 Windows에 대 한 17704 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2018/06/27/announcing-windows-10-insider-preview-build-17704/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-273">For general Windows information on build 17704 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2018/06/27/announcing-windows-10-insider-preview-build-17704/).</span></span>

### <a name="wsl"></a><span data-ttu-id="6f9d2-274">WSL</span><span class="sxs-lookup"><span data-stu-id="6f9d2-274">WSL</span></span>
* <span data-ttu-id="6f9d2-275">Wsl-u 또는--사용자 옵션 [GH 1203] 추가</span><span class="sxs-lookup"><span data-stu-id="6f9d2-275">Add wsl -u or --user option [GH 1203]</span></span>
* <span data-ttu-id="6f9d2-276">빠른 시작을 사용 하는 경우 WSL 시작 문제 해결 [GH 2576]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-276">Fix WSL launch issues when fast startup is enabled [GH 2576]</span></span>
* <span data-ttu-id="6f9d2-277">Unix 소켓 연결이 끊긴된 피어 자격 증명 [GH 3183]를 유지 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-277">Unix sockets need to retain disconnected peer credentials [GH 3183]</span></span>
* <span data-ttu-id="6f9d2-278">EAGAIN [GH 3191]를 사용 하 여 무기한 실패 무중단 Unix 소켓</span><span class="sxs-lookup"><span data-stu-id="6f9d2-278">Non-blocking Unix sockets failing indefinitely with EAGAIN [GH 3191]</span></span>
* <span data-ttu-id="6f9d2-279">대/소문자 = off는 새 기본 drvfs 탑재 [GH 2937, 3212, 3328] 형식</span><span class="sxs-lookup"><span data-stu-id="6f9d2-279">case=off is the new default drvfs mount type [GH 2937, 3212, 3328]</span></span>
    * <span data-ttu-id="6f9d2-280">참조 [블로그](https://blogs.msdn.microsoft.com/commandline/2018/06/14/improved-per-directory-case-sensitivity-support-in-wsl/) 자세한 내용은 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-280">See [blog](https://blogs.msdn.microsoft.com/commandline/2018/06/14/improved-per-directory-case-sensitivity-support-in-wsl/) for more information.</span></span>
* <span data-ttu-id="6f9d2-281">배포 실행을 중지 하려면 종료/wslconfig를 추가 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-281">Add wslconfig /terminate to stop running distributions.</span></span>

## <a name="build-17692"></a><span data-ttu-id="6f9d2-282">17692 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-282">Build 17692</span></span>
<span data-ttu-id="6f9d2-283">일반 Windows에 대 한 17692 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2018/06/14/announcing-windows-10-insider-preview-build-17692)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-283">For general Windows information on build 17692 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2018/06/14/announcing-windows-10-insider-preview-build-17692).</span></span>

### <a name="wsl"></a><span data-ttu-id="6f9d2-284">WSL</span><span class="sxs-lookup"><span data-stu-id="6f9d2-284">WSL</span></span>
* <span data-ttu-id="6f9d2-285">공간을 사용 하 여 경로 올바르게 처리 하지 않는 메뉴 항목 WSL 셸 컨텍스트를 사용 하 여 문제를 해결 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-285">Fix issue with the WSL shell context menu entries that do not correctly handle paths with spaces.</span></span>
* <span data-ttu-id="6f9d2-286">확장된 특성으로 단위 디렉터리에 대/소문자 구분. 노출</span><span class="sxs-lookup"><span data-stu-id="6f9d2-286">Expose per-directory case sensitivity as an extended attribute</span></span>
* <span data-ttu-id="6f9d2-287">ARM64: 캐시 유지 관리 작업을 에뮬레이트하십시오.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-287">ARM64: Emulate cache maintenance operations.</span></span> <span data-ttu-id="6f9d2-288">확인할 [dotnet 문제](https://github.com/dotnet/core/issues/1561)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-288">Resolve [dotnet issue](https://github.com/dotnet/core/issues/1561).</span></span>
* <span data-ttu-id="6f9d2-289">DrvFs: 개인 범위에 해당 하는 문자는 이스케이프 된 문자는 이스케이프을 해제 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-289">DrvFs: only unescape characters in the private range that correspond to an escaped character.</span></span>

## <a name="build-17686"></a><span data-ttu-id="6f9d2-290">17686 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-290">Build 17686</span></span>
<span data-ttu-id="6f9d2-291">일반 Windows에 대 한 17686 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2018/06/06/announcing-windows-10-insider-preview-build-17686)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-291">For general Windows information on build 17686 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2018/06/06/announcing-windows-10-insider-preview-build-17686).</span></span>

### <a name="wsl"></a><span data-ttu-id="6f9d2-292">WSL</span><span class="sxs-lookup"><span data-stu-id="6f9d2-292">WSL</span></span>
* <span data-ttu-id="6f9d2-293">ELF 파서 인터프리터 길이 유효성 검사 [GH 3154]에서 해제-오류 해결</span><span class="sxs-lookup"><span data-stu-id="6f9d2-293">Fix off-by-one error in ELF parser interpreter length validation [GH 3154]</span></span>
* <span data-ttu-id="6f9d2-294">과거의 시간을 사용 하 여 WSL 절대 타이머 [GH 3091] 실행 안 함</span><span class="sxs-lookup"><span data-stu-id="6f9d2-294">WSL absolute timers with a time in the past do not fire [GH 3091]</span></span>
* <span data-ttu-id="6f9d2-295">새로 만든된 재분석 지점을 부모 디렉터리에 따라서 나와 확인 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-295">Ensure newly created reparse points are listed as such in the parent directory.</span></span>
* <span data-ttu-id="6f9d2-296">원자 단위로 DrvFs에서 대/소문자 구분 디렉터리를 만듭니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-296">Atomically create case sensitive directories in DrvFs.</span></span>

## <a name="build-17677"></a><span data-ttu-id="6f9d2-297">17677 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-297">Build 17677</span></span>
<span data-ttu-id="6f9d2-298">일반 Windows에 대 한 17677 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2018/05/24/announcing-windows-10-insider-preview-build-17677/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-298">For general Windows information on build 17677 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2018/05/24/announcing-windows-10-insider-preview-build-17677/).</span></span>

### <a name="wsl"></a><span data-ttu-id="6f9d2-299">WSL</span><span class="sxs-lookup"><span data-stu-id="6f9d2-299">WSL</span></span>
* <span data-ttu-id="6f9d2-300">추가 문제를 해결 하 고 다중 스레드 작업 파일에 있는 경우에 ENOENT를 반환할 수 키를 누릅니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-300">Fixed an additional issue where multithreaded operations could return ENOENT even though the file exists.</span></span> <span data-ttu-id="6f9d2-301">[GH 2712]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-301">[GH 2712]</span></span>
* <span data-ttu-id="6f9d2-302">고정된 WSL UMCI을 사용 하는 경우 오류를 시작 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-302">Fixed WSL launch failure when UMCI is enabled.</span></span> <span data-ttu-id="6f9d2-303">[GH 3020]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-303">[GH 3020]</span></span>

## <a name="build-17666"></a><span data-ttu-id="6f9d2-304">17666 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-304">Build 17666</span></span>
<span data-ttu-id="6f9d2-305">일반 Windows에 대 한 17666 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2018/05/09/announcing-windows-10-insider-preview-build-17666/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-305">For general Windows information on build 17666 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2018/05/09/announcing-windows-10-insider-preview-build-17666/).</span></span>

### <a name="wsl"></a><span data-ttu-id="6f9d2-306">WSL</span><span class="sxs-lookup"><span data-stu-id="6f9d2-306">WSL</span></span>
#### <a name="warning-there-is-an-issue-preventing-wsl-from-running-on-some-amd-chipsets-gh-3134-a-fix-is-ready-and-making-its-way-to-the-insider-build-branch"></a><span data-ttu-id="6f9d2-307">경고: WSL에서 일부 AMD 칩셋 [GH 3134] 실행 방지 하는 문제가 없습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-307">WARNING: There is an issue preventing WSL from running on some AMD chipsets [GH 3134].</span></span> <span data-ttu-id="6f9d2-308">해결 방법은 준비을 높일 해당 참가자 빌드 분기입니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-308">A fix is ready and making its way to the Insider Build branch.</span></span>
* <span data-ttu-id="6f9d2-309">WSL [GH 437 603, 1836]를 시작 하려면 탐색기 상황에 맞는 메뉴를 추가 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-309">Add explorer context menu to launch WSL [GH 437, 603, 1836].</span></span> <span data-ttu-id="6f9d2-310">사용 하려면 보류 shift 및 탐색기 창에서 마우스 오른쪽 단추로 클릭 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-310">To use hold shift and right-click when in an explorer window.</span></span>
* <span data-ttu-id="6f9d2-311">Unix 소켓 비차단 동작 [GH 2822, 3100] 수정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-311">Fix unix socket non-blocking behavior [GH 2822, 3100]</span></span>
* <span data-ttu-id="6f9d2-312">GH 2026에 보고 된 NETLINK 명령을 중지를 수정 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-312">Fix hanging NETLINK command as reported in GH 2026.</span></span>
* <span data-ttu-id="6f9d2-313">탑재 전파 플래그 [GH 2911]에 대 한 지원을 추가 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-313">Add support for mount propagation flags [GH 2911].</span></span>
* <span data-ttu-id="6f9d2-314">자르기 유발 하지 inotify 이벤트 [GH 2978]를 사용 하 여 문제를 해결 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-314">Fix issue with truncate not causing inotify events [GH 2978].</span></span>
* <span data-ttu-id="6f9d2-315">추가-셸 없이 단일 바이너리를 호출 하는 wsl.exe exec 옵션입니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-315">Add --exec option for wsl.exe to invoke a single binary without a shell.</span></span>
* <span data-ttu-id="6f9d2-316">추가-특정 배포판을 선택 하려면 wsl.exe에 대 한 배포 옵션입니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-316">Add --distribution option for wsl.exe to select a specific distro.</span></span>

## <a name="build-17655-skip-ahead"></a><span data-ttu-id="6f9d2-317">빌드 17655 미리 건너 뛰 세요.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-317">Build 17655 (Skip Ahead)</span></span>
<span data-ttu-id="6f9d2-318">일반 Windows에 대 한 17655 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2018/04/25/announcing-windows-10-insider-preview-build-17655-for-skip-ahead/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-318">For general Windows information on build 17655 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2018/04/25/announcing-windows-10-insider-preview-build-17655-for-skip-ahead/).</span></span>

### <a name="wsl"></a><span data-ttu-id="6f9d2-319">WSL</span><span class="sxs-lookup"><span data-stu-id="6f9d2-319">WSL</span></span>
* <span data-ttu-id="6f9d2-320">Dmesg 제한적으로 지원 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-320">Limited support for dmesg.</span></span> <span data-ttu-id="6f9d2-321">응용 프로그램 dmesg를 로깅할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-321">Applications can now log to dmesg.</span></span> <span data-ttu-id="6f9d2-322">WSL 드라이버 dmesg를 제한 된 정보를 기록합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-322">WSL driver logs limited information to dmesg.</span></span> <span data-ttu-id="6f9d2-323">나중에이 드라이버에서 다른 정보/진단 전달할 확장할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-323">In future, this can be extended to carry other information/diagnostics from the driver.</span></span>
    * <span data-ttu-id="6f9d2-324">참고: dmesg를 통해 현재 지원 되는 `/dev/kmsg` 장치 인터페이스입니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-324">Note: dmesg is currently supported through the `/dev/kmsg` device interface.</span></span> `syslog` <span data-ttu-id="6f9d2-325">sycall 인터페이스 아직 지원 되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-325">sycall interface is not yet supported.</span></span> <span data-ttu-id="6f9d2-326">따라서 몇 가지는 `dmesg` 명령줄 옵션 등 `-S`, `-C` 작동 하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-326">And, so, some of the `dmesg` command line options such as `-S`, `-C` don't work.</span></span>
* <span data-ttu-id="6f9d2-327">다중 스레드 작업 파일에 있는 경우에 ENOENT를 반환할 수 있습니다 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-327">Fixed an issue where multithreaded operations could return ENOENT even though the file exists.</span></span> <span data-ttu-id="6f9d2-328">[GH 2712]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-328">[GH 2712]</span></span>

## <a name="build-17639-skip-ahead"></a><span data-ttu-id="6f9d2-329">빌드 17639 미리 건너 뛰 세요.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-329">Build 17639 (Skip Ahead)</span></span>
<span data-ttu-id="6f9d2-330">일반 Windows에 대 한 17639 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2018/04/04/announcing-windows-10-insider-preview-build-17639-for-skip-ahead/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-330">For general Windows information on build 17639 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2018/04/04/announcing-windows-10-insider-preview-build-17639-for-skip-ahead/).</span></span>

### <a name="wsl"></a><span data-ttu-id="6f9d2-331">WSL</span><span class="sxs-lookup"><span data-stu-id="6f9d2-331">WSL</span></span>
* <span data-ttu-id="6f9d2-332">기본 gid 및 네이티브 [GH 3042]에 맞게 직렬 장치 모드 변경</span><span class="sxs-lookup"><span data-stu-id="6f9d2-332">Change default gid and mode of serial devices to match native [GH 3042]</span></span>
* <span data-ttu-id="6f9d2-333">이제 DrvFs 확장 된 특성을 지원합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-333">DrvFs now supports extended attributes.</span></span>
    * <span data-ttu-id="6f9d2-334">참고: DrvFs 확장 된 특성의 이름에 몇 가지 제한 사항이 있습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-334">Note: DrvFs has some limitations on the name of extended attributes.</span></span> <span data-ttu-id="6f9d2-335">특히, 일부 문자 (같은 '/', ':' 및 '\*') 허용 되지 않습니다 되며 확장 특성 이름은 대/소문자 구분 DrvFs에서 하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-335">In particular, some characters (like '/', ':' and '\*') are not allowed, and extended attribute names are not case sensitive on DrvFs</span></span>

## <a name="build-17133-fast"></a><span data-ttu-id="6f9d2-336">17133 (Fast) 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-336">Build 17133 (Fast)</span></span>
<span data-ttu-id="6f9d2-337">일반 Windows에 대 한 17133 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2018/03/27/announcing-windows-10-insider-preview-build-17133-for-fast/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-337">For general Windows information on build 17133 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2018/03/27/announcing-windows-10-insider-preview-build-17133-for-fast/).</span></span>

### <a name="wsl"></a><span data-ttu-id="6f9d2-338">WSL</span><span class="sxs-lookup"><span data-stu-id="6f9d2-338">WSL</span></span>
* <span data-ttu-id="6f9d2-339">WSL에서 중지를 해결 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-339">Fix for hang in WSL.</span></span> <span data-ttu-id="6f9d2-340">[GH 3039, 3034]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-340">[GH 3039, 3034]</span></span>

## <a name="build-17128-fast"></a><span data-ttu-id="6f9d2-341">17128 (Fast) 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-341">Build 17128 (Fast)</span></span>
<span data-ttu-id="6f9d2-342">일반 Windows에 대 한 17128 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2018/03/23/announcing-windows-10-insider-preview-build-17128-for-fast/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-342">For general Windows information on build 17128 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2018/03/23/announcing-windows-10-insider-preview-build-17128-for-fast/).</span></span>

### <a name="wsl"></a><span data-ttu-id="6f9d2-343">WSL</span><span class="sxs-lookup"><span data-stu-id="6f9d2-343">WSL</span></span>
* <span data-ttu-id="6f9d2-344">없음</span><span class="sxs-lookup"><span data-stu-id="6f9d2-344">None</span></span>

## <a name="build-17627-skip-ahead"></a><span data-ttu-id="6f9d2-345">빌드 17627 미리 건너 뛰 세요.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-345">Build 17627 (Skip Ahead)</span></span>
<span data-ttu-id="6f9d2-346">일반 Windows에 대 한 17627 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2018/03/21/announcing-windows-10-insider-preview-build-17627-for-skip-ahead/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-346">For general Windows information on build 17627 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2018/03/21/announcing-windows-10-insider-preview-build-17627-for-skip-ahead/).</span></span>

### <a name="wsl"></a><span data-ttu-id="6f9d2-347">WSL</span><span class="sxs-lookup"><span data-stu-id="6f9d2-347">WSL</span></span>
* <span data-ttu-id="6f9d2-348">Futex pi 인식 작업에 대 한 지원을 추가 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-348">Add support for the futex pi-aware operations.</span></span> <span data-ttu-id="6f9d2-349">[GH 1006]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-349">[GH 1006]</span></span>
    * <span data-ttu-id="6f9d2-350">우선 순위는 현재 지원 되는 WSL 기능 제한 사항이 있지만 표준 사용을 차단 해야 하므로 note 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-350">Note that priorities are not currently a supported WSL feature so there are limitations, but standard usage should be unblocked.</span></span>
* <span data-ttu-id="6f9d2-351">WSL 프로세스에 대 한 Windows 방화벽 지원 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-351">Windows firewall support for WSL processes.</span></span> <span data-ttu-id="6f9d2-352">[GH 1852]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-352">[GH 1852]</span></span>
    * <span data-ttu-id="6f9d2-353">예를 들어는 WSL 수 있도록 모든 포트에서 수신 대기를 관리자 권한 Windows cmd를 사용 하 여 python 처리:</span><span class="sxs-lookup"><span data-stu-id="6f9d2-353">For example, to allow the WSL python process to listen on any port, use the elevated Windows cmd:</span></span>
```netsh.exe advfirewall firewall add rule name=wsl_python dir=in action=allow program="C:\users\<username>\appdata\local\packages\canonicalgrouplimited.ubuntuonwindows_79rhkp1fndgsc\localstate\rootfs\usr\bin\python2.7" enable=yes```
    * <span data-ttu-id="6f9d2-354">방화벽 규칙을 추가 하는 방법에 대 한 자세한 내용은 참조 하세요. [링크](https://support.microsoft.com/en-us/help/947709/how-to-use-the-netsh-advfirewall-firewall-context-instead-of-the-netsh)</span><span class="sxs-lookup"><span data-stu-id="6f9d2-354">For additional details on how to add firewall rules, see [link](https://support.microsoft.com/en-us/help/947709/how-to-use-the-netsh-advfirewall-firewall-context-instead-of-the-netsh)</span></span>
* <span data-ttu-id="6f9d2-355">Wsl.exe를 사용 하는 경우 사용자의 기본 셸을 따릅니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-355">Respect user's default shell when using wsl.exe.</span></span> <span data-ttu-id="6f9d2-356">[GH 2372]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-356">[GH 2372]</span></span>
* <span data-ttu-id="6f9d2-357">모든 네트워크 인터페이스가 이더넷으로 보고 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-357">Report all network interfaces as ethernet.</span></span> <span data-ttu-id="6f9d2-358">[GH 2996]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-358">[GH 2996]</span></span>
* <span data-ttu-id="6f9d2-359">/Etc/passwd 손상 된 파일의 향상 된 처리 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-359">Better handling of corrupt /etc/passwd file.</span></span> <span data-ttu-id="6f9d2-360">[GH 3001]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-360">[GH 3001]</span></span>

### <a name="console"></a><span data-ttu-id="6f9d2-361">콘솔</span><span class="sxs-lookup"><span data-stu-id="6f9d2-361">Console</span></span>
* <span data-ttu-id="6f9d2-362">수정 되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-362">No fixes.</span></span>

### <a name="ltp-results"></a><span data-ttu-id="6f9d2-363">LTP 결과:</span><span class="sxs-lookup"><span data-stu-id="6f9d2-363">LTP Results:</span></span>
<span data-ttu-id="6f9d2-364">진행 중인 테스트 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-364">Testing in progress.</span></span>

## <a name="build-17618-skip-ahead"></a><span data-ttu-id="6f9d2-365">빌드 17618 미리 건너 뛰 세요.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-365">Build 17618 (Skip Ahead)</span></span>
<span data-ttu-id="6f9d2-366">일반 Windows에 대 한 17618 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2018/03/07/announcing-windows-10-insider-preview-build-17618-skip-ahead/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-366">For general Windows information on build 17618 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2018/03/07/announcing-windows-10-insider-preview-build-17618-skip-ahead/).</span></span>

### <a name="wsl"></a><span data-ttu-id="6f9d2-367">WSL</span><span class="sxs-lookup"><span data-stu-id="6f9d2-367">WSL</span></span>
* <span data-ttu-id="6f9d2-368">NT interop pseudoconsole 기능 소개 [GH 988, 1366, 1433, 1542, 2370, 2406].</span><span class="sxs-lookup"><span data-stu-id="6f9d2-368">Introduce pseudoconsole functionality for NT interop [GH 988, 1366, 1433, 1542, 2370, 2406].</span></span>
* <span data-ttu-id="6f9d2-369">레거시 설치 메커니즘 (lxrun.exe) 더 이상 사용 되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-369">The legacy install mechanism (lxrun.exe) has been deprecated.</span></span> <span data-ttu-id="6f9d2-370">Microsoft Store 통해 배포를 설치 하기 위한 메커니즘을 지원 되는 경우</span><span class="sxs-lookup"><span data-stu-id="6f9d2-370">The supported mechanism for installing distributions is through the Microsoft Store.</span></span>

### <a name="console"></a><span data-ttu-id="6f9d2-371">콘솔</span><span class="sxs-lookup"><span data-stu-id="6f9d2-371">Console</span></span>
* <span data-ttu-id="6f9d2-372">수정 되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-372">No fixes.</span></span>

### <a name="ltp-results"></a><span data-ttu-id="6f9d2-373">LTP 결과:</span><span class="sxs-lookup"><span data-stu-id="6f9d2-373">LTP Results:</span></span>
<span data-ttu-id="6f9d2-374">진행 중인 테스트 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-374">Testing in progress.</span></span>

## <a name="build-17110"></a><span data-ttu-id="6f9d2-375">17110 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-375">Build 17110</span></span>
<span data-ttu-id="6f9d2-376">일반 Windows에 대 한 17110 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2018/02/27/announcing-windows-10-insider-preview-build-17110-fast/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-376">For general Windows information on build 17110 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2018/02/27/announcing-windows-10-insider-preview-build-17110-fast/).</span></span>

### <a name="wsl"></a><span data-ttu-id="6f9d2-377">WSL</span><span class="sxs-lookup"><span data-stu-id="6f9d2-377">WSL</span></span>
* <span data-ttu-id="6f9d2-378">/Init Windows [GH 2928]에서 종료 될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-378">Allow /init to be terminated from Windows [GH 2928].</span></span>
* <span data-ttu-id="6f9d2-379">이제 DrvFs 기본적으로 디렉터리 당 대/소문자 구분을 사용 (해당 하는 "대/소문자 dir =" 탑재 옵션).</span><span class="sxs-lookup"><span data-stu-id="6f9d2-379">DrvFs now uses per-directory case sensitivity by default (equivalent to the “case=dir” mount option).</span></span>
    * <span data-ttu-id="6f9d2-380">사용 하 여 "사례 force =" (이전 동작) 레지스트리 키를 설정 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-380">Using “case=force” (the old behavior) requires setting a registry key.</span></span> <span data-ttu-id="6f9d2-381">사용 하도록 설정 하려면 다음 명령을 실행 "대/소문자 force =" 사용 해야 할 경우: reg HKLM\SYSTEM\CurrentControlSet\Services\lxss /v DrvFsAllowForceCaseSensitivity /t REG_DWORD /d 1 추가</span><span class="sxs-lookup"><span data-stu-id="6f9d2-381">Run the following command to enable “case=force” if you need to use it: reg add HKLM\SYSTEM\CurrentControlSet\Services\lxss /v DrvFsAllowForceCaseSensitivity /t REG_DWORD /d 1</span></span>
    * <span data-ttu-id="6f9d2-382">WSL를 사용 하 여 대/소문자 구분 해야 하는 Windows의 이전 버전에서 만든 기존 디렉터리에 있는 fsutil.exe를 사용 하 여 표시할으로 대/소문자 구분: fsutil.exe 파일 setcasesensitiveinfo <path> 사용 하도록 설정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-382">If you have existing directories created with WSL in older version of Windows which need to be case sensitive, use fsutil.exe to mark them as case sensitive: fsutil.exe file setcasesensitiveinfo <path> enable</span></span>
* <span data-ttu-id="6f9d2-383">NULL 종료 uname syscall에서 반환 된 문자열입니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-383">NULL terminate strings returned from the uname syscall.</span></span>

### <a name="console"></a><span data-ttu-id="6f9d2-384">콘솔</span><span class="sxs-lookup"><span data-stu-id="6f9d2-384">Console</span></span>
* <span data-ttu-id="6f9d2-385">수정 되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-385">No fixes.</span></span>

### <a name="ltp-results"></a><span data-ttu-id="6f9d2-386">LTP 결과:</span><span class="sxs-lookup"><span data-stu-id="6f9d2-386">LTP Results:</span></span>
<span data-ttu-id="6f9d2-387">진행 중인 테스트 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-387">Testing in progress.</span></span>

## <a name="build-17107"></a><span data-ttu-id="6f9d2-388">17107 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-388">Build 17107</span></span>
<span data-ttu-id="6f9d2-389">일반 Windows에 대 한 17107 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2018/02/23/announcing-windows-10-insider-preview-build-17107-fast-ring/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-389">For general Windows information on build 17107 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2018/02/23/announcing-windows-10-insider-preview-build-17107-fast-ring/).</span></span>

### <a name="wsl"></a><span data-ttu-id="6f9d2-390">WSL</span><span class="sxs-lookup"><span data-stu-id="6f9d2-390">WSL</span></span>
* <span data-ttu-id="6f9d2-391">마스터 pty 끝점 [GH 2552]에서 TCSETSF 및 TCSETSW를 지원 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-391">Support TCSETSF and TCSETSW on master pty endpoints [GH 2552].</span></span>
* <span data-ttu-id="6f9d2-392">Interop 동시 프로세스를 시작 [GH 2813] EINVAL 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-392">Starting simultaneous interop processes can result in EINVAL [GH 2813].</span></span>
* <span data-ttu-id="6f9d2-393">PTRACE_ATTACH /proc/pid/status에서 적절 한 추적 상태를 표시 하도록 수정 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-393">Fix PTRACE_ATTACH to show proper tracing status in /proc/pid/status.</span></span>
* <span data-ttu-id="6f9d2-394">수정 경합 CLEARTID와 SETTID 플래그를 사용 하 여 단기 실행 프로세스를 복제 하는 위치는 TID 주소 선택을 취소 하지 않고 종료 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-394">Fix race where short-lived processes cloned with both the CLEARTID and SETTID flags could exit without clearing the TID address.</span></span>
* <span data-ttu-id="6f9d2-395">사전 17093 빌드에서 이동할 때 Linux 파일 시스템 디렉터리를 업그레이드할 때 메시지를 표시 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-395">Display a message when upgrading the Linux file system directories when moving from a pre-17093 build.</span></span> <span data-ttu-id="6f9d2-396">17093 파일 시스템 변경 내용에 대 한 자세한 내용은 릴리스 정보 참조 [17093](https://github.com/MicrosoftDocs/WSL/blob/live/WSL/release-notes.md#build-17093)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-396">For more details on the 17093 file system changes, see the release notes for [17093](https://github.com/MicrosoftDocs/WSL/blob/live/WSL/release-notes.md#build-17093).</span></span>

### <a name="console"></a><span data-ttu-id="6f9d2-397">콘솔</span><span class="sxs-lookup"><span data-stu-id="6f9d2-397">Console</span></span>
* <span data-ttu-id="6f9d2-398">수정 되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-398">No fixes.</span></span>

### <a name="ltp-results"></a><span data-ttu-id="6f9d2-399">LTP 결과:</span><span class="sxs-lookup"><span data-stu-id="6f9d2-399">LTP Results:</span></span>
<span data-ttu-id="6f9d2-400">진행 중인 테스트 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-400">Testing in progress.</span></span>

## <a name="build-17101"></a><span data-ttu-id="6f9d2-401">17101 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-401">Build 17101</span></span>
<span data-ttu-id="6f9d2-402">일반 Windows에 대 한 17101 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2018/02/14/announcing-windows-10-insider-preview-build-17101-fast-build-17604-skip-ahead/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-402">For general Windows information on build 17101 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2018/02/14/announcing-windows-10-insider-preview-build-17101-fast-build-17604-skip-ahead/).</span></span>

### <a name="wsl"></a><span data-ttu-id="6f9d2-403">WSL</span><span class="sxs-lookup"><span data-stu-id="6f9d2-403">WSL</span></span>
* <span data-ttu-id="6f9d2-404">Signalfd 지원 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-404">Support for signalfd.</span></span> <span data-ttu-id="6f9d2-405">[GH 129]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-405">[GH 129]</span></span>
* <span data-ttu-id="6f9d2-406">파일 이름을 개인 유니코드 문자로 인코딩하여 NTFS의 잘못 된 문자가 포함 된 지원.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-406">Support file-names containing illegal NTFS characters by encoding them as private Unicode characters.</span></span> <span data-ttu-id="6f9d2-407">[GH 1514]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-407">[GH 1514]</span></span>
* <span data-ttu-id="6f9d2-408">자동 탑재 쓰기를 지원 하지 않는 경우 읽기 전용으로 대체가 됩니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-408">Auto mount will fallback to read-only when write is not supported.</span></span> <span data-ttu-id="6f9d2-409">[GH 2603]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-409">[GH 2603]</span></span>
* <span data-ttu-id="6f9d2-410">유니코드 서로게이트 쌍 (예:이 모 지 자)의 붙여넣기를 허용 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-410">Allow pasting of Unicode surrogate pairs (like emoji characters).</span></span> <span data-ttu-id="6f9d2-411">[GH 2765]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-411">[GH 2765]</span></span>
* <span data-ttu-id="6f9d2-412">/Proc /sys에 의사 (pseudo) 파일은 읽기 반환 쓰고 준비 선택, 폴링, epoll, et al [GH 2838]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-412">Pseudo-files in /proc and /sys should return read and write ready from select, poll, epoll, et al. [GH 2838]</span></span>
* <span data-ttu-id="6f9d2-413">서비스 레지스트리 변조 또는 손상 된 경우 무한 루프로 이동 될 수 있는 문제를 해결 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-413">Fix issue that could cause service to go into infinite loop when the registry has been tampered with or is corrupt.</span></span>
* <span data-ttu-id="6f9d2-414">Netlink iproute2의 최신 (업스트림 4.14) 버전을 사용 하는 메시지를 수정 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-414">Fix netlink messages to work with newer (upstream 4.14) version of iproute2.</span></span>

### <a name="console"></a><span data-ttu-id="6f9d2-415">콘솔</span><span class="sxs-lookup"><span data-stu-id="6f9d2-415">Console</span></span>
* <span data-ttu-id="6f9d2-416">수정 되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-416">No fixes.</span></span>

### <a name="ltp-results"></a><span data-ttu-id="6f9d2-417">LTP 결과:</span><span class="sxs-lookup"><span data-stu-id="6f9d2-417">LTP Results:</span></span>
<span data-ttu-id="6f9d2-418">진행 중인 테스트 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-418">Testing in progress.</span></span>

## <a name="build-17093"></a><span data-ttu-id="6f9d2-419">17093 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-419">Build 17093</span></span>
<span data-ttu-id="6f9d2-420">일반 Windows에 대 한 17093 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2018/02/07/announcing-windows-10-insider-preview-build-17093-pc/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-420">For general Windows information on build 17093 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2018/02/07/announcing-windows-10-insider-preview-build-17093-pc/).</span></span>

#### <a name="important"></a><span data-ttu-id="6f9d2-421">중요:</span><span class="sxs-lookup"><span data-stu-id="6f9d2-421">Important:</span></span>
<span data-ttu-id="6f9d2-422">WSL이이 빌드로 업그레이드 후 처음으로 시작 하는 경우 Linux 파일 시스템 디렉터리를로 업그레이드 하는 일부 작업을 수행 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-422">When starting WSL for the first time after upgrading to this build, it needs to perform some work upgrading the Linux file system directories.</span></span> <span data-ttu-id="6f9d2-423">WSL 느리게 시작 하는 것 처럼 하므로 몇 분 정도 걸릴이 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-423">This may take up to several minutes, so WSL may appear to start slowly.</span></span> <span data-ttu-id="6f9d2-424">스토어에서 설치한 각 배포에 대 한 후에 발생 되어야이 있습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-424">This should only happen once for each distribution you have installed from the store.</span></span>
* <span data-ttu-id="6f9d2-425">DrvFs에서 대/소문자 구분 지원을 개선.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-425">Improved case sensitivity support in DrvFs.</span></span>
    * <span data-ttu-id="6f9d2-426">이제 DrvFs 디렉터리별 대/소문자 구분을 지원합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-426">DrvFs now supports per-directory case sensitivity.</span></span> <span data-ttu-id="6f9d2-427">새 플래그를 설정할 수 있는 해당 디렉터리에서 모든 작업을 처리 하도록 표시 하는 디렉터리와 대/소문자 구분, 대/소문자만 다른 파일 잘못 열려는 Windows 응용 프로그램을 허용 하는 경우</span><span class="sxs-lookup"><span data-stu-id="6f9d2-427">This is a new flag that can be set on directories to indicate all operations in those directories should be treated as case sensitive, which allows even Windows applications to correctly open files that differ only by case.</span></span>
    * <span data-ttu-id="6f9d2-428">DrvFs에 디렉터리 당 기준 대/소문자 구분을 제어 하는 새 탑재 옵션</span><span class="sxs-lookup"><span data-stu-id="6f9d2-428">DrvFs has new mount options controlling case sensitivity on a per-directory basis</span></span>
        * <span data-ttu-id="6f9d2-429">대/소문자 force =: 모든 디렉터리와 대/소문자 구분 (드라이브 루트) 제외 하 고 처리 됩니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-429">case=force: all directories are treated as case sensitive (except for the drive root).</span></span> <span data-ttu-id="6f9d2-430">WSL를 사용 하 여 만든 새 디렉터리는 대/소문자 구분으로 표시 됩니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-430">New directories created with WSL are marked as case sensitive.</span></span> <span data-ttu-id="6f9d2-431">이 새 디렉터리를 대/소문자 구분 표시를 제외 하 고 레거시 동작입니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-431">This is the legacy behavior except for marking new directories case sensitive.</span></span>
        * <span data-ttu-id="6f9d2-432">대/소문자 = dir: 디렉터리별 대/소문자 구분 플래그를 사용 하 여 디렉터리만 대/소문자; 다른 디렉터리는 대/소문자 구분.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-432">case=dir: only directories with the per-directory case sensitivity flag are treated as case sensitive; other directories are case insensitive.</span></span> <span data-ttu-id="6f9d2-433">WSL를 사용 하 여 만든 새 디렉터리는 대/소문자 구분으로 표시 됩니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-433">New directories created with WSL are marked as case sensitive.</span></span>
        * <span data-ttu-id="6f9d2-434">대/소문자 = off: 디렉터리별 대/소문자 구분 플래그를 사용 하 여 디렉터리만 대/소문자; 다른 디렉터리는 대/소문자 구분.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-434">case=off: only directories with the per-directory case sensitivity flag are treated as case sensitive; other directories are case insensitive.</span></span> <span data-ttu-id="6f9d2-435">WSL를 사용 하 여 만든 새 디렉터리는 대/소문자 구분으로 표시 됩니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-435">New directories created with WSL are marked as case insensitive.</span></span>
    * <span data-ttu-id="6f9d2-436">참고: 이전 릴리스에서 WSL에서 만든 디렉터리 없는 설정 처리 되지 것입니다 있도록으로 대/소문자 구분 사용 하는 경우이 플래그는 "사례 dir =" 옵션입니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-436">Note: directories created by WSL in previous releases do not have this flag set, so will not be treated as case sensitive if you use the “case=dir” option.</span></span> <span data-ttu-id="6f9d2-437">기존 디렉터리에서이 플래그를 설정 하는 방법을 곧 제공 됩니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-437">A way to set this flag on existing directories is coming soon.</span></span>
    * <span data-ttu-id="6f9d2-438">이러한 옵션을 사용 하 여 탑재의 예 (기존 드라이브에서 먼저 탑재 해제 해야 다양 한 옵션을 사용 하 여 탑재할 수 전에): sudo mount-t drvfs c: mnt은 / c o 사례 dir =</span><span class="sxs-lookup"><span data-stu-id="6f9d2-438">Example of mounting with these options (for existing drives, you must first unmount before you can mount with different options): sudo mount -t drvfs C: /mnt/c -o case=dir</span></span>
    * <span data-ttu-id="6f9d2-439">지금은 경우 = 강제 여전히 기본 옵션입니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-439">For now, case=force is still the default option.</span></span> <span data-ttu-id="6f9d2-440">이 대/소문자를 변경할 수는 나중에 dir =.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-440">This will be changed to case=dir in the future.</span></span>
* <span data-ttu-id="6f9d2-441">이제 사용할 수 있습니다 슬래시 Windows 경로 예: DrvFs, 탑재 하는 경우: sudo-t drvfs //server/share /mnt/share 탑재</span><span class="sxs-lookup"><span data-stu-id="6f9d2-441">You can now use forward slashes in Windows paths when mounting DrvFs, e.g.: sudo mount -t drvfs //server/share /mnt/share</span></span>
* <span data-ttu-id="6f9d2-442">이제 WSL 인스턴스 시작 [GH 2636] 중 /etc/fstab 파일을 처리합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-442">WSL now processes the /etc/fstab file during instance start [GH 2636].</span></span>
    * <span data-ttu-id="6f9d2-443">이 자동으로 DrvFs 드라이브를 탑재 하기 전에 작업 수행 fstab에서 이미 탑재 된 드라이브가 됩니다 하지 다시 탑재할 수 자동으로 특정 드라이브에 대 한 탑재 지점을 변경할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-443">This is done prior to automatically mounting DrvFs drives; any drives that were already mounted by fstab will not be remounted automatically, allowing you to change the mount point for specific drives.</span></span>
    * <span data-ttu-id="6f9d2-444">이 동작은 해제할 수 있습니다 wsl.conf를 사용 하 여 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-444">This behavior can be turned off using wsl.conf.</span></span>
* <span data-ttu-id="6f9d2-445">/Proc의 탑재를 mountinfo mountstats 파일에 백슬래시 및 공백 [GH 2799]와 같은 특수 문자가 올바르게 이스케이프</span><span class="sxs-lookup"><span data-stu-id="6f9d2-445">The mount, mountinfo and mountstats files in /proc properly escape special characters like backslashes and spaces [GH 2799]</span></span>
* <span data-ttu-id="6f9d2-446">이제 메타 데이터를 사용 하는 경우 WSL 기호화 된 링크 또는 fifos 및 소켓 같은 DrvFs를 사용 하 여 만든 특수 한 파일 복사 및 Windows에서 이동할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-446">Special files created with DrvFs such as WSL symbolic links, or fifos and sockets when metadata is enabled, can now be copied and moved from Windows.</span></span>

#### <a name="wsl-is-more-configurable-with-wslconf"></a><span data-ttu-id="6f9d2-447">WSL은 wsl.conf를 사용 하 여 구성 됩니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-447">WSL is more configurable with wsl.conf</span></span>
<span data-ttu-id="6f9d2-448">하위 시스템을 시작할 때마다 적용 되는 WSL에서 특정 기능을 자동으로 구성 하는 방법을 추가 했습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-448">We added a method for you to automatically configure certain functionality in WSL that will be applied every time you launch the subsystem.</span></span> <span data-ttu-id="6f9d2-449">자동 탑재 옵션 및 네트워크 구성이 포함 됩니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-449">This includes automount options and network configuration.</span></span> <span data-ttu-id="6f9d2-450">자세한 정보에 대 한이 블로그 게시물에: https://aka.ms/wslconf</span><span class="sxs-lookup"><span data-stu-id="6f9d2-450">Learn more about it in our blog post at: https://aka.ms/wslconf</span></span>

#### <a name="afunix-allows-socket-connections-between-linux-processes-on-wsl-and-windows-native-processes"></a><span data-ttu-id="6f9d2-451">WSL에서 Linux 프로세스와 Windows 네이티브 프로세스 사이의 소켓 연결을 허용 하는 AF_UNIX</span><span class="sxs-lookup"><span data-stu-id="6f9d2-451">AF_UNIX allows socket connections between Linux processes on WSL and Windows native processes</span></span>
<span data-ttu-id="6f9d2-452">WSL 및 Windows 응용 프로그램 이제 Unix 소켓을 통해 서로 통신할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-452">WSL and Windows applications can now communicate with each other over Unix sockets.</span></span> <span data-ttu-id="6f9d2-453">Windows에서 서비스를 실행 하 여 WSL 및 Windows 앱에 사용할 수 있도록 하 려 한다고 가정 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-453">Imagine you want to run a service in Windows and make it available to both Windows and WSL apps.</span></span> <span data-ttu-id="6f9d2-454">이제 Unix 소켓을 사용 하 여 가능한입니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-454">Now, that’s possible with Unix sockets.</span></span> <span data-ttu-id="6f9d2-455">블로그에서 자세한 내용을 게시물 읽기 https://aka.ms/afunixinterop</span><span class="sxs-lookup"><span data-stu-id="6f9d2-455">Read more in our blog post at https://aka.ms/afunixinterop</span></span>

### <a name="wsl"></a><span data-ttu-id="6f9d2-456">WSL</span><span class="sxs-lookup"><span data-stu-id="6f9d2-456">WSL</span></span>
* <span data-ttu-id="6f9d2-457">Support mmap() with MAP_NORESERVE [GH 121, 2784]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-457">Support mmap() with MAP_NORESERVE [GH 121, 2784]</span></span>
* <span data-ttu-id="6f9d2-458">CLONE_PTRACE 및 CLONE_UNTRACED [GH 121, 2781] 지원</span><span class="sxs-lookup"><span data-stu-id="6f9d2-458">Support CLONE_PTRACE and CLONE_UNTRACED [GH 121, 2781]</span></span>
* <span data-ttu-id="6f9d2-459">복제 [GH 121, 2781]에서 비 SIGCHLD 종료 신호를 처리 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-459">Handle non-SIGCHLD termination signal in clone [GH 121, 2781]</span></span>
* <span data-ttu-id="6f9d2-460">스텁 /proc/sys/fs/inotify/max_user_instances 및 /proc/sys/fs/inotify/max_user_watches [GH 1705]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-460">Stub /proc/sys/fs/inotify/max_user_instances and /proc/sys/fs/inotify/max_user_watches [GH 1705]</span></span>
* <span data-ttu-id="6f9d2-461">0이 아닌 오프셋 [GH 1884]를 사용 하 여 부하 헤더를 포함 하는 ELF 이진 파일을 로드 중 오류 발생</span><span class="sxs-lookup"><span data-stu-id="6f9d2-461">Error loading ELF binaries that contain load headers with non-zero offsets [GH 1884]</span></span>
* <span data-ttu-id="6f9d2-462">이미지를 로드할 때 후행 페이지 바이트 비워야 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-462">Zero out trailing page bytes when loading images.</span></span>
* <span data-ttu-id="6f9d2-463">여기서 execve 프로세스를 자동으로 종료 하는 경우를 줄이려면</span><span class="sxs-lookup"><span data-stu-id="6f9d2-463">Reduce cases where execve silently terminates process</span></span>

### <a name="console"></a><span data-ttu-id="6f9d2-464">콘솔</span><span class="sxs-lookup"><span data-stu-id="6f9d2-464">Console</span></span>
* <span data-ttu-id="6f9d2-465">수정 되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-465">No fixes.</span></span>

### <a name="ltp-results"></a><span data-ttu-id="6f9d2-466">LTP 결과:</span><span class="sxs-lookup"><span data-stu-id="6f9d2-466">LTP Results:</span></span>
<span data-ttu-id="6f9d2-467">진행 중인 테스트 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-467">Testing in progress.</span></span>

## <a name="build-17083"></a><span data-ttu-id="6f9d2-468">17083 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-468">Build 17083</span></span>
<span data-ttu-id="6f9d2-469">일반 Windows에 대 한 17083 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2018/01/24/announcing-windows-10-insider-preview-build-17083-for-pc/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-469">For general Windows information on build 17083 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2018/01/24/announcing-windows-10-insider-preview-build-17083-for-pc/).</span></span>

### <a name="wsl"></a><span data-ttu-id="6f9d2-470">WSL</span><span class="sxs-lookup"><span data-stu-id="6f9d2-470">WSL</span></span>
* <span data-ttu-id="6f9d2-471">[GH 2798, 2801, 2857] epoll와 관련 된 고정된 버그 확인</span><span class="sxs-lookup"><span data-stu-id="6f9d2-471">Fixed bugcheck related to epoll [GH 2798, 2801, 2857]</span></span>
* <span data-ttu-id="6f9d2-472">ASLR [GH 1185, 2870]을 해제 하는 경우 고정된 중지</span><span class="sxs-lookup"><span data-stu-id="6f9d2-472">Fixed hangs when turning off ASLR [GH 1185, 2870]</span></span>
* <span data-ttu-id="6f9d2-473">Mmap 작업이 표시 원자성 [GH 2732] 확인</span><span class="sxs-lookup"><span data-stu-id="6f9d2-473">Ensure mmap operations appear atomic [GH 2732]</span></span>

### <a name="console"></a><span data-ttu-id="6f9d2-474">콘솔</span><span class="sxs-lookup"><span data-stu-id="6f9d2-474">Console</span></span>
* <span data-ttu-id="6f9d2-475">수정 되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-475">No fixes.</span></span>

### <a name="ltp-results"></a><span data-ttu-id="6f9d2-476">LTP 결과:</span><span class="sxs-lookup"><span data-stu-id="6f9d2-476">LTP Results:</span></span>
<span data-ttu-id="6f9d2-477">진행 중인 테스트 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-477">Testing in progress.</span></span>

## <a name="build-17074"></a><span data-ttu-id="6f9d2-478">17074 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-478">Build 17074</span></span>
<span data-ttu-id="6f9d2-479">일반 Windows에 대 한 17074 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2018/01/11/announcing-windows-10-insider-preview-build-17074-pc/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-479">For general Windows information on build 17074 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2018/01/11/announcing-windows-10-insider-preview-build-17074-pc/).</span></span>

### <a name="wsl"></a><span data-ttu-id="6f9d2-480">WSL</span><span class="sxs-lookup"><span data-stu-id="6f9d2-480">WSL</span></span>
* <span data-ttu-id="6f9d2-481">고정 된 저장소 형식의 DrvFs 메타 데이터 [GH 2777]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-481">Fixed storage format of DrvFs metadata [GH 2777]</span></span> </br>
<span data-ttu-id="6f9d2-482">**중요:** 이 빌드는 잘못 되거나 전혀 표시 되기 전의 DrvFs 메타 데이터입니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-482">**Important:** DrvFs metadata created before this build will show up incorrectly or not at all.</span></span> <span data-ttu-id="6f9d2-483">영향을 받는 파일을 수정 하려면 메타 데이터를 다시 적용할 chmod 및 chown를 사용 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-483">To fix affected files, use chmod and chown to re-apply the metadata.</span></span>
* <span data-ttu-id="6f9d2-484">여러 신호 및 다시 시작 가능한 syscall를 사용 하 여 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-484">Fixed issue with multiple signals and restartable syscalls.</span></span>

### <a name="console"></a><span data-ttu-id="6f9d2-485">콘솔</span><span class="sxs-lookup"><span data-stu-id="6f9d2-485">Console</span></span>
* <span data-ttu-id="6f9d2-486">수정 되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-486">No fixes.</span></span>

### <a name="ltp-results"></a><span data-ttu-id="6f9d2-487">LTP 결과:</span><span class="sxs-lookup"><span data-stu-id="6f9d2-487">LTP Results:</span></span>
<span data-ttu-id="6f9d2-488">진행 중인 테스트 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-488">Testing in progress.</span></span>

## <a name="build-17063"></a><span data-ttu-id="6f9d2-489">17063 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-489">Build 17063</span></span>
<span data-ttu-id="6f9d2-490">일반 Windows에 대 한 17063 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2017/12/19/announcing-windows-10-insider-preview-build-17063-pc/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-490">For general Windows information on build 17063 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2017/12/19/announcing-windows-10-insider-preview-build-17063-pc/).</span></span>

### <a name="wsl"></a><span data-ttu-id="6f9d2-491">WSL</span><span class="sxs-lookup"><span data-stu-id="6f9d2-491">WSL</span></span>
* <span data-ttu-id="6f9d2-492">DrvFs 추가 Linux 메타 데이터를 지원합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-492">DrvFs supports additional Linux metadata.</span></span> <span data-ttu-id="6f9d2-493">따라서, 소유자 및 chmod/chown 그리고 fifos, unix 소켓 및 장치 파일과 같은 특수 한 파일의 생성을 사용 하 여 파일의 모드를 설정 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-493">This allows setting the owner and mode of files using chmod/chown, and also the creation of special files such as fifos, unix sockets and device files.</span></span> <span data-ttu-id="6f9d2-494">이 사용 되지 기본적으로 현재 여전히 실험적이 이기 때문입니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-494">This is disabled by default for now since it's still experimental.</span></span>
<span data-ttu-id="6f9d2-495">**참고:**  DrvFs에서 사용 하는 메타 데이터 형식에서 버그를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-495">**Note:**  We fixed a bug in the metadata format used by DrvFs.</span></span> <span data-ttu-id="6f9d2-496">메타 데이터 실험에 대 한이 빌드에 작동 하는 동안 이후 빌드 올바르게으로이 빌드에 의해 만들어진 메타 데이터를 읽지 못합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-496">While metadata works on this build for experimentation, future builds will not correctly read metadata created by this build.</span></span>  <span data-ttu-id="6f9d2-497">수정 된 파일의 소유자를 수동으로 업데이트 해야 하 고 사용자 지정 장치 ID 사용 하 여 장치를 다시 생성 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-497">You might need to manually update owner for modified files and devices with a custom device ID will have to be recreated.</span></span>

  <span data-ttu-id="6f9d2-498">메타 데이터 옵션을 사용 하 여 탑재 DrvFs을 사용 하려면 (기존 탑재를 사용 하려면 먼저 탑재 해제 해야 해당):</span><span class="sxs-lookup"><span data-stu-id="6f9d2-498">To enable, mount DrvFs with the metadata option (to enable it on an existing mount, you must first unmount it):</span></span>

  ```bash
  mount -t drvfs C: /mnt/c -o metadata
  ```

  <span data-ttu-id="6f9d2-499">Linux 권한은 파일에 추가 메타 데이터로 추가한 Windows 사용 권한에 영향을 주지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-499">Linux permissions are added as additional metadata to the file; they do not affect the Windows permissions.</span></span>  <span data-ttu-id="6f9d2-500">기억 메타 데이터를 제거할 수 있습니다 Windows 편집기를 사용 하 여 파일을 편집 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-500">Remember, editing a file using a Windows editor may remove the metadata.</span></span> <span data-ttu-id="6f9d2-501">이 경우 파일의 기본 권한으로 되돌아갑니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-501">In this case, the file will revert to its default permissions.</span></span>

* <span data-ttu-id="6f9d2-502">메타 데이터 없이 제어 파일에 추가 탑재 옵션 DrvFs입니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-502">Added mount options to DrvFs to control files without metadata.</span></span>
  * <span data-ttu-id="6f9d2-503">uid: 모든 파일의 소유자에 사용 된 사용자 ID입니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-503">uid: the user ID used for the owner of all files.</span></span>
  * <span data-ttu-id="6f9d2-504">gid: 모든 파일의 소유자에 사용 된 그룹 ID입니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-504">gid: the group ID used for the owner of all files.</span></span>
  * <span data-ttu-id="6f9d2-505">umask: 모든 파일 및 디렉터리를 제외 하려면 사용 권한 마스크를 8 진수입니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-505">umask: an octal mask of permissions to exclude for all files and directories.</span></span>
  * <span data-ttu-id="6f9d2-506">fmask: 제외할 모든 일반 파일에 대 한 사용 권한 마스크를 8 진수입니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-506">fmask: an octal mask of permissions to exclude for all regular files.</span></span>
  * <span data-ttu-id="6f9d2-507">dmask: 모든 디렉터리를 제외 하려면 사용 권한 마스크를 8 진수입니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-507">dmask: an octal mask of permissions to exclude for all directories.</span></span>

  <span data-ttu-id="6f9d2-508">예를 들어 다음과 같은 가치를 제공해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-508">For example:</span></span>
  ```
  mount -t drvfs C: /mnt/c -o uid=1000,gid=1000,umask=22,fmask=111
  ```

  <span data-ttu-id="6f9d2-509">메타 데이터 없이 파일에 대 한 기본 사용 권한을 지정 하는 메타 데이터 옵션을 사용 하 여 결합 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-509">Combine with the metadata option to specify default permissions for files without metadata.</span></span>

* <span data-ttu-id="6f9d2-510">새 환경 변수를 도입 `WSLENV`를 환경 변수 WSL 및 Win32 간에 전달 되는 방식을 구성 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-510">Introduced a new environment variable, `WSLENV`, to configure how environment variables flow between WSL and Win32.</span></span>

  <span data-ttu-id="6f9d2-511">예를 들어 다음과 같은 가치를 제공해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-511">For example:</span></span>

  ``` bash
  WSLENV=GOPATH/l:USERPROFILE/pu:DISPLAY
  ```

  `WSLENV` <span data-ttu-id="6f9d2-512">Win32에서 WSL 프로세스 또는 WSL에서 Win32 프로세스를 시작할 때 포함할 수 있는 환경 변수의 콜론으로 구분 된 목록이입니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-512">is a colon-delimited list of environment variables that can be included when launching WSL processes from Win32 or Win32 processes from WSL.</span></span>  <span data-ttu-id="6f9d2-513">각 변수 슬래시 뒤에 변환 하는 방법을 지정 하는 플래그를 사용 하 여 접미사 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-513">Each variable can be suffixed with a slash followed by flags to specify how it is translated.</span></span>
  * <span data-ttu-id="6f9d2-514">p: 값은 Win32 경로 및 WSL 경로 간에 변환 해야 하는 경로.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-514">p: The value is a path that should be translated between WSL paths and Win32 paths.</span></span>
  * <span data-ttu-id="6f9d2-515">l: 값은 경로의 목록.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-515">l: The value is a list of paths.</span></span> <span data-ttu-id="6f9d2-516">WSL를에서 콜론으로 구분 된 목록입니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-516">In WSL, it is a colon-delimited list.</span></span> <span data-ttu-id="6f9d2-517">Win32에서 세미콜론으로 구분 된 목록입니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-517">In Win32, it is a semicolon-delimited list.</span></span>
  * <span data-ttu-id="6f9d2-518">u: 값만 포함 해야 WSL Win32에서 호출 하는 경우</span><span class="sxs-lookup"><span data-stu-id="6f9d2-518">u: The value should only be included when invoking WSL from Win32</span></span>
  * <span data-ttu-id="6f9d2-519">w: 값만 포함 해야 WSL에서 Win32를 호출 하는 경우</span><span class="sxs-lookup"><span data-stu-id="6f9d2-519">w: The value should only be included when invoking Win32 from WSL</span></span>

  <span data-ttu-id="6f9d2-520">설정할 수 있습니다 `WSLENV` .bashrc 또는 사용자에 대 한 사용자 지정 Windows 환경에서.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-520">You can set `WSLENV` in .bashrc or in the custom Windows environment for your user.</span></span>

* <span data-ttu-id="6f9d2-521">drvfs 탑재 tar에서 타임 스탬프를 올바르게 유지 cp-p (GH 1939)</span><span class="sxs-lookup"><span data-stu-id="6f9d2-521">drvfs mounts correctly preserves timestamps from tar, cp -p (GH 1939)</span></span>
* <span data-ttu-id="6f9d2-522">drvfs symlink (GH 2641) 정확한 크기를 보고합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-522">drvfs symlinks report the correct size (GH 2641)</span></span>
* <span data-ttu-id="6f9d2-523">매우 큰 IO 크기 (GH 2653)에 대 한 작동에 대 한 읽기/쓰기</span><span class="sxs-lookup"><span data-stu-id="6f9d2-523">read/write works for very large IO sizes (GH 2653)</span></span>
* <span data-ttu-id="6f9d2-524">프로세스 그룹 (GH 2534) Id 사용 하 여 waitpid 작동</span><span class="sxs-lookup"><span data-stu-id="6f9d2-524">waitpid works with process group IDs (GH 2534)</span></span>
* <span data-ttu-id="6f9d2-525">향상 된 mmap 성능을 상당히 큰 예약 지역 선택 합니다. ghc 빨라집니다 (GH 1671)</span><span class="sxs-lookup"><span data-stu-id="6f9d2-525">significantly improved mmap performance for large reserve regions; improves ghc performance (GH 1671)</span></span>
* <span data-ttu-id="6f9d2-526">READ_IMPLIES_EXEC;에 대 한 성격 지원 최대 및 clisp (GH 1185)를 수정합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-526">personality supports for READ_IMPLIES_EXEC; fixes maxima and clisp (GH 1185)</span></span>
* <span data-ttu-id="6f9d2-527">mprotect PROT_GROWSDOWN; 지원 수정 clisp (GH 1128)</span><span class="sxs-lookup"><span data-stu-id="6f9d2-527">mprotect supports PROT_GROWSDOWN; fixes clisp (GH 1128)</span></span>
* <span data-ttu-id="6f9d2-528">모드를 과도 하 게 페이지 오류 수정 수정 sbcl (GH 1128)</span><span class="sxs-lookup"><span data-stu-id="6f9d2-528">page fault fixes in overcommit mode; fixes sbcl (GH 1128)</span></span>
* <span data-ttu-id="6f9d2-529">복제는 많은 플래그 조합이 지원</span><span class="sxs-lookup"><span data-stu-id="6f9d2-529">clone supports more flags combinations</span></span>
* <span data-ttu-id="6f9d2-530">선택/epoll epoll 파일 (이전에 아무)를 지원 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-530">Support select/epoll of epoll files (previously a no-op).</span></span>
* <span data-ttu-id="6f9d2-531">구현 되지 않은 syscall의 ptrace를 알립니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-531">Notify ptrace of unimplemented syscalls.</span></span>
* <span data-ttu-id="6f9d2-532">Resolv.conf 이름 서버 [GH 2694]을 생성 하는 경우 등록 되지 않은 인터페이스를 무시 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-532">Ignore interfaces that are not up when generating resolv.conf nameservers [GH 2694]</span></span>
* <span data-ttu-id="6f9d2-533">실제 주소가 없는 네트워크 인터페이스를 열거 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-533">Enumerate network interfaces with no physical address.</span></span> <span data-ttu-id="6f9d2-534">[GH 2685]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-534">[GH 2685]</span></span>
* <span data-ttu-id="6f9d2-535">추가 버그 수정 및 개선 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-535">Additional bug fixes and improvements.</span></span>

### <a name="linux-tools-available-to-developers-on-windows"></a><span data-ttu-id="6f9d2-536">Windows에서 개발자에 게 제공 되는 Linux 도구</span><span class="sxs-lookup"><span data-stu-id="6f9d2-536">Linux tools available to developers on Windows</span></span>

* <span data-ttu-id="6f9d2-537">Windows 명령줄 도구 체인에 bsdtar (tar) 및 넘기기가 포함 됩니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-537">Windows Command line Toolchain includes bsdtar (tar) and curl.</span></span>
  <span data-ttu-id="6f9d2-538">읽기 [이 블로그](https://aka.ms/tarcurlwindows) 이러한 두 가지 새로운 도구를 추가 하는 방법에 대 한 자세한 정보를 어떻게 개발자 환경에서 Windows 셰이핑 하는 이러한 참조 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-538">Read [this blog](https://aka.ms/tarcurlwindows) to learn more about the addition of these two new tools and see how they’re shaping the developer experience on Windows.</span></span>

*   `AF_UNIX` <span data-ttu-id="6f9d2-539">Windows Insider SDK (17061 이상)에서 제공 됩니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-539">is available in the Windows Insider SDK (17061+).</span></span>
  <span data-ttu-id="6f9d2-540">읽기 [이 블로그](https://blogs.msdn.microsoft.com/commandline/2017/12/19/af_unix-comes-to-windows/) 에 대해 자세히 알아보려면 `AF_UNIX` 개발자가 Windows에서 사용할 수 하는 방법입니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-540">Read [this blog](https://blogs.msdn.microsoft.com/commandline/2017/12/19/af_unix-comes-to-windows/) to learn more about `AF_UNIX` and how developers on Windows can use it.</span></span>

### <a name="console"></a><span data-ttu-id="6f9d2-541">콘솔</span><span class="sxs-lookup"><span data-stu-id="6f9d2-541">Console</span></span>
* <span data-ttu-id="6f9d2-542">수정 되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-542">No fixes.</span></span>

### <a name="ltp-results"></a><span data-ttu-id="6f9d2-543">LTP 결과:</span><span class="sxs-lookup"><span data-stu-id="6f9d2-543">LTP Results:</span></span>
<span data-ttu-id="6f9d2-544">진행 중인 테스트 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-544">Testing in progress.</span></span>


## <a name="build-17046"></a><span data-ttu-id="6f9d2-545">17046 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-545">Build 17046</span></span>

<span data-ttu-id="6f9d2-546">일반 Windows에 대 한 17046 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2017/11/22/announcing-windows-10-insider-preview-build-17046-pc)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-546">For general Windows information on build 17046 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2017/11/22/announcing-windows-10-insider-preview-build-17046-pc).</span></span>

### <a name="fixed"></a><span data-ttu-id="6f9d2-547">고정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-547">Fixed</span></span>
#### <a name="wsl"></a><span data-ttu-id="6f9d2-548">WSL</span><span class="sxs-lookup"><span data-stu-id="6f9d2-548">WSL</span></span>
- <span data-ttu-id="6f9d2-549">활성 터미널을 하지 않고 실행 하는 프로세스를 허용 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-549">Allow processes to run without an active terminal.</span></span> <span data-ttu-id="6f9d2-550">[GH 709, 1007, 1511, 2252, 2391, et al.]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-550">[GH 709, 1007, 1511, 2252, 2391, et al.]</span></span>
- <span data-ttu-id="6f9d2-551">CLONE_VFORK 및 CLONE_VM 더 나은 지원 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-551">Better support of CLONE_VFORK and CLONE_VM.</span></span> <span data-ttu-id="6f9d2-552">[GH 1878, 2615]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-552">[GH 1878, 2615]</span></span>
- <span data-ttu-id="6f9d2-553">WSL 네트워킹 작업에 대 한 TDI 필터 드라이버를 건너뜁니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-553">Skip TDI filter drivers for WSL networking operations.</span></span> <span data-ttu-id="6f9d2-554">[GH 1554]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-554">[GH 1554]</span></span>
- <span data-ttu-id="6f9d2-555">특정 조건이 충족 되 면 DrvFs NT symlink를 만듭니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-555">DrvFs creates NT symlinks when certain conditions are met.</span></span> <span data-ttu-id="6f9d2-556">[GH 353, 1475, 2602]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-556">[GH 353, 1475, 2602]</span></span>
    - <span data-ttu-id="6f9d2-557">링크 대상 상대 이어야 하 고 모든 탑재 지점 또는 symlink를 넘지 않아야 합니다 하며 존재 해야 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-557">The link target must be relative, must not cross any mount points or symlinks, and must exist.</span></span>
    - <span data-ttu-id="6f9d2-558">사용자는 SE_CREATE_SYMBOLIC_LINK_PRIVILEGE (일반적으로 해야 wsl.exe 권한 시작)에 있어야 합니다. 개발자 모드가 켜져 하지 않는 한 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-558">The user must have SE_CREATE_SYMBOLIC_LINK_PRIVILEGE (this normally requires you to launch wsl.exe elevated), unless Developer Mode is turned on.</span></span>
    - <span data-ttu-id="6f9d2-559">다른 모든 상황에서 DrvFs 여전히 WSL symlink를 만듭니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-559">In all other situations, DrvFs still creates WSL symlinks.</span></span>
- <span data-ttu-id="6f9d2-560">관리자 권한 및 권한 상승 되지 않은 WSL 인스턴스를 동시에 실행할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-560">Allow running elevated and non-elevated WSL instances simultaneously.</span></span>
- <span data-ttu-id="6f9d2-561">Support /proc/sys/kernel/yama/ptrace_scope</span><span class="sxs-lookup"><span data-stu-id="6f9d2-561">Support /proc/sys/kernel/yama/ptrace_scope</span></span>
- <span data-ttu-id="6f9d2-562">WSL <>-Windows 경로 변환을 수행 하는 wslpath를 추가 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-562">Add wslpath to do WSL<->Windows path conversions.</span></span> <span data-ttu-id="6f9d2-563">[GH 522, 1243, 1834, 2327, et al.]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-563">[GH 522, 1243, 1834, 2327, et al.]</span></span>
  ```
    wslpath usage:
      -a    force result to absolute path format
      -u    translate from a Windows path to a WSL path (default)
      -w    translate from a WSL path to a Windows path
      -m    translate from a WSL path to a Windows path, with ‘/’ instead of ‘\\’

      EX: wslpath ‘c:\users’
  ```
  #### <a name="console"></a><span data-ttu-id="6f9d2-564">콘솔</span><span class="sxs-lookup"><span data-stu-id="6f9d2-564">Console</span></span>
- <span data-ttu-id="6f9d2-565">수정 되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-565">No fixes.</span></span>

### <a name="ltp-results"></a><span data-ttu-id="6f9d2-566">LTP 결과:</span><span class="sxs-lookup"><span data-stu-id="6f9d2-566">LTP Results:</span></span>
<span data-ttu-id="6f9d2-567">진행 중인 테스트 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-567">Testing in progress.</span></span>


## <a name="build-17040"></a><span data-ttu-id="6f9d2-568">17040 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-568">Build 17040</span></span>

<span data-ttu-id="6f9d2-569">일반 Windows에 대 한 빌드 17040에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2017/11/16/announcing-windows-10-insider-preview-build-17040-pc)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-569">For general Windows information on build 17040 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2017/11/16/announcing-windows-10-insider-preview-build-17040-pc).</span></span><br/>


### <a name="fixed"></a><span data-ttu-id="6f9d2-570">고정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-570">Fixed</span></span>
#### <a name="wsl"></a><span data-ttu-id="6f9d2-571">WSL</span><span class="sxs-lookup"><span data-stu-id="6f9d2-571">WSL</span></span>
- <span data-ttu-id="6f9d2-572">17035 이후 수정 되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-572">No fixes since 17035.</span></span>

#### <a name="console"></a><span data-ttu-id="6f9d2-573">콘솔</span><span class="sxs-lookup"><span data-stu-id="6f9d2-573">Console</span></span>
- <span data-ttu-id="6f9d2-574">17035 이후 수정 되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-574">No fixes since 17035.</span></span>

### <a name="ltp-results"></a><span data-ttu-id="6f9d2-575">LTP 결과:</span><span class="sxs-lookup"><span data-stu-id="6f9d2-575">LTP Results:</span></span>
<span data-ttu-id="6f9d2-576">진행 중인 테스트 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-576">Testing in progress.</span></span>

## <a name="build-17035"></a><span data-ttu-id="6f9d2-577">17035 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-577">Build 17035</span></span>

<span data-ttu-id="6f9d2-578">일반 Windows에 대 한 17035 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2017/11/08/announcing-windows-10-insider-preview-build-17035-pc)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-578">For general Windows information on build 17035 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2017/11/08/announcing-windows-10-insider-preview-build-17035-pc).</span></span><br/>


### <a name="fixed"></a><span data-ttu-id="6f9d2-579">고정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-579">Fixed</span></span>
#### <a name="wsl"></a><span data-ttu-id="6f9d2-580">WSL</span><span class="sxs-lookup"><span data-stu-id="6f9d2-580">WSL</span></span>
- <span data-ttu-id="6f9d2-581">DrvFs에서 파일에 액세스할 경우에 따라 EINVAL를 사용 하 여 실패할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-581">Accessing files on DrvFs could occasionally fail with EINVAL.</span></span> <span data-ttu-id="6f9d2-582">[GH 2448]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-582">[GH 2448]</span></span>

#### <a name="console"></a><span data-ttu-id="6f9d2-583">콘솔</span><span class="sxs-lookup"><span data-stu-id="6f9d2-583">Console</span></span>
- <span data-ttu-id="6f9d2-584">VT 모드에서 줄 삽입/삭제 하는 경우 몇 가지 색 손실입니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-584">Some color loss when inserting/deleting lines in VT mode.</span></span>

### <a name="ltp-results"></a><span data-ttu-id="6f9d2-585">LTP 결과:</span><span class="sxs-lookup"><span data-stu-id="6f9d2-585">LTP Results:</span></span>
<span data-ttu-id="6f9d2-586">진행 중인 테스트 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-586">Testing in progress.</span></span>

## <a name="build-17025"></a><span data-ttu-id="6f9d2-587">빌드 17025</span><span class="sxs-lookup"><span data-stu-id="6f9d2-587">Build 17025</span></span>

<span data-ttu-id="6f9d2-588">일반 Windows에 대 한 빌드 17025에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2017/10/25/announcing-windows-10-insider-preview-build-17025-pc)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-588">For general Windows information on build 17025 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2017/10/25/announcing-windows-10-insider-preview-build-17025-pc).</span></span><br/>


### <a name="fixed"></a><span data-ttu-id="6f9d2-589">고정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-589">Fixed</span></span>
#### <a name="wsl"></a><span data-ttu-id="6f9d2-590">WSL</span><span class="sxs-lookup"><span data-stu-id="6f9d2-590">WSL</span></span>
- <span data-ttu-id="6f9d2-591">새 포그라운드 프로세스 그룹 [GH 1653, 2510]의 초기 프로세스를 시작 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-591">Start initial processes in a new foreground process group [GH 1653, 2510].</span></span>
- <span data-ttu-id="6f9d2-592">SIGHUP 배달 [GH 2496] 수정합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-592">SIGHUP delivery fixes [GH 2496].</span></span>
- <span data-ttu-id="6f9d2-593">[GH 2497] 아무 것도 제공 하는 경우 기본 가상 브리지 이름을 생성 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-593">Generate default virtual bridge name if none provided [GH 2497].</span></span>
- <span data-ttu-id="6f9d2-594">Implement /proc/sys/kernel/random/boot_id [GH 2518].</span><span class="sxs-lookup"><span data-stu-id="6f9d2-594">Implement /proc/sys/kernel/random/boot_id [GH 2518].</span></span>
- <span data-ttu-id="6f9d2-595">더 interop stdout/stderr 파이프를 수정합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-595">More interop stdout/stderr pipe fixes.</span></span>
- <span data-ttu-id="6f9d2-596">스텁 syncfs 시스템 호출 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-596">Stub syncfs system call.</span></span>

#### <a name="console"></a><span data-ttu-id="6f9d2-597">콘솔</span><span class="sxs-lookup"><span data-stu-id="6f9d2-597">Console</span></span>
- <span data-ttu-id="6f9d2-598">제 3 자 콘솔 [GH 111]에 대 한 입력된 VT 번역 수정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-598">Fix input VT translation for third party consoles [GH 111]</span></span>

### <a name="ltp-results"></a><span data-ttu-id="6f9d2-599">LTP 결과:</span><span class="sxs-lookup"><span data-stu-id="6f9d2-599">LTP Results:</span></span>
<span data-ttu-id="6f9d2-600">진행 중인 테스트 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-600">Testing in progress.</span></span>

## <a name="build-17017"></a><span data-ttu-id="6f9d2-601">17017 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-601">Build 17017</span></span>

<span data-ttu-id="6f9d2-602">일반 Windows에 대 한 17017 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2017/10/13/announcing-windows-10-insider-preview-build-17017-pc)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-602">For general Windows information on build 17017 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2017/10/13/announcing-windows-10-insider-preview-build-17017-pc).</span></span><br/>


### <a name="fixed"></a><span data-ttu-id="6f9d2-603">고정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-603">Fixed</span></span>
#### <a name="wsl"></a><span data-ttu-id="6f9d2-604">WSL</span><span class="sxs-lookup"><span data-stu-id="6f9d2-604">WSL</span></span>
- <span data-ttu-id="6f9d2-605">빈 ELF 프로그램 헤더 [GH 330]를 무시 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-605">Ignore empty ELF program headers [GH 330].</span></span>
- <span data-ttu-id="6f9d2-606">비 대화형 사용자에 대 한 WSL 인스턴스를 만드는 LxssManager 허용 (ssh 지원 작업을 예약 하 고) [GH 777, 1602].</span><span class="sxs-lookup"><span data-stu-id="6f9d2-606">Allow LxssManager to create WSL instances for non-interactive users (ssh and scheduled task support) [GH 777, 1602].</span></span>
- <span data-ttu-id="6f9d2-607">WSL 지원 Win32-> WSL ("초기") 시나리오 [GH 1228]-> 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-607">Support WSL->Win32->WSL ("inception") scenarios [GH 1228].</span></span>
- <span data-ttu-id="6f9d2-608">Interop [GH 1614]를 통해 호출 되는 콘솔 응용 프로그램 종료에 대 한 제한적으로 지원 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-608">Limited support for termination of console apps invoked via interop [GH 1614].</span></span>
- <span data-ttu-id="6f9d2-609">Devpts [GH 1948]에 대 한 탑재 옵션을 지원 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-609">Support mount options for devpts [GH 1948].</span></span>
- <span data-ttu-id="6f9d2-610">Ptrace 자식 시작 [GH 2333]를 차단 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-610">Ptrace blocking child startup [GH 2333].</span></span>
- <span data-ttu-id="6f9d2-611">누락 된 일부 이벤트 [GH 2462] EPOLLET 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-611">EPOLLET missing some events [GH 2462].</span></span>
- <span data-ttu-id="6f9d2-612">PTRACE_GETSIGINFO에 대 한 더 많은 데이터를 반환 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-612">Return more data for PTRACE_GETSIGINFO.</span></span>
- <span data-ttu-id="6f9d2-613">Lseek 사용 하 여 Getdents 잘못 된 결과 제공합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-613">Getdents with lseek gives incorrect results.</span></span>
- <span data-ttu-id="6f9d2-614">자세한 데이터가 없는 파이프에서 입력을 기다리는 일부 Win32 interop 응용 프로그램 중단을 수정 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-614">Fix some Win32 interop app hangs, waiting for input on a pipe that has no more data.</span></span>
- <span data-ttu-id="6f9d2-615">O_ASYNC는 tty/pty 파일에 대 한 지원.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-615">O_ASYNC support for tty/pty files.</span></span>
- <span data-ttu-id="6f9d2-616">추가 개선 사항 및 버그 수정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-616">Additional improvements and bug fixes</span></span>

#### <a name="console"></a><span data-ttu-id="6f9d2-617">콘솔</span><span class="sxs-lookup"><span data-stu-id="6f9d2-617">Console</span></span>
- <span data-ttu-id="6f9d2-618">콘솔이 관련이 릴리스의 변경 내용.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-618">No Console related changes in this release.</span></span>

### <a name="ltp-results"></a><span data-ttu-id="6f9d2-619">LTP 결과:</span><span class="sxs-lookup"><span data-stu-id="6f9d2-619">LTP Results:</span></span>
<span data-ttu-id="6f9d2-620">진행 중인 테스트 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-620">Testing in progress.</span></span>

## <a name="fall-creators-update"></a><span data-ttu-id="6f9d2-621">Fall Creators Update</span><span class="sxs-lookup"><span data-stu-id="6f9d2-621">Fall Creators Update</span></span>

## <a name="build-16288"></a><span data-ttu-id="6f9d2-622">16288 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-622">Build 16288</span></span>

<span data-ttu-id="6f9d2-623">일반 Windows에 대 한 16288 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2017/09/12/announcing-windows-10-insider-preview-build-16288-pc-build-15250-mobile/#7pLWQbj23JisfzV5.97/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-623">For general Windows information on build 16288 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2017/09/12/announcing-windows-10-insider-preview-build-16288-pc-build-15250-mobile/#7pLWQbj23JisfzV5.97/).</span></span><br/>


### <a name="fixed"></a><span data-ttu-id="6f9d2-624">고정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-624">Fixed</span></span>
#### <a name="wsl"></a><span data-ttu-id="6f9d2-625">WSL</span><span class="sxs-lookup"><span data-stu-id="6f9d2-625">WSL</span></span>
- <span data-ttu-id="6f9d2-626">올바르게 초기화 하 고 보고서 uid, gid 및 소켓 파일 설명자 [GH 2490]에 대 한 모드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-626">Correctly initialize and report uid, gid, and mode for socket file descriptors [GH 2490]</span></span>
- <span data-ttu-id="6f9d2-627">추가 개선 사항 및 버그 수정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-627">Additional improvements and bug fixes</span></span>

#### <a name="console"></a><span data-ttu-id="6f9d2-628">콘솔</span><span class="sxs-lookup"><span data-stu-id="6f9d2-628">Console</span></span>
- <span data-ttu-id="6f9d2-629">콘솔이 관련이 릴리스의 변경 내용.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-629">No Console related changes in this release.</span></span>

### <a name="ltp-results"></a><span data-ttu-id="6f9d2-630">LTP 결과:</span><span class="sxs-lookup"><span data-stu-id="6f9d2-630">LTP Results:</span></span>
<span data-ttu-id="6f9d2-631">16273 이후 변경 되지 않았습니다</span><span class="sxs-lookup"><span data-stu-id="6f9d2-631">No change since 16273</span></span>

## <a name="build-16278"></a><span data-ttu-id="6f9d2-632">16278 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-632">Build 16278</span></span>

<span data-ttu-id="6f9d2-633">일반 Windows에 대 한 162738 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2017/08/29/announcing-windows-10-insider-preview-build-16278-pc/#HMz6Xq7Su68WKi0t.97/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-633">For general Windows information on build 162738 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2017/08/29/announcing-windows-10-insider-preview-build-16278-pc/#HMz6Xq7Su68WKi0t.97/).</span></span><br/>


### <a name="fixed"></a><span data-ttu-id="6f9d2-634">고정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-634">Fixed</span></span>
#### <a name="wsl"></a><span data-ttu-id="6f9d2-635">WSL</span><span class="sxs-lookup"><span data-stu-id="6f9d2-635">WSL</span></span>
- <span data-ttu-id="6f9d2-636">LX MM 상태 [GH 2415]를 분해 하는 경우 명시적으로 매핑된 뷰 파일을 백업 섹션의 매핑을 해제합니다</span><span class="sxs-lookup"><span data-stu-id="6f9d2-636">Explicitly unmap mapped views of file backed sections when tearing down LX MM state [GH 2415]</span></span>
- <span data-ttu-id="6f9d2-637">추가 개선 사항 및 버그 수정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-637">Additional improvements and bug fixes</span></span>

#### <a name="console"></a><span data-ttu-id="6f9d2-638">콘솔</span><span class="sxs-lookup"><span data-stu-id="6f9d2-638">Console</span></span>
- <span data-ttu-id="6f9d2-639">콘솔이 관련이 릴리스의 변경 내용.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-639">No Console related changes in this release.</span></span>

### <a name="ltp-results"></a><span data-ttu-id="6f9d2-640">LTP 결과:</span><span class="sxs-lookup"><span data-stu-id="6f9d2-640">LTP Results:</span></span>
<span data-ttu-id="6f9d2-641">16273 이후 변경 되지 않았습니다</span><span class="sxs-lookup"><span data-stu-id="6f9d2-641">No change since 16273</span></span>

## <a name="build-16275"></a><span data-ttu-id="6f9d2-642">16275 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-642">Build 16275</span></span>

<span data-ttu-id="6f9d2-643">일반 Windows에 대 한 162735 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2017/08/25/announcing-windows-10-insider-preview-build-16275-pc-build-15245-mobile/#8QkxWqQbY37yZslV.97/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-643">For general Windows information on build 162735 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2017/08/25/announcing-windows-10-insider-preview-build-16275-pc-build-15245-mobile/#8QkxWqQbY37yZslV.97/).</span></span><br/>


### <a name="fixed"></a><span data-ttu-id="6f9d2-644">고정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-644">Fixed</span></span>
#### <a name="wsl"></a><span data-ttu-id="6f9d2-645">WSL</span><span class="sxs-lookup"><span data-stu-id="6f9d2-645">WSL</span></span>
- <span data-ttu-id="6f9d2-646">없는 WSL 관련이 릴리스의 변경 내용.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-646">No WSL related changes in this release.</span></span>

#### <a name="console"></a><span data-ttu-id="6f9d2-647">콘솔</span><span class="sxs-lookup"><span data-stu-id="6f9d2-647">Console</span></span>
- <span data-ttu-id="6f9d2-648">콘솔이 관련이 릴리스의 변경 내용.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-648">No Console related changes in this release.</span></span>

### <a name="ltp-results"></a><span data-ttu-id="6f9d2-649">LTP 결과:</span><span class="sxs-lookup"><span data-stu-id="6f9d2-649">LTP Results:</span></span>
<span data-ttu-id="6f9d2-650">16273 이후 변경 되지 않았습니다</span><span class="sxs-lookup"><span data-stu-id="6f9d2-650">No change since 16273</span></span>

## <a name="build-16273"></a><span data-ttu-id="6f9d2-651">16273 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-651">Build 16273</span></span>

<span data-ttu-id="6f9d2-652">일반 Windows에 대 한 16273 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2017/08/23/announcing-windows-10-insider-preview-build-16273-pc/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-652">For general Windows information on build 16273 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2017/08/23/announcing-windows-10-insider-preview-build-16273-pc/).</span></span><br/>


### <a name="fixed"></a><span data-ttu-id="6f9d2-653">고정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-653">Fixed</span></span>
#### <a name="wsl"></a><span data-ttu-id="6f9d2-654">WSL</span><span class="sxs-lookup"><span data-stu-id="6f9d2-654">WSL</span></span>
- <span data-ttu-id="6f9d2-655">디렉터리 [GH 2392]에 대 한 잘못 된 파일 형식에 DrvFs 경우에 따라 보고 문제를 해결 함</span><span class="sxs-lookup"><span data-stu-id="6f9d2-655">Fixed an issue where DrvFs sometimes reported the wrong file type for directories [GH 2392]</span></span>
- <span data-ttu-id="6f9d2-656">프로그램 차단을 해제 하려면 NETLINK_KOBJECT_UEVENT 소켓 만들기는 사용 하 여 uevent 허용 [GH 1121, 2293, 2242, 2295 2235, 648, 637]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-656">Allow creation of NETLINK_KOBJECT_UEVENT sockets to unblock programs that use uevent [GH 1121, 2293, 2242, 2295, 2235, 648, 637]</span></span>
- <span data-ttu-id="6f9d2-657">비차단 연결에 대 한 지원을 추가 [GH 903, 1391, 1584 1585, 1829, 2290, 2314]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-657">Add support for non-blocking connect [GH 903, 1391, 1584, 1585, 1829, 2290, 2314]</span></span>
- <span data-ttu-id="6f9d2-658">구현 CLONE_FS 복제 시스템 호출 플래그 [GH 2242]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-658">Implement CLONE_FS clone system call flag [GH 2242]</span></span>
- <span data-ttu-id="6f9d2-659">탭 또는 따옴표 NT interop [GH 1625, 2164]에서 올바르게 처리 하지 못할 경우 관련 된 문제를 해결 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-659">Fix issues around not handling tabs or quotes correctly in NT interop [GH 1625, 2164]</span></span>
- <span data-ttu-id="6f9d2-660">WSL를 다시 시작 하려고 하는 동안 오류가 발생 했습니다. [GH 651, 2095] 인스턴스 액세스 거부 해결</span><span class="sxs-lookup"><span data-stu-id="6f9d2-660">Resolve access denied error when trying to re-launch WSL instances [GH 651, 2095]</span></span>
- <span data-ttu-id="6f9d2-661">Futex FUTEX_REQUEUE 및 FUTEX_CMP_REQUEUE 작업 [GH 2242]를 구현 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-661">Implement futex FUTEX_REQUEUE and FUTEX_CMP_REQUEUE operations [GH 2242]</span></span>
- <span data-ttu-id="6f9d2-662">다양 한 SysFs 파일 [GH 2214]에 대 한 권한을 수정 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-662">Fix permissions for various SysFs files [GH 2214]</span></span>
- <span data-ttu-id="6f9d2-663">설치 [GH 2290] 중 Haskell 스택 중단을 수정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-663">Fix Haskell stack hang during setup [GH 2290]</span></span>
- <span data-ttu-id="6f9d2-664">'C' binfmt_misc 구현 ' o ' 및 'P' 플래그 [GH 2103]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-664">Implement binfmt_misc 'C' 'O' and 'P' flags [GH 2103]</span></span>
- <span data-ttu-id="6f9d2-665">추가 /proc/sys/kernel /shmmax /shmmni /threads-max [GH 1753]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-665">Add /proc/sys/kernel /shmmax /shmmni & /threads-max [GH 1753]</span></span>
- <span data-ttu-id="6f9d2-666">Ioprio_set 시스템 호출 [GH 498]에 대 한 부분 지원 추가</span><span class="sxs-lookup"><span data-stu-id="6f9d2-666">Add partial support for ioprio_set system call [GH 498]</span></span>
- <span data-ttu-id="6f9d2-667">스텁 SO_REUSEPORT & SO_PASSCRED netlink 소켓 [GH 69]에 대 한 지원 추가</span><span class="sxs-lookup"><span data-stu-id="6f9d2-667">Stub SO_REUSEPORT & adding support for SO_PASSCRED for netlink sockets [GH 69]</span></span>
- <span data-ttu-id="6f9d2-668">배포를 현재 중이면 RegisterDistribuiton에서 다른 오류 코드를 반환 설치 또는 제거 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-668">Return different error codes from RegisterDistribuiton if a distribution is currently being installed or uninstalled.</span></span>
- <span data-ttu-id="6f9d2-669">Wslconfig.exe 통해 부분적으로 설치 된 WSL 배포의 등록 취소 허용</span><span class="sxs-lookup"><span data-stu-id="6f9d2-669">Allow unregistration of partially installed WSL distributions via wslconfig.exe</span></span>
- <span data-ttu-id="6f9d2-670">Udp::msg_peek에서 python 소켓 테스트 중지를 수정 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-670">Fix python socket test hang from udp::msg_peek</span></span>
- <span data-ttu-id="6f9d2-671">추가 개선 사항 및 버그 수정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-671">Additional improvements and bug fixes</span></span>

#### <a name="console"></a><span data-ttu-id="6f9d2-672">콘솔</span><span class="sxs-lookup"><span data-stu-id="6f9d2-672">Console</span></span>
- <span data-ttu-id="6f9d2-673">콘솔이 관련이 릴리스의 변경 내용.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-673">No Console related changes in this release.</span></span>

### <a name="ltp-results"></a><span data-ttu-id="6f9d2-674">LTP 결과:</span><span class="sxs-lookup"><span data-stu-id="6f9d2-674">LTP Results:</span></span>
<span data-ttu-id="6f9d2-675">총 테스트: 1904</span><span class="sxs-lookup"><span data-stu-id="6f9d2-675">Total Tests: 1904</span></span><br/>
<span data-ttu-id="6f9d2-676">총 건너뛴 테스트: 209</span><span class="sxs-lookup"><span data-stu-id="6f9d2-676">Total Skipped Tests: 209</span></span><br/>
<span data-ttu-id="6f9d2-677">총 오류 횟수: 229</span><span class="sxs-lookup"><span data-stu-id="6f9d2-677">Total Failures: 229</span></span><br/>
[<span data-ttu-id="6f9d2-678">LTP 테스트 실행 로그</span><span class="sxs-lookup"><span data-stu-id="6f9d2-678">LTP Test Run Logs</span></span>](https://github.com/Microsoft/CommandLine-Documentation/tree/live/LTP_Results/16273)<br/>

## <a name="build-16257"></a><span data-ttu-id="6f9d2-679">16257 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-679">Build 16257</span></span>

<span data-ttu-id="6f9d2-680">일반 Windows에 대 한 16257 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2017/08/02/announcing-windows-10-insider-preview-build-16257-pc-build-15237-mobile/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-680">For general Windows information on build 16257 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2017/08/02/announcing-windows-10-insider-preview-build-16257-pc-build-15237-mobile/).</span></span><br/>


### <a name="fixed"></a><span data-ttu-id="6f9d2-681">고정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-681">Fixed</span></span>
#### <a name="wsl"></a><span data-ttu-id="6f9d2-682">WSL</span><span class="sxs-lookup"><span data-stu-id="6f9d2-682">WSL</span></span>
- <span data-ttu-id="6f9d2-683">구현 prlimit64 시스템 호출</span><span class="sxs-lookup"><span data-stu-id="6f9d2-683">Implement prlimit64 system call</span></span>
- <span data-ttu-id="6f9d2-684">Ulimit-n (setrlimit RLIMIT_NOFILE)에 대 한 지원을 추가 [GH 1688]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-684">Add support for ulimit -n (setrlimit RLIMIT_NOFILE) [GH 1688]</span></span>
- <span data-ttu-id="6f9d2-685">TCP 소켓 [GH 2351]에 대 한 스텁을 MSG_MORE</span><span class="sxs-lookup"><span data-stu-id="6f9d2-685">Stub MSG_MORE for TCP sockets [GH 2351]</span></span>
- <span data-ttu-id="6f9d2-686">잘못 된 AT_EXECFN 보조 벡터 동작 [GH 2133] 수정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-686">Fix invalid AT_EXECFN auxiliary vector behavior [GH 2133]</span></span>
- <span data-ttu-id="6f9d2-687">콘솔/tty에 대 한 복사/붙여넣기 동작을 수정 하 고 [GH 2204, 2131]를 처리 하는 더 나은 가득 찬 버퍼를 추가 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-687">Fix copy/paste behavior for console/tty, and add better full buffer handling [GH 2204, 2131]</span></span>
- <span data-ttu-id="6f9d2-688">집합-사용자 ID 및 집합-그룹-ID 프로그램 [GH 2031]에 대 한 보조 벡터에서 AT_SECURE 설정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-688">Set AT_SECURE in auxiliary vector for set-user-ID and set-group-ID programs [GH 2031]</span></span>
- <span data-ttu-id="6f9d2-689">유사 터미널 마스터 엔드포인트 TIOCPGRP [GH 1063]를 처리 하지 못할 경우</span><span class="sxs-lookup"><span data-stu-id="6f9d2-689">Psuedo-terminal master endpoint not handling TIOCPGRP [GH 1063]</span></span>
- <span data-ttu-id="6f9d2-690">수정 lseek LxFs [GH 2310]의 디렉터리 부분까지 되 감아야 않습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-690">Fix lseek does to rewind directories in LxFs [GH 2310]</span></span>
- <span data-ttu-id="6f9d2-691">사용량이 [GH 1882] 후 /dev/ptmx 작동 중지 됩니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-691">/dev/ptmx locks up after heavy usage [GH 1882]</span></span>
- <span data-ttu-id="6f9d2-692">추가 개선 사항 및 버그 수정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-692">Additional improvements and bug fixes</span></span>

#### <a name="console"></a><span data-ttu-id="6f9d2-693">콘솔</span><span class="sxs-lookup"><span data-stu-id="6f9d2-693">Console</span></span>
- <span data-ttu-id="6f9d2-694">가로 줄/밑줄 Everywhere [GH 2168]에 대 한 수정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-694">Fix for horizontal Lines/Underscores Everywhere [GH 2168]</span></span>
- <span data-ttu-id="6f9d2-695">처리 순서를 닫으려면 [GH 2170] 어렵게 만드는 NPM 변경에 대 한 수정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-695">Fix for process order changed making NPM harder to close [GH 2170]</span></span>
- <span data-ttu-id="6f9d2-696">이 새로운 색 구성표를 추가 합니다. https://blogs.msdn.microsoft.com/commandline/2017/08/02/updating-the-windows-console-colors/</span><span class="sxs-lookup"><span data-stu-id="6f9d2-696">Added our new color scheme: https://blogs.msdn.microsoft.com/commandline/2017/08/02/updating-the-windows-console-colors/</span></span>

### <a name="ltp-results"></a><span data-ttu-id="6f9d2-697">LTP 결과:</span><span class="sxs-lookup"><span data-stu-id="6f9d2-697">LTP Results:</span></span>
<span data-ttu-id="6f9d2-698">16251 이후 변경 되지 않았습니다</span><span class="sxs-lookup"><span data-stu-id="6f9d2-698">No change since 16251</span></span>

### <a name="syscall-support"></a><span data-ttu-id="6f9d2-699">Syscall 지원</span><span class="sxs-lookup"><span data-stu-id="6f9d2-699">Syscall Support</span></span>
<span data-ttu-id="6f9d2-700">다음은 새롭거나 향상 된 syscall WSL 구현에 있는 목록입니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-700">Below are a list of new or enhanced syscalls that have some implementation in WSL.</span></span> <span data-ttu-id="6f9d2-701">이 목록에 syscall 하나 이상의 시나리오에서 지원 되지만 수 있는 모든 매개 변수에서 지원 되지 않습니다이 시간.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-701">The syscalls on this list are supported in at least one scenario, but may not have all parameters supported at this time.</span></span>

`prlimit64`<br/>

### <a name="known-issues"></a><span data-ttu-id="6f9d2-702">알려진 문제</span><span class="sxs-lookup"><span data-stu-id="6f9d2-702">Known Issues</span></span>
#### [<a name="github-issue-2392-windows-folders-not-recognized-by-wsl-"></a><span data-ttu-id="6f9d2-703">GitHub Issue 2392: Windows 폴더 WSL에서 인식할 수 없습니다...</span><span class="sxs-lookup"><span data-stu-id="6f9d2-703">GitHub Issue 2392: Windows Folders not recognized by WSL ...</span></span>](https://github.com/Microsoft/BashOnWindows/issues/2392)
<span data-ttu-id="6f9d2-704">빌드 16257 WSL에 문제를 통해 Windows 파일/폴더를 열거 하는 동안 `/mnt/c/...`합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-704">In build 16257, WSL has issues when enumerating Windows files/folders via `/mnt/c/...`.</span></span>
<span data-ttu-id="6f9d2-705">이 문제는 해결 되었습니다 및에서 해제 되어야 참가자는 2017 년 8 월 14를 시작 하는 주 동안 빌드.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-705">This issue has been fixed and should be released in Insiders build during week commencing 8/14/2017.</span></span>

<br/>

## <a name="build-16251"></a><span data-ttu-id="6f9d2-706">16251 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-706">Build 16251</span></span>

<span data-ttu-id="6f9d2-707">일반 Windows에 대 한 16251 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2017/07/26/announcing-windows-10-insider-preview-build-16251-pc-build-15235-mobile/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-707">For general Windows information on build 16251 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2017/07/26/announcing-windows-10-insider-preview-build-16251-pc-build-15235-mobile/).</span></span><br/>


### <a name="fixed"></a><span data-ttu-id="6f9d2-708">고정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-708">Fixed</span></span>
#### <a name="wsl"></a><span data-ttu-id="6f9d2-709">WSL</span><span class="sxs-lookup"><span data-stu-id="6f9d2-709">WSL</span></span>
- <span data-ttu-id="6f9d2-710">WSL 선택적 구성 요소에서 베타 태그 제거를 참조 하십시오 [블로그 게시물](https://blogs.msdn.microsoft.com/commandline/2017/07/28/windows-subsystem-for-linux-out-of-beta/) 세부 정보에 대 한 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-710">Remove beta tag from WSL optional component, see [blog post](https://blogs.msdn.microsoft.com/commandline/2017/07/28/windows-subsystem-for-linux-out-of-beta/) for details.</span></span>
- <span data-ttu-id="6f9d2-711">저장 집합 uid 및 gid exec [GH 962, 1415, 2072]에서 집합-사용자 ID 및 집합-그룹-ID 바이너리를 제대로 초기화</span><span class="sxs-lookup"><span data-stu-id="6f9d2-711">Correctly initialize saved-set uid and gid for set-user-ID and set-group-ID binaries on exec [GH 962, 1415, 2072]</span></span>
- <span data-ttu-id="6f9d2-712">ptrace PTRACE_O_TRACEEXIT [GH 555]에 대 한 지원 추가</span><span class="sxs-lookup"><span data-stu-id="6f9d2-712">Added support for ptrace PTRACE_O_TRACEEXIT [GH 555]</span></span>
- <span data-ttu-id="6f9d2-713">ptrace에 대 한 지원이 추가 되었습니다 PTRACE_GETFPREGS 및 PTRACE_GETREGSET NT_FPREGSET [GH 555]를 사용 하 여</span><span class="sxs-lookup"><span data-stu-id="6f9d2-713">Added support for ptrace PTRACE_GETFPREGS and PTRACE_GETREGSET with NT_FPREGSET [GH 555]</span></span>
- <span data-ttu-id="6f9d2-714">무시 중지에 대해 ptrace를 고정 신호</span><span class="sxs-lookup"><span data-stu-id="6f9d2-714">Fixed ptrace to stop on ignored signals</span></span>
- <span data-ttu-id="6f9d2-715">추가 개선 사항 및 버그 수정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-715">Additional improvements and bug fixes</span></span>

#### <a name="console"></a><span data-ttu-id="6f9d2-716">콘솔</span><span class="sxs-lookup"><span data-stu-id="6f9d2-716">Console</span></span>
- <span data-ttu-id="6f9d2-717">콘솔이 관련이 릴리스의 변경 내용.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-717">No Console related changes in this release.</span></span>

### <a name="ltp-results"></a><span data-ttu-id="6f9d2-718">LTP 결과:</span><span class="sxs-lookup"><span data-stu-id="6f9d2-718">LTP Results:</span></span>
<span data-ttu-id="6f9d2-719">테스트 통과 수: 768</span><span class="sxs-lookup"><span data-stu-id="6f9d2-719">Number of Passing Tests: 768</span></span></br>
<span data-ttu-id="6f9d2-720">실패 한 테스트 수: 244</span><span class="sxs-lookup"><span data-stu-id="6f9d2-720">Number of Failing Tests: 244</span></span></br>
<span data-ttu-id="6f9d2-721">건너뛴된 테스트 수: 96</span><span class="sxs-lookup"><span data-stu-id="6f9d2-721">Number of Skipped Tests: 96</span></span></br>
[<span data-ttu-id="6f9d2-722">LTP 테스트 실행 로그</span><span class="sxs-lookup"><span data-stu-id="6f9d2-722">LTP Test Run Logs</span></span>](https://github.com/Microsoft/CommandLine-Documentation/tree/live/LTP_Results/16251)<br/>

</br>

## <a name="build-16241"></a><span data-ttu-id="6f9d2-723">16241 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-723">Build 16241</span></span>

<span data-ttu-id="6f9d2-724">일반 Windows에 대 한 16241 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2017/07/13/announcing-windows-10-insider-preview-build-16241-pc-build-15230-mobile/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-724">For general Windows information on build 16241 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2017/07/13/announcing-windows-10-insider-preview-build-16241-pc-build-15230-mobile/).</span></span><br/>


### <a name="fixed"></a><span data-ttu-id="6f9d2-725">고정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-725">Fixed</span></span>
#### <a name="wsl"></a><span data-ttu-id="6f9d2-726">WSL</span><span class="sxs-lookup"><span data-stu-id="6f9d2-726">WSL</span></span>
- <span data-ttu-id="6f9d2-727">없는 WSL 관련이 릴리스의 변경 내용.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-727">No WSL related changes in this release.</span></span>

#### <a name="console"></a><span data-ttu-id="6f9d2-728">콘솔</span><span class="sxs-lookup"><span data-stu-id="6f9d2-728">Console</span></span>
- <span data-ttu-id="6f9d2-729">원래 보고 교차 줄 dec 잘못 된 문자를 출력 하는 것에 대 한 수정 [여기](https://www.reddit.com/r/Windows10/comments/6in82t/i_believe_ive_found_the_most_obscure_bug_ever/)</span><span class="sxs-lookup"><span data-stu-id="6f9d2-729">Fix for outputting the wrong character for the crossing-lines DEC, originally reported [here](https://www.reddit.com/r/Windows10/comments/6in82t/i_believe_ive_found_the_most_obscure_bug_ever/)</span></span>
- <span data-ttu-id="6f9d2-730">코드 페이지 65001 (utf8)에 표시 되는 출력 텍스트가 없습니다에 대 한 수정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-730">Fix for no output text being displayed in codepage 65001 (utf8)</span></span>
- <span data-ttu-id="6f9d2-731">선택 변경에서 색상표의 다른 부분에 하나의 색의 RGB 값에 대 한 변경 내용을 전송 하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-731">Do not transfer changes made to one color's RGB values to other parts of the palette on selection change.</span></span> <span data-ttu-id="6f9d2-732">이렇게 하면 콘솔 속성 시트를 사용 하 여 훨씬 더 쉽습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-732">This will make the console properties sheet a lot easier to use.</span></span>
- <span data-ttu-id="6f9d2-733">Ctrl + S 제대로 작동 하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-733">Ctrl+S doesn't appear to work correctly</span></span>
- <span data-ttu-id="6f9d2-734">굵게 표시 되지 않은 /-차원 없는 완전히 ANSI 이스케이프 코드 [GH 2174]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-734">Un-Bold/-Dim completely absent from ANSI escape codes [GH 2174]</span></span>
- <span data-ttu-id="6f9d2-735">콘솔 [GH 1706] Vim 색 테마를 올바르게 지원 하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-735">Console doesn't correctly support Vim color themes [GH 1706]</span></span>
- <span data-ttu-id="6f9d2-736">[GH 2149] 특정 문자를 붙여 넣을 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-736">Cannot paste particular characters [GH 2149]</span></span>
- <span data-ttu-id="6f9d2-737">편집/명령줄 [GH ConEmu 1123]에 올려져 있는 경우 bash 창 크기 조정을 통한 리플로우 크기 조정 이상 하 게 상호 작용</span><span class="sxs-lookup"><span data-stu-id="6f9d2-737">Reflow resize interacts strangely with resizing a bash window when stuff is on the edit/command line [GH ConEmu 1123]</span></span>
- <span data-ttu-id="6f9d2-738">Ctrl-L 더티 화면 [GH 1978 년 5]을 떠날</span><span class="sxs-lookup"><span data-stu-id="6f9d2-738">Ctrl-L leaves the screen dirty [GH 1978]</span></span>
- <span data-ttu-id="6f9d2-739">HDPI [GH 1907]에서 VT를 표시할 때 콘솔 렌더링 버그</span><span class="sxs-lookup"><span data-stu-id="6f9d2-739">Console rendering bug when displaying VT on HDPI [GH 1907]</span></span>
- <span data-ttu-id="6f9d2-740">Japansese 문자는 유니코드 문자 U + 30FB를 사용 하 여 생소할 [GH 2146]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-740">Japansese characters look strange with Unicode Character U+30FB [GH 2146]</span></span>
- <span data-ttu-id="6f9d2-741">추가 개선 사항 및 버그 수정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-741">Additional improvements and bug fixes</span></span>

</br>

## <a name="build-16237"></a><span data-ttu-id="6f9d2-742">빌드 16237</span><span class="sxs-lookup"><span data-stu-id="6f9d2-742">Build 16237</span></span>

<span data-ttu-id="6f9d2-743">일반 Windows에 대 한 16237 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2017/07/07/announcing-windows-10-insider-preview-build-16237-pc/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-743">For general Windows information on build 16237 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2017/07/07/announcing-windows-10-insider-preview-build-16237-pc/).</span></span><br/>


### <a name="fixed"></a><span data-ttu-id="6f9d2-744">고정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-744">Fixed</span></span>
- <span data-ttu-id="6f9d2-745">EAs 없이 파일 lxfs (루트, 루트, 0000)에 대 한 기본 특성을 사용 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-745">Use default attributes for files without EAs in lxfs (root, root, 0000)</span></span>
- <span data-ttu-id="6f9d2-746">확장 된 특성을 사용 하는 배포에 대 한 지원 추가</span><span class="sxs-lookup"><span data-stu-id="6f9d2-746">Added support for distributions that use extended attributes</span></span>
- <span data-ttu-id="6f9d2-747">Getdents getdents64로 반환 되는 항목에 대 한 안쪽 여백을 수정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-747">Fix padding for entries returned by getdents and getdents64</span></span>
- <span data-ttu-id="6f9d2-748">수정 [GH 2068] shmctl SHM_STAT 시스템 호출에 대 한 사용 권한 확인</span><span class="sxs-lookup"><span data-stu-id="6f9d2-748">Fix permissions check for the shmctl SHM_STAT system call [GH 2068]</span></span>
- <span data-ttu-id="6f9d2-749">Tty [GH 2231]에 대 한 잘못 된 초기 epoll 고정된 상태</span><span class="sxs-lookup"><span data-stu-id="6f9d2-749">Fixed incorrect initial epoll state for ttys [GH 2231]</span></span>
- <span data-ttu-id="6f9d2-750">모든 항목 [GH 2077]를 반환 하지 않는 DrvFs readdir 수정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-750">Fix DrvFs readdir not returning all entries [GH 2077]</span></span>
- <span data-ttu-id="6f9d2-751">LxFs 해결 readdir 파일이 있는 경우 [GH 2077] 연결이 끊어진</span><span class="sxs-lookup"><span data-stu-id="6f9d2-751">Fix LxFs readdir when files are unlinked [GH 2077]</span></span>
- <span data-ttu-id="6f9d2-752">연결 되지 않은 drvfs 파일은 procfs 통해 다시 열 수</span><span class="sxs-lookup"><span data-stu-id="6f9d2-752">Allow unlinked drvfs files to be reopened through procfs</span></span>
- <span data-ttu-id="6f9d2-753">WSL 기능을 사용 하지 않도록 설정 하는 것에 대 한 전역 레지스트리 키 재정의 추가 (interop / 탑재 드라이브)</span><span class="sxs-lookup"><span data-stu-id="6f9d2-753">Added global registry key override for disabling WSL features (interop / drive mounting)</span></span>
- <span data-ttu-id="6f9d2-754">DrvFs (및 LxFs)에 대 한 "상태"에 잘못 된 블록 수를 수정 [GH 1894]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-754">Fix incorrect block count in "stat" for DrvFs (and LxFs) [GH 1894]</span></span>
- <span data-ttu-id="6f9d2-755">추가 개선 사항 및 버그 수정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-755">Additional improvements and bug fixes</span></span>

</br>

## <a name="build-16232"></a><span data-ttu-id="6f9d2-756">16232 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-756">Build 16232</span></span>

<span data-ttu-id="6f9d2-757">일반 Windows에 대 한 16232 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2017/06/28/announcing-windows-10-insider-preview-build-16232-pc-build-15228-mobile/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-757">For general Windows information on build 16232 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2017/06/28/announcing-windows-10-insider-preview-build-16232-pc-build-15228-mobile/).</span></span><br/>


### <a name="fixed"></a><span data-ttu-id="6f9d2-758">고정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-758">Fixed</span></span>
- <span data-ttu-id="6f9d2-759">없는 WSL 관련이 릴리스의 변경 내용.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-759">No WSL related changes in this release.</span></span>

</br>

## <a name="build-16226"></a><span data-ttu-id="6f9d2-760">16226 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-760">Build 16226</span></span>

<span data-ttu-id="6f9d2-761">일반 Windows에 대 한 16226 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2017/06/21/announcing-windows-10-insider-preview-build-16226-pc/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-761">For general Windows information on build 16226 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2017/06/21/announcing-windows-10-insider-preview-build-16226-pc/).</span></span><br/>


### <a name="fixed"></a><span data-ttu-id="6f9d2-762">고정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-762">Fixed</span></span>
- <span data-ttu-id="6f9d2-763">xattr 관련 syscall 지원 (getxattr setxattr, listxattr, removexattr).</span><span class="sxs-lookup"><span data-stu-id="6f9d2-763">xattr related syscalls support (getxattr, setxattr, listxattr, removexattr).</span></span>
- <span data-ttu-id="6f9d2-764">security.capablity xattr 지원 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-764">security.capablity xattr support.</span></span>
- <span data-ttu-id="6f9d2-765">특정 파일 시스템 및 비 MS SMB 서버를 포함 하 여 필터를 사용 하 여 향상 된 호환성.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-765">Improved compatibility with certain file systems and filters, including non-MS SMB servers.</span></span> <span data-ttu-id="6f9d2-766">[GH #1952]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-766">[GH #1952]</span></span>
- <span data-ttu-id="6f9d2-767">OneDrive 자리 표시자, GVFS 자리 표시자 및 Compact OS에 대 한 향상 된 지원 파일을 압축 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-767">Improved support for OneDrive placeholders, GVFS placeholders, and Compact OS compressed files.</span></span>
- <span data-ttu-id="6f9d2-768">추가 개선 사항 및 버그 수정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-768">Additional improvements and bug fixes</span></span>

</br>

## <a name="build-16215"></a><span data-ttu-id="6f9d2-769">16215 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-769">Build 16215</span></span>

<span data-ttu-id="6f9d2-770">일반 Windows에 대 한 16215 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2017/06/08/announcing-windows-10-insider-preview-build-16215-pc-build-15222-mobile/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-770">For general Windows information on build 16215 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2017/06/08/announcing-windows-10-insider-preview-build-16215-pc-build-15222-mobile/).</span></span><br/>


### <a name="fixed"></a><span data-ttu-id="6f9d2-771">고정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-771">Fixed</span></span>
- <span data-ttu-id="6f9d2-772">WSL은 개발자 모드를 더 이상 필요합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-772">WSL no longer requires developer mode.</span></span>
- <span data-ttu-id="6f9d2-773">Drvfs에서 디렉터리 연결을 지원 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-773">Support directory junctions in drvfs.</span></span>
- <span data-ttu-id="6f9d2-774">WSL 배포 appx 패키지 제거를 처리 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-774">Handle uninstalling of WSL distribution appx packages.</span></span>
- <span data-ttu-id="6f9d2-775">개인 표시할 procfs 업데이트 및 매핑을 공유 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-775">Update procfs to show private and shared mappings.</span></span>
- <span data-ttu-id="6f9d2-776">Wslconfig.exe 부분적으로 설치 되거나 제거 되는 배포를 정리 하는 기능을 추가 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-776">Add ability for wslconfig.exe to clean up distributions that are partially installed or uninstalled.</span></span>
- <span data-ttu-id="6f9d2-777">TCP 소켓에 대 한 IP_MTU_DISCOVER에 대 한 지원이 추가 되었습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-777">Added support for IP_MTU_DISCOVER for TCP sockets.</span></span> <span data-ttu-id="6f9d2-778">[GH 1639, 2115, 2205]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-778">[GH 1639, 2115, 2205]</span></span>
- <span data-ttu-id="6f9d2-779">프로토콜 패밀리가 AF_INADDR에 대 한 경로 대 한 유추 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-779">Infer protocol family for routes to AF_INADDR.</span></span>
- <span data-ttu-id="6f9d2-780">직렬 장치 개선 [GH 1929]입니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-780">Serial device improvements [GH 1929].</span></span>

</br>

## <a name="build-16199"></a><span data-ttu-id="6f9d2-781">16199 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-781">Build 16199</span></span>

<span data-ttu-id="6f9d2-782">일반 Windows에 대 한 16199 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2017/05/17/announcing-windows-10-insider-preview-build-16199-pc-build-15215-mobile/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-782">For general Windows information on build 16199 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2017/05/17/announcing-windows-10-insider-preview-build-16199-pc-build-15215-mobile/).</span></span><br/>


### <a name="fixed"></a><span data-ttu-id="6f9d2-783">고정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-783">Fixed</span></span>
- <span data-ttu-id="6f9d2-784">없는 WSL의에서 관련 변경 내용을 이러한 릴리스 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-784">No WSL related changes in these releases.</span></span>

</br>

## <a name="build-16193"></a><span data-ttu-id="6f9d2-785">16193 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-785">Build 16193</span></span>

<span data-ttu-id="6f9d2-786">일반 Windows에 대 한 16193 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2017/05/11/announcing-windows-10-insider-preview-build-16193-pc-build-15213-mobile/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-786">For general Windows information on build 16193 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2017/05/11/announcing-windows-10-insider-preview-build-16193-pc-build-15213-mobile/).</span></span><br/>


### <a name="fixed"></a><span data-ttu-id="6f9d2-787">고정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-787">Fixed</span></span>
- <span data-ttu-id="6f9d2-788">SIGCONT 및 [GH 1973] 종료는 threadgroup이 보내는 간격 사이의 경합 상태</span><span class="sxs-lookup"><span data-stu-id="6f9d2-788">Race condition between sending SIGCONT and a threadgroup terminating [GH 1973]</span></span>
- <span data-ttu-id="6f9d2-789">보고서 [GH 1840] FILE_DEVICE_CONSOLE 대신 FILE_DEVICE_NAMED_PIPE tty 및 pty 장치 변경</span><span class="sxs-lookup"><span data-stu-id="6f9d2-789">change tty and pty devices to report FILE_DEVICE_NAMED_PIPE instead of FILE_DEVICE_CONSOLE [GH 1840]</span></span>
- <span data-ttu-id="6f9d2-790">IP_OPTIONS에 대 한 SSH 수정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-790">SSH fix for IP_OPTIONS</span></span>
- <span data-ttu-id="6f9d2-791">Init 디먼 DrvFs 탑재 이동할 [GH 1862, 1968, 1767, 1933]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-791">Moved DrvFs mounting to init daemon [GH 1862, 1968, 1767, 1933]</span></span>
- <span data-ttu-id="6f9d2-792">NT symlink 따라 하는 데 DrvFs에서 지원이 추가 되었습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-792">Added support in DrvFs for following NT symlinks.</span></span>

</br>

## <a name="build-16184"></a><span data-ttu-id="6f9d2-793">16184 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-793">Build 16184</span></span>

<span data-ttu-id="6f9d2-794">일반 Windows에 대 한 16184 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2017/04/28/announcing-windows-10-insider-preview-build-16184-pc-build-15208-mobile/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-794">For general Windows information on build 16184 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2017/04/28/announcing-windows-10-insider-preview-build-16184-pc-build-15208-mobile/).</span></span><br/>


### <a name="fixed"></a><span data-ttu-id="6f9d2-795">고정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-795">Fixed</span></span>
- <span data-ttu-id="6f9d2-796">Apt 패키지 유지 관리 작업 (lxrun.exe /update)를 제거합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-796">Removed apt package maintenance task (lxrun.exe /update)</span></span>
- <span data-ttu-id="6f9d2-797">고정 된 출력에 표시 되지 node.js [GH 1840] Windows 프로세스에서</span><span class="sxs-lookup"><span data-stu-id="6f9d2-797">Fixed output not showing up in from Windows processes in node.js [GH 1840]</span></span>
- <span data-ttu-id="6f9d2-798">Lxcore [GH 1794]의 맞춤 요구 사항 완화</span><span class="sxs-lookup"><span data-stu-id="6f9d2-798">Relax alignment requirements in lxcore [GH 1794]</span></span>
- <span data-ttu-id="6f9d2-799">시스템 호출의 필드가에서 AT_EMPTY_PATH 플래그의 처리가 수정 되었습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-799">Fixed handling of the AT_EMPTY_PATH flag in a numer of system calls.</span></span>
- <span data-ttu-id="6f9d2-800">여기서 열린 핸들로 DrvFs 파일을 삭제 하면 정의 되지 않은 동작이 [GH 544,966,1357,1535,1615] 파일의 문제 해결된</span><span class="sxs-lookup"><span data-stu-id="6f9d2-800">Fixed issue where deleting DrvFs files with open handles will cause the file to exhibit undefined behavior [GH 544,966,1357,1535,1615]</span></span>
- <span data-ttu-id="6f9d2-801">/ 등 호스트에서 Windows 호스트 파일 (%windir%\system32\drivers\etc\hosts) 항목 상속 이제 [GH 1495]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-801">/etc/hosts will now inherit entries from the Windows hosts file (%windir%\system32\drivers\etc\hosts) [GH 1495]</span></span>

</br>

## <a name="build-16179"></a><span data-ttu-id="6f9d2-802">16179 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-802">Build 16179</span></span>

<span data-ttu-id="6f9d2-803">일반 Windows에 대 한 16179 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2017/04/19/announcing-windows-10-insider-preview-build-16179-pc-build-15205-mobile/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-803">For general Windows information on build 16179 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2017/04/19/announcing-windows-10-insider-preview-build-16179-pc-build-15205-mobile/).</span></span><br/>


### <a name="fixed"></a><span data-ttu-id="6f9d2-804">고정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-804">Fixed</span></span>
- <span data-ttu-id="6f9d2-805">없는 WSL 이번이 주를 변경합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-805">No WSL changes this week.</span></span>

</br>

## <a name="build-16176"></a><span data-ttu-id="6f9d2-806">16176 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-806">Build 16176</span></span>

<span data-ttu-id="6f9d2-807">일반 Windows에 대 한 16176 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2017/04/14/announcing-windows-10-insider-preview-build-16176-pc-build-15204-mobile/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-807">For general Windows information on build 16176 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2017/04/14/announcing-windows-10-insider-preview-build-16176-pc-build-15204-mobile/).</span></span><br/>


### <a name="fixed"></a><span data-ttu-id="6f9d2-808">고정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-808">Fixed</span></span>

- [<span data-ttu-id="6f9d2-809">직렬 지원 사용</span><span class="sxs-lookup"><span data-stu-id="6f9d2-809">Enabled serial support</span></span>](https://blogs.msdn.microsoft.com/wsl/2017/04/14/serial-support-on-the-windows-subsystem-for-linux/)
- <span data-ttu-id="6f9d2-810">추가 IP 소켓 옵션 IP_OPTIONS [GH 1116]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-810">Added IP socket option IP_OPTIONS [GH 1116]</span></span>
- <span data-ttu-id="6f9d2-811">Nginx/PHP-FPM에 파일 업로드) 하는 것 (동안 pwritev 함수 구현 [GH 1506]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-811">Implemented pwritev function (while uploading file to nginx/PHP-FPM) [GH 1506]</span></span>
- <span data-ttu-id="6f9d2-812">추가 IP 소켓 옵션 IP_MULTICAST_IF & IPV6_MULTICAST_IF [GH 990]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-812">Added IP socket options IP_MULTICAST_IF & IPV6_MULTICAST_IF [GH 990]</span></span>
- <span data-ttu-id="6f9d2-813">IP_MULTICAST_LOOP & IPV6_MULTICAST_LOOP 소켓 옵션에 대 한 지원 [GH 1678]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-813">Support for socket option IP_MULTICAST_LOOP & IPV6_MULTICAST_LOOP [GH 1678]</span></span>
- <span data-ttu-id="6f9d2-814">앱 노드의 traceroute, dig, nslookup 호스트에 대 한 추가 IP (V6) _MTU 소켓 옵션</span><span class="sxs-lookup"><span data-stu-id="6f9d2-814">Added IP(V6)_MTU socket option for apps node, traceroute, dig, nslookup, host</span></span>
- <span data-ttu-id="6f9d2-815">추가 IP 소켓 옵션 IPV6_UNICAST_HOPS</span><span class="sxs-lookup"><span data-stu-id="6f9d2-815">Added IP socket option IPV6_UNICAST_HOPS</span></span>
- [<span data-ttu-id="6f9d2-816">파일 시스템 개선 사항</span><span class="sxs-lookup"><span data-stu-id="6f9d2-816">Filesystem Improvements</span></span>](https://blogs.msdn.microsoft.com/wsl/2017/04/18/file-system-improvements-to-the-windows-subsystem-for-linux/)
    * <span data-ttu-id="6f9d2-817">탑재 되는 UNC 경로 허용 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-817">Allow mounting of UNC paths</span></span>
    * <span data-ttu-id="6f9d2-818">Drvfs에서 CDFS 지원을 사용 하도록 설정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-818">Enable CDFS support in drvfs</span></span>
    * <span data-ttu-id="6f9d2-819">Drvfs에서 네트워크 파일 시스템에 대 한 사용 권한을 올바르게 처리</span><span class="sxs-lookup"><span data-stu-id="6f9d2-819">Correctly handle permissions for network file systems in drvfs</span></span>
    * <span data-ttu-id="6f9d2-820">Drvfs에 원격 드라이브에 대 한 지원 추가</span><span class="sxs-lookup"><span data-stu-id="6f9d2-820">Add support for remote drives to drvfs</span></span>
    * <span data-ttu-id="6f9d2-821">FAT 사용 drvfs 지원</span><span class="sxs-lookup"><span data-stu-id="6f9d2-821">Enable FAT support in drvfs</span></span>
- <span data-ttu-id="6f9d2-822">추가 수정 및 개선 사항</span><span class="sxs-lookup"><span data-stu-id="6f9d2-822">Additional fixes and Improvements</span></span>

### <a name="ltp-results"></a><span data-ttu-id="6f9d2-823">LTP 결과</span><span class="sxs-lookup"><span data-stu-id="6f9d2-823">LTP Results</span></span>
<span data-ttu-id="6f9d2-824">15042 이후 변경 하지 않고</span><span class="sxs-lookup"><span data-stu-id="6f9d2-824">No changes since 15042</span></span>

</br>

## <a name="build-16170"></a><span data-ttu-id="6f9d2-825">16170 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-825">Build 16170</span></span>

<span data-ttu-id="6f9d2-826">일반 Windows에 대 한 16170 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2017/04/07/announcing-windows-10-insider-preview-build-16170-pc/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-826">For general Windows information on build 16170 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2017/04/07/announcing-windows-10-insider-preview-build-16170-pc/).</span></span><br/>

<span data-ttu-id="6f9d2-827">새 출시 [블로그 게시물](https://blogs.msdn.microsoft.com/wsl/2017/04/11/testing-the-windows-subsystem-for-linux/) WSL를 테스트 하기 위한 우리의 노력에 설명 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-827">We released a new [blog post](https://blogs.msdn.microsoft.com/wsl/2017/04/11/testing-the-windows-subsystem-for-linux/) discussing our efforts to test WSL.</span></span>

### <a name="fixed"></a><span data-ttu-id="6f9d2-828">고정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-828">Fixed</span></span>

- <span data-ttu-id="6f9d2-829">지원 소켓 IP_ADD_MEMBERSHIP & IPV6_ADD_MEMBERSHIP 옵션 [GH 1678]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-829">Support socket option IP_ADD_MEMBERSHIP & IPV6_ADD_MEMBERSHIP [GH 1678]</span></span>
- <span data-ttu-id="6f9d2-830">PTRACE_OLDSETOPTIONS 지원을 추가 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-830">Add support for PTRACE_OLDSETOPTIONS.</span></span> <span data-ttu-id="6f9d2-831">[GH 1692]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-831">[GH 1692]</span></span>
- <span data-ttu-id="6f9d2-832">추가 수정 및 개선 사항</span><span class="sxs-lookup"><span data-stu-id="6f9d2-832">Additional fixes and improvements</span></span>

### <a name="ltp-results"></a><span data-ttu-id="6f9d2-833">LTP 결과</span><span class="sxs-lookup"><span data-stu-id="6f9d2-833">LTP Results</span></span>
<span data-ttu-id="6f9d2-834">15042 이후 변경 하지 않고</span><span class="sxs-lookup"><span data-stu-id="6f9d2-834">No changes since 15042</span></span>

</br>

## <a name="build-15046-to-windows-10-creators-update"></a><span data-ttu-id="6f9d2-835">빌드 15046 windows 10 크리에이터 스 업데이트</span><span class="sxs-lookup"><span data-stu-id="6f9d2-835">Build 15046 to Windows 10 Creators Update</span></span>
<span data-ttu-id="6f9d2-836">WSL 수정 또는 Windows 10 크리에이터 스 업데이트에 포함 될 예정인 기능을 더 이상 있습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-836">There are no more WSL fixes or features planned for inclusion in the Creators Update to Windows 10.</span></span> <span data-ttu-id="6f9d2-837">WSL에 대 한 릴리스 정보는 다음 주요 Windows 업데이트를 대상으로 하는 추가 기능에 대 한 주간에 다시 시작 됩니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-837">Release notes for WSL will resume in the coming weeks for additions targeting the next major Windows Update.</span></span> <span data-ttu-id="6f9d2-838">빌드 15046 및 향후 참가자에 대 한 정보를 일반 Windows에 대 한 방문을 해제 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2017/02/28/announcing-windows-10-insider-preview-build-15046-pc/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-838">For general Windows information on build 15046 and future Insider releases visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2017/02/28/announcing-windows-10-insider-preview-build-15046-pc/).</span></span> <br/><br/>
 <br/>

## <a name="build-15042"></a><span data-ttu-id="6f9d2-839">15042 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-839">Build 15042</span></span>

<span data-ttu-id="6f9d2-840">일반 Windows에 대 한 15042 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2017/02/24/announcing-windows-10-insider-preview-build-15042-pc-build-15043-mobile/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-840">For general Windows information on build 15042 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2017/02/24/announcing-windows-10-insider-preview-build-15042-pc-build-15043-mobile/).</span></span><br/>


### <a name="fixed"></a><span data-ttu-id="6f9d2-841">고정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-841">Fixed</span></span>

- <span data-ttu-id="6f9d2-842">로 끝나는 경로 제거 하는 동안 교착 상태가 해결 "..."</span><span class="sxs-lookup"><span data-stu-id="6f9d2-842">Fix for a deadlock when removing a path ending in ".."</span></span>
- <span data-ttu-id="6f9d2-843">문제를 해결 함 위치 [GH 1683] 성공 시 0을 반환 하지 않는 FIONBIO</span><span class="sxs-lookup"><span data-stu-id="6f9d2-843">Fixed an issue where FIONBIO not returning 0 on success [GH 1683]</span></span>
- <span data-ttu-id="6f9d2-844">길이가 0 인 읽기 inet 데이터 그램 소켓의 문제 해결된</span><span class="sxs-lookup"><span data-stu-id="6f9d2-844">Fixed issue with zero-length reads of inet datagram sockets</span></span>
- <span data-ttu-id="6f9d2-845">Drvfs inode 조회 [GH 1675] 경합으로 인해 가능한 교착 상태 해결</span><span class="sxs-lookup"><span data-stu-id="6f9d2-845">Fix possible deadlock due to race condition in drvfs inode lookup [GH 1675]</span></span>
- <span data-ttu-id="6f9d2-846">Unix 소켓 보조 데이터에 대 한 지원 확장 SCM_CREDENTIALS 및 SCM_RIGHTS [GH 514, 613, 1326]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-846">Extended support for unix socket ancillary data; SCM_CREDENTIALS and SCM_RIGHTS [GH 514, 613, 1326]</span></span>
- <span data-ttu-id="6f9d2-847">추가 수정 및 개선 사항</span><span class="sxs-lookup"><span data-stu-id="6f9d2-847">Additional fixes and improvements</span></span>

### <a name="ltp-results"></a><span data-ttu-id="6f9d2-848">LTP 결과:</span><span class="sxs-lookup"><span data-stu-id="6f9d2-848">LTP Results:</span></span>
<span data-ttu-id="6f9d2-849">통과 한 테스트 수: 737</span><span class="sxs-lookup"><span data-stu-id="6f9d2-849">Number of Passing Test: 737</span></span></br>
<span data-ttu-id="6f9d2-850">불합격 개수 (실패, 건너뜀 등...): 255</span><span class="sxs-lookup"><span data-stu-id="6f9d2-850">Number of non-Passing (failing, skipped, etc…): 255</span></span>

</br>

## <a name="build-15031"></a><span data-ttu-id="6f9d2-851">15031 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-851">Build 15031</span></span>

<span data-ttu-id="6f9d2-852">일반 Windows에 대 한 15031 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2017/02/08/announcing-windows-10-insider-preview-build-15031-pc/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-852">For general Windows information on build 15031 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2017/02/08/announcing-windows-10-insider-preview-build-15031-pc/).</span></span><br/>


### <a name="fixed"></a><span data-ttu-id="6f9d2-853">고정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-853">Fixed</span></span>

- <span data-ttu-id="6f9d2-854">여기서 time(2) 오동작 산발적는 버그가 수정 되었습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-854">Fixed a bug where time(2) would sporadically misbehave.</span></span>
- <span data-ttu-id="6f9d2-855">고정 및 where 발급 \* SIGPROCMASK syscall 신호 마스크 손상 될 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-855">Fixed and issue where \*SIGPROCMASK syscalls could corrupt signal mask.</span></span>
- <span data-ttu-id="6f9d2-856">프로세스 만들기 알림 WSL에서에서 이제 전체 명령줄 길이 반환 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-856">Now return full command line length in WSL process creation notification.</span></span> <span data-ttu-id="6f9d2-857">[GH 1632]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-857">[GH 1632]</span></span>
- <span data-ttu-id="6f9d2-858">WSL은 GDB 중단에 ptrace 통해 스레드 종료를 보고합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-858">WSL now reports thread exit through ptrace for GDB hangs.</span></span> <span data-ttu-id="6f9d2-859">[GH 1196]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-859">[GH 1196]</span></span>
- <span data-ttu-id="6f9d2-860">과도 한 tmux IO 후 ptys가 중단 되는 버그가 수정 되었습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-860">Fixed bug where ptys would hang after heavy tmux IO.</span></span> <span data-ttu-id="6f9d2-861">[GH 1358]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-861">[GH 1358]</span></span>
- <span data-ttu-id="6f9d2-862">많은 시스템 호출 (futex semtimedop, ppoll, sigtimedwait, itimer, timer_create)에서 고정 된 제한 시간 유효성 검사</span><span class="sxs-lookup"><span data-stu-id="6f9d2-862">Fixed timeout validation in many system calls (futex, semtimedop, ppoll, sigtimedwait, itimer, timer_create)</span></span>
- <span data-ttu-id="6f9d2-863">추가 eventfd EFD_SEMAPHORE 지원 [GH 452]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-863">Added eventfd EFD_SEMAPHORE support [GH 452]</span></span>
- <span data-ttu-id="6f9d2-864">추가 수정 및 개선 사항</span><span class="sxs-lookup"><span data-stu-id="6f9d2-864">Additional fixes and improvements</span></span>

### <a name="ltp-results"></a><span data-ttu-id="6f9d2-865">LTP 결과:</span><span class="sxs-lookup"><span data-stu-id="6f9d2-865">LTP Results:</span></span>
<span data-ttu-id="6f9d2-866">통과 한 테스트 수: 737</span><span class="sxs-lookup"><span data-stu-id="6f9d2-866">Number of Passing Test: 737</span></span></br>
<span data-ttu-id="6f9d2-867">불합격 개수 (실패, 건너뜀 등...): 255</span><span class="sxs-lookup"><span data-stu-id="6f9d2-867">Number of non-Passing (failing, skipped, etc…): 255</span></span> </br>
[<span data-ttu-id="6f9d2-868">LTP 테스트 실행 로그</span><span class="sxs-lookup"><span data-stu-id="6f9d2-868">LTP Test Run Logs</span></span>](https://github.com/Microsoft/CommandLine-Documentation/tree/live/LTP_Results/15031)<br/>

<br/>

## <a name="build-15025"></a><span data-ttu-id="6f9d2-869">15025 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-869">Build 15025</span></span>

<span data-ttu-id="6f9d2-870">일반 Windows에 대 한 15025 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2017/02/01/announcing-windows-10-insider-preview-build-15025-pc/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-870">For general Windows information on build 15025 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2017/02/01/announcing-windows-10-insider-preview-build-15025-pc/).</span></span><br/>


### <a name="fixed"></a><span data-ttu-id="6f9d2-871">고정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-871">Fixed</span></span>

- <span data-ttu-id="6f9d2-872">해당 고장 grep 2.27 [GH 1578] 버그 수정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-872">Fix for bug that broke grep 2.27 [GH 1578]</span></span>
- <span data-ttu-id="6f9d2-873">Eventfd2 syscall [GH 452]에 대 한 구현된 EFD_SEMAPHORE 플래그</span><span class="sxs-lookup"><span data-stu-id="6f9d2-873">Implemented EFD_SEMAPHORE flag for eventfd2 syscall [GH 452]</span></span>
- <span data-ttu-id="6f9d2-874">[Pid] /proc//net ipv6_route 구현 [GH 1608]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-874">Implemented /proc/[pid]/net/ipv6_route [GH 1608]</span></span>
- <span data-ttu-id="6f9d2-875">Unix 스트림 소켓 [GH 393를 68]에 대 한 IO 지원 기반 신호</span><span class="sxs-lookup"><span data-stu-id="6f9d2-875">Signal driven IO support for unix stream sockets [GH 393, 68]</span></span>
- <span data-ttu-id="6f9d2-876">F_GETPIPE_SZ 및 F_SETPIPE_SZ [GH 1012] 지원</span><span class="sxs-lookup"><span data-stu-id="6f9d2-876">Support F_GETPIPE_SZ and F_SETPIPE_SZ [GH 1012]</span></span>
- <span data-ttu-id="6f9d2-877">Implement recvmmsg() syscall [GH 1531]</span><span class="sxs-lookup"><span data-stu-id="6f9d2-877">Implement recvmmsg() syscall [GH 1531]</span></span>
- <span data-ttu-id="6f9d2-878">Epoll_wait() 되지 않은 대기 하는 [GH 1609] 버그가 수정 되었습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-878">Fixed bug where epoll_wait() wasn't waiting [GH 1609]</span></span>
- <span data-ttu-id="6f9d2-879">/Proc/version_signature 구현</span><span class="sxs-lookup"><span data-stu-id="6f9d2-879">Implement /proc/version_signature</span></span>
- <span data-ttu-id="6f9d2-880">동일한 파이프 파일 설명자 두 참조 하는 경우 이제 tee syscall 실패 반환</span><span class="sxs-lookup"><span data-stu-id="6f9d2-880">Tee syscall now returns failure if both file descriptors refer to the same pipe</span></span>
- <span data-ttu-id="6f9d2-881">Unix 소켓에 대 한 SO_PEERCRED에 대 한 올바른 구현 된 동작</span><span class="sxs-lookup"><span data-stu-id="6f9d2-881">Implemented correct behavior for SO_PEERCRED for Unix sockets</span></span>
- <span data-ttu-id="6f9d2-882">고정된 tkill syscall 잘못 된 매개 변수 처리</span><span class="sxs-lookup"><span data-stu-id="6f9d2-882">Fixed tkill syscall invalid parameter handling</span></span>
- <span data-ttu-id="6f9d2-883">Drvfs의 preformace 높이기 위해 변경 내용</span><span class="sxs-lookup"><span data-stu-id="6f9d2-883">Changes to increase the preformace of drvfs</span></span>
- <span data-ttu-id="6f9d2-884">Ruby IO 차단에 대해 사소한 수정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-884">Minor fix for Ruby IO blocking</span></span>
- <span data-ttu-id="6f9d2-885">고정된 recvmsg() EINVAL inet 소켓 [GH 1296] MSG_DONTWAIT 플래그에 대 한 반환</span><span class="sxs-lookup"><span data-stu-id="6f9d2-885">Fixed recvmsg() returning EINVAL for the MSG_DONTWAIT flag for inet sockets [GH 1296]</span></span>
- <span data-ttu-id="6f9d2-886">추가 수정 및 개선 사항</span><span class="sxs-lookup"><span data-stu-id="6f9d2-886">Additional fixes and improvements</span></span>

### <a name="ltp-results"></a><span data-ttu-id="6f9d2-887">LTP 결과:</span><span class="sxs-lookup"><span data-stu-id="6f9d2-887">LTP Results:</span></span>
<span data-ttu-id="6f9d2-888">통과 한 테스트 수: 732</span><span class="sxs-lookup"><span data-stu-id="6f9d2-888">Number of Passing Test: 732</span></span></br>
<span data-ttu-id="6f9d2-889">불합격 개수 (실패, 건너뜀 등...): 255</span><span class="sxs-lookup"><span data-stu-id="6f9d2-889">Number of non-Passing (failing, skipped, etc…): 255</span></span> </br>
[<span data-ttu-id="6f9d2-890">LTP 테스트 실행 로그</span><span class="sxs-lookup"><span data-stu-id="6f9d2-890">LTP Test Run Logs</span></span>](https://github.com/Microsoft/CommandLine-Documentation/tree/live/LTP_Results/15025)<br/>

<br/>

## <a name="build-15019"></a><span data-ttu-id="6f9d2-891">빌드 15019</span><span class="sxs-lookup"><span data-stu-id="6f9d2-891">Build 15019</span></span>

<span data-ttu-id="6f9d2-892">일반 Windows에 대 한 빌드 15019에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2017/01/27/announcing-windows-10-insider-preview-build-15019-pc/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-892">For general Windows information on build 15019 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2017/01/27/announcing-windows-10-insider-preview-build-15019-pc/).</span></span><br/>


### <a name="fixed"></a><span data-ttu-id="6f9d2-893">고정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-893">Fixed</span></span>

- <span data-ttu-id="6f9d2-894">버그에서 CPU 사용량을 올바르게 보고 한다면 (GH 823 945, 971)와 같은 도구에 대 한 procfs</span><span class="sxs-lookup"><span data-stu-id="6f9d2-894">Fixed bug that incorrectly reported CPU usage in procfs for tools like htop (GH 823, 945, 971)</span></span>
- <span data-ttu-id="6f9d2-895">파일 inotify IN_OPEN 전에 IN_MODIFY 이제 생성 기존 O_TRUNC 사용 하 여 open ()를 호출 하는 경우</span><span class="sxs-lookup"><span data-stu-id="6f9d2-895">When calling open() with O_TRUNC on an existing file inotify now generates IN_MODIFY before IN_OPEN</span></span>
- <span data-ttu-id="6f9d2-896">Unix 소켓 getsockopt SO_ERROR postgress [GH 61이 1354]를 사용 하도록 설정 하기 위한 수정 사항</span><span class="sxs-lookup"><span data-stu-id="6f9d2-896">Fixes to unix socket getsockopt SO_ERROR to enable postgress [GH 61, 1354]</span></span>
- <span data-ttu-id="6f9d2-897">GO 언어에 대 한 구현 /proc/sys/net/core/somaxconn</span><span class="sxs-lookup"><span data-stu-id="6f9d2-897">Implement /proc/sys/net/core/somaxconn for the GO language</span></span>
- <span data-ttu-id="6f9d2-898">Apt get 패키지 업데이트 백그라운드 작업 지금 실행 숨겨진 뷰에서</span><span class="sxs-lookup"><span data-stu-id="6f9d2-898">Apt-get package update background task now runs hidden from view</span></span>
- <span data-ttu-id="6f9d2-899">Ipv6 localhost (Spring-Framework(Java) 실패)에 대 한 일반 범위입니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-899">Clear scope for ipv6 localhost (Spring-Framework(Java) failure).</span></span>
- <span data-ttu-id="6f9d2-900">추가 수정 및 개선 사항</span><span class="sxs-lookup"><span data-stu-id="6f9d2-900">Additional fixes and improvements</span></span>

### <a name="ltp-results"></a><span data-ttu-id="6f9d2-901">LTP 결과:</span><span class="sxs-lookup"><span data-stu-id="6f9d2-901">LTP Results:</span></span>
<span data-ttu-id="6f9d2-902">통과 한 테스트 수: 714</span><span class="sxs-lookup"><span data-stu-id="6f9d2-902">Number of Passing Test: 714</span></span> </br>
<span data-ttu-id="6f9d2-903">불합격 개수 (실패, 건너뜀 등...): 249</span><span class="sxs-lookup"><span data-stu-id="6f9d2-903">Number of non-Passing (failing, skipped, etc…): 249</span></span> </br>
[<span data-ttu-id="6f9d2-904">LTP 테스트 실행 로그</span><span class="sxs-lookup"><span data-stu-id="6f9d2-904">LTP Test Run Logs</span></span>](https://github.com/Microsoft/CommandLine-Documentation/tree/live/LTP_Results/15019)<br/>

<br/>

## <a name="build-15014"></a><span data-ttu-id="6f9d2-905">15014 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-905">Build 15014</span></span>

<span data-ttu-id="6f9d2-906">일반 Windows에 대 한 15014 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2017/01/19/announcing-windows-10-insider-preview-build-15014-for-pc-and-mobile-hello-windows-insiders-today-we-are-excited-to-be-releasing-windows-10-insider-preview-build-15014-for-pc-and-mobile)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-906">For general Windows information on build 15014 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2017/01/19/announcing-windows-10-insider-preview-build-15014-for-pc-and-mobile-hello-windows-insiders-today-we-are-excited-to-be-releasing-windows-10-insider-preview-build-15014-for-pc-and-mobile).</span></span><br/>


### <a name="fixed"></a><span data-ttu-id="6f9d2-907">고정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-907">Fixed</span></span>

- <span data-ttu-id="6f9d2-908">Ctrl + C는 이제 의도 한 대로 작동</span><span class="sxs-lookup"><span data-stu-id="6f9d2-908">Ctrl+C now works as intended</span></span>
- <span data-ttu-id="6f9d2-909">htop 및 ps auxw 이제 표시 올바른 리소스 사용률 (GH #516)</span><span class="sxs-lookup"><span data-stu-id="6f9d2-909">htop and ps auxw now show correct resource utilization (GH #516)</span></span>
- <span data-ttu-id="6f9d2-910">기본 신호 NT 예외 변환 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-910">Basic translation of NT exceptions to signals.</span></span> <span data-ttu-id="6f9d2-911">(#513 GH)</span><span class="sxs-lookup"><span data-stu-id="6f9d2-911">(GH #513)</span></span>
- <span data-ttu-id="6f9d2-912">fallocate 이제 실패 ENOSPC EINVAL (GH #1571) 대신 공간 부족</span><span class="sxs-lookup"><span data-stu-id="6f9d2-912">fallocate now fails with ENOSPC  when running out of space instead of EINVAL (GH #1571)</span></span>
- <span data-ttu-id="6f9d2-913">추가 /proc/sys/kernel/sem 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-913">Added /proc/sys/kernel/sem.</span></span>
- <span data-ttu-id="6f9d2-914">구현 된 semop 및 semtimedop 시스템 호출</span><span class="sxs-lookup"><span data-stu-id="6f9d2-914">Implemented semop and semtimedop system calls</span></span>
- <span data-ttu-id="6f9d2-915">IP_RECVTOS & IPV6_RECVTCLASS 소켓 옵션 (GH 69)를 사용 하 여 고정된 nslookup 오류</span><span class="sxs-lookup"><span data-stu-id="6f9d2-915">Fixed nslookup errors with IP_RECVTOS & IPV6_RECVTCLASS socket option (GH 69)</span></span>
- <span data-ttu-id="6f9d2-916">IP_RECVTTL 및 IPV6_RECVHOPLIMIT 소켓 옵션에 대 한 지원</span><span class="sxs-lookup"><span data-stu-id="6f9d2-916">Support for socket options IP_RECVTTL and IPV6_RECVHOPLIMIT</span></span>
- <span data-ttu-id="6f9d2-917">추가 수정 및 개선 사항</span><span class="sxs-lookup"><span data-stu-id="6f9d2-917">Additional fixes and improvements</span></span>

### <a name="ltp-results"></a><span data-ttu-id="6f9d2-918">LTP 결과:</span><span class="sxs-lookup"><span data-stu-id="6f9d2-918">LTP Results:</span></span>
<span data-ttu-id="6f9d2-919">통과 한 테스트 수: 709</span><span class="sxs-lookup"><span data-stu-id="6f9d2-919">Number of Passing Test: 709</span></span> </br>
<span data-ttu-id="6f9d2-920">불합격 개수 (실패, 건너뜀 등...): 255</span><span class="sxs-lookup"><span data-stu-id="6f9d2-920">Number of non-Passing (failing, skipped, etc…): 255</span></span> </br>
[<span data-ttu-id="6f9d2-921">LTP 테스트 실행 로그</span><span class="sxs-lookup"><span data-stu-id="6f9d2-921">LTP Test Run Logs</span></span>](https://github.com/Microsoft/CommandLine-Documentation/tree/live/LTP_Results/15014)<br/>

### <a name="syscall-summary"></a><span data-ttu-id="6f9d2-922">Syscall 요약</span><span class="sxs-lookup"><span data-stu-id="6f9d2-922">Syscall Summary</span></span>
<span data-ttu-id="6f9d2-923">총 Syscall: 384</span><span class="sxs-lookup"><span data-stu-id="6f9d2-923">Total Syscalls: 384</span></span> </br>
<span data-ttu-id="6f9d2-924">전체 구현: 235</span><span class="sxs-lookup"><span data-stu-id="6f9d2-924">Total Implemented: 235</span></span> </br>
<span data-ttu-id="6f9d2-925">스텁 합계: 22</span><span class="sxs-lookup"><span data-stu-id="6f9d2-925">Total Stubbed: 22</span></span> </br>
<span data-ttu-id="6f9d2-926">구현 되지 않았으며 합계: 127</span><span class="sxs-lookup"><span data-stu-id="6f9d2-926">Total Unimplemented: 127</span></span> </br>
[<span data-ttu-id="6f9d2-927">세부적인된 분석 결과</span><span class="sxs-lookup"><span data-stu-id="6f9d2-927">Detailed Breakdown</span></span>](https://github.com/Microsoft/CommandLine-Documentation/tree/live/LTP_Results/15014/Syscalls.txt)<br/>

<br/>

## <a name="build-15007"></a><span data-ttu-id="6f9d2-928">15007 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-928">Build 15007</span></span>

<span data-ttu-id="6f9d2-929">일반 Windows에 대 한 15007 빌드에 대 한 정보를 방문 합니다 [Windows 블로그]( https://blogs.windows.com/windowsexperience/2017/01/12/announcing-windows-10-insider-preview-build-15007-pc-mobile)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-929">For general Windows information on build 15007 visit the [Windows Blog]( https://blogs.windows.com/windowsexperience/2017/01/12/announcing-windows-10-insider-preview-build-15007-pc-mobile).</span></span><br/>


### <a name="known-issue"></a><span data-ttu-id="6f9d2-930">알려진된 문제</span><span class="sxs-lookup"><span data-stu-id="6f9d2-930">Known Issue</span></span>

- <span data-ttu-id="6f9d2-931">콘솔 일부 Ctrl 인식 하지 못하는 알려진 버그가 + <key> 입력 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-931">There is a known bug where the console does not recognize some Ctrl + <key> input.</span></span>  <span data-ttu-id="6f9d2-932">일반 'c' keypress 역할을 할 ctrl + c 명령 포함 됩니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-932">This includes the ctrl-c command which will act as a normal ‘c’ keypress.</span></span>

  - <span data-ttu-id="6f9d2-933">해결 방법: Ctrl + C를 대체 키를 매핑하십시오.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-933">Workaround: Map an alternate key to Ctrl+C.</span></span> <span data-ttu-id="6f9d2-934">예를 들어, 매핑할 Ctrl + K Ctrl + C를 수행: `stty intr \^k`합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-934">For example, to map Ctrl+K to Ctrl+C do: `stty intr \^k`.</span></span>  <span data-ttu-id="6f9d2-935">이 매핑은 터미널 당 이며 완료 해야 할 *마다* 시간 bash 시작 됩니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-935">This mapping is per terminal and will have to be done *every* time bash is launched.</span></span> <span data-ttu-id="6f9d2-936">사용자는이 포함 하는 옵션을 탐색할 수 있습니다는</span><span class="sxs-lookup"><span data-stu-id="6f9d2-936">Users can explore the option to include this in their</span></span> `.bashrc`

### <a name="fixed"></a><span data-ttu-id="6f9d2-937">고정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-937">Fixed</span></span>

- <span data-ttu-id="6f9d2-938">여기서 실행 WSL를 사용 하 게 CPU 코어의 100% 문제를 수정 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-938">Corrected the issue where running WSL would consume 100% of a CPU core</span></span>
- <span data-ttu-id="6f9d2-939">소켓 옵션 IP_PKTINFO, IPV6_RECVPKTINFO 이제 지원 됩니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-939">Socket option IP_PKTINFO, IPV6_RECVPKTINFO now supported.</span></span> <span data-ttu-id="6f9d2-940">(GH #851, 987)</span><span class="sxs-lookup"><span data-stu-id="6f9d2-940">(GH #851, 987)</span></span>
- <span data-ttu-id="6f9d2-941">네트워크 인터페이스 물리적 주소 lxcore 16 바이트를 자르기 (1414, GH #1452, 1343, 468, 308)</span><span class="sxs-lookup"><span data-stu-id="6f9d2-941">Truncate network interface physical address to 16 bytes in lxcore (GH #1452, 1414, 1343, 468, 308)</span></span>
- <span data-ttu-id="6f9d2-942">추가 수정 및 개선 사항</span><span class="sxs-lookup"><span data-stu-id="6f9d2-942">Additional fixes and improvements</span></span>

### <a name="ltp-results"></a><span data-ttu-id="6f9d2-943">LTP 결과:</span><span class="sxs-lookup"><span data-stu-id="6f9d2-943">LTP Results:</span></span>
<span data-ttu-id="6f9d2-944">통과 한 테스트 수: 709</span><span class="sxs-lookup"><span data-stu-id="6f9d2-944">Number of Passing Test: 709</span></span> </br>
<span data-ttu-id="6f9d2-945">불합격 개수 (실패, 건너뜀 등...): 255</span><span class="sxs-lookup"><span data-stu-id="6f9d2-945">Number of non-Passing (failing, skipped, etc…): 255</span></span> </br>
[<span data-ttu-id="6f9d2-946">LTP 테스트 실행 로그</span><span class="sxs-lookup"><span data-stu-id="6f9d2-946">LTP Test Run Logs</span></span>](https://github.com/Microsoft/CommandLine-Documentation/tree/live/LTP_Results/15007)<br/>

<br/>

## <a name="build-15002"></a><span data-ttu-id="6f9d2-947">빌드 15002</span><span class="sxs-lookup"><span data-stu-id="6f9d2-947">Build 15002</span></span>

<span data-ttu-id="6f9d2-948">일반 Windows 빌드 15002 방법은 참조를 [Windows 블로그](https://blogs.windows.com/windowsexperience/2017/01/09/announcing-windows-10-insider-preview-build-15002-pc/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-948">For general Windows information on build 15002 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2017/01/09/announcing-windows-10-insider-preview-build-15002-pc/).</span></span><br/>


### <a name="known-issue"></a><span data-ttu-id="6f9d2-949">알려진된 문제</span><span class="sxs-lookup"><span data-stu-id="6f9d2-949">Known Issue</span></span>

<span data-ttu-id="6f9d2-950">두 가지 알려진된 문제:</span><span class="sxs-lookup"><span data-stu-id="6f9d2-950">Two known issues:</span></span>
- <span data-ttu-id="6f9d2-951">콘솔 일부 Ctrl 인식 하지 못하는 알려진 버그가 + <key> 입력 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-951">There is a known bug where the console does not recognize some Ctrl + <key> input.</span></span>  <span data-ttu-id="6f9d2-952">일반 'c' keypress 역할을 할 ctrl + c 명령 포함 됩니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-952">This includes the ctrl-c command which will act as a normal ‘c’ keypress.</span></span>

  - <span data-ttu-id="6f9d2-953">해결 방법: Ctrl + C를 대체 키를 매핑하십시오.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-953">Workaround: Map an alternate key to Ctrl+C.</span></span> <span data-ttu-id="6f9d2-954">예를 들어, 매핑할 Ctrl + K Ctrl + C를 수행: `stty intr \^k`합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-954">For example, to map Ctrl+K to Ctrl+C do: `stty intr \^k`.</span></span>  <span data-ttu-id="6f9d2-955">이 매핑은 터미널 당 이며 완료 해야 할 *마다* 시간 bash 시작 됩니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-955">This mapping is per terminal and will have to be done *every* time bash is launched.</span></span> <span data-ttu-id="6f9d2-956">사용자는이 포함 하는 옵션을 탐색할 수 있습니다는</span><span class="sxs-lookup"><span data-stu-id="6f9d2-956">Users can explore the option to include this in their</span></span> `.bashrc`

- <span data-ttu-id="6f9d2-957">WSL에서 실행 되는 동안 시스템 스레드를 CPU 코어의 100%를 사용 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-957">While WSL is running a system thread will consume 100% of a CPU core.</span></span>  <span data-ttu-id="6f9d2-958">근본 원인은 해결 되어 내부적으로 고정 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-958">The root cause has been addressed and fixed internally.</span></span>

### <a name="fixed"></a><span data-ttu-id="6f9d2-959">고정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-959">Fixed</span></span>

- <span data-ttu-id="6f9d2-960">이제 모든 bash 세션 같은 권한 수준에서 만들어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-960">All bash sessions must now be created at the same permission level.</span></span>  <span data-ttu-id="6f9d2-961">여러 수준에서 세션을 시작 하는 동안 차단 됩니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-961">Attempting to start a session at a different level will be blocked.</span></span>  <span data-ttu-id="6f9d2-962">즉, 관리자 및 비관리자 콘솔 동시에 실행할 수 없습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-962">This means admin and non-admin consoles cannot run at the same time.</span></span> <span data-ttu-id="6f9d2-963">(#626 GH)</span><span class="sxs-lookup"><span data-stu-id="6f9d2-963">(GH #626)</span></span>
<br/>
- <span data-ttu-id="6f9d2-964">다음 NETLINK_ROUTE 메시지 구현 (Windows 관리 해야 함)</span><span class="sxs-lookup"><span data-stu-id="6f9d2-964">Implemented the following NETLINK_ROUTE messages (requires Windows admin)</span></span>
     - <span data-ttu-id="6f9d2-965">RTM_NEWADDR (지원 `ip addr add`)</span><span class="sxs-lookup"><span data-stu-id="6f9d2-965">RTM_NEWADDR (supports `ip addr add`)</span></span>
     - <span data-ttu-id="6f9d2-966">RTM_NEWROUTE (지원 `ip route add`)</span><span class="sxs-lookup"><span data-stu-id="6f9d2-966">RTM_NEWROUTE (supports `ip route add`)</span></span>
     - <span data-ttu-id="6f9d2-967">RTM_DELADDR (지원 `ip addr del`)</span><span class="sxs-lookup"><span data-stu-id="6f9d2-967">RTM_DELADDR (supports `ip addr del`)</span></span>
     - <span data-ttu-id="6f9d2-968">RTM_DELROUTE (지원 `ip route del`)</span><span class="sxs-lookup"><span data-stu-id="6f9d2-968">RTM_DELROUTE (supports `ip route del`)</span></span>
- <span data-ttu-id="6f9d2-969">패키지 업데이트를 확인 하는 예약 된 작업 (GH #1371) 데이터 통신된 연결에서 수행 되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-969">Scheduled task checking for packages to update will no longer run on a metered connection (GH #1371)</span></span>
- <span data-ttu-id="6f9d2-970">고정 오류 가져옵니다 파이프 멈춘 즉, bash-c "ls alR /" | bash-c "고양이" (GH #1214)</span><span class="sxs-lookup"><span data-stu-id="6f9d2-970">Fixed error where piping gets stuck i.e. bash -c "ls -alR /" | bash -c "cat" (GH #1214)</span></span>
- <span data-ttu-id="6f9d2-971">구현 된 TCP_KEEPCNT 소켓 옵션 (GH #843)</span><span class="sxs-lookup"><span data-stu-id="6f9d2-971">Implemented TCP_KEEPCNT socket option (GH #843)</span></span>
- <span data-ttu-id="6f9d2-972">구현 된 IP_MTU_DISCOVER INET 소켓 옵션 (GH #720, 717, 170, 69)</span><span class="sxs-lookup"><span data-stu-id="6f9d2-972">Implemented IP_MTU_DISCOVER INET socket option (GH #720, 717, 170, 69)</span></span>
- <span data-ttu-id="6f9d2-973">NT 경로 조회를 사용 하 여 초기화에서 NT 이진 파일을 실행 하는 레거시 기능을 제거 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-973">Removed legacy functionality to run NT binaries from init with NT path lookup.</span></span> <span data-ttu-id="6f9d2-974">(#1325 GH)</span><span class="sxs-lookup"><span data-stu-id="6f9d2-974">(GH #1325)</span></span>
- <span data-ttu-id="6f9d2-975">그룹 / 기타 읽기 (0644) (GH #1321) 액세스할 수 있도록/kmsg의 모드를 수정 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-975">Fix mode of /dev/kmsg to allow group / other read access (0644) (GH #1321)</span></span>
- <span data-ttu-id="6f9d2-976">구현 된 /proc/sys/kernel/random/uuid (GH #1092)</span><span class="sxs-lookup"><span data-stu-id="6f9d2-976">Implemented /proc/sys/kernel/random/uuid  (GH #1092)</span></span>
- <span data-ttu-id="6f9d2-977">프로세스 시작 시간 (GH #974) 2432 연도로 표시 되어 있는 오류를 수정 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-977">Corrected error where process start time was showing as year 2432 (GH #974)</span></span>
- <span data-ttu-id="6f9d2-978">Xterm-256color (GH #1446)로 전환된 하는 기본 용어 환경 변수</span><span class="sxs-lookup"><span data-stu-id="6f9d2-978">Switched default TERM environment variable to xterm-256color (GH #1446)</span></span>
- <span data-ttu-id="6f9d2-979">수정 된 커밋을 처리 하는 방식으로 프로세스 분기 하는 동안 계산 됩니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-979">Modified the way that process commit is calculated during process fork.</span></span> <span data-ttu-id="6f9d2-980">(GH #1286)</span><span class="sxs-lookup"><span data-stu-id="6f9d2-980">(GH #1286)</span></span>
- <span data-ttu-id="6f9d2-981">/Proc/sys/vm/overcommit_memory 구현된 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-981">Implemented /proc/sys/vm/overcommit_memory.</span></span> <span data-ttu-id="6f9d2-982">(GH #1286)</span><span class="sxs-lookup"><span data-stu-id="6f9d2-982">(GH #1286)</span></span>
- <span data-ttu-id="6f9d2-983">구현 된 /proc/net/route 파일 (GH #69)</span><span class="sxs-lookup"><span data-stu-id="6f9d2-983">Implemented /proc/net/route file (GH #69)</span></span>
- <span data-ttu-id="6f9d2-984">바로 가기 이름이 올바르게 오류 수정된 했습니다 (GH #696) 지역화</span><span class="sxs-lookup"><span data-stu-id="6f9d2-984">Fixed error where shortcut name was incorrectly localized (GH #696)</span></span>
- <span data-ttu-id="6f9d2-985">프로그램 헤더를 올바르게 검사할 되는 논리를 구문 분석 하는 고정된 elf 작아야 (크거나 같음) PATH_MAX 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-985">Fixed elf parsing logic that is incorrectly validating the program headers must be less than (or equal to) PATH_MAX.</span></span> <span data-ttu-id="6f9d2-986">(#1048 GH)</span><span class="sxs-lookup"><span data-stu-id="6f9d2-986">(GH #1048)</span></span>
- <span data-ttu-id="6f9d2-987">구현 된 statfs 콜백 procfs, sysfs, cgroupfs, 및 binfmtfs (GH #1378)</span><span class="sxs-lookup"><span data-stu-id="6f9d2-987">Implemented statfs callback for procfs, sysfs, cgroupfs, and binfmtfs (GH #1378)</span></span>
- <span data-ttu-id="6f9d2-988">(GH #1184, GH # 1193에 대해서도 설명)를 닫지는 고정 된 AptPackageIndexUpdate windows</span><span class="sxs-lookup"><span data-stu-id="6f9d2-988">Fixed AptPackageIndexUpdate windows that won’t close (GH #1184, also discussed in GH #1193)</span></span>
- <span data-ttu-id="6f9d2-989">ADDR_NO_RANDOMIZE 지원 ASLR 성격을 추가 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-989">Added ASLR personality  ADDR_NO_RANDOMIZE support.</span></span> <span data-ttu-id="6f9d2-990">(GH #1148, 1128)</span><span class="sxs-lookup"><span data-stu-id="6f9d2-990">(GH #1148, 1128)</span></span>
- <span data-ttu-id="6f9d2-991">향상 된 PTRACE_GETSIGINFO, AV (GH #875) 하는 동안 적절 한 gdb 스택 추적에 대 한 SIGSEGV</span><span class="sxs-lookup"><span data-stu-id="6f9d2-991">Improved PTRACE_GETSIGINFO, SIGSEGV, for proper gdb stack traces during AV (GH #875)</span></span>
- <span data-ttu-id="6f9d2-992">더 이상 구문 분석 elf patchelf 이진 파일에 대 한 실패 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-992">Elf parsing no longer fails for patchelf binaries.</span></span> <span data-ttu-id="6f9d2-993">(GH #471)</span><span class="sxs-lookup"><span data-stu-id="6f9d2-993">(GH #471)</span></span>
- <span data-ttu-id="6f9d2-994">/Etc/resolv.conf (GH #416, 1350)를 VPN DNS 전파</span><span class="sxs-lookup"><span data-stu-id="6f9d2-994">VPN DNS propagated to /etc/resolv.conf (GH #416, 1350)</span></span>
- <span data-ttu-id="6f9d2-995">TCP의 향상 된 기능을 더 신뢰할 수 있는 데이터 전송에 대 한 닫습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-995">Improvements to TCP close for more reliable data transfer.</span></span> <span data-ttu-id="6f9d2-996">(GH #610, 616, 1025, 1335)</span><span class="sxs-lookup"><span data-stu-id="6f9d2-996">(GH #610, 616, 1025, 1335)</span></span>
- <span data-ttu-id="6f9d2-997">이제 올바른 너무 많은 파일이 있는 경우 오류 코드 (EMFILE) 열을 반환 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-997">Now return correct error code when too many files are opened (EMFILE).</span></span> <span data-ttu-id="6f9d2-998">(GH #1126, 2090)</span><span class="sxs-lookup"><span data-stu-id="6f9d2-998">(GH #1126, 2090)</span></span>
- <span data-ttu-id="6f9d2-999">프로세스의 이미지 이름을 Windows 감사 로그 이제 보고서는 감사를 만듭니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-999">Windows Audit log now reports the image name in process create audit.</span></span>
- <span data-ttu-id="6f9d2-1000">Bash 창 내에서 bash.exe 시작할 때 이제 정상적으로 실패</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1000">Now gracefully fail when launching bash.exe from within a bash window</span></span>
- <span data-ttu-id="6f9d2-1001">추가 오류 메시지가 나타난다 interop LxFs (예: notepad.exe.bashrc)에서 작업 디렉터리에 액세스할 수 없는</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1001">Added error message when interop is unable to access a working directory under LxFs (i.e. notepad.exe .bashrc)</span></span>
- <span data-ttu-id="6f9d2-1002">Windows 경로 WSL에서 잘린 여기서 문제 해결된</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1002">Fixed issue where Windows path was truncated in WSL</span></span>
- <span data-ttu-id="6f9d2-1003">추가 수정 및 개선 사항</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1003">Additional fixes and improvements</span></span>

### <a name="ltp-results"></a><span data-ttu-id="6f9d2-1004">LTP 결과:</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1004">LTP Results:</span></span>
<span data-ttu-id="6f9d2-1005">통과 한 테스트 수: 690</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1005">Number of Passing Test: 690</span></span> </br>
<span data-ttu-id="6f9d2-1006">불합격 개수 (실패, 건너뜀 등...): 274</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1006">Number of non-Passing (failing, skipped, etc…): 274</span></span> </br>
[<span data-ttu-id="6f9d2-1007">LTP 테스트 실행 로그</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1007">LTP Test Run Logs</span></span>](https://github.com/Microsoft/CommandLine-Documentation/tree/live/LTP_Results/15002)<br/>

<br/>

### <a name="syscall-support"></a><span data-ttu-id="6f9d2-1008">Syscall 지원</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1008">Syscall Support</span></span>
<span data-ttu-id="6f9d2-1009">다음은 새롭거나 향상 된 syscall WSL 구현에 있는 목록입니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1009">Below are a list of new or enhanced syscalls that have some implementation in WSL.</span></span> <span data-ttu-id="6f9d2-1010">이 목록에 syscall 하나 이상의 시나리오에서 지원 되지만 수 있는 모든 매개 변수에서 지원 되지 않습니다이 시간.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1010">The syscalls on this list are supported in at least one scenario, but may not have all parameters supported at this time.</span></span>

`shmctl`<br/>
`shmget`<br/>
`shmdt`<br/>
`shmat`<br/>
<br/>

## <a name="build-14986"></a><span data-ttu-id="6f9d2-1011">14986 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1011">Build 14986</span></span>

<span data-ttu-id="6f9d2-1012">일반 Windows에 대 한 14986 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2016/12/07/announcing-windows-10-insider-preview-build-14986-pc/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1012">For general Windows information on build 14986 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2016/12/07/announcing-windows-10-insider-preview-build-14986-pc/).</span></span><br/>


### <a name="fixed"></a><span data-ttu-id="6f9d2-1013">고정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1013">Fixed</span></span>

- <span data-ttu-id="6f9d2-1014">Netlink Pty Ioctl와 고정된 버그</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1014">Fixed bugchecks with Netlink and Pty IOCTLs</span></span>
- <span data-ttu-id="6f9d2-1015">커널 버전에는 이제 4.4.0-43 Xenial와의 일관성에 대 한 보고</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1015">Kernel version now reports 4.4.0-43 for consistency with Xenial</span></span>
- <span data-ttu-id="6f9d2-1016">Bash.exe 입력으로 전달 하는 경우 이제 시작 ' nul:' (GH #1259)</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1016">Bash.exe now launches when input directed to 'nul:' (GH #1259)</span></span>
- <span data-ttu-id="6f9d2-1017">스레드 Id procfs (GH #967)에서 올바르게 이제 보고</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1017">Thread IDs now reported correctly in procfs (GH #967)</span></span>
- <span data-ttu-id="6f9d2-1018">IN_UNMOUNT | IN_Q_OVERFLOW | IN_IGNORED | 이제 inotify_add_watch() (GH #1280)에서 지원 되는 IN_ISDIR 플래그</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1018">IN_UNMOUNT | IN_Q_OVERFLOW | IN_IGNORED | IN_ISDIR flags now supported in inotify_add_watch() (GH #1280)</span></span>
- <span data-ttu-id="6f9d2-1019">구현 timer_create 및 관련된 시스템 호출 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1019">Implement timer_create and related system calls.</span></span>  <span data-ttu-id="6f9d2-1020">이렇게 하면 GHC 지원 (GH #307)</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1020">This enables GHC support (GH #307)</span></span>
- <span data-ttu-id="6f9d2-1021">Ping 0.000ms (GH #1296)의 시간을 반환 하는 위치 하는 문제 해결된</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1021">Fixed issue where ping returned a time of 0.000ms (GH #1296)</span></span>
- <span data-ttu-id="6f9d2-1022">너무 많은 파일이 열려 있는 경우 올바른 오류 코드를 반환 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1022">Return correct error code when too many files are opened.</span></span>
- <span data-ttu-id="6f9d2-1023">인터페이스의 하드웨어 주소 (예: Teredo 인터페이스)를 32 바이트 이면 EINVAL를 사용 하 여 네트워크 인터페이스 데이터에 대 한 Netlink 요청 실패는 WSL에서 문제 해결된</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1023">Fixed issue in WSL where Netlink request for network interface data would fail with EINVAL if the interface's hardware address is 32-bytes (such as the Teredo interface)</span></span>
   - <span data-ttu-id="6f9d2-1024">Note Linux "ip" 유틸리티 WSL 32 비트 하드웨어 주소를 보고 하는 경우 충돌이 있는 버그를 포함 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1024">Note that the Linux "ip" utility contains a bug where it will crash if WSL reports a 32-byte hardware address.</span></span> <span data-ttu-id="6f9d2-1025">WSL 없습니다 "ip"의 버그입니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1025">This is a bug in "ip", not WSL.</span></span> <span data-ttu-id="6f9d2-1026">"ip" 유틸리티 하드 코드 길이 문자열 버퍼의 하드웨어 주소를 인쇄 하는 데 사용 하 고 32 비트 하드웨어 주소를 인쇄 하는 버퍼가 너무 작습니다.입니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1026">The “ip” utility hard-codes the length of the string buffer used to print the hardware address, and that buffer is too small to print a 32-byte hardware address.</span></span>
- <span data-ttu-id="6f9d2-1027">추가 수정 및 개선 사항</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1027">Additional fixes and improvements</span></span>

### <a name="ltp-results"></a><span data-ttu-id="6f9d2-1028">LTP 결과:</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1028">LTP Results:</span></span>
<span data-ttu-id="6f9d2-1029">통과 한 테스트 수: 669</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1029">Number of Passing Test: 669</span></span> </br>
<span data-ttu-id="6f9d2-1030">불합격 개수 (실패, 건너뜀 등...): 258</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1030">Number of non-Passing (failing, skipped, etc…): 258</span></span> </br>
[<span data-ttu-id="6f9d2-1031">LTP 테스트 실행 로그</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1031">LTP Test Run Logs</span></span>](https://github.com/Microsoft/CommandLine-Documentation/tree/live/LTP_Results/14986)<br/>

<br/>

### <a name="syscall-support"></a><span data-ttu-id="6f9d2-1032">Syscall 지원</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1032">Syscall Support</span></span>
<span data-ttu-id="6f9d2-1033">다음은 새롭거나 향상 된 syscall WSL 구현에 있는 목록입니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1033">Below are a list of new or enhanced syscalls that have some implementation in WSL.</span></span> <span data-ttu-id="6f9d2-1034">이 목록에 syscall 하나 이상의 시나리오에서 지원 되지만 수 있는 모든 매개 변수에서 지원 되지 않습니다이 시간.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1034">The syscalls on this list are supported in at least one scenario, but may not have all parameters supported at this time.</span></span>

`timer_create`<br/>
`timer_delete`<br/>
`timer_gettime`<br/>
`timer_settime`<br/>
<br/>

## <a name="build-14971"></a><span data-ttu-id="6f9d2-1035">14971 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1035">Build 14971</span></span>

<span data-ttu-id="6f9d2-1036">일반 Windows에 대 한 14971 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2016/11/17/announcing-windows-10-insider-preview-build-14971-for-pc/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1036">For general Windows information on build 14971 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2016/11/17/announcing-windows-10-insider-preview-build-14971-for-pc/).</span></span><br/>


### <a name="fixed"></a><span data-ttu-id="6f9d2-1037">고정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1037">Fixed</span></span>

 - <span data-ttu-id="6f9d2-1038">제어권 초과 상황으로 인해 업데이트가 없는 Linux 용 Windows 하위 시스템에 대 한이 빌드 에입니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1038">Due to circumstances beyond our control there are no updates in this build for the Windows Subsystem for Linux.</span></span>  <span data-ttu-id="6f9d2-1039">정기적으로 예약 된 업데이트는 다음 릴리스에서 다시 시작 됩니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1039">Regularly scheduled updates will resume on the next release.</span></span>

### <a name="ltp-results"></a><span data-ttu-id="6f9d2-1040">LTP 결과:</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1040">LTP Results:</span></span>
<span data-ttu-id="6f9d2-1041">14965에서 변경 되지 않음</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1041">Unchanged from 14965</span></span> </br>
<span data-ttu-id="6f9d2-1042">통과 한 테스트 수: 664</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1042">Number of Passing Test: 664</span></span> </br>
<span data-ttu-id="6f9d2-1043">불합격 개수 (실패, 건너뜀 등...): 263</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1043">Number of non-Passing (failing, skipped, etc…): 263</span></span> </br>
[<span data-ttu-id="6f9d2-1044">LTP 테스트 실행 로그</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1044">LTP Test Run Logs</span></span>](https://github.com/Microsoft/CommandLine-Documentation/tree/live/LTP_Results/14965)<br/>

<br/>

## <a name="build-14965"></a><span data-ttu-id="6f9d2-1045">14965 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1045">Build 14965</span></span>

<span data-ttu-id="6f9d2-1046">일반 Windows에 대 한 14965 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2016/11/09/announcing-windows-10-insider-preview-build-14965-for-mobile-and-pc/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1046">For general Windows information on build 14965 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2016/11/09/announcing-windows-10-insider-preview-build-14965-for-mobile-and-pc/).</span></span><br/>


### <a name="fixed"></a><span data-ttu-id="6f9d2-1047">고정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1047">Fixed</span></span>

- <span data-ttu-id="6f9d2-1048">Netlink 지원 소켓 NETLINK_ROUTE 프로토콜 RTM_GETLINK 및 RTM_GETADDR (GH #468)</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1048">Support for Netlink sockets NETLINK_ROUTE protocol's RTM_GETLINK and RTM_GETADDR (GH #468)</span></span>
  - <span data-ttu-id="6f9d2-1049">네트워크 열거형에 대 한 명령을 ifconfig 및 ip를 사용 하도록 설정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1049">Enables ifconfig and ip commands for network enumeration</span></span>
  - <span data-ttu-id="6f9d2-1050">자세한 정보를 찾을 수 있습니다 우리의 [블로그 게시물 WSL 네트워킹](https://blogs.msdn.microsoft.com/wsl/2016/11/08/225/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1050">More information can be found in our [WSL Networking blog post](https://blogs.msdn.microsoft.com/wsl/2016/11/08/225/).</span></span>

- <span data-ttu-id="6f9d2-1051">기본적으로 사용자의 경로에 포함 되었습니다 /sbin</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1051">/sbin is now in the user's path by default</span></span>
- <span data-ttu-id="6f9d2-1052">NT 사용자 경로 (즉, 이제 입력할 있습니다 notepad.exe System32 Linux 경로에 추가 하지 않고) 기본적으로 이제 WSL 경로에 추가</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1052">NT user path now appended to the WSL path by default (i.e. you can now type notepad.exe without adding System32 to the Linux path)</span></span>
- <span data-ttu-id="6f9d2-1053">/Proc/sys/kernel/cap_last_cap 지원 추가 됨된</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1053">Added support for /proc/sys/kernel/cap_last_cap</span></span>
- <span data-ttu-id="6f9d2-1054">현재 작업 디렉터리 (GH #1254) ansi 이외의 문자를 포함 하는 경우 NT 바이너리 WSL에서 시작할 수 이제</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1054">NT Binaries can now be launched from WSL when the current working directory contains non-ansi characters (GH #1254)</span></span>
- <span data-ttu-id="6f9d2-1055">연결이 끊긴된 unix 스트림 소켓에서 종료를 허용 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1055">Allow shutdown on disconnected unix stream socket.</span></span>
- <span data-ttu-id="6f9d2-1056">PR_GET_PDEATHSIG 지원이 추가 되었습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1056">Added support for PR_GET_PDEATHSIG.</span></span>
- <span data-ttu-id="6f9d2-1057">CLONE_PARENT 지원 추가 됨된</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1057">Added support for CLONE_PARENT</span></span>
- <span data-ttu-id="6f9d2-1058">고정 오류 가져옵니다 파이프 멈춘 즉, bash-c "ls alR /" | bash-c "고양이" (GH #1214)</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1058">Fixed error where piping gets stuck i.e. bash -c "ls -alR /" | bash -c "cat" (GH #1214)</span></span>
- <span data-ttu-id="6f9d2-1059">현재 터미널에 연결할 핸들 요청 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1059">Handle requests to connect to the current terminal.</span></span>
- <span data-ttu-id="6f9d2-1060">/Proc/ 표시<pid>/oom_score_adj 쓰기 가능으로 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1060">Mark /proc/<pid>/oom_score_adj as writable.</span></span>
- <span data-ttu-id="6f9d2-1061">/Sys/fs/cgroup 폴더를 추가 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1061">Add /sys/fs/cgroup folder.</span></span>
- <span data-ttu-id="6f9d2-1062">sched_setaffinity는 선호도 비트 마스크의 수를 반환 해야</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1062">sched_setaffinity should return number of affinity bits mask</span></span>
- <span data-ttu-id="6f9d2-1063">이 경우 올바르게 가정 하지 인터프리터 경로 보다 작거나 64 자 이어야 합니다. ELF 유효성 검사 논리를 수정 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1063">Fix ELF validation logic which incorrectly assumes interpreter paths must be less than 64 characters long.</span></span> <span data-ttu-id="6f9d2-1064">(GH #743)</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1064">(GH #743)</span></span>
- <span data-ttu-id="6f9d2-1065">열린 파일 설명자는 콘솔 창 열기 (GH #1187)를 유지할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1065">Open file descriptors can keep console window open (GH #1187)</span></span>
- <span data-ttu-id="6f9d2-1066">Rename () 뒤에 슬래시가 대상 이름 (GH #1008)에 실패 한 Fixeed 오류</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1066">Fixeed error where rename() failed with trailing slash on target name (GH #1008)</span></span>
- <span data-ttu-id="6f9d2-1067">구현 /proc/net/dev 파일</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1067">Implement /proc/net/dev file</span></span>
- <span data-ttu-id="6f9d2-1068">타이머 해상도 인해 고정된 0.000ms ping합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1068">Fixed 0.000ms pings due to timer resolution.</span></span>
- <span data-ttu-id="6f9d2-1069">구현 된 /proc/self/environ (GH #730)</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1069">Implemented /proc/self/environ (GH #730)</span></span>
- <span data-ttu-id="6f9d2-1070">추가 버그 수정 및 향상 된 기능</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1070">Additional bugfixes and improvements</span></span>

### <a name="ltp-results"></a><span data-ttu-id="6f9d2-1071">LTP 결과:</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1071">LTP Results:</span></span>
<span data-ttu-id="6f9d2-1072">통과 한 테스트 수: 664</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1072">Number of Passing Test: 664</span></span> </br>
<span data-ttu-id="6f9d2-1073">불합격 개수 (실패, 건너뜀 등...): 263</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1073">Number of non-Passing (failing, skipped, etc…): 263</span></span> </br>
[<span data-ttu-id="6f9d2-1074">LTP 테스트 실행 로그</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1074">LTP Test Run Logs</span></span>](https://github.com/Microsoft/CommandLine-Documentation/tree/live/LTP_Results/14965)<br/>

<br/>

## <a name="build-14959"></a><span data-ttu-id="6f9d2-1075">14959 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1075">Build 14959</span></span>

<span data-ttu-id="6f9d2-1076">일반 Windows에 대 한 14959 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2016/11/03/announcing-windows-10-insider-preview-build-14959-for-mobile-and-pc/#iI82GufJxMF3POU1.97)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1076">For general Windows information on build 14959 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2016/11/03/announcing-windows-10-insider-preview-build-14959-for-mobile-and-pc/#iI82GufJxMF3POU1.97).</span></span><br/>


### <a name="fixed"></a><span data-ttu-id="6f9d2-1077">고정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1077">Fixed</span></span>

- <span data-ttu-id="6f9d2-1078">Windows에 대 한 향상 된 Pico 프로세스 알림입니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1078">Improved Pico Process notification for Windows.</span></span>  <span data-ttu-id="6f9d2-1079">추가 정보에는 [WSL 블로그](https://blogs.msdn.microsoft.com/wsl/2016/11/01/wsl-antivirus-and-firewall-compatibility/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1079">Additional information found on the [WSL Blog](https://blogs.msdn.microsoft.com/wsl/2016/11/01/wsl-antivirus-and-firewall-compatibility/).</span></span>
- <span data-ttu-id="6f9d2-1080">Windows 상호 운용성을 사용 하 여 향상 된 안정성</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1080">Improved stability with Windows interoperability</span></span>
- <span data-ttu-id="6f9d2-1081">엔터프라이즈 데이터 보호 (EDP)을 사용 하는 경우 bash.exe를 시작할 때 0x80070057 오류가 수정 됨된</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1081">Fixed error 0x80070057 when launching bash.exe when Enterprise Data Protection (EDP) is enabled</span></span>
- <span data-ttu-id="6f9d2-1082">추가 버그 수정 및 향상 된 기능</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1082">Additional bugfixes and improvements</span></span>

### <a name="ltp-results"></a><span data-ttu-id="6f9d2-1083">LTP 결과:</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1083">LTP Results:</span></span>
<span data-ttu-id="6f9d2-1084">통과 한 테스트 수: 665</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1084">Number of Passing Test: 665</span></span> </br>
<span data-ttu-id="6f9d2-1085">불합격 개수 (실패, 건너뜀 등...): 263</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1085">Number of non-Passing (failing, skipped, etc…): 263</span></span> </br>
[<span data-ttu-id="6f9d2-1086">LTP 테스트 실행 로그</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1086">LTP Test Run Logs</span></span>](https://github.com/Microsoft/CommandLine-Documentation/tree/live/LTP_Results/14959)<br/>

<br/>

## <a name="build-14955"></a><span data-ttu-id="6f9d2-1087">14955 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1087">Build 14955</span></span>

<span data-ttu-id="6f9d2-1088">일반 Windows에 대 한 14955 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2016/10/25/announcing-windows-10-insider-preview-build-14955-for-mobile-and-pc/#guGXQzKVFrZIDUYR.97)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1088">For general Windows information on build 14955 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2016/10/25/announcing-windows-10-insider-preview-build-14955-for-mobile-and-pc/#guGXQzKVFrZIDUYR.97).</span></span><br/>


### <a name="fixed"></a><span data-ttu-id="6f9d2-1089">고정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1089">Fixed</span></span>

 - <span data-ttu-id="6f9d2-1090">제어권 초과 상황으로 인해 업데이트가 없는 Linux 용 Windows 하위 시스템에 대 한이 빌드 에입니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1090">Due to circumstances beyond our control there are no updates in this build for the Windows Subsystem for Linux.</span></span>  <span data-ttu-id="6f9d2-1091">정기적으로 예약 된 업데이트는 다음 릴리스에서 다시 시작 됩니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1091">Regularly scheduled updates will resume on the next release.</span></span>

### <a name="ltp-results"></a><span data-ttu-id="6f9d2-1092">LTP 결과:</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1092">LTP Results:</span></span>
<span data-ttu-id="6f9d2-1093">통과 한 테스트 수: 665</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1093">Number of Passing Test: 665</span></span> </br>
<span data-ttu-id="6f9d2-1094">불합격 개수 (실패, 건너뜀 등...): 263</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1094">Number of non-Passing (failing, skipped, etc…): 263</span></span> </br>
[<span data-ttu-id="6f9d2-1095">LTP 테스트 실행 로그</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1095">LTP Test Run Logs</span></span>](https://github.com/Microsoft/CommandLine-Documentation/tree/live/LTP_Results/14955)<br/>

<br/>

## <a name="build-14951"></a><span data-ttu-id="6f9d2-1096">14951 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1096">Build 14951</span></span>

<span data-ttu-id="6f9d2-1097">일반 Windows에 대 한 14951 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2016/10/19/announcing-windows-10-insider-preview-build-14951-for-mobile-and-pc/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1097">For general Windows information on build 14951 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2016/10/19/announcing-windows-10-insider-preview-build-14951-for-mobile-and-pc/).</span></span><br/>


### <a name="new-feature-windows--ubuntu-interoperability"></a><span data-ttu-id="6f9d2-1098">새로운 기능: Windows / Ubuntu 상호 운용성</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1098">New Feature: Windows / Ubuntu Interoperability</span></span>
<span data-ttu-id="6f9d2-1099">이제 WSL 명령줄에서 직접 Windows 이진 파일을 호출할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1099">Windows binaries can now be invoked directly from the WSL command line.</span></span>  <span data-ttu-id="6f9d2-1100">이렇게 하면 사용자는 Windows 환경 및 가능한 되지 않은 방식으로 상호 작용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1100">This gives users the ability to interact with their Windows environment and system in a way that has not been possible.</span></span>  <span data-ttu-id="6f9d2-1101">간단한 예제로 다음 명령을 실행 하는 사용자에 대 한 가능한 되었습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1101">As a quick example, it is now possible for users to run the following commands:</span></span>

    ```
    $ export PATH=$PATH:/mnt/c/Windows/System32
    $ notepad.exe
    $ ipconfig.exe | grep IPv4 | cut -d: -f2
    $ ls -la | findstr.exe foo.txt
    $ cmd.exe /c dir
    ```

<span data-ttu-id="6f9d2-1102">자세한 내용은에서 찾을 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1102">More information can be found at:</span></span>

- [<span data-ttu-id="6f9d2-1103">Interop에 대 한 WSL 팀 블로그</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1103">WSL Team Blog for Interop</span></span>](https://blogs.msdn.microsoft.com/wsl/2016/10/19/windows-and-ubuntu-interoperability/)<br/>
- [<span data-ttu-id="6f9d2-1104">MSDN Interop 설명서</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1104">MSDN Interop Documentation</span></span>](https://msdn.microsoft.com/en-us/commandline/wsl/interop)<br/>

### <a name="fixed"></a><span data-ttu-id="6f9d2-1105">고정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1105">Fixed</span></span>

- <span data-ttu-id="6f9d2-1106">Ubuntu 16.04 (Xenial)는 이제 모든 새 WSL 인스턴스에 대 한 설치 됩니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1106">Ubuntu 16.04 (Xenial) is now installed for all new WSL instances.</span></span>  <span data-ttu-id="6f9d2-1107">기존 14.04 (믿음직한) 인스턴스를 사용 하 여 사용자가 자동으로 업그레이드 되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1107">Users with existing 14.04 (Trusty) instances will not be automatically upgraded.</span></span>
- <span data-ttu-id="6f9d2-1108">설치 중에 설정 된 로캘을 표시 됩니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1108">Locale set during install is now displayed</span></span>
- <span data-ttu-id="6f9d2-1109">항상 그렇지는 않음 않습니다 WSL 프로세스 파일로 리디렉션하는 버그를 포함 하 여 터미널 향상 작업</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1109">Terminal improvements including bug where redirecting a WSL process to a file does not always work</span></span>
- <span data-ttu-id="6f9d2-1110">콘솔의 수명이 bash.exe 수명에 연결 해야</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1110">Console lifetime should be tied to bash.exe lifetime</span></span>
- <span data-ttu-id="6f9d2-1111">콘솔 창 크기는 버퍼 크기가 아니라 표시 크기를 사용 해야</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1111">Console window size should use visible size, not buffer size</span></span>
- <span data-ttu-id="6f9d2-1112">추가 버그 수정 및 향상 된 기능</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1112">Additional bugfixes and improvements</span></span>

### <a name="ltp-results"></a><span data-ttu-id="6f9d2-1113">LTP 결과:</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1113">LTP Results:</span></span>
<span data-ttu-id="6f9d2-1114">통과 한 테스트 수: 665</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1114">Number of Passing Test: 665</span></span> </br>
<span data-ttu-id="6f9d2-1115">불합격 개수 (실패, 건너뜀 등...): 263</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1115">Number of non-Passing (failing, skipped, etc…): 263</span></span> </br>
[<span data-ttu-id="6f9d2-1116">LTP 테스트 실행 로그</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1116">LTP Test Run Logs</span></span>](https://github.com/Microsoft/CommandLine-Documentation/tree/live/LTP_Results/14951)<br/>

<br/>

## <a name="build-14946"></a><span data-ttu-id="6f9d2-1117">14946 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1117">Build 14946</span></span>

<span data-ttu-id="6f9d2-1118">일반 Windows에 대 한 14946 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2016/10/13/announcing-windows-10-insider-preview-build-14946-for-pc-and-mobile/#xj8GdVooEqo4H7H7.97)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1118">For general Windows information on build 14946 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2016/10/13/announcing-windows-10-insider-preview-build-14946-for-pc-and-mobile/#xj8GdVooEqo4H7H7.97).</span></span><br/>


### <a name="fixed"></a><span data-ttu-id="6f9d2-1119">고정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1119">Fixed</span></span>

- <span data-ttu-id="6f9d2-1120">공백이 나 따옴표가 포함 된 NT 사용자 이름을 사용 하 여 사용자에 대 한 WSL 사용자 계정 만들기를 방해 하는 문제가 수정 되었습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1120">Fixed an issue that prevented creating WSL user accounts for users with NT usernames that contain spaces or quotes.</span></span> 
- <span data-ttu-id="6f9d2-1121">바뀌는 VolFs DrvFs stat에서 디렉터리의 링크 개수에 대 한 0을 반환 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1121">Change VolFs and DrvFs to return 0 for directory's link count in stat</span></span>
- <span data-ttu-id="6f9d2-1122">IPV6_MULTICAST_HOPS 소켓 옵션을 지원 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1122">Support IPV6_MULTICAST_HOPS socket option.</span></span>
- <span data-ttu-id="6f9d2-1123">Tty 당 I/O 루프는 단일 콘솔을 제한 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1123">Limit to a single console I/O loop per tty.</span></span> <span data-ttu-id="6f9d2-1124">예 명령을 불가능 합니다.:</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1124">Example: the following command is possible:</span></span>
  - <span data-ttu-id="6f9d2-1125">bash -c "echo data" | bash -c "ssh user@example.com 'cat > foo.txt'"</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1125">bash -c "echo data" | bash -c "ssh user@example.com 'cat > foo.txt'"</span></span>

- <span data-ttu-id="6f9d2-1126">공백은 /proc/cpuinfo (GH #1115) 탭으로 대체</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1126">replace spaces with tabs in /proc/cpuinfo (GH #1115)</span></span>
- <span data-ttu-id="6f9d2-1127">이제 탑재 된 Windows 볼륨을 일치 하는 이름의 mountinfo DrvFs에 나타납니다</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1127">DrvFs now appears in mountinfo with a name that matches mounted Windows volume</span></span>
- <span data-ttu-id="6f9d2-1128">/home 및 /root 이제 올바른 이름의 mountinfo에 표시</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1128">/home and /root now appear in mountinfo with correct names</span></span>
- <span data-ttu-id="6f9d2-1129">추가 버그 수정 및 향상 된 기능</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1129">Additional bugfixes and improvements</span></span>

### <a name="ltp-results"></a><span data-ttu-id="6f9d2-1130">LTP 결과:</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1130">LTP Results:</span></span>
<span data-ttu-id="6f9d2-1131">통과 한 테스트 수: 665</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1131">Number of Passing Test: 665</span></span> </br>
<span data-ttu-id="6f9d2-1132">불합격 개수 (실패, 건너뜀 등...): 263</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1132">Number of non-Passing (failing, skipped, etc…): 263</span></span> </br>
[<span data-ttu-id="6f9d2-1133">LTP 테스트 실행 로그</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1133">LTP Test Run Logs</span></span>](https://github.com/Microsoft/CommandLine-Documentation/tree/live/LTP_Results/14946)<br/>

<br/>

## <a name="build-14942"></a><span data-ttu-id="6f9d2-1134">14942 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1134">Build 14942</span></span>

<span data-ttu-id="6f9d2-1135">일반 Windows에 대 한 14942 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://aka.ms/onefourninefourtwoooooo)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1135">For general Windows information on build 14942 visit the [Windows Blog](https://aka.ms/onefourninefourtwoooooo).</span></span><br/>


### <a name="fixed"></a><span data-ttu-id="6f9d2-1136">고정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1136">Fixed</span></span>

- <span data-ttu-id="6f9d2-1137">다양 한 메모리를 포함 하는 "시도 실행의 NOEXECUTE" 네트워킹 SSH 차단 된 충돌 해결 버그</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1137">A number of bugchecks addressed, including the “ATTEMPTED EXECUTE OF NOEXECUTE MEMORY” networking crash which was blocking SSH</span></span>
- <span data-ttu-id="6f9d2-1138">inotifiy DrvFs에서 Windows 응용 프로그램에서 생성 된 알림에 대 한 지원은 이제</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1138">inotifiy support for notifications generated from Windows applications on DrvFs is now in</span></span>
- <span data-ttu-id="6f9d2-1139">TCP_KEEPIDLE 및 TCP_KEEPINTVL mongod에 대 한 구현 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1139">Implement TCP_KEEPIDLE and TCP_KEEPINTVL for mongod.</span></span> <span data-ttu-id="6f9d2-1140">(GH #695)</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1140">(GH #695)</span></span>
- <span data-ttu-id="6f9d2-1141">Pivot_root 시스템 호출을 구현 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1141">Implement the pivot_root system call</span></span>
- <span data-ttu-id="6f9d2-1142">SO_DONTROUTE 소켓 옵션을 구현 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1142">Implement socket option for SO_DONTROUTE</span></span>
- <span data-ttu-id="6f9d2-1143">추가 버그 수정 및 향상 된 기능</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1143">Additional bugfixes and improvements</span></span>


### <a name="ltp-results"></a><span data-ttu-id="6f9d2-1144">LTP 결과:</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1144">LTP Results:</span></span>
<span data-ttu-id="6f9d2-1145">통과 한 테스트 수: 665</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1145">Number of Passing Test: 665</span></span> </br>
<span data-ttu-id="6f9d2-1146">불합격 개수 (실패, 건너뜀 등...): 263</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1146">Number of non-Passing (failing, skipped, etc…): 263</span></span> </br>
[<span data-ttu-id="6f9d2-1147">LTP 테스트 실행 로그</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1147">LTP Test Run Logs</span></span>](https://github.com/Microsoft/CommandLine-Documentation/tree/live/LTP_Results/14942)<br/>

### <a name="syscall-support"></a><span data-ttu-id="6f9d2-1148">Syscall 지원</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1148">Syscall Support</span></span>
<span data-ttu-id="6f9d2-1149">다음은 새롭거나 향상 된 syscall WSL 구현에 있는 목록입니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1149">Below are a list of new or enhanced syscalls that have some implementation in WSL.</span></span> <span data-ttu-id="6f9d2-1150">이 목록에 syscall 하나 이상의 시나리오에서 지원 되지만 수 있는 모든 매개 변수에서 지원 되지 않습니다이 시간.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1150">The syscalls on this list are supported in at least one scenario, but may not have all parameters supported at this time.</span></span>

`pivot_root`<br/>
<br/>

## <a name="build-14936"></a><span data-ttu-id="6f9d2-1151">14936 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1151">Build 14936</span></span>

<span data-ttu-id="6f9d2-1152">일반 Windows에 대 한 14936 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2016/09/28/announcing-windows-10-insider-preview-build-14936-for-pc/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1152">For general Windows information on build 14936 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2016/09/28/announcing-windows-10-insider-preview-build-14936-for-pc/).</span></span><br/>


<span data-ttu-id="6f9d2-1153">참고: WSL 예정 된 릴리스에서 Ubuntu 버전 16.04 (Xenial) 대신 Ubuntu 14.04 (신뢰할 수 있는)를 설치 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1153">Note: WSL will install Ubuntu version 16.04 (Xenial) instead of Ubuntu 14.04 (Trusty) in an upcoming release.</span></span>  <span data-ttu-id="6f9d2-1154">이 변경 (lxrun.exe /install 또는 bash.exe의 첫 번째 실행)의 새 인스턴스를 설치 하는 참가자에 적용 됩니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1154">This change will apply to Insiders installing new instances (lxrun.exe /install or first run of bash.exe).</span></span>  <span data-ttu-id="6f9d2-1155">신뢰할 수 있는 사용 하 여 기존 인스턴스는 자동으로 업그레이드 되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1155">Existing instances with Trusty will not be upgraded automatically.</span></span> <span data-ttu-id="6f9d2-1156">사용자 믿음직한 이미지 Xenial 수행 릴리스 업그레이드 명령을 사용 하 여 업그레이드할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1156">Users can upgrade their Trusty image to Xenial using the do-release-upgrade command.</span></span>

### <a name="known-issue"></a><span data-ttu-id="6f9d2-1157">알려진된 문제</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1157">Known Issue</span></span>
<span data-ttu-id="6f9d2-1158">WSL에서 일부 소켓 구현 문제가 발생 했습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1158">WSL is experiencing an issue with some socket implementations.</span></span>  <span data-ttu-id="6f9d2-1159">버그 확인 자체 명시 "시도 실행의 NOEXECUTE MEMORY" 오류와 충돌 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1159">The bugcheck manifests itself as a crash with the error “ATTEMPTED EXECUTE OF NOEXECUTE MEMORY”.</span></span>  <span data-ttu-id="6f9d2-1160">이 문제의 가장 일반적인 특성 충돌이 경우 ssh를 사용 하 여입니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1160">The most common manifestation of this issue is a crash when using ssh.</span></span>  <span data-ttu-id="6f9d2-1161">근본 원인을 내부 빌드에 고정 하 고 가능한 한 빨리 참가자에 밀어넣습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1161">The root cause is fixed on internal builds and will be pushed to Insiders at the earliest opportunity.</span></span>

### <a name="fixed"></a><span data-ttu-id="6f9d2-1162">고정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1162">Fixed</span></span>

- <span data-ttu-id="6f9d2-1163">Chroot 시스템 호출이 구현</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1163">Implemented the chroot system call</span></span>
- <span data-ttu-id="6f9d2-1164">Inotify의 향상 된 기능 ~~DrvFs에서 Windows 응용 프로그램에서 생성 된 알림에 대 한 지원을 비롯 하 여~~</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1164">Improvements in inotify ~~including support for notifications generated from Windows applications on DrvFs~~</span></span>
  - <span data-ttu-id="6f9d2-1165">수정: Inotify 지금은 사용할 수 없는 Windows 응용 프로그램에서 시작 된 변경을 지원 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1165">Correction: Inotify support for changes originating from Windows applications not available at this time.</span></span>
- <span data-ttu-id="6f9d2-1166">소켓을 IPV6 바인딩::<port n> IPV6_V6ONLY는 이제 (GH #68, #157, #393, #460, #674, #740, #982, #996)</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1166">Socket binding to IPV6::<port n> now supports IPV6_V6ONLY  (GH #68, #157, #393, #460, #674, #740, #982, #996)</span></span>
- <span data-ttu-id="6f9d2-1167">Waitid systemcall 구현 (GH #638)에 대 한 WNOWAIT 동작</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1167">WNOWAIT behavior for waitid systemcall implemented (GH #638)</span></span>
- <span data-ttu-id="6f9d2-1168">IP_HDRINCL 및 IP_TTL IP 소켓 옵션에 대 한 지원</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1168">Support for IP socket options IP_HDRINCL and IP_TTL</span></span>
- <span data-ttu-id="6f9d2-1169">길이가 0 인 read ()가 즉시 반환 하도록 (GH #975)</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1169">Zero-length read() should return immediately (GH #975)</span></span>
- <span data-ttu-id="6f9d2-1170">.Tar 파일에는 NULL 종결자를 포함 하지 않는 파일 이름 및 파일 이름 접두사를 올바르게 처리 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1170">Correctly handle filenames and filename prefixes that don't include a NULL terminator in a .tar file.</span></span>
- <span data-ttu-id="6f9d2-1171">/dev/null epoll 지원</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1171">epoll support for /dev/null</span></span>
- <span data-ttu-id="6f9d2-1172">/Dev/alarm 시간 원본 수정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1172">Fix /dev/alarm time source</span></span>
- <span data-ttu-id="6f9d2-1173">-C 파일을 리디렉션할 수 이제 bash</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1173">Bash -c now able to redirect to a file</span></span>
- <span data-ttu-id="6f9d2-1174">추가 버그 수정 및 향상 된 기능</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1174">Additional bugfixes and improvements</span></span>

### <a name="ltp-results"></a><span data-ttu-id="6f9d2-1175">LTP 결과:</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1175">LTP Results:</span></span>
<span data-ttu-id="6f9d2-1176">통과 한 테스트 수: 664</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1176">Number of Passing Test: 664</span></span> </br>
<span data-ttu-id="6f9d2-1177">불합격 개수 (실패, 건너뜀 등...): 264</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1177">Number of non-Passing (failing, skipped, etc…): 264</span></span> </br>
[<span data-ttu-id="6f9d2-1178">LTP 테스트 실행 로그</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1178">LTP Test Run Logs</span></span>](https://github.com/Microsoft/CommandLine-Documentation/tree/live/LTP_Results/14936)<br/>

### <a name="syscall-support"></a><span data-ttu-id="6f9d2-1179">Syscall 지원</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1179">Syscall Support</span></span>
<span data-ttu-id="6f9d2-1180">다음은 새롭거나 향상 된 syscall WSL 구현에 있는 목록입니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1180">Below are a list of new or enhanced syscalls that have some implementation in WSL.</span></span> <span data-ttu-id="6f9d2-1181">이 목록에 syscall 하나 이상의 시나리오에서 지원 되지만 수 있는 모든 매개 변수에서 지원 되지 않습니다이 시간.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1181">The syscalls on this list are supported in at least one scenario, but may not have all parameters supported at this time.</span></span>

`chroot`<br/>
<br/>

## <a name="build-14931"></a><span data-ttu-id="6f9d2-1182">14931 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1182">Build 14931</span></span>

<span data-ttu-id="6f9d2-1183">일반 Windows에 대 한 14931 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2016/09/21/announcing-windows-10-insider-preview-build-14931-for-pc/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1183">For general Windows information on build 14931 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2016/09/21/announcing-windows-10-insider-preview-build-14931-for-pc/).</span></span><br/>


### <a name="fixed"></a><span data-ttu-id="6f9d2-1184">고정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1184">Fixed</span></span>

 - <span data-ttu-id="6f9d2-1185">제어권 초과 상황으로 인해 업데이트가 없는 Linux 용 Windows 하위 시스템에 대 한이 빌드 에입니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1185">Due to circumstances beyond our control there are no updates in this build for the Windows Subsystem for Linux.</span></span>  <span data-ttu-id="6f9d2-1186">정기적으로 예약 된 업데이트는 다음 릴리스에서 다시 시작 됩니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1186">Regularly scheduled updates will resume in the next release.</span></span>

<br/>

## <a name="build-14926"></a><span data-ttu-id="6f9d2-1187">14926 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1187">Build 14926</span></span>

<span data-ttu-id="6f9d2-1188">일반 Windows에 대 한 14926 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2016/09/14/announcing-windows-10-insider-preview-build-14926-for-pc-and-mobile/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1188">For general Windows information on build 14926 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2016/09/14/announcing-windows-10-insider-preview-build-14926-for-pc-and-mobile/).</span></span><br/>


### <a name="fixed"></a><span data-ttu-id="6f9d2-1189">고정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1189">Fixed</span></span>

- <span data-ttu-id="6f9d2-1190">Ping 이제 관리자 권한이 없는 콘솔에서 작동 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1190">Ping now works in consoles which do not have administrator privileges</span></span>
- <span data-ttu-id="6f9d2-1191">이제 지원도 관리자 권한 없이 Ping6</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1191">Ping6 now supported, also without administrator privileges</span></span>
- <span data-ttu-id="6f9d2-1192">WSL를 통해 수정 된 파일에 대 한 Inotify 지원 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1192">Inotify support for files modified through WSL.</span></span> <span data-ttu-id="6f9d2-1193">(GH #216)</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1193">(GH #216)</span></span>
  - <span data-ttu-id="6f9d2-1194">플래그를 지원 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1194">Flags supported:</span></span>
    - <span data-ttu-id="6f9d2-1195">inotify_init1: LX_O_CLOEXEC, LX_O_NONBLOCK</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1195">inotify_init1: LX_O_CLOEXEC, LX_O_NONBLOCK</span></span>
    - <span data-ttu-id="6f9d2-1196">inotify_add_watch 이벤트: LX_IN_ACCESS, LX_IN_MODIFY, LX_IN_ATTRIB, LX_IN_CLOSE_WRITE, LX_IN_CLOSE_NOWRITE, LX_IN_OPEN, LX_IN_MOVED_FROM, LX_IN_MOVED_TO, LX_IN_CREATE, LX_IN_DELETE, LX_IN_DELETE_SELF, LX_IN_MOVE_SELF</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1196">inotify_add_watch events: LX_IN_ACCESS, LX_IN_MODIFY, LX_IN_ATTRIB, LX_IN_CLOSE_WRITE, LX_IN_CLOSE_NOWRITE, LX_IN_OPEN, LX_IN_MOVED_FROM, LX_IN_MOVED_TO, LX_IN_CREATE, LX_IN_DELETE, LX_IN_DELETE_SELF, LX_IN_MOVE_SELF</span></span>
    - <span data-ttu-id="6f9d2-1197">inotify_add_watch 특성: LX_IN_DONT_FOLLOW, LX_IN_EXCL_UNLINK, LX_IN_MASK_ADD, LX_IN_ONESHOT, LX_IN_ONLYDIR</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1197">inotify_add_watch attributes: LX_IN_DONT_FOLLOW, LX_IN_EXCL_UNLINK, LX_IN_MASK_ADD, LX_IN_ONESHOT, LX_IN_ONLYDIR</span></span>
    - <span data-ttu-id="6f9d2-1198">출력을 읽어보세요. LX_IN_ISDIR, LX_IN_IGNORED</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1198">read output: LX_IN_ISDIR, LX_IN_IGNORED</span></span>
  - <span data-ttu-id="6f9d2-1199">알려진된 문제: 이벤트를 생성 하지 않는 Windows 응용 프로그램에서 파일 수정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1199">Known issue: Modifying files from Windows applications does not generate any events</span></span>
- <span data-ttu-id="6f9d2-1200">Unix 소켓에 이제 SCM_CREDENTIALS</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1200">Unix socket now supports SCM_CREDENTIALS</span></span>

### <a name="ltp-results"></a><span data-ttu-id="6f9d2-1201">LTP 결과:</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1201">LTP Results:</span></span>
<span data-ttu-id="6f9d2-1202">통과 한 테스트 수: 651</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1202">Number of Passing Test: 651</span></span> </br>
<span data-ttu-id="6f9d2-1203">불합격 개수 (실패, 건너뜀 등...): 258</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1203">Number of non-Passing (failing, skipped, etc…): 258</span></span> </br>
[<span data-ttu-id="6f9d2-1204">LTP 테스트 실행 로그</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1204">LTP Test Run Logs</span></span>](https://github.com/Microsoft/CommandLine-Documentation/tree/live/LTP_Results/14926)<br/>

<br/>

## <a name="build-14915"></a><span data-ttu-id="6f9d2-1205">14915 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1205">Build 14915</span></span>

<span data-ttu-id="6f9d2-1206">일반 Windows에 대 한 14915 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2016/08/31/announcing-windows-10-insider-preview-build-14915-for-pc-and-mobile)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1206">For general Windows information on build 14915 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2016/08/31/announcing-windows-10-insider-preview-build-14915-for-pc-and-mobile).</span></span><br/>


### <a name="fixed"></a><span data-ttu-id="6f9d2-1207">고정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1207">Fixed</span></span>
-  <span data-ttu-id="6f9d2-1208">Unix 데이터 그램 소켓 (GH #262)에 대 한 Socketpair</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1208">Socketpair for unix datagram sockets (GH #262)</span></span>
- <span data-ttu-id="6f9d2-1209">SO_REUSEADDR Unix 소켓 지원</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1209">Unix socket support for SO_REUSEADDR</span></span>
- <span data-ttu-id="6f9d2-1210">UNIX 소켓 지원 SO_BROADCAST (GH #568)</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1210">UNIX socket support for SO_BROADCAST (GH #568)</span></span>
- <span data-ttu-id="6f9d2-1211">Unix 소켓 지원 SOCK_SEQPACKET (GH #758, #546)</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1211">Unix socket support for SOCK_SEQPACKET (GH #758, #546)</span></span>
- <span data-ttu-id="6f9d2-1212">Unix 데이터 그램 소켓 전송, 수신 및 종료에 대 한 지원 추가</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1212">Adding support for unix datagram socket send, recv and shutdown</span></span>
- <span data-ttu-id="6f9d2-1213">고정 되지 않은 주소에 대 한 잘못 된 mmap 매개 변수 유효성 검사로 인해 오류 검사를 수정 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1213">Fix bugcheck due to invalid mmap parameter validation for non-fixed addresses.</span></span> <span data-ttu-id="6f9d2-1214">(GH #847)</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1214">(GH #847)</span></span>
- <span data-ttu-id="6f9d2-1215">일시 중단에 대 한 지원 / 터미널 상태는 다시 시작</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1215">Support for suspend / resume of terminal states</span></span>
- <span data-ttu-id="6f9d2-1216">화면 유틸리티 (GH #774) 차단을 해제 하려면 TIOCPKT ioctl에 대 한 지원</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1216">Support for TIOCPKT ioctl to unblock the Screen utility (GH #774)</span></span>
    - <span data-ttu-id="6f9d2-1217">알려진된 문제: 기능 키 작동 하지 않음</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1217">Known issue: Function keys not operational</span></span>
- <span data-ttu-id="6f9d2-1218">해제 된 멤버 'ReaderReady' LxpTimerFdWorkerRoutine (GH #814)에서 액세스 될 수 있는 TimerFd 경합이 수정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1218">Corrected a race in TimerFd that could cause a freed member 'ReaderReady' to be accessed by LxpTimerFdWorkerRoutine (GH #814)</span></span>
- <span data-ttu-id="6f9d2-1219">Futex, 설문 조사, 및 clock_nanosleep 다시 시작할 수 있는 시스템 호출 지원을 사용 하도록 설정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1219">Enable restartable system call support for futex, poll, and clock_nanosleep</span></span>
- <span data-ttu-id="6f9d2-1220">추가 바인딩 탑재 지원</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1220">Added bind mount support</span></span>
- <span data-ttu-id="6f9d2-1221">탑재 네임 스페이스 지원에 대 한 공유 해제</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1221">unshare for mount namespace support</span></span>
    - <span data-ttu-id="6f9d2-1222">알려진된 문제: 사용 하 여 새 탑재 네임 스페이스를 만들 때 `unshare(CLONE_NEWNS)` 현재 작업 디렉터리를 이전 네임 스페이스를 가리키도록 계속 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1222">Known issue: When creating a new mount namespace with `unshare(CLONE_NEWNS)` the current working directory will continue to point to the old namespace</span></span>
- <span data-ttu-id="6f9d2-1223">추가 개선 사항 및 버그 수정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1223">Additional improvements and bug fixes</span></span>

<br/>

## <a name="build-14905"></a><span data-ttu-id="6f9d2-1224">14905 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1224">Build 14905</span></span>

<span data-ttu-id="6f9d2-1225">일반 Windows에 대 한 14905 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2016/08/17/announcing-windows-10-insider-preview-build-14905-for-pc-mobile/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1225">For general Windows information on build 14905 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2016/08/17/announcing-windows-10-insider-preview-build-14905-for-pc-mobile/).</span></span><br/>


### <a name="fixed"></a><span data-ttu-id="6f9d2-1226">고정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1226">Fixed</span></span>
- <span data-ttu-id="6f9d2-1227">다시 시작할 수 있는 시스템 호출 됩니다 (GH #349, GH #520) 지원</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1227">Restartable system calls are now supported (GH #349, GH #520)</span></span>
- <span data-ttu-id="6f9d2-1228">Symlink 디렉터리에 / 이제 작업 종료 (GH #650)</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1228">Symlinks to directories ending in / now operational (GH #650)</span></span>
- <span data-ttu-id="6f9d2-1229">/Dev/random에 대 한 구현된 RNDGETENTCNT ioctl</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1229">Implemented RNDGETENTCNT ioctl for /dev/random</span></span>
- <span data-ttu-id="6f9d2-1230">[Pid] /proc/ 구현 / 탑재를 /proc/ [pid] / mountinfo 및 /proc/ [pid] / mountstats 파일</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1230">Implemented the /proc/[pid]/mounts, /proc/[pid]/mountinfo and /proc/[pid]/mountstats files</span></span>
- <span data-ttu-id="6f9d2-1231">추가 버그 수정 및 향상 된 기능</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1231">Additional bugfixes and improvements</span></span>

</br>

## <a name="build-14901"></a><span data-ttu-id="6f9d2-1232">14901 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1232">Build 14901</span></span>
<span data-ttu-id="6f9d2-1233">Windows 10 1 주년 업데이트 릴리스 게시물에 대 한 첫 번째 참가자 빌드.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1233">First Insider build for the post Windows 10 Anniversary Update release.</span></span>

<span data-ttu-id="6f9d2-1234">일반 Windows에 대 한 14901 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2016/08/11/announcing-windows-10-insider-preview-build-14901-for-pc/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1234">For general Windows information on build 14901 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2016/08/11/announcing-windows-10-insider-preview-build-14901-for-pc/).</span></span><br/>


### <a name="fixed"></a><span data-ttu-id="6f9d2-1235">고정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1235">Fixed</span></span>
- <span data-ttu-id="6f9d2-1236">후행 슬래시 문제 해결된</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1236">Fixed trailing slash issue</span></span>
    - <span data-ttu-id="6f9d2-1237">같은 명령 `$ mv a/c/ a/b/` 이제 작동</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1237">Commands such as `$ mv a/c/ a/b/` now work</span></span>
- <span data-ttu-id="6f9d2-1238">Ubuntu 로캘 Windows 로캘을 설정 해야 하는 경우 이제 프롬프트 설치</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1238">Installing now prompts if Ubuntu locale should be set to Windows locale</span></span>
- <span data-ttu-id="6f9d2-1239">Ns 폴더에 대 한 procfs 지원</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1239">Procfs support for ns folder</span></span>
- <span data-ttu-id="6f9d2-1240">탑재를 추가 및 tmpfs procfs 한 sysfs 파일 시스템 탑재 해제</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1240">Added mount and unmount for tmpfs, procfs and sysfs file systems</span></span>
- <span data-ttu-id="6f9d2-1241">[At] 32 비트 ABI 서명 mknod 수정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1241">Fix mknod[at] 32-bit ABI signature</span></span>
- <span data-ttu-id="6f9d2-1242">모델에 디스패치할 때 이동 하는 Unix 소켓</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1242">Unix sockets moved to dispatch model</span></span>
- <span data-ttu-id="6f9d2-1243">INET 소켓 수신 버퍼 크기는 setsockopt를 사용 하 여 설정에 적용 되어야 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1243">INET socket recv buffer size set using the setsockopt should be honored</span></span>
- <span data-ttu-id="6f9d2-1244">구현 MSG_CMSG_CLOEXEC unix 소켓 수신 메시지 플래그</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1244">Implement MSG_CMSG_CLOEXEC unix socket receive message flag</span></span>
- <span data-ttu-id="6f9d2-1245">Linux 프로세스 stdin/stdout 파이프 리디렉션 (GH #2)</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1245">Linux process stdin/stdout pipe redirection (GH #2)</span></span>
    - <span data-ttu-id="6f9d2-1246">명령줄에서 bash-c 명령의 파이핑 허용</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1246">Allows for piping of bash -c commands in CMD.</span></span>  <span data-ttu-id="6f9d2-1247">예: > dir | bash-c "grep foo"</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1247">Example:  >dir | bash -c "grep foo"</span></span>
- <span data-ttu-id="6f9d2-1248">Bash은 이제 여러 사용량과 (GH #538, #358)를 사용 하 여 시스템에 설치할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1248">Bash can now be installed on systems with multiple pagefiles (GH #538, #358)</span></span>
- <span data-ttu-id="6f9d2-1249">기본 INET 소켓 버퍼 크기를 일치 해야 함을 기본 Ubuntu 설치</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1249">Default INET Socket buffer size should match that of default Ubuntu setup</span></span>
- <span data-ttu-id="6f9d2-1250">Xattr syscall listxattr에 맞춤</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1250">Align xattr syscalls to listxattr</span></span>
- <span data-ttu-id="6f9d2-1251">유효한 IPv4 주소를 사용 하 여 인터페이스 SIOCGIFCONF에서 반환</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1251">Only return interfaces with a valid IPv4 address from SIOCGIFCONF</span></span>
- <span data-ttu-id="6f9d2-1252">신호 ptrace에 의해 삽입 된 경우 기본 동작 수정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1252">Fix signal default action when injected by ptrace</span></span>
- <span data-ttu-id="6f9d2-1253">implement /proc/sys/vm/min_free_kbytes</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1253">implement /proc/sys/vm/min_free_kbytes</span></span>
- <span data-ttu-id="6f9d2-1254">Sigreturn 컨텍스트를 복원 하는 경우 컴퓨터 컨텍스트 등록 값을 사용 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1254">Use machine context register values when restoring context in sigreturn</span></span>
    - <span data-ttu-id="6f9d2-1255">Java 및 javac 일부 사용자에 대 한 중지 된 문제 해결</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1255">This resolves the issue where java and javac were hanging for some users</span></span>
- <span data-ttu-id="6f9d2-1256">/Proc/sys/kernel/hostname 구현</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1256">Implement /proc/sys/kernel/hostname</span></span>

### <a name="syscall-support"></a><span data-ttu-id="6f9d2-1257">Syscall 지원</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1257">Syscall Support</span></span>
<span data-ttu-id="6f9d2-1258">다음은 새롭거나 향상 된 syscall WSL 구현에 있는 목록입니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1258">Below are a list of new or enhanced syscalls that have some implementation in WSL.</span></span> <span data-ttu-id="6f9d2-1259">이 목록에 syscall 하나 이상의 시나리오에서 지원 되지만 수 있는 모든 매개 변수에서 지원 되지 않습니다이 시간.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1259">The syscalls on this list are supported in at least one scenario, but may not have all parameters supported at this time.</span></span>

`waitid`<br/>
`epoll_pwait`<br/>

<br/>

## <a name="build-14388-to-windows-10-anniversary-update"></a><span data-ttu-id="6f9d2-1260">Windows 10 1 주년 업데이트에 14388 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1260">Build 14388 to Windows 10 Anniversary Update</span></span>
<span data-ttu-id="6f9d2-1261">일반 Windows에 대 한 14388 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://aka.ms/14388wip)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1261">For general Windows information on build 14388 visit the [Windows Blog](https://aka.ms/14388wip).</span></span> <br/>

### <a name="fixed"></a><span data-ttu-id="6f9d2-1262">고정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1262">Fixed</span></span>
- <span data-ttu-id="6f9d2-1263">8/2에서 Windows 10 1 주년 업데이트에 대 한 준비를 수정 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1263">Fixes to prepare for the Windows 10 Anniversary Update on 8/2</span></span>
  - <span data-ttu-id="6f9d2-1264">WSL 1 주년 업데이트에 대 한 자세한 내용은에서 확인할 수 있습니다이 [블로그](https://blogs.msdn.microsoft.com/wsl/)</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1264">More information about WSL in the Anniversary Update can be found on our [blog](https://blogs.msdn.microsoft.com/wsl/)</span></span>

<br/>

## <a name="build-14376"></a><span data-ttu-id="6f9d2-1265">14376 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1265">Build 14376</span></span>
<span data-ttu-id="6f9d2-1266">일반 Windows에 대 한 14376 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2016/06/28/announcing-windows-10-insider-preview-build-14376-for-pc-and-mobile/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1266">For general Windows information on build 14376 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2016/06/28/announcing-windows-10-insider-preview-build-14376-for-pc-and-mobile/).</span></span> <br/>

### <a name="fixed"></a><span data-ttu-id="6f9d2-1267">고정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1267">Fixed</span></span>
- <span data-ttu-id="6f9d2-1268">Get apt (GH #493)를 중지 하는 되는 일부 인스턴스에서 제거</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1268">Removed some instances where apt-get hangs (GH #493)</span></span>
- <span data-ttu-id="6f9d2-1269">빈 탑재 올바르게 처리 되지 않은 문제를 해결 함</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1269">Fixed an issue where empty mounts were not handled correctly</span></span>
- <span data-ttu-id="6f9d2-1270">Ramdisks 올바르게 탑재 되지 않은 문제를 해결 함</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1270">Fixed an issue where ramdisks were not mounted correctly</span></span>
- <span data-ttu-id="6f9d2-1271">(부분 GH #451) 플래그를 지원 하기 위해 변경 unix 소켓 수락</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1271">Change unix socket accept to support flags (partial GH #451)</span></span>
- <span data-ttu-id="6f9d2-1272">고정된 공용 네트워크 관련 블루 스크린</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1272">Fixed common network related bluescreen</span></span>
- <span data-ttu-id="6f9d2-1273">블루 스크린 /proc/ [pid]에 액세스할 때 고정 (GH #523) 작업 /</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1273">Fixed bluescreen when accessing /proc/[pid]/task (GH #523)</span></span>
- <span data-ttu-id="6f9d2-1274">일부 pty 시나리오 (GH #488, #504)에 대 한 고정된 높은 CPU 사용률</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1274">Fixed high CPU utilization for some pty scenarios (GH #488, #504)</span></span>
- <span data-ttu-id="6f9d2-1275">추가 버그 수정 및 향상 된 기능</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1275">Additional bugfixes and improvements</span></span>

<br/>

## <a name="build-14371"></a><span data-ttu-id="6f9d2-1276">14371 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1276">Build 14371</span></span>
<span data-ttu-id="6f9d2-1277">일반 Windows에 대 한 14371 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2016/06/22/announcing-windows-10-insider-preview-build-14371-for-pc/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1277">For general Windows information on build 14371 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2016/06/22/announcing-windows-10-insider-preview-build-14371-for-pc/).</span></span> <br/>

### <a name="fixed"></a><span data-ttu-id="6f9d2-1278">고정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1278">Fixed</span></span>
- <span data-ttu-id="6f9d2-1279">SIGCHLD wait()와 타이밍 경합 ptrace를 사용 하는 경우 수정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1279">Corrected timing race with SIGCHLD and wait() when using ptrace</span></span>
- <span data-ttu-id="6f9d2-1280">경로 후행를 포함 하는 경우 몇 가지 동작을 수정 / (GH #432)</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1280">Corrected some behavior when paths have a trailing /  (GH #432)</span></span>
- <span data-ttu-id="6f9d2-1281">이름 바꾸기 끊고 열린 핸들을 자식으로 인해 실패 한 문제 해결된</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1281">Fixed issue with rename/unlink failing due to open handles to children</span></span>
- <span data-ttu-id="6f9d2-1282">추가 버그 수정 및 향상 된 기능</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1282">Additional bugfixes and improvements</span></span>

<br/>

## <a name="build-14366"></a><span data-ttu-id="6f9d2-1283">14366 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1283">Build 14366</span></span>
<span data-ttu-id="6f9d2-1284">일반 Windows에 대 한 14366 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://blogs.windows.com/windowsexperience/2016/06/14/announcing-windows-10-insider-preview-build-14366-mobile-build-14364/)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1284">For general Windows information on build 14366 visit the [Windows Blog](https://blogs.windows.com/windowsexperience/2016/06/14/announcing-windows-10-insider-preview-build-14366-mobile-build-14364/).</span></span> <br/>

### <a name="fixed"></a><span data-ttu-id="6f9d2-1285">고정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1285">Fixed</span></span>
- <span data-ttu-id="6f9d2-1286">Symlink 통해 파일 생성에서 수정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1286">Fix in file creation through symlinks</span></span>
-   <span data-ttu-id="6f9d2-1287">Python (GH 385)에 대 한 추가 listxattr</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1287">Added listxattr for Python (GH 385)</span></span>
-   <span data-ttu-id="6f9d2-1288">추가 버그 수정 및 향상 된 기능</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1288">Additional bugfixes and improvements</span></span>

### <a name="syscall-support"></a><span data-ttu-id="6f9d2-1289">Syscall 지원</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1289">Syscall Support</span></span>
-   <span data-ttu-id="6f9d2-1290">다음은 새롭거나 향상 된 syscall WSL 구현에 있는 목록입니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1290">Below are a list of new or enhanced syscalls that have some implementation in WSL.</span></span> <span data-ttu-id="6f9d2-1291">이 목록에 syscall 하나 이상의 시나리오에서 지원 되지만 수 있는 모든 매개 변수에서 지원 되지 않습니다이 시간.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1291">The syscalls on this list are supported in at least one scenario, but may not have all parameters supported at this time.</span></span>

`listxattr`<br/>
<br/>

## <a name="build-14361"></a><span data-ttu-id="6f9d2-1292">빌드 14361</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1292">Build 14361</span></span>
<span data-ttu-id="6f9d2-1293">일반 Windows에 대 한 빌드 14361에서 정보를 방문 합니다 [Windows 블로그](https://aka.ms/wip14361)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1293">For general Windows information on build 14361 visit the [Windows Blog](https://aka.ms/wip14361).</span></span> <br/>

### <a name="fixed"></a><span data-ttu-id="6f9d2-1294">고정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1294">Fixed</span></span>
- <span data-ttu-id="6f9d2-1295">Windows에서 Ubuntu의 Bash에서 실행 중인 경우 DrvFs 대/소문자 구분 됩니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1295">DrvFs is now case sensitive when running in Bash on Ubuntu on Windows.</span></span>
  - <span data-ttu-id="6f9d2-1296">사용자가 월 case.txt 및 사례입니다. TXT 해당/mnt c 드라이브</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1296">Users may case.txt and CASE.TXT on their /mnt/c drives</span></span>
  - <span data-ttu-id="6f9d2-1297">Windows에서 ubuntu의 Bash에서 대/소문자만 지원 됩니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1297">Case sensitivity is only supported within Bash on Ubuntu on Windows.</span></span> <span data-ttu-id="6f9d2-1298">경우 NTFS Bash의 외부 파일을 올바르게 보고 됩니다 있지만 Windows에서 파일을 사용 하 여 상호 작용 예기치 않은 동작이 발생할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1298">When outside of Bash NTFS will report the files correctly, but unexpected behavior may occur interacting with the files from Windows.</span></span>
  - <span data-ttu-id="6f9d2-1299">각 볼륨 (즉, /mnt/c)의 루트가 대/소문자 구분 되지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1299">The root of each volume (i.e. /mnt/c) is not case sensitive</span></span>
  - <span data-ttu-id="6f9d2-1300">Windows에서 이러한 파일을 처리 하는 방법은 찾을 수 있습니다 [여기](https://support.microsoft.com/en-us/kb/100625)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1300">More information on handling these files in Windows can be found [here](https://support.microsoft.com/en-us/kb/100625).</span></span>
- <span data-ttu-id="6f9d2-1301">크게 향상 pty / tty 지원 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1301">Greatly enhanced pty / tty support.</span></span>  <span data-ttu-id="6f9d2-1302">이제 지원 됩니다 (GH #40) TMUX와 같은 응용 프로그램</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1302">Applications like TMUX now supported (GH #40)</span></span>
- <span data-ttu-id="6f9d2-1303">사용자 계정이 항상 생성 하는 고정 된 설치 문제</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1303">Fixed install issue where user accounts not always created</span></span>
- <span data-ttu-id="6f9d2-1304">매우 긴 인수 목록에 대 한 허용 하는 명령줄 인수 구조를 최적화 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1304">Optimized command line arg structure allowing for extremely long argument list.</span></span> <span data-ttu-id="6f9d2-1305">(GH #153)</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1305">(GH #153)</span></span>
- <span data-ttu-id="6f9d2-1306">DrvFs에서 삭제 및 chmod read_only 파일 이제 수</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1306">Now able to delete and chmod read_only files from DrvFs</span></span>
- <span data-ttu-id="6f9d2-1307">일부 경우에서 터미널 중지 (GH #43)를 분리 하는 위치를 수정 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1307">Fixed some instances where the terminal hangs on disconnect (GH #43)</span></span>
- <span data-ttu-id="6f9d2-1308">chmod 및 chown 이제 tty 장치에서 작동</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1308">chmod and chown now work on tty devices</span></span>
- <span data-ttu-id="6f9d2-1309">0.0.0.0으로 연결을 허용 하 고:: localhost (#388 GH)</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1309">Allow connection to 0.0.0.0 and :: as localhost (GH #388)</span></span>
- <span data-ttu-id="6f9d2-1310">Sendmsg/recvmsg의는 IO 벡터 길이 이제 처리할 > 1 (부분 GH #376)</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1310">Sendmsg/recvmsg now handle an IO vector length of >1 (partial GH #376)</span></span>
- <span data-ttu-id="6f9d2-1311">사용자가 이제 옵트아웃할 수 자동으로 생성 된 호스트 파일 (GH #398)의</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1311">Users can now opt-out of auto-generated hosts file (GH #398)</span></span>
- <span data-ttu-id="6f9d2-1312">자동으로 NT 로캘로 Linux 로캘 (GH #11) 설치 하는 동안 일치</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1312">Automatically match Linux locale to the NT locale during install (GH #11)</span></span>
- <span data-ttu-id="6f9d2-1313">/Proc/sys/vm/swappiness 파일 (GH #306) 추가</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1313">Added the /proc/sys/vm/swappiness file (GH #306)</span></span>
- <span data-ttu-id="6f9d2-1314">strace 이제 올바르게 종료</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1314">strace now exits correctly</span></span>
- <span data-ttu-id="6f9d2-1315">파이프 /proc/self/fd (GH #222)를 통해 다시 열 수를 허용 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1315">Allow pipes to be reopened through /proc/self/fd (GH #222)</span></span>
- <span data-ttu-id="6f9d2-1316">디렉터리가 %LOCALAPPDATA%\lxss DrvFs (GH #270)에서 숨기기</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1316">Hide directories under %LOCALAPPDATA%\lxss from DrvFs (GH #270)</span></span>
- <span data-ttu-id="6f9d2-1317">Bash.exe 보다 효율적으로 처리 ~입니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1317">Better handling of bash.exe ~.</span></span>  <span data-ttu-id="6f9d2-1318">와 같은 명령도 "bash ~-c ls" (GH #467) 지원</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1318">Commands like “bash ~ -c ls” now supported (GH #467)</span></span>
- <span data-ttu-id="6f9d2-1319">소켓에는 이제 epoll 알림 (GH #271) 종료 하는 동안 사용할 수 있는 읽기</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1319">Sockets now notify epoll read available during shutdown (GH #271)</span></span>
- <span data-ttu-id="6f9d2-1320">lxrun / 제거는 더 효율적으로 파일 및 폴더를 삭제 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1320">lxrun /uninstall does a better job of deleting the files and folders</span></span>
- <span data-ttu-id="6f9d2-1321">수정 된 ps-f (GH #246)</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1321">Corrected ps -f (GH #246)</span></span>
- <span data-ttu-id="6f9d2-1322">X11 지원 개선 xEmacs (GH #481)와 같은 앱</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1322">Improved support for x11 apps such as xEmacs (GH #481)</span></span>
- <span data-ttu-id="6f9d2-1323">초기 스레드 스택 크기 기본값 Ubuntu 및 크기를 올바르게 보고 get_rlimit syscall (GH # 172를 #258)를 일치 시키는 업데이트</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1323">Updated initial thread stack size to match default Ubuntu setting and reporting the size correctly to the get_rlimit syscall (GH #172, #258)</span></span>
- <span data-ttu-id="6f9d2-1324">Pico 프로세스 이미지 이름 (예: 감사) 보고 개선</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1324">Improved reporting of pico process image names (e.g., for auditing)</span></span>
- <span data-ttu-id="6f9d2-1325">Df 명령에 대 한 구현된 /proc/mountinfo</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1325">Implemented /proc/mountinfo for df command</span></span>
- <span data-ttu-id="6f9d2-1326">자식 이름에 대 한 고정된 symlink 오류 코드입니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1326">Fixed symlink error code for child name .</span></span> <span data-ttu-id="6f9d2-1327">및...</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1327">and ..</span></span>
- <span data-ttu-id="6f9d2-1328">추가 개선 사항 버그 수정 및 향상 된 기능</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1328">Additional improvements bugfixes and improvements</span></span>

### <a name="syscall-support"></a><span data-ttu-id="6f9d2-1329">Syscall 지원</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1329">Syscall Support</span></span>
<span data-ttu-id="6f9d2-1330">다음은 새롭거나 향상 된 syscall WSL 구현에 있는 목록입니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1330">Below are a list of new or enhanced syscalls that have some implementation in WSL.</span></span> <span data-ttu-id="6f9d2-1331">이 목록에 syscall 하나 이상의 시나리오에서 지원 되지만 수 있는 모든 매개 변수에서 지원 되지 않습니다이 시간.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1331">The syscalls on this list are supported in at least one scenario, but may not have all parameters supported at this time.</span></span>

`GETTIMER`<br/>
`MKNODAT`<br/>
`RENAMEAT`<br/>
`SENDFILE`<br/>
`SENDFILE64`<br/>
`SYNC_FILE_RANGE`<br/>
<br/>

## <a name="build-14352"></a><span data-ttu-id="6f9d2-1332">빌드 14352</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1332">Build 14352</span></span>
<span data-ttu-id="6f9d2-1333">일반 Windows에 대 한 빌드 14352에 대 한 정보를 방문 합니다 [Windows 블로그](https://aka.ms/wip14352)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1333">For general Windows information on build 14352 visit the [Windows Blog](https://aka.ms/wip14352).</span></span><br/>


### <a name="fixed"></a><span data-ttu-id="6f9d2-1334">고정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1334">Fixed</span></span>
- <span data-ttu-id="6f9d2-1335">큰 파일 된 되지 않음 다운로드 / 올바르게 생성 문제를 해결 했습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1335">Fixed issue where large files were not downloaded / created correctly.</span></span>  <span data-ttu-id="6f9d2-1336">Npm 및 다른 시나리오 (GH 3, GH #313) 차단을 해제 해야이</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1336">This should unblock npm and other scenarios (GH #3, GH #313)</span></span>
- <span data-ttu-id="6f9d2-1337">소켓의 중지 일부 인스턴스를 제거 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1337">Removed some instances where sockets hang</span></span>
- <span data-ttu-id="6f9d2-1338">일부 ptrace 오류 수정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1338">Corrected some ptrace errors</span></span>
- <span data-ttu-id="6f9d2-1339">파일 이름이 255 자 보다 긴 허용 WSL 사용 하 여 문제 해결된</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1339">Fixed issue with WSL allowing filenames longer than 255 characters</span></span>
- <span data-ttu-id="6f9d2-1340">영어가 아닌 문자에 대 한 향상 된 지원</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1340">Improved support for non-English characters</span></span>
- <span data-ttu-id="6f9d2-1341">현재 Windows 표준 시간대 데이터를 추가 하 고 기본값으로 설정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1341">Add current Windows timezone data and set as default</span></span>
- <span data-ttu-id="6f9d2-1342">고유한 장치 id의 각각에 대 한 탑재 지점 (jre 수정-GH #49)</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1342">Unique device id’s for each mount point (jre fix – GH #49)</span></span>
- <span data-ttu-id="6f9d2-1343">포함 하는 경로 사용 하 여 문제를 해결 합니다. "."</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1343">Correct issue with paths containing “.”</span></span> <span data-ttu-id="6f9d2-1344">및 "..."</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1344">and “..”</span></span>
- <span data-ttu-id="6f9d2-1345">Fifo 지원이 추가 되었습니다 (#71 GH)</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1345">Added Fifo support (GH #71)</span></span>
- <span data-ttu-id="6f9d2-1346">업데이트 된 형식의 기본 Ubuntu 형식과 일치 하도록 하기 위해 resolv.conf</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1346">Updated format of resolv.conf to match native Ubuntu format</span></span>
- <span data-ttu-id="6f9d2-1347">일부 procfs 정리</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1347">Some procfs cleanup</span></span>
- <span data-ttu-id="6f9d2-1348">관리자 콘솔 (GH #18)에 대해 설정 된 ping</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1348">Enabled ping for Administrator consoles (GH #18)</span></span>

### <a name="syscall-support"></a><span data-ttu-id="6f9d2-1349">Syscall 지원</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1349">Syscall Support</span></span>
<span data-ttu-id="6f9d2-1350">다음은 새롭거나 향상 된 syscall WSL 구현에 있는 목록입니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1350">Below are a list of new or enhanced syscalls that have some implementation in WSL.</span></span> <span data-ttu-id="6f9d2-1351">이 목록에 syscall 하나 이상의 시나리오에서 지원 되지만 수 있는 모든 매개 변수에서 지원 되지 않습니다이 시간.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1351">The syscalls on this list are supported in at least one scenario, but may not have all parameters supported at this time.</span></span>

`FALLOCATE`<br/>
`EXECVE`<br/>
`LGETXATTR`<br/>
`FGETXATTR`<br/>
<br/>

## <a name="build-14342"></a><span data-ttu-id="6f9d2-1352">14342 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1352">Build 14342</span></span>
<span data-ttu-id="6f9d2-1353">일반 Windows에 대 한 정보 빌드 14342 합니다 [Windows 블로그](https://aka.ms/wip14342)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1353">For general Windows information on build 14342 the [Windows Blog](https://aka.ms/wip14342).</span></span> <br/>

<span data-ttu-id="6f9d2-1354">VolFs 및 DriveFs에 대 한 정보를 확인할 수 있습니다 합니다 [WSL 블로그](https://blogs.msdn.microsoft.com/wsl)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1354">Information on VolFs and DriveFs can be found on the [WSL Blog](https://blogs.msdn.microsoft.com/wsl).</span></span> <br/>

### <a name="fixed"></a><span data-ttu-id="6f9d2-1355">고정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1355">Fixed</span></span>
- <span data-ttu-id="6f9d2-1356">Windows 사용자 사용자 이름에 유니코드 문자가 있을 때에 설치 문제를 해결 함</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1356">Fixed install issue when the Windows user had Unicode characters in the username</span></span>
- <span data-ttu-id="6f9d2-1357">FAQ apt get 업데이트 udev 해결 방법은 첫 번째 실행에서 기본적으로 제공 됩니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1357">The apt-get update udev workaround in the FAQ is now provided by default on first run</span></span>
- <span data-ttu-id="6f9d2-1358">DriveFs에 symlink를 사용 하도록 설정 (/mnt/<drive>) 디렉터리</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1358">Enabled symlinks in DriveFs (/mnt/<drive>) directories</span></span>
- <span data-ttu-id="6f9d2-1359">Symlink은 DriveFs 사이의 VolFs 이제 작동</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1359">Symlinks now work between DriveFs and VolFs</span></span>
- <span data-ttu-id="6f9d2-1360">주소가 지정 된 상위 수준 경로 문제를 구문 분석: l s. / / 이제 정상적으로 작동 됩니다</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1360">Addressed top level path parsing issue: ls .// will now work as expected</span></span>
- <span data-ttu-id="6f9d2-1361">DriveFs에 npm 설치 하 고-g 옵션은 이제 작동</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1361">npm install on DriveFs and the -g options are now working</span></span>
- <span data-ttu-id="6f9d2-1362">PHP 서버를 시작 하지 못하도록 방지 하는 문제 해결된</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1362">Fixed issue preventing PHP server from launching</span></span>
- <span data-ttu-id="6f9d2-1363">네이티브 Ubuntu에 더 가깝게 맞게 $PATH 같은 업데이트 된 기본 환경 값</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1363">Updated default environment values, such as $PATH to closer match native Ubuntu</span></span>
- <span data-ttu-id="6f9d2-1364">Apt 패키지 캐시를 업데이트 하는 Windows에서 매주 유지 관리 작업을 추가</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1364">Added a weekly maintenance task in Windows to update the apt package cache</span></span>
- <span data-ttu-id="6f9d2-1365">ELF 헤더 유효성 검사를 사용 하 여 문제를 해결, WSL 이제 모든 Melkor 옵션</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1365">Fixed issue with ELF header validation, WSL now supports all Melkor options</span></span>
- <span data-ttu-id="6f9d2-1366">Zsh shell은 기능</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1366">Zsh shell is functional</span></span>
- <span data-ttu-id="6f9d2-1367">이동의 미리 컴파일된 이진 파일은 이제 지원</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1367">Precompiled Go binaries are now supported</span></span>
- <span data-ttu-id="6f9d2-1368">올바르게 이제 지역화 된 Bash.exe 첫 번째 실행에서 메시지를 표시</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1368">Prompting on Bash.exe first run is now localized correctly</span></span>
- <span data-ttu-id="6f9d2-1369">/proc/meminfo 이제 올바른 정보를 반환</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1369">/proc/meminfo now returns correct information</span></span>
- <span data-ttu-id="6f9d2-1370">이제 VFS에서 지원 되는 소켓</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1370">Sockets now supported in VFS</span></span>
- <span data-ttu-id="6f9d2-1371">사용 하기 위해 /dev 이제 tempfs로 탑재</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1371">/dev now mounted as tempfs</span></span>
- <span data-ttu-id="6f9d2-1372">Fifo 이제 지원</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1372">Fifo now supported</span></span>
- <span data-ttu-id="6f9d2-1373">이제/proc/cpuinfo에 올바르게 표시 하는 다중 코어 시스템</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1373">Multi-core systems now showing correctly in /proc/cpuinfo</span></span>
- <span data-ttu-id="6f9d2-1374">추가 개선 사항 및 첫 번째 실행 동안 다운로드 하는 오류 메시지</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1374">Additional improvements and error messages downloading during first run</span></span>
- <span data-ttu-id="6f9d2-1375">Syscall 개선 사항 및 버그 수정입니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1375">Syscall improvements and bugfixes.</span></span> <span data-ttu-id="6f9d2-1376">아래 지원 되는 syscall 목록입니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1376">Supported syscall list below.</span></span>
- <span data-ttu-id="6f9d2-1377">추가 버그 수정 및 향상 된 기능</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1377">Additional bugfixes and improvements</span></span>

### <a name="known-issues"></a><span data-ttu-id="6f9d2-1378">알려진 문제</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1378">Known Issues</span></span>
- <span data-ttu-id="6f9d2-1379">확인 하지 못하는 '..'</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1379">Not resolving ‘..’</span></span> <span data-ttu-id="6f9d2-1380">일부 경우에는 DriveFs에서 올바르게</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1380">correctly on DriveFs in some cases</span></span>

### <a name="syscall-support"></a><span data-ttu-id="6f9d2-1381">Syscall 지원</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1381">Syscall Support</span></span>
<span data-ttu-id="6f9d2-1382">다음은 새롭거나 향상 된 syscall WSL 구현에 있는 목록입니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1382">Below are a list of new or enhanced syscalls that have some implementation in WSL.</span></span> <span data-ttu-id="6f9d2-1383">이 목록에 syscall 하나 이상의 시나리오에서 지원 되지만 수 있는 모든 매개 변수에서 지원 되지 않습니다이 시간.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1383">The syscalls on this list are supported in at least one scenario, but may not have all parameters supported at this time.</span></span>

`FCHOWNAT`<br/>
`GETEUID`<br/>
`GETGID`<br/>
`GETRESUID`<br/>
`GETXATTR`<br/>
`PTRACE`<br/>
`SETGID`<br/>
`SETGROUPS`<br/>
`SETHOSTNAME`<br/>
`SETXATTR`<br/>
<br/>

## <a name="build-14332"></a><span data-ttu-id="6f9d2-1384">14332 빌드</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1384">Build 14332</span></span>

<span data-ttu-id="6f9d2-1385">일반 Windows에 대 한 14332 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://aka.ms/wip14332)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1385">For general Windows information on build 14332 visit the [Windows Blog](https://aka.ms/wip14332).</span></span> <br/>


### <a name="fixed"></a><span data-ttu-id="6f9d2-1386">고정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1386">Fixed</span></span>
- <span data-ttu-id="6f9d2-1387">DNS 항목을 우선 순위 지정을 비롯 한 효율적인 resolv.conf 생성</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1387">Better resolv.conf generation including prioritizing DNS entries</span></span>
- <span data-ttu-id="6f9d2-1388">/Mnt 사이 및 비 파일 및 디렉터리를 이동 하는 문제가-mnt 드라이브 /</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1388">Issue with moving files and directories between /mnt and non-/mnt drives</span></span>
- <span data-ttu-id="6f9d2-1389">Tar 파일 symlink를 사용 하 여 만들 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1389">Tar files can now be created with symlinks</span></span>
- <span data-ttu-id="6f9d2-1390">인스턴스 만들기에서 추가 기본 /run/lock 디렉터리</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1390">Added default /run/lock directory on instance creation</span></span>
- <span data-ttu-id="6f9d2-1391">적절 한 상태 정보를 반환할 /dev/null 업데이트</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1391">Update /dev/null to return proper stat info</span></span>
- <span data-ttu-id="6f9d2-1392">첫 번째 실행 동안 다운로드 하는 경우 추가 오류</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1392">Additional errors when downloading during first run</span></span>
- <span data-ttu-id="6f9d2-1393">Syscall 개선 사항 및 버그 수정입니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1393">Syscall improvements and bugfixes.</span></span> <span data-ttu-id="6f9d2-1394">아래 지원 되는 syscall 목록입니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1394">Supported syscall list below.</span></span>
- <span data-ttu-id="6f9d2-1395">추가 개선 사항 버그 수정 및 향상 된 기능</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1395">Additional improvements bugfixes and improvements</span></span>

### <a name="syscall-support"></a><span data-ttu-id="6f9d2-1396">Syscall 지원</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1396">Syscall Support</span></span>
<span data-ttu-id="6f9d2-1397">다음은 WSL에서 구현 된 새 syscall입니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1397">Below is the new syscall that has some implementation in WSL.</span></span> <span data-ttu-id="6f9d2-1398">Syscall이이 목록에는 하나 이상의 시나리오에서 지원 되지만 수 있는 모든 매개 변수가 지원 되지이 이번.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1398">The syscall on this list is supported in at least one scenario, but may not have all parameters supported at this time.</span></span>

`READLINKAT`<br/>
<br/>

## <a name="build-14328"></a><span data-ttu-id="6f9d2-1399">빌드 14328</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1399">Build 14328</span></span>

<span data-ttu-id="6f9d2-1400">일반 Windows에 대 한 14332 빌드에 대 한 정보를 방문 합니다 [Windows 블로그](https://aka.ms/wip14328)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1400">For general Windows information on build 14332 visit the [Windows Blog](https://aka.ms/wip14328).</span></span> <br/>


### <a name="new-features"></a><span data-ttu-id="6f9d2-1401">새로운 기능</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1401">New Features</span></span>
* <span data-ttu-id="6f9d2-1402">이제 Linux 사용자를 지원 합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1402">Now support Linux users.</span></span>  <span data-ttu-id="6f9d2-1403">Windows에서 ubuntu의 Bash를 설치한 Linux 사용자를 만드는 메시지가 나타납니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1403">Installing Bash on Ubuntu on Windows will prompt for creation of a Linux user.</span></span>  <span data-ttu-id="6f9d2-1404">자세한 내용은 참조 하세요. https://aka.ms/wslusers</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1404">For more information, visit https://aka.ms/wslusers</span></span>
* <span data-ttu-id="6f9d2-1405">Hostname는 Windows 컴퓨터 이름에 더 이상 설정 되었습니다. @localhost</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1405">Hostname is now set to the Windows computer name, no more @localhost</span></span>
* <span data-ttu-id="6f9d2-1406">빌드 14328 대 한 자세한 내용은 참조 하십시오. https://aka.ms/wip14328</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1406">For more information on build 14328, visit: https://aka.ms/wip14328</span></span>

### <a name="fixed"></a><span data-ttu-id="6f9d2-1407">고정</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1407">Fixed</span></span>
* <span data-ttu-id="6f9d2-1408">비 /mnt/ Symlink 향상<drive> 파일</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1408">Symlink improvements for non /mnt/<drive> files</span></span>
    * <span data-ttu-id="6f9d2-1409">npm 설치가 작동</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1409">npm install now works</span></span>
    * <span data-ttu-id="6f9d2-1410">jdk 지침을 사용 하 여 설치할 수 있는 이제 jre [여기](https://xubuntugeek.blogspot.com/2012/09/how-to-install-oracle-jdk-7-manually-in.html)합니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1410">jdk / jre now installable using instructions found [here](https://xubuntugeek.blogspot.com/2012/09/how-to-install-oracle-jdk-7-manually-in.html).</span></span>
    * <span data-ttu-id="6f9d2-1411">알려진 문제: Windows 탑재에 대 한 symlink 작동 하지 않습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1411">known issue: symlinks do not work for Windows mounts.</span></span>  <span data-ttu-id="6f9d2-1412">기능을 이후 빌드에서 사용할 수 있습니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1412">Functionality will be available in a later build</span></span>
* <span data-ttu-id="6f9d2-1413">위쪽과 htop 표시</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1413">top and htop now display</span></span>
* <span data-ttu-id="6f9d2-1414">추가 오류 메시지 일부에 대 한 설치 실패</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1414">Additional error messages for some install failures</span></span>
* <span data-ttu-id="6f9d2-1415">Syscall 개선 사항 및 버그 수정입니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1415">Syscall improvements and bugfixes.</span></span>  <span data-ttu-id="6f9d2-1416">아래 지원 되는 syscall 목록입니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1416">Supported syscall list below.</span></span>
* <span data-ttu-id="6f9d2-1417">추가 개선 사항 버그 수정 및 향상 된 기능</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1417">Additional improvements bugfixes and improvements</span></span>

### <a name="syscall-support"></a><span data-ttu-id="6f9d2-1418">Syscall 지원</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1418">Syscall Support</span></span>
<span data-ttu-id="6f9d2-1419">다음은 syscall WSL 구현에 있는 목록입니다.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1419">Below is a list of syscalls that have some implementation in WSL.</span></span>  <span data-ttu-id="6f9d2-1420">Syscall이이 목록에 하나 이상의 시나리오에서 지원 되지만 수 있는 모든 매개 변수에서 지원 되지 않습니다이 시간.</span><span class="sxs-lookup"><span data-stu-id="6f9d2-1420">Syscalls on this list are supported in at least one scenario, but may not have all parameters supported at this time.</span></span>

`ACCEPT`<br/>
`ACCEPT4`<br/>
`ACCESS`<br/>
`ALARM`<br/>
`ARCH_PRCTL`<br/>
`BIND`<br/>
`BRK`<br/>
`CAPGET`<br/>
`CAPSET`<br/>
`CHDIR`<br/>
`CHMOD`<br/>
`CHOWN`<br/>
`CLOCK_GETRES`<br/>
`CLOCK_GETTIME`<br/>
`CLOCK_NANOSLEEP`<br/>
`CLONE`<br/>
`CLOSE`<br/>
`CONNECT`<br/>
`CREAT`<br/>
`DUP`<br/>
`DUP2`<br/>
`DUP3`<br/>
`EPOLL_CREATE`<br/>
`EPOLL_CREATE1`<br/>
`EPOLL_CTL`<br/>
`EPOLL_WAIT`<br/>
`EVENTFD`<br/>
`EVENTFD2`<br/>
`EXECVE`<br/>
`EXIT`<br/>
`EXIT_GROUP`<br/>
`FACCESSAT`<br/>
`FADVISE64`<br/>
`FCHDIR`<br/>
`FCHMOD`<br/>
`FCHMODAT`<br/>
`FCHOWN`<br/>
`FCHOWNAT`<br/>
`FCNTL64`<br/>
`FDATASYNC`<br/>
`FLOCK`<br/>
`FORK`<br/>
`FSETXATTR`<br/>
`FSTAT64`<br/>
`FSTATAT64`<br/>
`FSTATFS64`<br/>
`FSYNC`<br/>
`FTRUNCATE`<br/>
`FTRUNCATE64`<br/>
`FUTEX`<br/>
`GETCPU`<br/>
`GETCWD`<br/>
`GETDENTS`<br/>
`GETDENTS64`<br/>
`GETEGID`<br/>
`GETEGID16`<br/>
`GETEUID`<br/>
`GETEUID16`<br/>
`GETGID`<br/>
`GETGID16`<br/>
`GETGROUPS`<br/>
`GETPEERNAME`<br/>
`GETPGID`<br/>
`GETPGRP`<br/>
`GETPID`<br/>
`GETPPID`<br/>
`GETPRIORITY`<br/>
`GETRESGID`<br/>
`GETRESGID16`<br/>
`GETRESUID`<br/>
`GETRESUID16`<br/>
`GETRLIMIT`<br/>
`GETRUSAGE`<br/>
`GETSID`<br/>
`GETSOCKNAME`<br/>
`GETSOCKOPT`<br/>
`GETTID`<br/>
`GETTIMEOFDAY`<br/>
`GETUID`<br/>
`GETUID16`<br/>
`GETXATTR`<br/>
`GET_ROBUST_LIST`<br/>
`GET_THREAD_AREA`<br/>
`INOTIFY_ADD_WATCH`<br/>
`INOTIFY_INIT`<br/>
`INOTIFY_RM_WATCH`<br/>
`IOCTL`<br/>
`IOPRIO_GET`<br/>
`IOPRIO_SET`<br/>
`KEYCTL`<br/>
`KILL`<br/>
`LCHOWN`<br/>
`LINK`<br/>
`LINKAT`<br/>
`LISTEN`<br/>
`LLSEEK`<br/>
`LSEEK`<br/>
`LSTAT64`<br/>
`MADVISE`<br/>
`MKDIR`<br/>
`MKDIRAT`<br/>
`MKNOD`<br/>
`MLOCK`<br/>
`MMAP`<br/>
`MMAP2`<br/>
`MOUNT`<br/>
`MPROTECT`<br/>
`MREMAP`<br/>
`MSYNC`<br/>
`MUNLOCK`<br/>
`MUNMAP`<br/>
`NANOSLEEP`<br/>
`NEWUNAME`<br/>
`OPEN`<br/>
`OPENAT`<br/>
`PAUSE`<br/>
`PERF_EVENT_OPEN`<br/>
`PERSONALITY`<br/>
`PIPE`<br/>
`PIPE2`<br/>
`POLL`<br/>
`PPOLL`<br/>
`PRCTL`<br/>
`PREAD64`<br/>
`PROCESS_VM_READV`<br/>
`PROCESS_VM_WRITEV`<br/>
`PSELECT6`<br/>
`PTRACE`<br/>
`PWRITE64`<br/>
`READ`<br/>
`READLINK`<br/>
`READV`<br/>
`REBOOT`<br/>
`RECV`<br/>
`RECVFROM`<br/>
`RECVMSG`<br/>
`RENAME`<br/>
`RMDIR`<br/>
`RT_SIGACTION`<br/>
`RT_SIGPENDING`<br/>
`RT_SIGPROCMASK`<br/>
`RT_SIGRETURN`<br/>
`RT_SIGSUSPEND`<br/>
`RT_SIGTIMEDWAIT`<br/>
`SCHED_GETAFFINITY`<br/>
`SCHED_GETPARAM`<br/>
`SCHED_GETSCHEDULER`<br/>
`SCHED_GET_PRIORITY_MAX`<br/>
`SCHED_GET_PRIORITY_MIN`<br/>
`SCHED_SETAFFINITY`<br/>
`SCHED_SETPARAM`<br/>
`SCHED_SETSCHEDULER`<br/>
`SCHED_YIELD`<br/>
`SELECT`<br/>
`SEND`<br/>
`SENDMMSG`<br/>
`SENDMSG`<br/>
`SENDTO`<br/>
`SETDOMAINNAME`<br/>
`SETGID`<br/>
`SETGROUPS`<br/>
`SETHOSTNAME`<br/>
`SETITIMER`<br/>
`SETPGID`<br/>
`SETPRIORITY`<br/>
`SETREGID`<br/>
`SETRESGID`<br/>
`SETRESUID`<br/>
`SETREUID`<br/>
`SETRLIMIT`<br/>
`SETSID`<br/>
`SETSOCKOPT`<br/>
`SETTIMEOFDAY`<br/>
`SETUID`<br/>
`SETXATTR`<br/>
`SET_ROBUST_LIST`<br/>
`SET_THREAD_AREA`<br/>
`SET_TID_ADDRESS`<br/>
`SHUTDOWN`<br/>
`SIGACTION`<br/>
`SIGALTSTACK`<br/>
`SIGPENDING`<br/>
`SIGPROCMASK`<br/>
`SIGRETURN`<br/>
`SIGSUSPEND`<br/>
`SOCKET`<br/>
`SOCKETCALL`<br/>
`SOCKETPAIR`<br/>
`SPLICE`<br/>
`STAT64`<br/>
`STATFS64`<br/>
`SYMLINK`<br/>
`SYMLINKAT`<br/>
`SYNC`<br/>
`SYSINFO`<br/>
`TEE`<br/>
`TGKILL`<br/>
`TIME`<br/>
`TIMERFD_CREATE`<br/>
`TIMERFD_GETTIME`<br/>
`TIMERFD_SETTIME`<br/>
`TIMES`<br/>
`TKILL`<br/>
`TRUNCATE`<br/>
`TRUNCATE64`<br/>
`UMASK`<br/>
`UMOUNT`<br/>
`UMOUNT2`<br/>
`UNLINK`<br/>
`UNLINKAT`<br/>
`UNSHARE`<br/>
`UTIME`<br/>
`UTIMENSAT`<br/>
`UTIMES`<br/>
`VFORK`<br/>
`WAIT4`<br/>
`WAITPID`<br/>
`WRITE`<br/>
`WRITEV`<br/>
