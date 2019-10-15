# weixin-sdk-js

[![Build Status](https://img.shields.io/npm/l/weixin-sdk-js)](https://www.npmjs.com/package/weixin-sdk-js)
[![Build Status](https://img.shields.io/npm/v/weixin-sdk-js)](https://www.npmjs.com/package/weixin-sdk-js)
[![Build Status](https://img.shields.io/npm/dm/weixin-sdk-js)](https://www.npmjs.com/package/weixin-sdk-js)

微信官方 Js SDK for commonjs and ts  
Wechat official Js SDK for commonjs and ts

## breif
将微信官方 Js SDK 封装，便于 commonjs 与 ts 环境直接使用  
Encapsulate wechat official Js SDK for easy use of commonjs and ts 

## original js
[微信官方 Js sdk v1.4.0](http://res.wx.qq.com/open/js/jweixin-1.4.0.js)  
[Wechat official Js sdk v1.4.0](http://res.wx.qq.com/open/js/jweixin-1.4.0.js)
## usage
install  
`npm i -S weixin-sdk-js`

for commonjs  
`const wx = require('weixin-sdk-js');`

for ts  
```
import wx from 'weixin-sdk-js';
```
> Commonly, it is done. The sdk will work as long as be packaged to broswer static source. 
> In case of something wrong, try `/// <reference path="<path>" />` with the import statement  
> `<path>` is the relative path to the containing file, if root files not set.  
> **For more about [`path`](http://www.typescriptlang.org/docs/handbook/triple-slash-directives.html#preprocessing-input-files)**  
> Or just renameand copy node_module/weixin-sdk-js/dist/index.d.ts anywhere you want. 

## api
[微信官方 API doc](https://developers.weixin.qq.com/doc/offiaccount/OA_Web_Apps/JS-SDK)  
[Wechat official API doc](https://developers.weixin.qq.com/doc/offiaccount/OA_Web_Apps/JS-SDK)

## link
Looking for next stpes?  
[分享给朋友，分享至朋友圈](https://github.com/wind2esg/weixin-sharelink)  
[Share to friend and share to timeline](https://github.com/wind2esg/weixin-sharelink)