# LittlePrograme demo 
demo code for littleprograme.
操作步骤：
+ 打开微信开发者工具
+ 添加本地项目(不需要关联appID)
+ 启动

`app.json`查看:
```javascript
{
  "pages":[
    "pages/index/index",//page route
    "pages/logs/logs" //page route
  ],
  "window":{ //settings for window
    "backgroundTextStyle":"light",
    "navigationBarBackgroundColor": "#fff",
    "navigationBarTitleText": "WeChat Demo for Goods",
    "navigationBarTextStyle":"black"
  },
  "tabBar": {//define tab bar in bottom
    "list": [
      {
        "pagePath": "pages/index/index",
        "text": "首页"
      },
      {
        "pagePath": "pages/logs/logs",
        "text": "好券"
      },
      {
        "pagePath": "pages/logs/logs",
        "text": "清单"
      },
      {
        "pagePath": "pages/logs/logs",
        "text": "好物"
      },
      {
        "pagePath": "pages/logs/logs",
        "text": "我"
      }
    ]
  }
}
```
