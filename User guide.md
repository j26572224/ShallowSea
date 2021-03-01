# 更新整合包指南 Update aio-package guide:
| 中文指南 | English guide |
| ------ | ------------- |
| 1. 從[這裡](https://github.com/carcaschoi/ShallowSea/releases/latest)下載ShallowSea整合包「Shalloesea.rar」，並從[這裡](https://github.com/carcaschoi/rcmloader-package)下載rcmloader注入器整合包 | 1. Download ShallowSea aio package「Shallowsea.rar」 from [here](https://github.com/carcaschoi/ShallowSea/releases/latest) , and also download rcmloader package from [here](https://github.com/carcaschoi/rcmloader-package) (optional) |
| 2. 如果您是大氣層用戶：除了（Nintendo，emuiibo，emuMMC，BCAT，JKSV，warmboot_mariko，license.dat）文件夾，刪除其餘文件夾。然後打開「ShallowSea」文件夾，再打開「atmosphere X.XX.X」文件夾，把裏面所有東西解壓縮放到SD卡中。 | 2. If you are Atmosphere user: Delete all the folders but not (Nintendo,emuiibo,emuMMC,BCAT,JKSV,warmboot_mariko，license.dat) folders. Then drape and drop shallowsea/atmosphere X.XX.X/ into your sd card. |
| 2. 如果您是sxos用戶：除了（Nintendo，emuiibo，sxos/emunand，BCAT，license.dat，Emutendo，JKSV）文件夾，刪除其餘文件夾。然後打開「ShallowSea」文件夾，再打開「sxos X.X.X」文件夾，把裏面所有東西解壓縮放到SD卡中。 | 2. If you are sxos user: Delete all the folders but not (Nintendo,license.dat,emuiibo,sxos/emunand,BCAT,Emutendo,JKSV) folders. Then drape and drop shallowsea/sxos X.X.X/ into your sd card. |
| 3. 如果你有注入器，請把[注入器整合包](https://github.com/carcaschoi/rcmloader-package)解壓縮到注入器 | 3. extract [rcmloader package](https://github.com/carcaschoi/rcmloader-package) to your rcmloader if u have it |

# 使用方法 How to use:
| 中文 | English |
| --- | ------- |
| 1.1 . 用[tegrarcmgui](https://github.com/eliboa/TegraRcmGUI/releases/latest)注入整合包的ShallowSea/payload for injection/payload.bin  | 1.1 . use [tegrarcmgui](https://github.com/eliboa/TegraRcmGUI/releases/latest) to inject the ShallowSea/payload for injection/payload.bin which is inside the aio package |
| 1.2 . 或者[更新注入器檔案](https://github.com/carcaschoi/rcmloader-package)後，使用rcmloader注入(使用藍燈) | 1.2 . or using rcmloader(blue light) to inject payload after [updating rcmloader file](https://github.com/carcaschoi/rcmloader-package)
| 2. 進入hekate menu | 2. get into hekate menu |
| 3. 第一次使用的話建議創建虛擬系統，[大氣層&SXOS創建虛擬系統指南(點擊查看)](https://github.com/carcaschoi/ShallowSea/blob/main/create%20emuMMC%20guide%20(Chinese).md) | 3. recommended to create emuMMC/emunand if u r first time to hack switch |
| 4. 點選launch | 4. press 「launch」|
| 5. 如果你是使用大氣層，點選CFW Atmosphere ; 如果你是使用sxos，點選CFW SXOS，有虛擬系統的話它會自動引導到虛擬系統 | 5. press 「CFW Atmosphere」 if u r using atmosphere. press 「CFW SXOS」 if u r using sxos. They will launch emuMMC/emunand automatically if u have emuMMC/emunand |

# sxos轉大氣層指南 Change sxos to atmosphere
| 中文 | English |
| --- | ------- |
| 1. 先到sxos破解系統用JKSV備份存檔 | ……
| 2. (硬破機需做此步驟，只需做一次即可)先用sxos 3.1.0到sxos menu→options→sx core→clean up，之後到nand→repair GPT | ……
| 3. 保留Nintendo，license.dat，JKSV | ……
| 4. 解壓縮大氣層整合包 | ……
| 5. 正常開機(軟破機需注入payload.bin)會進入hekate menu | ……
| 6. (sxos有虛擬系統才需做此步驟)，https://github.com/carcaschoi/ShallowSea/blob/main/create%20emuMMC%20guide%20(Chinese).md#%E5%A4%A7%E6%B0%A3%E5%B1%A4%E5%89%B5%E5%BB%BAsd-file-%E8%99%9B%E6%93%AC%E7%B3%BB%E7%B5%B1- | ……
| 7. 每次開機選launch→CFW Atmosphere | ……
| *. 如果硬破機出現boot0 error，https://www.sthetix.info/generating-a-fresh-boot0-from-scratch-fix-your-switch-now/ | …… |
| 8. 完成😎 | ……
| 9. 有需要的話可以用JKSV還原存檔 | ……
