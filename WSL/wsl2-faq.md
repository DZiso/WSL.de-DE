---
title: WSL 2 – häufig gestellte Fragen
description: Häufig gestellte Fragen zum Windows-Subsystem für Linux 2
keywords: Installieren Sie BashOnWindows, Bash, Wsl, wsl2, Windows, Windows-Subsystem für Linux, Windowssubsystem, Ubuntu, Debian, Suse, Windows 10
author: mscraigloewen
ms.author: mscraigloewen
ms.date: 05/30/2019
ms.topic: article
ms.assetid: 7afaeacf-435a-4e58-bff0-a9f0d75b8a51
ms.custom: seodec18
ms.openlocfilehash: 84805278abaeb6334c662e1dfab1bced3e0ddb0b
ms.sourcegitcommit: bb88269eb37405192625fa81ff91162393fb491f
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 06/12/2019
ms.locfileid: "67038090"
---
# <a name="wsl-2-faq"></a><span data-ttu-id="b7823-104">WSL 2 FAQ</span><span class="sxs-lookup"><span data-stu-id="b7823-104">WSL 2 FAQ</span></span>

<span data-ttu-id="b7823-105">Im folgenden finden eine Liste mit häufig gestellten Fragen (FAQ) zum Windows-Subsystem für Linux 2 ein.</span><span class="sxs-lookup"><span data-stu-id="b7823-105">Below is a list of frequently asked questions (FAQ) about the Windows Subsystem for Linux 2.</span></span>

## <a name="does-wsl-2-use-hyper-v-will-it-be-available-on-windows-10-home"></a><span data-ttu-id="b7823-106">Werden WSL 2 wird Hyper-V verwendet?</span><span class="sxs-lookup"><span data-stu-id="b7823-106">Does WSL 2 use Hyper-V?</span></span> <span data-ttu-id="b7823-107">Ist es auf Windows 10 Home erhältlich?</span><span class="sxs-lookup"><span data-stu-id="b7823-107">Will it be available on Windows 10 Home?</span></span>

<span data-ttu-id="b7823-108">WSL 2 werden auf alle SKUs verfügbar, in denen WSL derzeit verfügbar ist, einschließlich Windows 10 Home.</span><span class="sxs-lookup"><span data-stu-id="b7823-108">WSL 2 will be available on all SKUs where WSL is currently available, including Windows 10 Home.</span></span>

<span data-ttu-id="b7823-109">Die neueste Version von WSL verwendet Hyper-V-Architektur, um Virtualisierung zu aktivieren.</span><span class="sxs-lookup"><span data-stu-id="b7823-109">The newest version of WSL uses Hyper-V architecture to enable its virtualization.</span></span> <span data-ttu-id="b7823-110">Diese Architektur wird in eine optionale Komponente verfügbar sein, die eine Teilmenge der Hyper-V-Funktion.</span><span class="sxs-lookup"><span data-stu-id="b7823-110">This architecture will be available in an optional component that is a subset of the Hyper-V feature.</span></span> <span data-ttu-id="b7823-111">Diese optionale Komponente wird auf alle SKUs verfügbar sein.</span><span class="sxs-lookup"><span data-stu-id="b7823-111">This optional component will be available on all SKUs.</span></span> <span data-ttu-id="b7823-112">Sie erwarten können hier erfahren mehr über diese Benutzeroberfläche schnell, wie wir näher auf die WSL-2-Version erhalten.</span><span class="sxs-lookup"><span data-stu-id="b7823-112">You can expect to see more details about this experience soon as we get closer to the WSL 2 release.</span></span>

## <a name="what-will-happen-to-wsl-1-will-it-be-abandoned"></a><span data-ttu-id="b7823-113">Was geschieht mit WSL 1?</span><span class="sxs-lookup"><span data-stu-id="b7823-113">What will happen to WSL 1?</span></span> <span data-ttu-id="b7823-114">Wird sie werden verworfen?</span><span class="sxs-lookup"><span data-stu-id="b7823-114">Will it be abandoned?</span></span>

<span data-ttu-id="b7823-115">Wir stellen Ihnen derzeit keine Pläne WSL 1 als veraltet markiert.</span><span class="sxs-lookup"><span data-stu-id="b7823-115">We currently have no plans to deprecate WSL 1.</span></span> <span data-ttu-id="b7823-116">Sie können WSL-1 und 2 von WSL Distributionen nebeneinander ausgeführt und können Upgrades bzw. Downgrades-Distribution, die alle zu einem beliebigen Zeitpunkt.</span><span class="sxs-lookup"><span data-stu-id="b7823-116">You can run WSL 1 and WSL 2 distros side by side, and can upgrade and downgrade any distro at any time.</span></span> <span data-ttu-id="b7823-117">Hinzufügen von WSL 2 als eine neue Architektur bietet eine bessere Plattform für das Team WSL um bereitzustellen, die WSL eine fantastische Möglichkeit zum Ausführen von einer Linux-Umgebung in Windows machen.</span><span class="sxs-lookup"><span data-stu-id="b7823-117">Adding WSL 2 as a new architecture presents a better platform for the WSL team to deliver features that make WSL an amazing way to run a Linux environment in Windows.</span></span>

