# Install - 請安裝flask以及lint_chatbot_sdk
可透過pip install
~~~
pip install flask
pip install lint_chatbot_sdk
~~~

# Line Develop Account - 建立一個Line Develop帳號，以及建置最基礎的環境
<可參考我寫的文章-透過Python 架設 Line Chatbot 教學。>
http://www.xiaosean.website/chatbot/2018/04/10/LineChatbot/


# Config - 更換成你的token
記得將my_token.py的token換成你的！！！
記得將my_token.py的token換成你的！！！
記得將my_token.py的token換成你的！！！

# 可以看這篇tutorial了
<可參考我寫的文章-透過Python 架設 Line Chatbot 教學-應用篇。>

http://www.xiaosean.website/chatbot/2018/04/19/LineChatbot_usage/


## Step1.架設基礎的line chatbot
	
#### line_chatbot_basic.py

透過flask結合line_chatbot做出基本的伺服器，
會覆誦你說出的話。

## Step2.如何獲得user id	

#### show_how_to_get_user_id.py

了解如何獲得user id
接下來的教學push_tutorial.ipynb會需要使用user id做推播。

## Step3.如何推送訊息以及訊息種類展示	
	
#### push_tutorial.ipynb

了解line chatbot有什麼訊息格式可發送

裡面有一些示範

- Text
- Image
- Location
- Imagemap
- template
	- button - template
	- Carousel - template
	- Image Carousel - template

## Step4.Reply-透過回覆回來的訊息做處理		

#### line_chatbot_reply.py

介紹處理回傳訊息的方式。
	- MessageEvent
	- PostbackEvent
使用方式：

先在line聊天室隨便打個字發送，之後看看各個選項所輸出的結果。以及有用到get_profile的API，可以獲得用戶資料。

## Step5.Follow event-首次追蹤後會發送訊息

#### line_chatbot_follow.py

相當好用的功能，首次追蹤後會發送訊息


## Step5.Rich menu - 圖文選單
在聊天室下方可出現一個長方形的按鈕選單，

點選每個按鈕有不同的功能

有兩種做法 
- 可在官網設定 
https://admin-official.line.me/ 
- 可寫API達成
有較高的彈性，可對特定使用者客製化。

不過我實際使用連RichMenu都不能import跳過，等勇者嘗試

https://github.com/line/line-bot-sdk-python/blob/master/tests/api/test_rich_menu.py

## Todos:
[NTUST_CC_Line_chat]


## LIcense
MIT

[NTUST_CC_Line_chat]:https://github.com/xiaosean/NTUST_Line_Chatbot