README
===========================
这个项目是公司目前用到的spa项目目录里面有自己负责开发的几个小游戏。

****
###　　　　　　　　　　　　Author:川少
###　　　　　　　　　 E-mail:905603055@qq.com

===========================

##项目结构
* spa                     //编译后打包的目录
* src                     //开发目录
    * hbs                 //模板引擎采用handlebars
    * js                  //js目录
        * build           //打包文件
        * commons         //开发组件，小插件
        * eui             //eui框架
        * lib             //插件目录
        * spa             //js源码目录
    * json                //数据json
    * less                //less css文件
    
===========================

###2048
hbs 源码文件在 src > hbs > spa > wx-game-2048.hbs
js  源码文件在 src > js  > spa > wx-game-2048.js
json源码文件在 src > json> spa > wx-game-2048.json
less源码文件在 src > less> spa > wx-game-2048.less
最终会打包成 spa目录里面的wx-game-2048.html文件

===========================

###吃月饼有戏
hbs 源码文件在 src > hbs > spa > moonCake.hbs
js  源码文件在 src > js  > spa > moonCake.js && moonCake
json源码文件在 src > json> spa > moonCake.json
less源码文件在 src > less> spa > moonCake.less
最终会打包成 spa目录里面的moonCake.html文件
