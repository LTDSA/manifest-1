<p align="center">
<img src="https://github.com/DotOS/manifest/blob/dot-o/About.png" > 
</p>

--------------------------------------------------------------

 Dot OS 2.x - Oreo
 ==========


 Credits
 =======
 * [**JDCTeam**](https://github.com/AOSP-JF-MM)
 * [**ABC**](https://github.com/ezio84?tab=repositories)
 * [**DirtyUnicorns**](https://github.com/dirtyunicorns)
 * [**LineageOS**](https://github.com/LineageOS)
 * [**Nitrogen-Project**](https://github.com/nitrogen-project)
 * [**AospExtended**](https://github.com/AospExtended)
 * [**TeamSubstratum (Theme Engine)**](https://github.com/Substratum)


-----------------------------------------------------------------------------
 
 Gerrit
 ==============
 提交您的全部patches通过我们的[Gerrit Code Review](http://gerrit.droidontime.com/).

 Getting Started
 ==============

To get started with the building process, you'll need to get familiar with [Git和Repo](http://source.android.com/source/using-repo.html).

要初始化您的本地数据库，使用一个像这样的命令：

```bash
    repo init -u git://github.com/DotOS/manifest.git -b dot-o
```

然后to sync up:

```bash
    repo sync  -f --force-sync --no-clone-bundle
```

另外，您可以define the number of parallel下载数据库should do:

```bash
    repo sync -f -jX --force-sync --no-clone-bundle  ( X is the number of parallel下载数据库should do choose depending on您的cpu )
```

----------------------------------
 
 Compilation of Dot OS
 ==================

从root directory of项目, perform following命令在终端


```bash
	. build/envsetup.sh
   
        lunch dot_<codename>
   
	brunch <codename>
```


<p align="center">
<img src="https://github.com/DotOS/manifest/blob/dot-n/dotlogo.png" > 
</p>

--------------------------------------------------------------------------------------------------------------------------

For maintainership & to提交patches refer [**这里**](https://github.com/DotOS/android_vendor_dot/blob/dot-o/README.md)

--------------------------------------------------------------------------------------------------------------------------



