This guide is updated on 24/3/2021
# 目錄 table of contents
- [What is the Different between [ShallowSea-ams+reinxspoof.rar] & [ShallowSea-neutos]](https://github.com/carcaschoi/ShallowSea/blob/main/User%20guide.md#what-is-the-different-between-shallowsea-amsreinxspoofrar--shallowsea-neutos)
- [大氣層更新整合包指南 Atmosphere update aio-package guide](#%E5%A4%A7%E6%B0%A3%E5%B1%A4%E6%9B%B4%E6%96%B0%E6%95%B4%E5%90%88%E5%8C%85%E6%8C%87%E5%8D%97-atmosphere-update-aio-package-guide)
- [sxos更新整合包指南 sxos update aio-package guide](https://github.com/carcaschoi/ShallowSea/blob/main/User%20guide.md#sxos%E6%9B%B4%E6%96%B0%E6%95%B4%E5%90%88%E5%8C%85%E6%8C%87%E5%8D%97-sxos-update-aio-package-guide)
- [ShallowSea使用方法 How to use ShallowSea](https://github.com/carcaschoi/ShallowSea/blob/main/User%20guide.md#%E4%BD%BF%E7%94%A8%E6%96%B9%E6%B3%95-how-to-use)
- [sxos轉大氣層指南 Change sxos to atmosphere](https://github.com/carcaschoi/ShallowSea/blob/main/User%20guide.md#sxos%E8%BD%89%E5%A4%A7%E6%B0%A3%E5%B1%A4%E6%8C%87%E5%8D%97-change-sxos-to-atmosphere)
- [魔改sxos 3.1.0以支持11.0.1 modify sxos 3.1.0 to support 11.0.1](https://shipengliang.com/games/switch-%e7%a1%ac%e7%a0%b4%e8%ae%be%e5%a4%87-11-0-1-%e7%9c%9f%e5%ae%9e%e7%b3%bb%e7%bb%9f-%e9%ad%94%e6%94%b9%e6%94%af%e6%8c%81sx-3-1-0%e5%bc%95%e5%af%bc%e5%9b%be%e6%96%87%e6%95%99%e7%a8%8b.html)

# What is the Different between [ShallowSea-ams+reinxspoof.rar] & [ShallowSea-neutos]
/I recomended to use [ShallowSea-neutos] if you are a rookie\

=== **ShallowSea-ams+reinxspoof** ===

**pros**
* can get support from atmosphere-nx if they are not about piracy
* can get update as soon as possible

**cons (mainly about ReiNX-spoofer)**
* Since some homebrew app detect ReiNX because of ReiNX-spoofer, they may have error. Solution: Disable the plugin & reboot the console before using these app.

=== **ShallowSea-neutos** ===

**pros**
* Do not have problem when using the homebrew app that force atmosphere to run

**cons**
* cannot get support from official [Atmosphere-NX](https://github.com/Atmosphere-NX/Atmosphere) bacause NeutOS is a modded version of atmosphere
* If the owner of neutos does not update neutos, then you cannot use the latest version of atmosphere
* 
# 大氣層更新整合包指南 Atmosphere update aio-package guide:
| 中文指南 | English guide |
| ------ | ------------- |
| 1. 從[這裡](https://github.com/carcaschoi/ShallowSea/releases/latest)下載ShallowSea整合包「Shalloesea-neutos.rar」or「Shalloesea-ams+reinxspoof.rar」，並從[這裡](https://github.com/carcaschoi/rcmloader-package)下載rcmloader注入器整合包 | 1. Download ShallowSea aio package 「Shalloesea-neutos.rar」or「Shalloesea-ams+reinxspoof.rar」 & 「switch English extra package.rar」 from [here](https://github.com/carcaschoi/ShallowSea/releases/latest) , and also download rcmloader package from [here](https://github.com/carcaschoi/rcmloader-package) (optional) |
| 2. 除了（Nintendo，emuiibo，emuMMC，BCAT，JKSV，warmboot_mariko，license.dat）文件夾，刪除其餘文件夾。把整合包裏面所有東西解壓縮放到SD卡中。 | 2. Delete all the folders except (Nintendo,emuiibo,emuMMC,BCAT,JKSV,warmboot_mariko，license.dat) folders or files. Then drapes and drops aio package contents into your sd card. Replace all existing file |
| ...... | 3. After that extract 「switch English extra package.rar」 into the root of the sd card. Replace all existing file. |
| 3. 如果你有注入器，請把[注入器整合包](https://github.com/carcaschoi/rcmloader-package)解壓縮到注入器 | 4. extract [rcmloader package](https://github.com/carcaschoi/rcmloader-package) to your rcmloader if u have it |
| [點此繼續查看使用方法](#%E4%BD%BF%E7%94%A8%E6%96%B9%E6%B3%95-how-to-use) | [press here to continue read the guide (How to use)](#%E4%BD%BF%E7%94%A8%E6%96%B9%E6%B3%95-how-to-use) |

# sxos更新整合包指南 sxos update aio-package guide:
| 中文指南 | English guide |
| ------- | ------------- |
| 1. 從[這裡](https://github.com/carcaschoi/ShallowSea/releases/latest)下載ShallowSea整合包「Shalloesea-sxos.rar」，並從[這裡](https://github.com/carcaschoi/rcmloader-package)下載rcmloader注入器整合包 | 1. Download ShallowSea aio package「Shallowsea-sxos.rar」 from [here](https://github.com/carcaschoi/ShallowSea/releases/latest) , and also download rcmloader package from [here](https://github.com/carcaschoi/rcmloader-package) (optional) |
| 2. 除了（Nintendo，emuiibo，sxos/emunand，BCAT，license.dat，Emutendo，JKSV）文件夾，刪除其餘文件夾。把ShallowSea-sxos整合包裏面所有東西解壓縮放到SD卡中。 | 2. If you are sxos user: Delete all the folders but not (Nintendo,license.dat,emuiibo,sxos/emunand,BCAT,Emutendo,JKSV) folders. Then drapes and drops ShallowSea-sxos contents into your sd card. Replace all existing file. |
| ...... | 3. After that extract 「switch English extra package.rar」 into the root of the sd card. Replace all existing file. |
| 3. 如果你有注入器，請把[注入器整合包](https://github.com/carcaschoi/rcmloader-package)解壓縮到注入器 | 4. extract [rcmloader package](https://github.com/carcaschoi/rcmloader-package) to your rcmloader if u have it |

# 使用方法 How to use:
| 中文 | English |
| --- | ------- |
| 1.1 . 用[tegrarcmgui](https://github.com/eliboa/TegraRcmGUI/releases/latest)注入release附有的payload.bin(the same payload in every releases, no any update)  | 1.1 . use [tegrarcmgui](https://github.com/eliboa/TegraRcmGUI/releases/latest) to inject the payload.bin enclose the releases(the same payload in every releases, no any update) |
| 1.2 . 或者[更新注入器檔案](https://github.com/carcaschoi/rcmloader-package)後，使用rcmloader注入(使用藍燈) | 1.2 . or using rcmloader(blue light) to inject payload after [updating rcmloader file](https://github.com/carcaschoi/rcmloader-package)
| 2. 進入hekate menu | 2. get into hekate menu |
| 3. 第一次使用的話建議創建虛擬系統，[大氣層&SXOS創建虛擬系統指南(點擊查看)](https://github.com/carcaschoi/ShallowSea/blob/main/create%20emuMMC%20guide%20(Chinese).md) | 3. recommended to create emuMMC/emunand if u r first time to hack switch |
| 4. 點選launch | 4. press 「launch」|
| 5. 如果你是使用大氣層，點選CFW Atmosphere ; 如果你是使用sxos，點選CFW SXOS，有虛擬系統的話它會自動引導到虛擬系統 | 5. press 「CFW Atmosphere」 if u r using atmosphere. press 「CFW SXOS」 if u r using sxos. They will launch emuMMC/emunand automatically if u have emuMMC/emunand |

# sxos轉大氣層指南 Change sxos to atmosphere
| 中文 | English |
| --- | ------- |
| 1. 先到sxos破解系統用JKSV備份存檔 | get into sxos cfw & use JKSV to backup game save if possible |
| 2. (硬破機需做此步驟，只需做一次即可)先用sxos 3.1.0到sxos menu→options→sx core→clean up，之後到nand→repair GPT | (sx core/lite user need to to this step)
| 3. 保留Nintendo，license.dat，JKSV | ……
| 4. 解壓縮[大氣層整合包](https://github.com/carcaschoi/ShallowSea/blob/main/User%20guide.md#%E5%A4%A7%E6%B0%A3%E5%B1%A4%E6%9B%B4%E6%96%B0%E6%95%B4%E5%90%88%E5%8C%85%E6%8C%87%E5%8D%97-atmosphere-update-aio-package-guide) | ……
| 5. 正常開機(軟破機需注入payload.bin)會進入hekate menu | ……
| 6. (sxos有虛擬系統才需做此步驟)，[點擊查看步驟](https://github.com/carcaschoi/ShallowSea/blob/main/create%20emuMMC%20guide%20(Chinese).md#%E5%A4%A7%E6%B0%A3%E5%B1%A4%E5%89%B5%E5%BB%BAsd-file-%E8%99%9B%E6%93%AC%E7%B3%BB%E7%B5%B1-) | ……
| 7. 每次開機選launch→CFW Atmosphere | ……
| *. 如果硬破機出現boot0 error，[點擊查看方法](https://www.sthetix.info/generating-a-fresh-boot0-from-scratch-fix-your-switch-now/) | …… |
| 8. 完成😎 | ……
| 9. 有需要的話可以用JKSV還原存檔 | ……
