# 更新整合包指南 Update aio-package guide:
| 中文指南 | English guide |
| ------ | ------------- |
| 1. 從[這裡](https://github.com/carcaschoi/ShallowSea/releases/latest)下載整合包「Shalloesea.rar」 | 1. Download aio package「Shallowsea.rar」 from [here](https://github.com/carcaschoi/ShallowSea/releases/latest) |
| 2. 如果您是大氣層用戶：除了（Nintendo，emuiibo，emuMMC，BCAT，JKSV，warmboot_mariko，license.dat）文件夾，刪除其餘文件夾。然後打開「ShallowSea」文件夾，再打開「atmosphere X.XX.X」文件夾，把裏面所有東西解壓縮放到SD卡中。 | 2. If you are Atmosphere user: Delete all the folders but not (Nintendo,emuiibo,emuMMC,BCAT,JKSV,warmboot_mariko，license.dat) folders. Then drape and drop shallowsea/atmosphere X.XX.X/ into your sd card. |
| 2. 如果您是sxos用戶：除了（Nintendo，emuiibo，sxos/emunand，BCAT，license.dat，Emutendo，JKSV）文件夾，刪除其餘文件夾。然後打開「ShallowSea」文件夾，再打開「sxos X.X.X」文件夾，把裏面所有東西解壓縮放到SD卡中。 | 2. If you are sxos user: Delete all the folders but not (Nintendo,license.dat,emuiibo,sxos/emunand,BCAT,Emutendo,JKSV) folders. Then drape and drop shallowsea/sxos X.X.X/ into your sd card. |

# 使用方法 How to use:
| 中文 | English |
| --- | ------- |
| 1. 注入整合包的payload.bin(hekate) | 1. inject the payload.bin(hekate) which is inside the aio package |
| 2. 進入hekate menu | 2. get into hekate menu |
| 3. 點選launch | 3. press 「launch」|
| 4. 如果你是使用大氣層/sxos，點選CFW Atmosphere/CFW SXOS，有虛擬系統的話它會自動引導到虛擬系統 | 4. press 「CFW Atmosphere」 if u r using atmosphere. press 「CFW SXOS」 if u r using sxos. They will launch emuMMC/emunand automatically if u have emuMMC/emunand |

# sxos轉大氣層指南
| 中文 | English |
| 1. 先到sxos破解系統用JKSV備份存檔 | 
| 2. (硬破機需做此步驟，只需做一次即可)先用sxos 3.1.0到sxos menu→options→sx core→clean up，之後到nand→repair GPT | ……
| 3. 保留Nintendo，license.dat，JKSV | ……
| 4. 解壓縮大氣層整合包 | ……
| 5. 正常開機(軟破機需注入payload.bin)會進入hekate menu | ……
| 6. (sxos有虛擬系統才需做此步驟)，到hekate menu，點選emuMMC→create emuMMC→sd file (只需做一次即可) | ……
| 7. 每次開機選launch→CFW Atmosphere | ……
| 8. 完成😎 | ……
