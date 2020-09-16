<a href="http://info.flagcounter.com/T2RV"><img src="http://s09.flagcounter.com/count2/T2RV/bg_FFFFFF/txt_000000/border_CCCCCC/columns_6/maxflags_20/viewers_GFWList/labels_1/pageviews_1/flags_0/percent_0/" border="0"></a>

考虑到ShadowsocksR因为暂停更新项目删除，导致客户端无法直接更新GFWList PAC文件，所以我写了个脚本自动把 gfwlist 转换为ShadowsocksR客户端可用的 pac.txt 文件。

pac.txt 文件会每天定时生成一次，在 pac.txt 文件的顶部写的有最后更新时间。

大家只需要每隔一段时间下载这个文件并覆盖 ShadowsocksR.exe 同目录下的 pac.txt 文件即可。

（如果找不到，那么点击 右键SSR客户端托盘图标 - PAC - 编辑本地PAC文件...）。

因为 gfwlist 更新频率不高，往往一个月也没更新多少条内容，所以不需要频繁更新 pac.txt 文件，偶尔更新一次就行了。

注意：此 GFWList.txt 生成脚本只是提供给需要的人学习研究用的，普通用户并不需要用这个脚本，只需要下载 gfwlist.txt 覆盖即可。