## <a name="will-i-be-able-to-run-wsl-2-and-other-3rd-party-virtualization-tools-such-as-vmware-or-virtualbox"></a><span data-ttu-id="b7823-118">Werden WSL-2 und andere 3rd Party Virtualisierungstools z. B. VMware, VirtualBox oder ausgeführt?</span><span class="sxs-lookup"><span data-stu-id="b7823-118">Will I be able to run WSL 2 and other 3rd party virtualization tools such as VMware, or VirtualBox?</span></span>

<span data-ttu-id="b7823-119">Einige 3rd Party-Anwendungen funktioniert nicht, wenn Hyper-V verwendet, wird dies bedeutet, dass sie nicht werden ausgeführt, wenn die WSL 2 aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="b7823-119">Some 3rd party applications cannot work when Hyper-V is in use, which means they will not be able to run when WSL 2 is enabled.</span></span> <span data-ttu-id="b7823-120">Dies schließt leider ein VMware und Versionen von VirtualBox vor VirtualBox-6 (VirtualBox 6.0.0 veröffentlicht im Dezember 2018 [unterstützt nun Hyper-V als einen Kern fallback Ausführung auf einem Windows-Host] [ 1]!)</span><span class="sxs-lookup"><span data-stu-id="b7823-120">Unfortunately, this does include VMware, and versions of VirtualBox before VirtualBox 6 (VirtualBox 6.0.0 released in December 2018 [now supports Hyper-V as a fallback execution core on a Windows host][1]!)</span></span>

<span data-ttu-id="b7823-121">Wir untersuchen Methoden, um dieses Problem zu beheben.</span><span class="sxs-lookup"><span data-stu-id="b7823-121">We are investigating ways to help resolve this issue.</span></span> <span data-ttu-id="b7823-122">Z. B. machen wir eine Reihe von APIs, die aufgerufen [Hypervisorplattform] [ 2] , Anbieter von Drittanbietern verwenden können, um ihre Software mit Hyper-V kompatibel zu machen</span><span class="sxs-lookup"><span data-stu-id="b7823-122">For example, we expose a set of APIs called [Hypervisor Platform][2] that third-party virtualization providers can use to make their software compatible with Hyper-V’s.</span></span> <span data-ttu-id="b7823-123">Dies ermöglicht es Anwendungen, die die Hyper-V-Architektur für die Netzwerkemulation verwenden, z. B. [der Google Android Emulator][3], und VirtualBox, 6 und höher die jetzt mit Hyper-V kompatibel sind.</span><span class="sxs-lookup"><span data-stu-id="b7823-123">This lets applications use the Hyper-V architecture for their emulation such as [the Google Android Emulator][3], and VirtualBox 6 and above which are both now compatible with Hyper-V.</span></span>

## <a name="can-i-access-the-gpu-in-wsl-2-are-there-plans-to-increase-hardware-support"></a><span data-ttu-id="b7823-124">Kann ich die GPU in WSL 2 zugreifen?</span><span class="sxs-lookup"><span data-stu-id="b7823-124">Can I access the GPU in WSL 2?</span></span> <span data-ttu-id="b7823-125">Gibt es Pläne, um die Hardware-Unterstützung zu erhöhen?</span><span class="sxs-lookup"><span data-stu-id="b7823-125">Are there plans to increase hardware support?</span></span>

<span data-ttu-id="b7823-126">In der ursprünglichen Version von WSL 2 Hardwarezugriff Unterstützung ist beschränkt, z.B.: Sie werden nicht den Zugriff der GPU, serielle oder USB sehr.</span><span class="sxs-lookup"><span data-stu-id="b7823-126">In initial releases of WSL 2 hardware access support will be limited, e.g: you will be unable to access the GPU, serial or USBs .</span></span> <span data-ttu-id="b7823-127">Hinzufügen von Unterstützung für bessere Geräte ist jedoch in unserem Backlog, hoch, wie viele weitere Anwendungsfälle für Entwickler wird geöffnet, die mit diesen Geräten interagieren möchten.</span><span class="sxs-lookup"><span data-stu-id="b7823-127">However, adding better device support is high on our backlog, as this opens many more use cases for developers that wish to interact with these devices.</span></span> <span data-ttu-id="b7823-128">In der Zwischenzeit können Sie immer WSL 1 verwenden, an der seriellen Anschluss und USB-Zugriff verfügt.</span><span class="sxs-lookup"><span data-stu-id="b7823-128">In the meantime, you can always use WSL 1 which has serial port and USB access.</span></span> <span data-ttu-id="b7823-129">Sie bleiben auf dem laufenden, die für diesen Blog und WSL-Teammitglieder auf Twitter, um über die neuesten Funktionen für Insider informiert zu bleiben erstellt und wenden Sie sich an uns Feedback für welche Geräte Sie interagieren möchten!</span><span class="sxs-lookup"><span data-stu-id="b7823-129">Please stay tuned to this blog and WSL team members on Twitter to stay informed about the latest features coming to insider builds and reach out to give us feedback on what devices you’d like to interact with!</span></span>

