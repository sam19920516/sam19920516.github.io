---
layout: post
title:  "Google Analytics Note 4"
date:   2017-09-13 18:27:00 +0800
categories: Google Analytics
---
<h3>行為</h3>
{% highlight ruby %}{% endhighlight %}
<h4>總覽(Overview)</h4>
<h4>行為流程(Behaviour Flow): 使用者流程重視流量；行為流程重視參訪流程</h4>
<h4>網站內容(Site Content): 離開率v.s跳出率</h4>
　　[Link][Exit-Bouncing]<br>
　　所有網頁(All Pages)<br>
　　內容深入分析(Content Drilldown): 以網站層級結構來觀看網頁參訪情況<br>
　　到達網頁(Landing Pages): 入站路徑(Entrance Paths)強調頁面內容分析；行為流程(Behaviour Flow)注重行為脈絡。<br>
　　離開網頁(Exit Pages)<br>
<h4>網站速度(Site Speed)</h4>
　　總覽(Overview)<br>
　　網頁操作時間(Page Timings):<br> 
　　　　多層檢視(Explorer)－網站使用情況(Usage)、技術(Technical)、DOM計時(DOM Timings)<br>
　　　　分發(Distribution)<br>
　　　　訪客分布圖(Map Overlay)<br>
　　速度建議(Speed Suggestions)<br>
　　使用者載入時間(User Timings): [Link][User-Timing]<br>
<h4>站內搜尋(Site Search)</h4>
　　總覽(Overview)<br>
　　使用情況(Usage)<br>
　　搜尋字詞(Search Terms)<br>
　　搜尋網頁(Search Pages)<br>
<h4>事件(Events): 網站上被觸發的事物分兩類，事件及目標。事件－觸發之事物並未開啟新分頁。目標－觸發之事物開啟新分頁</h4>
　　總覽(Overview)<br>
　　熱門事件(Top Events)<br>
　　網頁(Pages): 事件觸發需加入程式碼<br>
{% highlight ruby %}<a href="example.com" onclick="ga('send', 'event', 'catagory', 'action', 'label', 'value')">title</a>{% endhighlight %}
`send及event為告知GA目前將傳送事件`、`category: 事件類別`、`action: 事件動作`、`label: 活動標籤`、`value: 事件值(事件觸發所衍生的值)`<br>
＊或是可以將event改為pageview用虛擬網頁的方式，將點擊視為一個網頁瀏覽。<br>
　　事件流程(Events Flow)<br>
<h4>發佈商(Publisher): 刊登廣告需求者；出版商則為提供網站供廣告刊登</h4>
　　總覽(Overview)<br>
　　發佈商網頁(Publisher Pages)<br>
　　發佈商參照網址(Publisher Referrers)<br>
<h4>實驗(Experiments)</h4>



- - -

[Exit-Bouncing]:https://support.google.com/analytics/answer/2525491?hl=zh-Hant
[User-Timing]:https://developers.google.com/analytics/devguides/collection/analyticsjs/user-timings?hl=zh-tw