## 🏵 Purpose of this project

i. Can communicate and respond to users.
> Data can be sent to the database and data is retrieved to the user.

ii. Compatible with other systems.
> As an intermediary to connect data with other systems Messages can be sent to the destination database.



</br>

## 💭 Flow
```
CASE 1: user talking linebot

User      ->  Linebot  ->  Dynamodb
send msg      get msg      put msg  

CASE 2: linebot talking user

Dynamodb    ->  linebot   ->  User
query data      Response      send data
```

### Inspiration

Sending messages 🧭 [**web - line**](https://developers.line.biz/en/docs/messaging-api/sending-messages/#send-narrowcast-message)

Be a LINE bot to record who +1! Group LINE Bot production teaching and sharing 🧭 [**web - jcshawn.com/addone-linebot/**](https://jcshawn.com/addone-linebot/)

LINE 加一紀錄機器人（ PlusOne Bot ）🧭 [**github - jschang19/plusone-linebot**](https://github.com/jschang19/plusone-linebot)



</br>

## 🔬 In branch progress

work-01 ( err, doing ) 🧭 [**Github**](https://github.com/Wolke/botbuilder-linebot-connector)
> serverless can't show log when error >> empty >> doing

work-02-ngrok ( done ) 🧭 [**Github**](https://github.com/Wolke/botbuilder-linebot-connector)
> success , example to work-03

work-03-ngrok ( done, doing ) 🧭 [**Github**](https://github.com/Wolke/botbuilder-linebot-connector)
> accomplished something and doing someting



</br>

## 📑 Document

Please refer to the official API documents for details.
- Developer Documents - https://developers.line.me/messaging-api/overview
- API Reference - https://devdocs.line.me/en/#messaging-api
- Messaging API SDKs - https://developers.line.biz/en/docs/messaging-api/line-bot-sdk/



</br>

## 💞 References 
Microsoft Bot Framework V3 connector for Line office account 🧭 [**Wolke/botbuilder-linebot-connector**](https://github.com/Wolke/botbuilder-linebot-connector)

SDK for the LINE Messaging API for Node.js 🧭 [**boybundit/linebot**](https://github.com/boybundit/linebot)



