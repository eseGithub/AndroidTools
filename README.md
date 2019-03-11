# AndroidTools

#查看apk信息----> GetApkInfo.jar --->  java -jar GetApkInfo.jar Janus.apk

#反编译dex成文件夹   ---->  baksmali.jar  ---> java -jar baksmali.jar d classes.dex

#文件夹重打包dex ---> smali.jar ----> java -jar smali.jar assemble out

#查看dex源代码 --->dex2jar.jar

#查看jar源代码 --->jd_gui.jar

#反编译apk成文件夹 ---> apktool --> java -jar apktool.jar d app-release.apk

#文件夹重打包apk  ---> apktool --> java -jar apktool.jar b calendar

#APK

#APK_Messenger_v3.0.zip  ----> apk信息查看器

#JustTrustMe.apk  --->Xposed框架模块--> 绕过ssl证书校验 可结合hook-helper.apk 使用

#hook-helper.apk  --->Xposed框架模块--> hook apk函数，hook输入框，修改函数返回值等。

#hijack.apk    --->界面劫持（5.0以下）

#hijack5.apk    --->界面劫持（5.0以上）

#MemSpector.apk  --->内存搜索

#RE_file_list.apk  --->文件搜索

#injectDalvik  ---> 注入 结合 libhello.so -----> ./injectDalvik packageName  ---->cat /cat /proc/pid/maps | grep hello

#injecArt  ---> 注入 结合 libhello.so -----> ./injecArt packageName  ---->cat /cat /proc/pid/maps | grep hello

#xposedInstaller.apk  ---> Android Xposed框架

#jeb2.3.6  ---> 链接：https://pan.baidu.com/s/1qahKuVcjDeGNDvUyklHSuw 提取码：1qvk 
