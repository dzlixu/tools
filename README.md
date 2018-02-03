# tools
做了一年半的前端，发现很多东西没有积累，实际在开发过程中实现的一些组件，可以剥离页面，独立出来便于下一次的复用。所以决定常见的组件，自己实现一遍，一来练手，而来如果工作中需要，可以少做修改便能用。工作中jquery用的比较多，上手先实现jquery版本，最近咋看vue,试着实现vue的版本。
# jquery

## alert
用法：
引入js 和css 代码，引入jquery 。
```
$.(opts,callback);
opt={
    title:"提示标题",
    content:"提示内容"
}

function callback(data){
       data={
           res:"yes/no"
       }
}
```



