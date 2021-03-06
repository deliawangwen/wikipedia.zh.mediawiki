{{NoteTA|G1=IT}}
{{Infobox software
| name                = 适用于 Linux 的 Windows 子系统
| logo                =
| logo_size           =
| logo_caption        =
| screenshot          = Screenshot of ‘Bash on Ubuntu on Windows’.png
| caption             = 正在[[Windows|Windows]]中运行的[[Ubuntu|Ubuntu]]子系统界面
| other_names         = Windows Subsystem for Linux
| type                = [[兼容层|兼容层]]
| service_name        =
| service_description =
| included_with       = [[Windows_10#Redstone_系列|Windows 10 1607]]及更新版本
| also_available_for  =
| replaces            = {{tsl|en|Windows Services for UNIX|Windows Services for UNIX}}
| replaced_by         =
| support_status      =
| developer =微软
}}
'''适用于 Linux 的 Windows 子系统'''（{{lang-en|Windows Subsystem for Linux}}，简称'''WSL'''）是一个为在[[Windows_10|Windows 10]]和[[Windows_Server_2019|Windows Server 2019]]上能够原生运行[[Linux|Linux二进制可执行文件]]（[[可執行與可鏈接格式|ELF]]格式）的[[兼容层|兼容层]]。

==概览==
WSL提供了一个由微软开发的[[Linux|Linux]]兼容的内核接口（不包含[[Linux内核|Linux内核]]代码），<ref>{{Cite web|url=https://mikegerwitz.com/2016/04/GNU-kWindows|title=GNU/kWindows|last=Gerwitz|first=Mike|date=|website=mikegerwitz.com|archive-url=|archive-date=|dead-url=|access-date=2018-04-08}}</ref>然后可以在其上运行[[GNU|GNU]][[用户空间|用户空间]]，例如[[Ubuntu|Ubuntu]]，<ref>{{cite web|last1=Harsh|first1=Mike|title=Run Bash on Ubuntu on Windows|url=https://blogs.windows.com/buildingapps/2016/03/30/run-bash-on-ubuntu-on-windows/|website=Building Apps for Windows|publisher=[[Microsoft|Microsoft]]|date=30 March 2016}}</ref><ref>{{cite web|last1=Finley|first1=Klint|title=Why Microsoft Making Linux Apps Run on Windows Isn't Crazy|url=https://www.wired.com/2016/03/microsoft-making-linux-apps-run-windows-isnt-crazy/|website=[[Wired_(website)|Wired]]|publisher=[[Condé_Nast|Condé Nast]]|date=30 March 2016}}</ref><ref>{{Cite web|url=http://insights.ubuntu.com/2016/03/30/ubuntu-on-windows-the-ubuntu-userspace-for-windows-developers/|title=Ubuntu on Windows – The Ubuntu Userspace for Windows Developers|last=Kirkland|first=Dustin|date=30 March 2016|website=Ubuntu Insights|publisher=[[Canonical_(company)|Canonical]]|access-date=}}</ref><ref>{{cite web|last1=Hammons|first1=Jack|title=Bash on Ubuntu on Windows|url=https://msdn.microsoft.com/en-us/commandline/wsl/about|website=[[MSDN|MSDN]]|publisher=[[Microsoft|Microsoft]]|date=9 April 2016}}</ref>[[openSUSE|openSUSE]]，<ref>[https://www.microsoft.com/store/apps/9njvjts82tjx Get openSUSE Leap 42 - Microsoft Store]</ref>[[SUSE_Linux_Enterprise_Server|SUSE Linux Enterprise Server]]，<ref>[https://www.microsoft.com/store/apps/9p32mwbh6cns Get SUSE Linux Enterprise Server 12 - Microsoft Store]</ref><ref>{{cite web|url=https://www.infoworld.com/article/3196284/linux/windows-subsystem-for-linux-welcomes-suse-and-fedora-options.html|website=[[InfoWorld|InfoWorld]]|date=2017-05-12|accessdate=2017-09-16|title=Windows Subsystem for Linux welcomes Suse and Fedora options|last=Yegulalp|first=Serdar}}</ref><ref name="fall"></ref>[[Debian|Debian]]<ref>{{Cite news|url=https://blogs.msdn.microsoft.com/commandline/2018/03/06/debian-gnulinux-for-wsl-now-available-in-the-windows-store/|title=Debian GNU/Linux for WSL now available in the Windows Store|work=Windows Command Line Tools For Developers|access-date=2018-03-07|language=en-US}}</ref>和[[Kali_Linux|Kali Linux]]。<ref>{{Cite news|url=https://www.kali.org/news/kali-linux-in-the-windows-app-store/|title=Kali Linux in the Windows App Store|access-date=2018-03-09|language=en-US}}</ref>这样的用户空间可能包含[[Bash|Bash]] shell和命令语言，使用本机GNU/Linux命令行工具（[[sed|sed]]，[[awk|awk]]等），编程语言解释器（Ruby，Python等），甚至是图形应用程序（使用主机端的[[X窗口系统|X窗口系统]]）。<ref name="ms-faq">{{cite web|title=Frequently Asked Questions for WSL|url=https://msdn.microsoft.com/en-us/commandline/wsl/faq|publisher=[[Microsoft|Microsoft]]|accessdate=2016-11-13}}</ref>

==简介和可用性==
在周年更新中引入时，只有Ubuntu镜像可用。秋季创意者更新将Linux发行版的安装过程移至[[Microsoft商店|Microsoft商店]]，并引入了[[Fedora|Fedora]]和[[SUSE|SUSE]]镜像。<ref name=fall>{{cite web |url=https://blogs.msdn.microsoft.com/commandline/2017/05/11/new-distros-coming-to-bashwsl-via-windows-store/ |title=Ubuntu now available from the Windows Store! |date=July 10, 2017 |website=Windows Command Line Tools For Developers Blog |accessdate=2017-08-11}}</ref>

WSL仅在版本1607之后的64位版本的Windows 10中可用。它也可在Windows Server 2019中使用。

==发展==
微软首次尝试在Windows上实现类似Unix的兼容性，首先是[[微软POSIX子系统|微软POSIX子系统]]，由Windows Services for UNIX通过MKS/Interix取代，后者最终因[[Windows_8.1|Windows 8.1]]的发布而被弃用。Windows Subsystem for Linux背后的技术起源于未发布的Astoria项目，它使一些[[Android|Android]]应用程序能够在[[Windows_10_移动版|Windows 10 移动版]]上运行。<ref name="Ars-March">{{cite web|url=https://arstechnica.com/information-technology/2016/04/why-microsoft-needed-to-make-windows-run-linux-software/|title=Why Microsoft needed to make Windows run Linux software|last1=Bright|first1=Peter|date=6 April 2016|website=[[Ars_Technica|Ars Technica]]|publisher=[[Condé_Nast|Condé Nast]]}}</ref>它首先在[[Windows预览体验计划|Windows 10 Insider Preview]] build 14316中提供。<ref>{{cite web|last1=Aul|first1=Gabe|title=Announcing Windows 10 Insider Preview Build 14316|url=https://blogs.windows.com/windowsexperience/2016/04/06/announcing-windows-10-insider-preview-build-14316/|website=Windows Experience Blog|publisher=[[Microsoft|Microsoft]]|date=6 April 2016}}</ref>

虽然微软以前的项目和第三方[[Cygwin|Cygwin]]专注于基于[[POSIX|POSIX]]标准创建自己独特的[[类Unix|类Unix]]环境，但WSL的目标是原生Linux兼容性。WSL不是将非原生功能包装到[[Win32|Win32]][[系统调用|系统调用]]中，而是利用[[Windows_NT体系结构|NT内核]]执行程序将Linux程序作为特殊的、隔离的最小[[进程|进程]]（称为''“pico-processes”''）作为专用系统连接到内核模式''“pico-providers”''。调用和[[异常处理|异常处理]]程序不同于vanilla NT进程。<ref>{{Cite news|url=https://blogs.msdn.microsoft.com/wsl/2016/04/22/windows-subsystem-for-linux-overview/|title=Windows Subsystem for Linux Overview|work=Windows Subsystem for Linux|access-date=2018-04-22|language=en-US}}</ref>

微软将WSL视为“主要面向开发人员的工具 — 尤其是Web开发人员以及在开源项目上工作或使用开源项目的人员”。<ref name="ms-faq" />WSL使用的资源少于完全虚拟化的机器，这是在Windows环境中运行Linux软件的最直接方式，同时还允许用户在同一组文件上使用Windows应用程序和Linux工具。<ref name="ms-faq" />

==体系结构==
'''LXSS Manager Service'''是负责与子系统交互的服务（通过''[[驱动程序|驱动程序]]''{{code|lxss.sys}}和{{code|lxcore.sys}}），以及Bash.exe（不要与Linux发行版提供的Shell混淆）的方式启动Linux进程，以及在执行期间处理Linux[[系统调用|系统调用]]和二进制锁。<ref>{{cite web|url=https://blogs.msdn.microsoft.com/wsl/2016/04/22/windows-subsystem-for-linux-overview|title=Windows Subsystem for Linux Overview|website=Windows Subsystem for Linux blog on [[MSDN|MSDN]]|author=Jack Hammons|date=April 22, 2016}}</ref>

特定用户调用的所有Linux进程都进入“Linux实例”（通常，第一个调用的进程是[[init|init]]）。关闭所有应用程序后，将关闭实例。

===硬件和文件系统访问===
由于没有硬件仿真/虚拟化（与coLinux等其他项目不同），WSL直接使用主机文件系统（通过{{code|VolFS}}和{{code|DrvFS}}）<ref>{{cite web|title=WSL File System Support|url=https://blogs.msdn.microsoft.com/wsl/2016/06/15/wsl-file-system-support|website=Windows Subsystem for Linux blog on [[MSDN|MSDN]]|author=Jack Hammons|date=June 15, 2016}}</ref>和硬件的某些部分，例如网络（Web服务器，用于例如，可以通过主机上配置的相同接口和IP地址进行访问，并且对使用需要管理权限的端口或已经被其他应用程序占用的端口共享相同的限制），这保证了互操作性。<ref>{{Cite web|url=https://blogs.msdn.microsoft.com/wsl/2016/11/08/225/|title=WSL Networking|website=Windows Subsystem for Linux blog on [[MSDN|MSDN]]|author=Jack Hammons|date=November 8, 2016}}</ref>

即使从shell运行[[sudo|sudo]]，某些位置（例如系统文件夹）和配置的访问/修改也受到限制。必须启动具有提升权限的实例才能获得“真正的sudo”并允许此类访问。<ref name="ms-faq"/>

===局限性===
此子系统无法运行所有Linux软件（如32位二进制文件）<ref name="32bit-elf3">{{Cite web|url=https://wpdev.uservoice.com/forums/266908-command-prompt-console-bash-on-ubuntu-on-windo/suggestions/13377507-please-add-32-bit-elf-support-to-the-kernel|title=Please enable WSL to run 32 bit ELF binaries|website=Windows Developer feedback (Microsoft/UserVoice)}}</ref><ref name="32bit-elf22">{{Cite web|url=https://github.com/Microsoft/WSL/issues/390|title=Support for 32-bit i386 ELF binaries|website=GitHub}}</ref>或需要在WSL中未实现的特定Linux内核服务的软件。由于WSL中没有“真正的”Linux内核，因此无法运行内核模块（如设备驱动程序）。

可以通过在Windows（主机）环境（例如VcXsrv或[[Xming|Xming]]）<ref name="pcworld-x112">{{Cite web|url=http://www.pcworld.com/article/3055403/windows/windows-10s-bash-shell-can-run-graphical-linux-applications-with-this-trick.html|title=Windows 10's Bash shell can run graphical Linux applications with this trick|access-date=September 10, 2018|website=[[PC_World|PC World]]}}</ref>中安装[[X窗口系统|X窗口系统]]来运行一些图形（GUI）应用程序（例如Mozilla [[Firefox|Firefox]]），尽管并非没有警告，例如缺乏音频支持或硬件加速（导致图形性能不佳）。目前还没有实施对[[OpenCL|OpenCL]]和[[CUDA|CUDA]]的支持，尽管计划在将来的版本中使用。<ref>{{Cite web|url=https://github.com/Microsoft/WSL/issues/1788|title=GPU not accesssible for running tensorflow and installing CUDA · Issue #1788 · Microsoft/WSL|access-date=September 10, 2018|website=GitHub}}</ref><ref>{{Cite web|title=OpenCL & CUDA GPU support|url=https://wpdev.uservoice.com/forums/266908-command-prompt-console-windows-subsystem-for-l/suggestions/16108045-opencl-cuda-gpu-support|date=September 15, 2016|access-date=September 10, 2018|website=Windows Developer feedback (Microsoft/UserVoice)}}</ref>

也就是说，微软明确指出'''WSL'''面向应用程序的开发者，而不是面向桌面环境或生产服务器，建议使用[[虚拟机|虚拟机]]（[[Hyper-V|Hyper-V]]或[[Kubernetes|Kubernetes]]）和[[Microsoft_Azure|Azure]]来实现这些目的。<ref name="ms-faq"/>

===性能===
在性能测试中，Windows Subsystem for Linux通常接近原生Linux，如Ubuntu，Debian，Intel Clear Linux或其他Linux发行版。I/O在某些测试中是WSL的瓶颈。<ref>{{cite web|url=https://www.phoronix.com/scan.php?page=search&q=Windows+Subsystem+for+Linux|title=Windows Subsystem for Linux|website=[[Phoronix|Phoronix]]}}</ref>
<ref>{{cite web|url=https://www.phoronix.com/scan.php?page=article&item=windows10-okt-wsl&num=1|title=A Look At The Windows 10 October 2018 Update Performance With WSL|author=Michael Larabel|date=October 12, 2018|website=Phoronix}}</ref>

==截图==
<gallery>
File:WSL gui Firefox.png|运行于WSL中的[[Firefox|Firefox]]
File:WSL gui Synaptic.png|运行于WSL中的[[Synaptic|Synaptic]]
</gallery>

== 参见 ==
{{div col||20em}}
* [[Azure_Sphere|Azure Sphere]]
* [[andLinux|andLinux]]
* [[Cooperative_Linux|Cooperative Linux]]
* [[Cygwin|Cygwin]]
* [[FreeBSD|FreeBSD的Linux兼容层]]
* [[万圣节文件|万圣节文件]]
* [[SmartOS|SmartOS]]
* [[Interix|Interix]]
* [[Wine|Wine]]
* [[Xenix|Xenix]]
{{div col end}}

== 参考资料 ==
{{Reflist|30em}}

== 外部链接 ==
* {{Official blog}}
* 微软文档上的[https://docs.microsoft.com/en-us/windows/wsl/about WSL]页面
* {{GitHub|Microsoft/WSL}}
* [https://blogs.msdn.microsoft.com/commandline/ ''Windows Command Line Tools For Developers'' blog]
* {{Cite web |url=https://blogs.windows.com/buildingapps/2016/07/22/fun-with-the-windows-subsystem-for-linux/ |title=Fun with the Windows Subsystem for Linux |first=Pete |last=Brown |website=Windows Developer Blog |publisher=Microsoft |date=22 July 2016}}

{{Microsoft Windows components}}
{{Unix-Windows interoperability}}

[[Category:兼容层|Category:兼容层]]
[[Category:Ubuntu|Category:Ubuntu]]
[[Category:Windows_10|Category:Windows 10]]
[[Category:Windows组件|Category:Windows组件]]