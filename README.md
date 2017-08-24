# XDuCloudKiller
## 破解某度网盘限速
## 代码如下（也可在code.txt中下载）：

### // ==UserScript==
### // @name        XDuYunKiller
### // @namespace   http://tampermonkey.net/
### // @version      0.1
### // @description  try to take over the world!
### // @author       You
### // @match        https://pan.baidu.com/*
### // @match        http://pan.baidu.com/*
### // @run-at       document-start
### // @grant        none
### // ==/UserScript==
###    // Your code here...
###    Object.defineProperty(navigator,'platform',{get:function(){return 'XDuYunKiller';}});
