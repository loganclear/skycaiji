当前data目录：
> install.lock文件可检测系统是否安装（删除可重装系统）
> config.php文件为系统配置文件（勿删）
> app目录保存应用程序数据（勿删）
> program/upgrade目录保存升级时下载的新文件（可删除）
> program/backup目录保存升级后被替换的文件（按需删除）
> 其他文件为使用中产生的数据文件（按需删除）

系统根目录：
> app目录保存应用程序文件（勿删）
> plugin目录保存插件文件（勿删）

其他文件：
> 其他文件皆为系统自带文件，如误删可进入 https://gitee.com/zorlan/skycaiji 或 https://github.com/zorlan/skycaiji 下载相应版本文件覆盖即可

伪静态设置：
> 参考系统根目录/public中的htaccess-apache、htaccess-nginx、htaccess-iis
