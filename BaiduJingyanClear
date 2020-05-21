// ==UserScript==
// @name         百度经验纯净版
// @namespace    https://saltzmanalaric.github.io
// @version      1.0.0
// @description  BaiduJingyanClear
// @author       Saltzman
// @license      MIT
// @date         2020-05-21
// @modified     2020-05-21
// @match        *://jingyan.baidu.com/*/*
// @run-at       document-end
// @noframes
// @icon         https://saltzmanalaric.github.io/favicon.ico
// ==/UserScript==

(function() {
    'use strict';

    var children = [
        document.getElementsByClassName("clearfix feeds-video-box")[0],
        document.getElementsByClassName("f-light feeds-video-one-view")[0],
        document.getElementsByClassName("wgt-income-money")[0],
         document.getElementById("fresh-share-exp-e"),
        document.getElementById("w-share"),
        document.getElementById("w-favor"),
        document.getElementById("wgt-like")
    ];
    for (var child of children) {
        if (child) {
            child.parentNode.removeChild(child);
        }
    }

})();
