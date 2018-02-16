# webCombination

不確定這樣子組合你方不方便，希望能麻煩你看一下，跟我說怎麼改比較好(我知道現在這樣還很醜，抱歉...)

目前找到能改進的地方有：

+ 繼續調整背景或找背景顏色讓他們不會太過奇怪
+ 還有每個網頁內容跟carousel的距離我會調整
+ 加入javascript控制submenu與subpage的對應


整個repo結構為


+ 頁面對應：subpage為同名之html檔

	+ 首頁 - index.php
	+ 系所公告 - News.php
	+ 系所簡介 - Introduce.php
	+ 課程資訊 - Course.php
	+ 招生資訊 - Enrollment.php
	+ 法令/表單 - Download.php
	+ 學生資訊 - Student.php
	+ 網路資源 - Source.php

+ navbar、carousel、footer在/subpage/unit裡
	+ /src/php 是為了統一更動navbar、carousel、footer

+ 打包的css檔、js檔都暫時丟入裡面了

