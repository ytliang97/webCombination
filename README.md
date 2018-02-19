# webCombination


目前找到能改進的地方有：

+ 繼續調整背景或找背景顏色讓他們不會太過奇怪
	+ 背景顏色的調整
	+ footer的寬窄
+ 還有每個網頁內容跟carousel的距離我會調整(+)
+ 加入javascript控制submenu與subpage的對應(+)
+ 暫時還不知道怎麼調整submenu歪一邊的問題(+)
+ 首頁快速通道的內容決定

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

+ 打包的css檔、js檔都暫時丟入/src了
