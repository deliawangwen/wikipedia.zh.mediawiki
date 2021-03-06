{{multiple issues|
{{copy edit|date=2014年8月}}
{{Incomplete|date=2014年8月}}
{{Expand English|iOS jailbreaking}}
}}
{{lowercase}}
{{noteTA
|G1=IT
<!--|T=zh-cn:越狱; zh-tw:越獄; zh-hk:越獄; zh-sg:越狱;-->
}}

[[File:A_jailbreaking_iPhone_with_Electra.png|thumb]]

'''iOS越狱'''（{{lang-en|'''iOS Jailbreaking'''}}）是获取[[IOS设备列表|iOS设备]]的[[超级用户|Root权限]]的技术手段。iOS系统的Root用户对除Apple特定私有进程之外的其他进程不开放，使用Root用户运行的进程在进程树中的PID为0。程序员在iOS中挖掘出一些可以将进程提权至PID0的漏洞（例如Task For PID0）。利用Root用户运行的进程意味着可以任意读取设备其中的APFS分区表和内核缓存地址，拥有一个用户可以随意控制的PID0进程还不能称之为一个完整的越狱。之后还需要利用Bypass（旁路）手段绕过Apple在iOS系统中设置的其他安全防护措施，将APFS或HFS+文件系统中的ROOTFS分区重新挂载（Remount）为可读写（R/W），从而达到添加二进制文件和守护进程的目的。通常大众用户认为能够正常使用Cydia才能被称为越狱，但其实这种说法是不正确的。但通过此软件可以完成越狱前不可能进行的动作，例如安装[[App_Store_(iOS)|App Store]]以外未经过签名的应用、修改SpringBoard、运行[[Shell|Shell]]程序、使有运营商锁的设备利用卡贴解锁后通过替换配置文件形式实现本地化（例如“去除+86”，解锁FaceTime功能）。<ref>[http://unloc.kr/ http://unloc.kr/]</ref>

越狱软件分发商店Cydia的创始人Jay Freeman在2010年10月估计，全球大概有10%的iPhone曾进行过越狱<ref>{{cite web|last=Freeman |first=Jay |url=http://www.saurik.com/id/12 |title=Caching Apple's Signature Server |publisher=saurik.com |accessdate=2010-12-18}}</ref>。
当iOS设备越狱后，用户可對系統進行編輯或是運行不被蘋果公司所驗證的軟體。

== 种类 ==
[[File:Cydia_on_ios11.png|thumb]]

目前对越狱的完美程度，业界开发人员给出了三种定义<ref>{{cite web|title=What is semi-tethered iPhone jailbreaking?|url=http://www.iphonefaq.org/archives/971612|publisher=Iphone FAQ|accessdate=2014-11-09}}</ref>：
*'''引导式越狱'''（Tethered Jailbreak），指的是，当处于此状态的iOS设备开机重启后，之前进行的越狱程序就会失效，用户将失去Root权限，需要將設備连接电脑来使用（如：红雪（redsn0w））等越狱软件进行引导开机以後，才可再次使用越狱程序。否则设备將无法正常開機。

*'''不完美越狱'''（Semi-tethered Jailbreak）設備在重啟後，將遺失越獄狀態，並恢復成未越獄狀態。而若想要再获得Root权限，则需再次進行越狱。

*'''完美越狱'''（Untethered Jailbreak），指设备在進行重啟後，越獄狀態仍被完整保留。

== 用途 == 
*'''使用第三方软件：'''越狱的主要原因之一是可以扩展苹果App Store的有限的应用程序。<ref>{{Cite web|url=https://mrmad.com.tw/jb|title=[iOS JB]越獄JB是什麼？|accessdate=2016-06-02|date=2014-05-10|work=瘋先生|language=zh-TW}}</ref>苹果会检查即将发布在App Store中的应用程序是否符合iOS开发者许可协议，然后再将其发布在App Store上。越狱后可以下载并安装苹果不允许出现在App Store上的应用程序<ref>{{cite news |url= http://www.wired.com/epicenter/2010/04/apple-bans-satire/ |title= Apple App Store Bans Pulitzer-Winning Satirist for Satire |author= Ryan Singel |date= April 15, 2010 |accessdate= February 12, 2011 |work=Wired}}</ref><ref>[http://www.foxnews.com/tech/2010/07/26/apple-iphone-jailbreak-unapproved-apps/ FoxNews]</ref>。Cydia上的应用程序并不需要完全按照App Store上的指导方针和要求，其中不少是适用于iOS或其他应用程序的扩展和定制。用户安装这些应用程序,更多被称作“插件”（Tweaks） 。这些插件可以达到个性化的目的，定制用户界面和字体，为iOS设备添加新功能等（苹果公司近几年的iOS系统更新所添加的新功能有很多都是从越狱插件中借鉴的）<ref name="lifehacker-dachis">{{cite web |url= http://lifehacker.com/5781437/how-to-get-the-most-out-of-your-jailbroken-ios-device |title= How to Get the Most Out of Your Jailbroken iOS Device |author= Adam Dachis |date= March 14, 2011 |work= |publisher= Lifehacker |accessdate=August 2, 2011}}</ref> 。并且可以访问文件系统和安装命令行工具，使得在iOS设备上的开发工作更加容易<ref>{{cite book |title= iPhone Open Application Development: Write Native Applications Using the Open Source Tool Chain |last= Zdziarski |first= Jonathan |authorlink= |coauthors= |year= 2008 |publisher= |location= |isbn= |page= |pages= 3–4 |url= http://books.google.com/books?id=fkXvibFJrpIC&lpg=PA3&dq=cydia%20-pomonella%20-moth&pg=PA3#v=onepage&q&f=false |accessdate=}}</ref><ref>{{cite book |title= Take control of your iPhone |last= Landau |first= Ted |authorlink= |coauthors= |year= 2009 |publisher= |location= |isbn= |page= 107 |pages= |url= http://books.google.com/books?id=GiOVkVS4XZkC&lpg=PA109&dq=cydia%20iphone&pg=PA107#v=onepage&q&f=false |accessdate=}}</ref> 。在允许安装第三方输入法的'''[[iOS_8|iOS 8]]'''发布之前，很多中国的iOS用户也因为安装第三方的中文输入法而越狱iOS设备，因为它们比原生输入法更容易使用<ref>{{cite web |url= http://blogs.hbr.org/cs/2012/05/apple_discovers_a_new_market_i.html |title= Apple Discovers a New Market in China: Rich Boyfriends |author= Nathan T. Washburn |date= May 4, 2012 |work= HBR Blog Network |publisher= Harvard Business Review |accessdate=January 9, 2013}}</ref>。在[[中国大陆|中国大陆]]，通过越狱获取的[[root|root]]权限被某些软件用于安装[[盗版|盗版]]软件，<ref>{{cite web|url=|title=|accessdate=|}}</ref>并造成了部分人存在越狱等于盗版的误解。<ref>{{cite web|url=http://netsec.ccert.edu.cn/cnsc/2011/03/20/%E8%B6%8A%E7%8B%B1%E5%92%8C%E7%9B%97%E7%89%88/|title=越狱和盗版|date=2011-03-20|accessdate=2012-08-08|deadurl=yes|archiveurl=https://web.archive.org/web/20131212214458/http://netsec.ccert.edu.cn/cnsc/2011/03/20/%E8%B6%8A%E7%8B%B1%E5%92%8C%E7%9B%97%E7%89%88/|archivedate=2013-12-12}}</ref><ref>{{cite web|url=http://www.mei521.com/?p=19916/|title=论越狱（通俗版）|date=2013-12-08|accessdate=2013-12-08|work=苹果学院|archive-url=https://web.archive.org/web/20131215062920/http://www.mei521.com/?p=19916%2F|archive-date=2013-12-15|dead-url=yes}}</ref>
*'''解除限制：'''越狱也可以非正式地解开运营商对iPhone的锁定，使得能够使用其它运营商提供的服务<ref>{{cite web |url= http://www.wired.com/gadgetlab/2009/08/reasons-to-jailbreak/ |title= 6 Reasons to Jailbreak Your iPhone |author= Brian X. Chen |date= August 7, 2009 |work= Gadget Lab |publisher= Wired |accessdate=May 1, 2012}}</ref>。基于软件的解锁，每一个不同的基带版本都对应了一个不同的解锁工具<ref>{{cite web |url= http://www.pcworld.com/article/155873/3g_iphone_unlock_expected.html |title= 3G iPhone Unlock Expected |author= Ian Paul |date= December 22, 2008 |work= Today @ PCWorld |publisher= PCWorld |accessdate=May 1, 2012}}</ref>。
*'''修复漏洞：'''2011年7月15日，越狱工具[[JailbreakMe|JailbreakMe]] 3.0利用了一个[[Safari|Safari]]浏览器在显示PDF文档时达到越狱的目的。这也就意味着iOS用户可能在不知不觉中丢失自己的个人信息或者被安装恶意软件<ref>{{cite news|url=http://www.news-record.com/content/2011/07/08/article/security_holes_discovered_in_iphones_ipads|title=Security holes discovered in iPhones, iPads|last=Robertson|first=Jordan|work=[[News_&_Record|News & Record]]|agency=[[Associated_Press|Associated Press]]|date=2011-07-08|accessdate=2011-07-09|deadurl=yes|archiveurl=https://web.archive.org/web/20110711154914/http://www.news-record.com/content/2011/07/08/article/security_holes_discovered_in_iphones_ipads|archivedate=2011-07-11}}</ref>。在苹果发布4.3.4更新修补该漏洞之前，越狱开发者comex就已经先行修补了这个漏洞。

== 动机 ==
將iOS裝置越狱的原因是为了突破[[苹果公司|苹果公司]]及其[[App_Store_(iOS)|App Store]]的限制，其中最主要的原因是为了能安装那些未遭苹果公司审核的应用程序。

苹果公司對应用程序审核程序的原因不仅局限于安全问题，有时也可能有意的禁止某些应用程序上架，（比如苹果公司[[禁止|禁止]]普利策获奖[[漫画家|漫画家]]所编写的应用程序上架，並聲稱其违反了开发许可协议。除外，协议上也明確規定禁止上架含有“嘲笑、醜化[[公众人物|公众人物]]”之類的应用程序。因此为了能夠成功运行被禁止上架的应用程序，用户不得不依靠越狱手段来脫離此類限制。

==历史==
仅仅在iPhone上市的几天后的2007年7月，开发人员就发布了第一个越狱工具<ref name="ricker2007">{{cite web|last=Ricker |first=Thomas |url=http://www.engadget.com/2007/07/10/iphone-hackers-we-have-owned-the-filesystem/ |title=iPhone Hackers: "we have owned the filesystem" |publisher=[[Engadget|Engadget]] |date=2007-07-10 |accessdate=2009-07-17}}</ref>，并且很快，一个仅支持越狱后iPhone的游戏应用就发布了<ref>{{cite web|last=Topolsky |first=Joshua |url=http://www.engadget.com/2007/08/06/first-third-party-game-app-appears-for-iphone/ |title=First third-party "game" app appears for iPhone |publisher=[[Engadget|Engadget]] |date=2007-08-06 |accessdate=2009-07-17}}</ref>。2007年10月，[[JailbreakMe|JailbreakMe]] 1.0（也被称为AppSnapp）就正式开始提供iPhone OS 1.1.1的iPhone和iPod touch越狱了<ref>{{cite web|last=Wilson |first=Ben |url=http://reviews.cnet.com/8301-19512_7-10115200-233.html |title=Official iPhone 1.1.1 jailbreak released with easy-to-follow instructions; does not require TIFF exploit |publisher=[[CNET.com|CNET.com]] |date=2007-10-10 |accessdate=2009-11-10}}</ref><ref>{{cite web |url=http://www.pcworld.com/article/139061/hacker_software_can_install_unauthorized_software_on_iphones.html |title=Hacker Software Can Install Unauthorized Software on iPhones |date=October 29, 2007 |author= Gregg Keizer |publisher=PCWorld |accessdate=August 25, 2011}}</ref> 。2008年2月，Zibri发布了ZiPhone，可以越狱iPhone OS 1.1.3和1.1.4的工具<ref>{{cite web|last=Block|first=Ryan|url=http://www.engadget.com/2008/02/12/ziphone-jailbreak-any-version-iphone-out-of-the-box-including/|title=ZiPhone: jailbreak any version iPhone out of the box, including 1.1.3 |date= 2008-02-12 |publisher=[[Engadget|Engadget]]|accessdate=2012-06-10}}</ref>。

iPhone Dev Team发布了一系列的越狱工具。2008年7月，PwnageTool提供针对iPhone OS 2.0的[[iPhone_3G|iPhone 3G]]和iPod touch的越狱<ref>{{cite news |url= http://www.wired.com/gadgetlab/2008/07/pwnage-20-relea/ |title= Pwnage 2.0 Released: Gadget Lab Jailbreaks iPod Touch |author= Charlie Sorrel |date= July 21, 2008 |work= Gadget Lab |publisher= Wired |accessdate=November 2, 2011 }}</ref>，更新包括作为越狱软件中主要的第三方安装程序[[Cydia|Cydia]]<ref>{{cite web |url= http://www.tuaw.com/2008/07/20/first-look-pwnage-for-2-0/ |title= First Look: Pwnage for 2.0 |author= Erica Sadun |date= July 20, 2008 |work= |publisher= TUAW |accessdate=November 1, 2011 }}</ref>；QuickPwn可以用来越狱iPhone OS 2.2版本的设备<ref>{{cite news |url= http://www.wired.com/gadgetlab/2008/11/quickpwn-adds-s/ |title= QuickPWN Adds Street View to iPod Touch |author= Charlie Sorrel |date= November 25, 2008 |work= Gadget Lab |publisher= Wired |accessdate=November 2, 2011 }}</ref>；在苹果推出iPhone OS 3.0时，Dev Team发布了一个更简单的针对于Windows和Mac的越狱工具[[redsn0w|redsn0w]]，并继续更新PwnageTool<ref>{{cite web |url= http://www.readwriteweb.com/archives/how_to_jailbreak_your_iphone_to_os_30.php |title= How to Jailbreak your iPhone to OS 3.0 |author= Sarah Perez |date= June 23, 2009 |work=  |publisher= ReadWriteWeb |accessdate= November 2, 2011 |deadurl= yes |archiveurl= https://web.archive.org/web/20111113014400/http://www.readwriteweb.com/archives/how_to_jailbreak_your_iphone_to_os_30.php |archivedate= 2011年11月13日 }}</ref>。更新版本的redsn0w也可以越狱iOS 4和iOS 5的版本。

==安全== 
2009年11月，21岁的澳大利亚学生编寫第一个iPhone蠕虫iKee。在其接受媒体採訪時表示，他之所以编写出iOS蠕虫病毒，是為提升人们对安全问题的重视。同時，也表示越狱后iOS裝置可使用[[SSH|SSH]]協議進行通訊<ref>{{cite news |title= Australian admits creating first iPhone virus |author= Brigid Andersen |url= http://www.abc.net.au/news/2009-11-09/australian-admits-creating-first-iphone-virus/1135474 |newspaper= [[ABC_Online|ABC Online]] |date= November 9, 2009 |accessdate=October 26, 2011}}</ref> <ref>{{Cite news|url=http://news.bbc.co.uk/2/hi/technology/8373739.stm |title=New iPhone worm can act like botnet say experts |publisher=BBC News |date=2009-11-23 |accessdate=2010-04-10}}</ref><ref>{{cite web|url=http://www.f-secure.com/weblog/archives/00001822.html |title=Malicious iPhone Worm |work= News from the Lab |publisher=F-secure |author= Mikko |date=2009-11-22 |accessdate=2010-04-10}}</ref>。

2011年7月15日，[[苹果公司|苹果公司]]封锁了一个被[[JailbreakMe|JailbreakMe]] 3.0利用的漏洞。德国联邦信息安全办公室称，已发现JailbreakMe 3.0可利用的[[PDF|PDF]]显示方面的漏洞，會使iOS用户的個人信息在不知不覺的情況下被盗取或是被控制下载恶意软體<ref>{{cite news|url=http://www.news-record.com/content/2011/07/08/article/security_holes_discovered_in_iphones_ipads|title=Security holes discovered in iPhones, iPads|last=Robertson|first=Jordan|work=[[News_&_Record|News & Record]]|agency=[[Associated_Press|Associated Press]]|date=2011-07-08|accessdate=2011-07-09|deadurl=yes|archiveurl=https://web.archive.org/web/20110711154914/http://www.news-record.com/content/2011/07/08/article/security_holes_discovered_in_iphones_ipads|archivedate=2011-07-11}}</ref>。

部分[[黑客|黑客]]可远程控制已越狱iOS裝置，以便其安装恶意软件或竊取用戶資料。

[[意大利|意大利]]网络安全公司Hacking Team向执法机构出售黑客软件并建议警方將其安裝至已越狱的iOS裝置中，以便在進行位置跟踪。

== 法律地位 ==
越狱iOS系统的法律地位受到不同国家的法律的影响，例如：保护数字版权管理（DRM）机制的法律。但许多国家并没有这样的法律。除此之外国际性的条约影响到越狱法律的发展，例如：1996 年世界知识产权组织（知识产权组织）版权条约要求条约的国家缔约国颁布有关规避DRM规则的法律。美国的实施是“ 数字千年版权法案”（DMCA），其中包括为违法侵权目的豁免程序，包括越狱。
虽然[[苹果公司|苹果公司]]不赞同用户自行越狱，但越狱社区一般也没有受到苹果公司的法律威胁。目前至少有两名杰出的越狱者在苹果公司获得职位。有时候苹果公司也经常（半开玩笑的）感谢越狱社区帮助iOS系统检测安全[[漏洞|漏洞]]。
苹果公司发布对于越狱iOS系统的的支持文章中声称：“拒绝为已经越狱的iPhone、iPad或iPod touch提供保修服务”。
=== 澳大利亚 ===
2010年，[[澳大利亚|澳大利亚]]政府表示，澳大利亚越狱iOS系统的法律地位中的合法地位尚不明确，其很可能是受“2006年版权修正法”影响。

=== 加拿大 ===
2012年11月，[[加拿大|加拿大]]政府修改“版权法”，其中包括禁止篡改数字锁，但除了软件操作以外。

2008-2011年，加拿大政府修改“版权法案”（C-60号法案，C-61号法案和第C-32号法案），内容包括禁止篡改数字锁，以及对限制性更强的C-11的提出初步建议， 但目前这些法案被搁置了。

2011年，加拿大版权学者迈克尔·盖斯（Michael Geist）将越狱iOS系统的人行为视为违反版权法的行为。

=== 新西兰 ===
新西兰的版权法允许使用技术保护措施（TPM）的规避方法，但这些只适用于法律，并且建立在非侵犯版权的范围内。目前，新西兰政府将“2008年版权（新技术）修正法”的一部分内容添加到“1994年版权法”。

=== 新加坡 ===
目前在新加坡越狱iOS系统可能处于合法状态，但新加坡当局政府并未对此公开声明。

==设备==
===首次越狱===
{| style="width:80%;" class="wikitable sortable"
|-
!设备名称/系统版本
!发布到成功越狱所花时间<br><small>以天计算，包括不完美越狱</small>
!首次越狱使用工具
!越狱开发者
|-
| 第一代iPhone/iPhone OS 1.0
| 11
| 无名字
| rowspan="2"|iPhone Dev Team<ref name="How to Escape Jail">{{cite web|url=http://iphone.fiveforty.net/wiki/index.php/How_to_Escape_Jail|title=How to Escape Jail|author=iPhone Dev Team|deadurl=yes|archiveurl=https://web.archive.org/web/20071005150518/http://iphone.fiveforty.net/wiki/index.php/How_to_Escape_Jail|archivedate=2007-10-05}}</ref>
|-
| [[iPhone_3G|iPhone 3G]]/iPhone OS 2.0
| 9
| [[PwnageTool|PwnageTool]]
|-
| 第二代iPod touch
| 143
| [[redsn0w|redsn0w]]
| 
|-
| [[iPad_(第三代)|iPad (第三代)]]<br><small>也称iPad 3、the New iPad</small>
| 70
| Absinthe 2.0
| pod2g, Chronic Dev Team, iPhone Dev Team
|-
| iOS 6.0－6.1.2
| 0
| redsn0w
| iPhone Dev Team
|-
| [[iPhone_5|iPhone 5]]
| 136
| rowspan="4"|[[evasi0n|evasi0n]]
| rowspan="8"|[[evad3rs|evad3rs]]
|-
| 第五代[[iPod_touch|iPod touch]]
| 104
|-
| [[iPad_(第四代)|iPad (第四代)]] 
| 94
|-
| [[iPad_Mini|iPad Mini]]
| 94
|-
| [[iPhone_5C|iPhone 5C]]
| 93
| rowspan="4"|[[evasi0n|evasi0n]]7
|-
| [[iPhone_5S|iPhone 5S]]
| 93
|-
| [[iPad_Air|iPad Air]]
| 51
|-
| [[iPad_mini_2|iPad mini 2]]
| 40
|-
| [[iOS_7|iOS 7]] 7.1－7.1.2
| 25
| [[盘古越狱|盘古越狱]]v1.1.0~v1.2.1
| rowspan="6"|[[盘古越狱|盘古越狱团队]]
|-
| [[iOS_8|iOS 8]]
| 35
| rowspan="5"|[[盘古越狱|盘古越狱]]for iOS 8
|-
| [[iPhone_6|iPhone 6]]
| 33
|-
| [[iPhone_6_Plus|iPhone 6 Plus]]
| 33
|-
| [[iPad_Air_2|iPad Air 2]]
| 0
|-
| [[iPad_mini_3|iPad mini 3]]
| 0
|-
| iOS 8.1.1
| 12
| 太极越狱V1.0
| rowspan="6"|[[太极越狱|太极越狱团队]]
|-
| iOS 8.1.2
| 1
| 太极越狱V1.2.0
|-
| iOS 8.1.3
| 147
| rowspan="3"|太极越狱V2.0
|-
| iOS 8.2
| 106
|-
| iOS 8.3
| 76
|-
| iOS 8.4
| 0
| 太极越狱V2.2.0
|-
| iOS 8.4.1
| -
| EtasonJB
| tihmstar
|-
| [[iPhone_6S|iPhone 6S]]
| 5
| rowspan="2"|[[盘古越狱|盘古越狱]]
| rowspan="5"|[[盘古越狱|盘古越狱团队]]
|-
| [[iPhone_6s_Plus|iPhone 6s Plus]]
| 5
|-
| iOS 9.0
| 25
| rowspan="3"|[[盘古越狱|盘古越狱]]V1.0.0
|-
| iOS 9.0.1
| 20
|-
| iOS 9.0.2
| 13
|-
| iOS 9.1
| 142
|[[盘古越狱|盘古越狱]]V1.3.0（Windows版）<br/>[[盘古越狱|盘古越狱]]V1.1.0（Mac版）<br/>[[Jailbreakme|Jailbreakme]] 4.0 (jailbreak.me)
|rowspan="7"|[[盘古越狱|盘古越狱团队]]<br/>[[Tihmstar|Tihmstar]](jailbreakme4.0)(支援32位元設備)
|-
| iOS 9.2
| 228
|rowspan="6"|PP助手 v5.0.3.1142<br/>[[Jailbreakme|Jailbreakme]] 4.0
|-
| iOS 9.2.1
| 186
|-
| iOS 9.3
| 124
|-
|iOS 9.3.1
| 114
|-
|iOS 9.3.2
| 68<br>51
|-
|iOS 9.3.3
| 5
|-
|iOS 9.3.4
| 155
|Trident<br/>Home Depot<br/>[[Jailbreakme|Jailbreakme]] 4.0 (jailbreak.me)
|antiquedev<br/>NSO, Benjamin, qwertyoruiop, planetbeing, Jon Seals, Tihmstar, ih8sn0w<br/>[[Tihmstar|Tihmstar]](jailbreakme4.0)(支援32位元設備)
|-
|iOS 9.3.5
| -
|Phoenix
|Siguza, tihmstar, mbazaliy, qwertyoruiop, realkjcmember
|-
|[[iPhone_7|iPhone 7]]
| 103
|rowspan="6"|yalu
|rowspan="7"|Luca Todesco
|-
|[[iPhone_7_Plus|iPhone 7 Plus]]
| 103
|-
|iOS 10.0.1
| 91
|-
|iOS 10.0.2
| 87
|-
|iOS 10.1
| 59
|-
|iOS 10.1.1
| 49
|-
|iOS 10.2
| 23
|yalu102
|-
|iOS 10.2.1
| -
|Saigon
|cheesecakeufo, Ian Beer, Adam Donenfeld, xerub, Luca Todesco, Siguza
|-
|iOS 10.3.x
| -
|h3lix (32位元)<br/>g0blin (64位元)<br/>Meridian (64位元)
|tihmstar, siguza, @FoxletFox, Jacky C<br/>Jakeashacks<br/>PsychoTea（@iBSparkes）
|-
|iOS 11 - iOS 11.1.2
|160
|FilzaEscaped<br/>LiberiOS<br/>Electra
|Ian Beer, Bas vT, theninjaprawn, Jakeashacks<br/>Jonathan Levin, QiLin（麒麟）<br/>CoolStar,xerub,Siguza, theninjaprawn, stek29
|-
|iOS 11.2 - iOS 11.4 Beta 3
|31
|Electra<br/>RootlessJB
|lan Beer, CoolStar, xerub, Siguza, pwn20wnd, theninjaprawn, stek29, PsychoTea, aesign_<br/>Jakeashacks
|-
|iOS 11 - iOS 11.4.1
| -
|unc0ver
|pwn20wnd, Sam Bingner, DennisBednarz, Samg_is_a_Ninja, xerub, iBSparkes, stek29, theninjaprawn
|-
|iOS 12 - iOS 12.1.2
| -
|RootlessJB<br/>unc0ver
|Jakeashacks<br/>pwn20wnd, Sam Bingner, DennisBednarz, Samg_is_a_Ninja, Jakeashacks, notcom
|-
|}

===停止支持的设备===  
{| style="width:80%;" class="wikitable sortable"
|- 
! 设备名称 
! 发布时间 
! 首次越狱时间 
! 支持的最新版本的iOS系统 
! 越狱所用软件（最新版本適用）
! 越狱后是否需要引导启动（是否为完美越狱） 
|- 
| [[iPhone_(第一代)|iPhone]]<br /> 
| 2007年6月29日 
| 2007年10月10日<ref name="autogenerated1">{{cite web|last=Wilson |first=Ben |url=http://reviews.cnet.com/8301-19512_7-10115200-233.html |title=Official iPhone 1.1.1 jailbreak released with easy-to-follow instructions; does not requir bulmpkine TIFF exploit | iPhone Atlas - CNET Reviews |publisher=CNet |date=2007-10-10 |accessdate=2009-07-17}}</ref> 
| 3.1.3
|  
* redsn0w 0.9.4<ref>http://www.redmondpie.com/jailbreak-iphone-os-3.1.3-firmware-with-redsn0w-0.9.4/</ref> 
* Spirit 
* Jailbreakme 2.0 
* Sn0wbreeze 2.0.2 
* PwnageTool 3.1.5 
* Whited00r 
| {{Yes|不需要引导启动（完美越狱）}}
|- 
| [[iPhone_3G|iPhone 3G]] <br /> 
| 2008年7月11日 
| 2008年7月20日<ref>{{cite web|url=http://www.redmondpie.com/jailbreak-ios-4.1-with-redsn0w-0.9.6-how-to-guide/ |title=Jailbreak for iPhone 3G redsn0w0.9.6b7 |publisher=DevTeam |date=2010-09-21 |accessdate=2010-09-22}}</ref> 
| 4.2.1
|  
* redsn0w 0.9.6rc18 
* PwnageTool 4.2 
* Sn0wbreeze 2.2.1 
* Whited00r 
* Greenpois0n RC6.2 
| {{Yes|不需要引导启动（完美越狱）}}
|- 
| [[IPod_touch#%E7%AC%AC%E4%B8%80%E4%BB%A3|iPod touch]]<br /> 
| 2007年9月5日 
| 2007年10月10日<ref>{{cite web |url=http://mac.blorge.com/2007/10/10/ipod-touch-iphone-111-jailbreak-released/ |title=iPod Touch / iPhone 1.1.1 jailbreak released |publisher=Mac.Blorge |date=2007-10-10 |accessdate=2010-09-11 |archive-url=https://web.archive.org/web/20101226060919/http://mac.blorge.com/2007/10/10/ipod-touch-iphone-111-jailbreak-released/ |archive-date=2010-12-26 |dead-url=yes }}</ref> 
| 3.1.3
|  
* redsn0w 0.9.4<ref>http://www.redmondpie.com/jailbreak-iphone-os-3.1.3-firmware-with-redsn0w-0.9.4/</ref> 
* Spirit 
* Jailbreakme 2.0 
* Sn0wbreeze 2.0.2 
* PwnageTool 3.1.5 
* Whited00r 
* greenpois0n
| {{Yes|不需要引导启动（完美越狱）}} 
|- 
| [[iPod_touch|iPod touch]] 2<br /><small>MB Model</small><br /> 
| 2008年9月9日 
| 2009年3月11日<ref>{{cite web|url=http://chronic-dev.org/blog/2009/03/rough-untethered-released/ |title=Rough Untethered Released « Chronic Dev Blog |publisher=Chronic-dev.org |date=2009-03-11 |accessdate=2010-04-10}} {{Dead link|date=September 2010|bot=H3llBot}}</ref> 
| 4.2.1
|  
* redsn0w 0.9.6rc18 
* PwnageTool 4.2 
* Sn0wbreeze 2.2.1 
* Whited00r 
* Greenpois0n RC6.2 
| {{Yes|不需要引导启动（完美越狱）}}
|- 
| [[iPhone_3GS|iPhone 3GS]]<br /><small>(16GB 32GB)<br />(旧bootrom)</small> 
| 2009年6月19日 
| 2009年7月3日 
| 6.1.6
|
* redsn0w  
* Absinthe 2.0.4 
* evasi0n 
| {{Yes|不需要引导启动（完美越狱）}}
|- 
| [[iPod_touch|iPod touch]] 2 <br /><small>MC model</small><br /> 
| 2009年9月9日 
| 2009年10月25日 
| 4.2.1
|  
* redsn0w 0.9.6rc18 
* PwnageTool 4.2 
* Sn0wbreeze 2.2.1 
* Greenpois0n RC6.2 
| {{Yes|不需要引导启动（完美越狱）}}
|- 
| [[iPod_touch|iPod touch]] 3<br /> 
| 2009年9月9日 
| 2009年10月11日 
| 5.1.1
| 
* redsn0w 0.9.12b2 
* Absinthe 2.0.4 
| {{Yes|不需要引导启动（完美越狱）}}
|- 
| [[iPad|iPad]]<br /><small>(Wi-Fi model)</small> 
| 2010年4月3日 
| 2010年5月2日  
| 5.1.1
| 
* redsn0w 0.9.12b2 
* Absinthe 2.0.4 
* Jailbreakme 
| {{Yes|不需要引导启动（完美越狱）}}
|- 
| [[iPad|iPad]]<br /><small>(3G model)</small> 
| 2010年4月30日 
| 2010年5月2日 
| 5.1.1
| 
* redsn0w 0.9.12b2 
* Absinthe 2.0.4 
* Jailbreakme  
| {{Yes|不需要引导启动（完美越狱）}}
|- 
| [[iPhone_3GS|iPhone 3GS]]<br /><small>(8GB)<br />(新bootrom)</small> 
| 2010年6月24日 
| 2010年8月1日 
| 6.1.6 
| 
* redsn0w 0.9.12b2 
* Absinthe 2.0.4  
| {{Yes|不需要引导启动（完美越狱）}}
|- 
| [[iPod_touch|iPod touch]] 4 
| 2010年9月1日 
| 2010年10月9日 
| 6.1.6 
| 
*redsn0w 0.9.12b2 
*evasi0n
*Absinthe 2.0.4 
| {{Yes|不需要引导启动（完美越狱）}}
|- 
| [[iPhone_4|iPhone 4]]<br /><small>(16GB 32GB)</small> 
| 2010年6月24日 
| 2009年8月1日 
| 7.1.2
| 
* redsn0w  
* Absinthe 2.0.4 
* evasi0n
* evasi0n7 
| {{Yes|不需要引导启动（完美越狱）}} 
|- 
| [[iPhone_4S|iPhone 4S]]<br /> 
| 2011年10月4日 
| 2012年1月21日 
| 9.3.5
| 
* Phoenix
| style="background:#ffcc00;text-align: center;"|需要引导启动（不完美越狱） 
|- 
| [[iPad_(第二代)|iPad 2]]<br /> 
| 2012年3月7日 
| 2012年5月25日 
| 9.3.5
| 
* Phoenix
| style="background:#ffcc00;text-align: center;"|需要引导启动（不完美越狱） 
|- 
| [[iPad_(第三代)|iPad 3]]<br /><small>(Global model)</small> 
| 2012年3月7日 
| 2012年5月25日 
| 9.3.5
| 
* Phoenix
| style="background:#ffcc00;text-align: center;"|需要引导启动（不完美越狱）  
|- 
| [[iPad_4|iPad 4]]
| 2012年11月2日 
| 2013年2月5日 
| 10.3.3
| 
* h3lix
| style="background:#ffcc00;text-align: center;"|需要引导启动（不完美越狱）
|- 
| [[iPhone_5|iPhone 5]] 
| 2012年9月13日 
| 2013年2月5日 
| 10.3.3
|  
* h3lix
| style="background:#ffcc00;text-align: center;"|需要引导启动（不完美越狱）
|- 
| [[iPad_mini|iPad mini]]<br /><small>包括所有的iPad mini版本</small> 
| 2012年11月2日 
| 2013年2月5日
| 9.3.5
| 
* Phoenix
| style="background:#ffcc00;text-align: center;"|需要引导启动（不完美越狱）
|- 
| [[iPod_touch|iPod touch]] 5 
| 2012年9月13日 
| 2013年2月5日 
| 9.3.5
| 
* Phoenix
| style="background:#ffcc00;text-align: center;"|需要引导启动（不完美越狱）
|- 
| [[iPhone_5C|iPhone 5C]] 
| 2013年9月20日 
| 2013年12月22日 
| 10.3.3
|  
* h3lix
| style="background:#ffcc00;text-align: center;"|需要引导启动（不完美越狱）
|}

===支持中的设备=== 
{| style="width:80%;" class="wikitable sortable"
! 支持的最新版本的iOS系统 
! 越狱所用软件 
! 可正常越狱的固件版本号 
! 最新正常越狱可使用的软件 
! 越狱后是否需要引导启动（是否为完美越狱） 
|- 
| 12.1.2
| unc0ver
| IOS 12 - iOS 12.1.2
| unc0ver
| style="background:#ffcc00;"|需要引导启动（不完美越狱）
|}

==相关条目== 
*[[Chronic_dev_team|Chronic dev team]] 
*[[Greenpois0n|Greenpois0n]] 
*[[盘古越狱|盘古越狱]]
*[[evasi0n|evasi0n]]
*[[Root_(Android)|Root (Android)]]

==参考注释== 
{{Reflist|2}}

{{IOS}}

[[Category:自制软件|Category:自制软件]] 
[[Category:IOS越獄|Category:IOS越獄]]