# hi3531d_uboot_patch
1. hi3531d uboot修改补丁
   原SDK使用的uboot版本是u-boot-2010.06。  
   增加了USB转以太网驱动，使用芯片为rtl8152，此驱动代码移植自u-boot-2016.05。
   增加了CONFIG_NET_MULTI宏以及相关higmac代码。
