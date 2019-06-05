# extundelete
ext3 or ext4 undelete utility <br>

http://extundelete.sourceforge.net/

注意：在 autogen 或 make 时，如果出现 "configure.ac:10: error: AC_INIT should be called with package and version arguments"

需要修改 configure.ac 文件中关于 AC_INIT 的版本号（EU_VERSION），比如 

AC_INIT(extundelete, EU_VERSION, extundelete.sourceforge.net) 改为 

AC_INIT(extundelete, 0.2.4, extundelete.sourceforge.net)
