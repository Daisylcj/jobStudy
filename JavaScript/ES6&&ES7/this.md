1.箭头函数
function name(arg1,arg2){ ... } 可以使用 (arg1,arg2)=>{...}
js普通函数
//var arr= [1,2,3];
arr.map(function(item){
    console.log(item)
    return item+1;
})
//es6箭头函数   存在的意义：1.写法简洁 2.解决es6之前函数执行中this变量问题
const arr = [1,2,3];
arr.map((item)=>{
    console.log(item)
    return item+1;
})
