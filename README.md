## 环信 WebIM sdk

测试环信WebIM请访问 http://webim.easemob.com。  登录可以使用环信Demo的账号和密码（见http://www.easemob.com/demo)

环信WebIM快速入门文档请见：https://github.com/easemob/web-im/blob/master/quickstart.md

更多关于环信的开发文档请见：http://developer.easemob.com

## 增强版新增的方法

### connection.setPresenceForGroup(roomId) 

说明：用来在群聊的时候加入到房间里。如果不调用这个方法，将不能在群里发送消息。

### Easemob.im.Helper.parseTextMessageRaw 

说明：用来解析带有表情符的文本类型的消息。但是仅将表情符从文本中提取出来，放到返回的数组中，在页面渲染的时候在动态的替换成图片。
用这个方法可以在发送消息回显的时候动态替换表情图片。

### sendVideo(options)   sendVideoMessage(options)

说明：用来发送视频类型的消息。

### sendFile(options) 

说明：用来发送普通文件类型的消息。

