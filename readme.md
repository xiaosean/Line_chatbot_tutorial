#1.請安裝flask以及lint_chatbot_sdk<br>
---
可透過pip install<br>
~~~
pip install flask
pip install lint_chatbot_sdk
~~~

#2.建立一個Line Develop帳號，以及建置最基礎的環境<br>
---
<可參考我寫的文章-透過Python 架設 Line Chatbot 教學。><br>
http://www.xiaosean.website/chatbot/2018/04/10/LineChatbot/
<br>

#3.更換成你的token
---
記得將my_token.py的token換成你的！！！<br>
記得將my_token.py的token換成你的！！！<br>
記得將my_token.py的token換成你的！！！<br>

#4.可以看這篇tutorial了
---
<可參考我寫的文章-透過Python 架設 Line Chatbot 教學-應用篇。><br>
http://www.xiaosean.website/chatbot/2018/04/19/LineChatbot_usage/
<br>

<br><br>step1.架設基礎的line chatbot<br><br>
	<t>line_chatbot_basic.py<br>
	<t>透過flask結合line_chatbot做出基本的伺服器，<br>
	<t>會覆誦你說出的話。<br>

<br><br>step2.如何獲得user id<br>	<br>
	<t>show_how_to_get_user_id.py<br>
	<t>了解如何獲得user id<br>
	<t>接下來的教學push_tutorial.ipynb會需要使用user id做推播。<br>

<br><br>step3.如何推送訊息以及訊息種類展示<br><br>	
	<t>push_tutorial.ipynb<br>
	<t>可了解line chatbot有什麼訊息格式可發送<br>
	<t>裡面有一些示範<br>
	<t>- Text<br>
	<t>- Image<br>
	<t>- Location<br>
	<t>- Imagemap<br>
	<t>- template<br>
		- button - template<br>
		- Carousel - template<br>
		- Image Carousel - template<br>
<br><br>step4.reply-透過回覆回來的訊息做處理<br>	<br>	
	<t>介紹處理回傳訊息的方式。
		- MessageEvent
		- PostbackEvent
		使用方式：<br>
		先在line聊天室隨便打個字發送，<br>
		之後看看各個選項所輸出的結果。<br>
		以及有用到get_profile的API，可以獲得用戶資料。

<br><br>step5.follow event-首次追蹤後會發送訊息<br>	<br>
	<t>line_chatbot_follow.py<br>
	<t>相當好用的功能


<br><br>step5.rich menu - 圖文選單<br><br>	
	<t>在聊天室下方可出現一個長方形的按鈕選單，點選每個按鈕有不同的功能
	<t>有兩種做法 <br>
		1.可在官網設定<br> 
			https://admin-official.line.me/ <br>
		2.可寫API達成<br>
			有較高的彈性，可對特定使用者客製化。<br>
			不過我實際使用連RichMenu都不能import跳過，等勇者嘗試<br>
			https://github.com/line/line-bot-sdk-python/blob/master/tests/api/test_rich_menu.py


