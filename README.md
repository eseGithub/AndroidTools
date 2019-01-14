# AndroidTools
查看apk信息----> GetApkInfo.jar --->  java -jar GetApkInfo.jar Janus.apk
反编译dex成文件夹   ---->  baksmali.jar  ---> java -jar baksmali.jar d classes.dex
文件夹重打包dex ---> smali.jar ----> java -jar smali.jar assemble out
查看dex源代码 --->dex2jar.jar
查看jar源代码 --->jd_gui.jar
反编译apk成文件夹 ---> apktool --> java -jar apktool.jar d app-release.apk
文件夹重打包apk  ---> apktool --> java -jar apktool.jar b calendar
