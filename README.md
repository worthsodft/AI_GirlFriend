# AI_GirlFriend
## LangChain 实现 AI 女友

* OpenAI ChatGPT

## 涉及工具
* ElevenLabs
* FlowGPT
* 阿里云 机器翻译
* 阿里 灵积模型  Sambert 语音合成

## 使用前
* 运行前，请务必先自行完善 .env文件中的参数。包括但不限于各类 API key\Secret Key等。
* 如果有疑问, 欢迎 email: 798800165@qq.com

## .env文件必要参数 list
* OPENAI_API_KEY=
* ELEVEN_LABS_API_KEY=
* ALI_API_KEY=
* ALI_CLOUD_ACCESS_KEY_ID=
* ALI_CLOUD_ACCESS_KEY_SECRET=

### 由于在国内不能直接用opennai，本版本改为使用阿里云的通义千问模型，因此无需再提供OPENAI_API_KEY
### ELEVEN_LABS网站elevenlabs.io国内可以打开，但是注册时验证码出不来，也得去墙外 
###  ALI_API_KEY是阿里云灵积模型服务的key，可到https://dashscope.console.aliyun.com/apiKey创建
###  阿里云的ACCESS_KEY_ID和ACCESS_KEY_SECRET，创建比较麻烦，AccessKey=ACCESS_KEY_ID+ACCESS_KEY_SECRET，只有在创建AccessKey的时候，才能在弹出窗里看到ACCESS_KEY_SECRET，弹窗关闭后就只能看到ACCESS_KEY_ID，而且界面上没有任何提示告诉你想看到ACCESS_KEY_SECRET，只能创建一个新的ACCESS_KEY，体验非常糟糕。好像多写一句话就会死。AccessKey需要在阿里云的控制台创建。

## 视频讲解
* B站       https://www.bilibili.com/video/BV1yH4y1S7jJ/
* youtube   https://youtu.be/v4U1DwQasiM

## 小小声明

### 本项目代码均为演示 Demo 和授课讲解用，因为不是生产环境使用且时间仓促原因，代码质量请各位包涵，如果实际应用，请务必按照代码规范完善，谢谢
### zbh备注：我在原代码基础上增加了前端显示ELEVEN_LABS的声音列表，用户可以选择用哪个声音。不过外国人说中文都显得很怪异好玩
![逐鹿机器人二维码](http://bst.yaodianma.com/h5/img/zhulubot.jpg "扫码加我微信交流")
