# astrbot_plugin_sum

AstrBot 插件
ChatGPT on WeChat项目插件, 使用jina reader和ChatGPT总结网页链接内容

支持总结公众号、小红书、csdn等分享卡片链接(有的卡片链接会触发验证，一般直链没有此问题)
ChatGPT on WeChat项目插件使用jina reader和ChatGPT总结网页链接内容，支持总结公众号、小红书、知乎等分享卡片链接

#功能
支持自动总结微信文章
支持手动触发总结
支持总结后追问文章内容
支持群聊和私聊场景
支持黑名单群组配置
使用方法
私聊：

#直接发送文章链接或分享卡片，会自动总结
总结完成后5分钟内可发送"问xxx"追问文章内容

#群聊：
当auto_sum=true时：
非黑名单群组：自动总结分享卡片和链接
黑名单群组：需要发送"总结"触发总结
当auto_sum=false时：
所有群组都需要发送"总结"触发总结
分享卡片总结：
发送卡片后，发送"总结"触发
URL总结方式灵活，支持：
"总结 链接"
"总结链接"
"链接总结"
总结完成后5分钟内可发送"问xxx"追问文章内容
# 支持

[帮助文档](https://astrbot.app)
