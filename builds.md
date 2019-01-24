Welcome to Termux!

Wiki:            https://wiki.termux.com
Community forum: https://termux.com/community
IRC channel:     #termux on freenode
Gitter chat:     https://gitter.im/termux/termux
Mailing list:    termux+subscribe@groups.io

Search packages:   pkg search <query>
Install a package: pkg install <package>
Upgrade packages:  pkg upgrade
Learn more:        pkg help
[user09:24~]$ cd storage/downloads/
[user09:24downloads]$ d builtAPKs*
463364  builtAPKs
285788  builtAPKs190115a
90676   builtAPKs190115b
493360  builtAPKs190116
171152  builtAPKs190120
604884  builtAPKs190121
163872  builtAPKs190122
116108  builtAPKs20190114
160968  builtAPKs20190117
[user09:24downloads]$ find builtAPKs* -name step* |wc -l
20610
[user09:25downloads]$ find builtAPKs190115a -name step* |wc -l
2175
[user09:25downloads]$ find builtAPKs190115b -name step* |wc -l
698
[user09:25downloads]$ find builtAPKs190116 -name step* |wc -l
4454
[user09:25downloads]$ find builtAPKs190120 -name step* |wc -l
1362
[user09:26downloads]$ find builtAPKs190121 -name step* |wc -l
4684
[user09:26downloads]$ find builtAPKs190122 -name step* |wc -l
999
[user09:26downloads]$ find builtAPKs20190117 -name step* |wc -l
1316
[user09:26downloads]$ find builtAPKs20190114 -name step* |wc -l
977
[user09:26downloads]$
