setwd("/Users/brittneyshaull/Documents/UCDavis/Stat250/Assign4")
library(maps)
library(mapdata)
library(XML)
library(SVGAnnotation)

china=map('china')
identify(china, n=1)
china$names
sum(is.na(china$x))
#svg('china.svg')
#map('china')
#dev.off()
#doc = xmlParse("china.svg")



chinadata=read.csv('china.txt', header=FALSE, sep="\t")
date=chinadata$V2+(chinadata$V3/12)
chinadata=cbind(chinadata, date)
anhui=chinadata[which(chinadata$V1>=1 & chinadata$V1<14) , ]

anhui=anhui[order(anhui$date), ]
png('pmin_anhui.png')
pmin_anhui=plot(anhui$date, anhui$V5, type="line")
dev.off()
png('pmax_anhui.png')
pmax_anhui=plot(anhui$date, anhui$V6, type="line")
dev.off()

fujian=chinadata[which(chinadata$V1>=14 & chinadata$V1<26) , ]
fujian=fujian[order(fujian$date), ]
png('pmin_fujian.png')
pmin_fujian=plot(fujian$date, fujian$V5, type="line")
dev.off()
png('pmax_fujian.png')
pmax_fujian=plot(fujian$date, fujian$V6, type="line")
dev.off()

guangdong=chinadata[which(chinadata$V1>=26 & chinadata$V1<39) , ]
guangdong=guangdong[order(guangdong$date), ]
png('pmin_guangdong.png')
pmin_guangdong=plot(guangdong$date, guangdong$V5, type="line")
dev.off()
png('pmax_guangdong.png')
pmax_guangdong=plot(guangdong$date, guangdong$V6, type="line")
dev.off()

guizhou=chinadata[which(chinadata$V1>=39 & chinadata$V1<52) , ]
guizhou=guizhou[order(guizhou$date), ]
png('pmin_guizhou.png')
pmin_guizhou=plot(guizhou$date, guizhou$V5, type="line")
dev.off()
png('pmax_guizhou.png')
pmax_guizhou=plot(guizhou$date, guizhou$V6, type="line")
dev.off()

guangxi=chinadata[which(chinadata$V1>=52 & chinadata$V1<64) , ]
guangxi=guangxi[order(guangxi$date), ]
png('pmin_guangxi.png')
pmin_guangxi=plot(guangxi$date, guangxi$V5, type="line")
dev.off()
png('pmax_guangxi.png')
pmax_guangxi=plot(guangxi$date, guangxi$V6, type="line")
dev.off()


hubei=chinadata[which(chinadata$V1>=64 & chinadata$V1<74) , ]
hubei=hubei[order(hubei$date), ]
png('pmin_hubei.png')
pmin_hubei=plot(hubei$date, hubei$V5, type="line")
dev.off()
png('pmax_hubei.png')
pmax_hubei=plot(hubei$date, hubei$V6, type="line")
dev.off()

hunan=chinadata[which(chinadata$V1>=74 & chinadata$V1<87) , ]
hunan=hunan[order(hunan$date), ]
png('pmin_hunan.png')
pmin_hunan=plot(hunan$date, hunan$V5, type="line")
dev.off()
png('pmax_hunan.png')
pmax_hunan=plot(hunan$date, hunan$V6, type="line")
dev.off()

jiangsu=chinadata[which(chinadata$V1>=87 & chinadata$V1<97) , ]
jiangsu=jiangsu[order(jiangsu$date), ]
png('pmin_jiangsu.png')
pmin_jiangsu=plot(jiangsu$date, jiangsu$V5, type="line")
dev.off()
png('pmax_jiangsu.png')
pmax_jiangsu=plot(jiangsu$date, jiangsu$V6, type="line")
dev.off()

jiangxi=chinadata[which(chinadata$V1>=97 & chinadata$V1<111) , ]
jiangxi=jiangxi[order(jiangxi$date), ]
png('pmin_jiangxi.png')
pmin_jiangxi=plot(jiangxi$date, jiangxi$V5, type="line")
dev.off()
png('pmax_jiangxi.png')
pmax_jiangxi=plot(jiangxi$date, jiangxi$V6, type="line")
dev.off()

zhejiang=chinadata[which(chinadata$V1>=111 & chinadata$V1<122) , ]
zhejiang=zhejiang[order(jiangxi$date), ]
png('pmin_zhejiang.png')
pmin_zhejiang=plot(zhejiang$date, zhejiang$V5, type="line")
dev.off()
png('pmax_zhejiang.png')
pmax_zhejiang=plot(zhejiang$date, zhejiang$V6, type="line")
dev.off()