## <a name="will-wsl-2-be-able-to-use-networking-applications"></a><span data-ttu-id="b7823-130">Wird WSL 2 netzwerkanwendungen verwenden kann?</span><span class="sxs-lookup"><span data-stu-id="b7823-130">Will WSL 2 be able to use networking applications?</span></span>

<span data-ttu-id="b7823-131">Ja, im Allgemeinen netzwerkanwendungen wird schneller und besser funktionieren, da wir die vollständige systemüberprüfung Kompatibilität aufgerufen haben.</span><span class="sxs-lookup"><span data-stu-id="b7823-131">Yes, in general networking applications will be faster and work better since we have full system call compatibility.</span></span> <span data-ttu-id="b7823-132">Allerdings verwendet die neue Architektur virtualisierte Netzwerkkomponenten.</span><span class="sxs-lookup"><span data-stu-id="b7823-132">However, the new architecture uses virtualized networking components.</span></span> <span data-ttu-id="b7823-133">Verhält sich das heißt, die in der ersten Vorschau WSL 2 baut auf ähnliche Weise mehr an einen virtuellen Computer, z.B.: WSL 2 müssen eine andere IP-Adresse als der Hostcomputer.</span><span class="sxs-lookup"><span data-stu-id="b7823-133">This means that in initial preview builds WSL 2 will behave more similarly to a virtual machine, e.g: WSL 2 will have a different IP address than the host machine.</span></span> <span data-ttu-id="b7823-134">Wir haben sich verpflichtet, wodurch WSL 2 können Sie die WSL 1 identisch, und enthält unsere Netzwerke Geschichte zu verbessern.</span><span class="sxs-lookup"><span data-stu-id="b7823-134">We are committed to making WSL 2 feel the same as WSL 1, and that includes improving our networking story.</span></span> <span data-ttu-id="b7823-135">Wir erwarten, dass Verbesserungen so schnell wie möglich, z. B. Zugriff auf alle Netzwerke apps unter Linux oder Windows mithilfe von "localhost", werden hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="b7823-135">We expect to add improvements as quickly as we are able to, such as accessing all networking apps from Linux or Windows using localhost.</span></span> <span data-ttu-id="b7823-136">Wir veröffentlichen werden weitere Details zu unserem Netzwerk Story und Verbesserungen, wie wir die Veröffentlichung von WSL-2-Ansatz.</span><span class="sxs-lookup"><span data-stu-id="b7823-136">We will be posting more details about our networking story and improvements as we approach the release of WSL 2.</span></span>

## <a name="can-i-run-wsl-2-in-a-virtual-machine"></a><span data-ttu-id="b7823-137">Kann ich WSL 2 auf einem virtuellen Computer ausführen?</span><span class="sxs-lookup"><span data-stu-id="b7823-137">Can I run WSL 2 in a virtual machine?</span></span>

<span data-ttu-id="b7823-138">Ja!</span><span class="sxs-lookup"><span data-stu-id="b7823-138">Yes!</span></span> <span data-ttu-id="b7823-139">Sie müssen sicherstellen, dass die virtuelle Maschine Virtualisierung aktiviert geschachtelte werden.</span><span class="sxs-lookup"><span data-stu-id="b7823-139">You need to make sure that the virtual machine has nested virtualization enabled.</span></span> <span data-ttu-id="b7823-140">Dies kann in Hyper-V aktiviert werden, durch den folgenden Befehl in einem PowerShell-Fenster mit Administratorrechten ausführen:</span><span class="sxs-lookup"><span data-stu-id="b7823-140">This can be enabled in Hyper-V by running the following command in a PowerShell window with Administrator privileges:</span></span>

`Set-VMProcessor -VMName <VMName> -ExposeVirtualizationExtensions $true`

<span data-ttu-id="b7823-141">Achten Sie darauf, ersetzen Sie "&lt;VMName&gt;" mit dem Namen des virtuellen Computers.</span><span class="sxs-lookup"><span data-stu-id="b7823-141">Make sure to replace '&lt;VMName&gt;' with the name of your virtual machine.</span></span>

 [1]: https://www.virtualbox.org/wiki/Changelog-6.0
 [2]: https://docs.microsoft.com/en-us/virtualization/api/
 [3]: https://devblogs.microsoft.com/visualstudio/hyper-v-android-emulator-support/