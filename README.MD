一个调用网易云音乐API的node模块
![](http://binaryify.github.io/images/api.jpg)
# start
```
npm install NeteaseCloudMusicApi
```
# usage

```js
var api=require('NeteaseCloudMusicApi').api
api.search('年度之歌',function(data){
    console.log(data)
}
```
or
```js
import {api} from 'NeteaseCloudMusicApi'
api.search('年度之歌',(data)=>{
    console.log(data)
}
```

# api
## search
 ```js
api.search(name:String,[callback:function,limit:Nnumber default:3, offset:Number default:0])
 ```

## lrc
 ```js
api.lrc(id:Number,[callback:function,lv:Number default:-1])
 ```

## song
 ```js
api.song(id:Number,[callback:function])
 ```

[github](https://github.com/Binaryify/NeteaseCloudMusicApi)

[npm](https://www.npmjs.com/package/NeteaseCloudMusicApi)