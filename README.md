# Timg
使用picgo上传，用于存储hexo blog中用到的图片

使用中遇到的问题
1. 因为新换了电脑，重下下载了个pic-go进行配置，就一直报下面错误

```
[PicGo INFO] Before transform 
[PicGo INFO] Transforming... Current transformer is [path] 
[PicGo INFO] Before upload 
[PicGo INFO] beforeUploadPlugins: renameFn running 
[PicGo INFO] Uploading... Current uploader is [github] 
[PicGo WARN] failed 
[PicGo ERROR] 
------Error Stack Begin------
StatusCodeError: 404 - {"message":"Not Found","documentation_url":"https://docs.github.com/rest/reference/repos#create-or-update-file-contents"}
    at new StatusCodeError (/Applications/PicGo.app/Contents/Resources/app.asar/node_modules/request-promise-core/lib/errors.js:32:15)
    at Request.plumbing.callback (/Applications/PicGo.app/Contents/Resources/app.asar/node_modules/request-promise-core/lib/plumbing.js:104:33)
    at Request.RP$callback [as _callback] (/Applications/PicGo.app/Contents/Resources/app.asar/node_modules/request-promise-core/lib/plumbing.js:46:31)
    at Request.self.callback (/Applications/PicGo.app/Contents/Resources/app.asar/node_modules/request/request.js:185:22)
    at Request.emit (events.js:200:13)
    at Request.<anonymous> (/Applications/PicGo.app/Contents/Resources/app.asar/node_modules/request/request.js:1154:10)
    at Request.emit (events.js:200:13)
    at IncomingMessage.<anonymous> (/Applications/PicGo.app/Contents/Resources/app.asar/node_modules/request/request.js:1076:12)
    at Object.onceWrapper (events.js:288:20)
    at IncomingMessage.emit (events.js:205:15)
-------Error Stack End------- 
2022-04-07 17:05:01 [PicGo ERROR] 

```
