# MultiAVChatWeb 
MultiPlayer AVChatDemo for Web, powered by NIM web sdk.

## Login Part
The UI is refer to https://app.yunxin.163.com/webdemo/im/login.html
Login part is just a fake login, save the account and password to Cookie, and shart to the main.js for real login.

## Main Part
After jump to this page Main.html, var nim = NIM.getInstance will connect the NIM server for AVChat signal Logic.
For more NIM information please refer to : 
[NIM init](https://dev.yunxin.163.com/docs/product/IM%E5%8D%B3%E6%97%B6%E9%80%9A%E8%AE%AF/SDK%E5%BC%80%E5%8F%91%E9%9B%86%E6%88%90/Web%E5%BC%80%E5%8F%91%E9%9B%86%E6%88%90/%E5%88%9D%E5%A7%8B%E5%8C%96)


After Login, we can strat a new Meeting, or Join a Meeting which is already existed. The function startMeeting will automatically create a new Meeting if the meeting that user input does not created before.

After Join Meeting , the following Logic you can refer to : 
[NIM Meeting](https://dev.yunxin.163.com/docs/product/%E9%9F%B3%E8%A7%86%E9%A2%91%E9%80%9A%E8%AF%9D/SDK%E5%BC%80%E5%8F%91%E9%9B%86%E6%88%90/Web%E5%BC%80%E5%8F%91%E9%9B%86%E6%88%90/%E9%9F%B3%E8%A7%86%E9%A2%91%E9%80%9A%E8%AF%9D%E6%B5%81%E7%A8%8B%E5%A4%9A%E4%BA%BA)


I design four Container for Remote View, so this demo can support 5 people meeting.
You can also find the Player's accid above his View.
