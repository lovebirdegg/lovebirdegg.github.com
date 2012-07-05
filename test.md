
# JavaScript生成随机数和Math方法
<pre><code>
function fRandomBy(under, over){ 
  switch(arguments.length){ 
  case 1: return parseInt(Math.random()*under+1); 
  case 2: return parseInt(Math.random()*(over-under+1) + under); 
  default: return 0; 
} 

function randomSort(a,b){
   var tmp = Math.round(Math.random());
   // var tmp=Math.random();
   console.log(tmp);
  // if(tmp<0.5){
  //    tmp=0;
  // }else{
  //    tmp=1;
  // }
  return tmp?a.ID-b.ID:b.ID-a.ID;
}
</code>
</pre>



## Math函数 
1. Math.abs() -- 返回数字的绝对值
1. Math.acos() -- 返回数字的反余弦值 
1. Math.asin() -- 返回数字的反正弦值 
1. Math.atan() -- 返回数字的反正切值 
1. Math.atan2() -- 返回由x轴到点(x,y)的角度(以弧度为单位)
1. Math.ceil() -- 返回大于等于数字参数的最小整数(取整函数)，对数字进行上舍入 
1. Math.cos() -- 返回数字的余弦值 
1. Math.exp() -- 返回E(自然对数的底数)的x次幂(指数) 
1. Math.floor() -- 返回小于等于数字参数的最大整数，对数字进行下舍入 
1. Math.log() -- 返回数字的自然对数 Math.max() -- 返回数个数字中较大的值 
1. Math.min() -- 返回数个数字中较小的值 
1. Math.pow() -- 返回底数的指定次幂
1. Math.random() -- 返回0和1之间的伪随机数
1. Math.round() -- 返回数字最接近的整数，四舍五入
1. Math.sin() -- 返回数字的正弦值
1. Math.sqrt() -- 返回数字的平方根 
1. Math.tan() -- 返回数字的正切值 Math属性 
1. Math.E 属性 -- 返回自然对数的底数，E约等于2.718
1. Math.LN2 属性 -- 返回2的自然对数loge2，约等于0.693
1. Math.LN10 属性 -- 返回10的自然对数loge2，约等于2.302
1. Math.LOG2E 属性 -- 返回以2为底的E的对数log2e，约等于1.442
1. Math.LOG10E 属性 -- 返回以10为底的E的对数log10e，越等于0.434
1. Math.PI 属性 -- 返回圆的周长与其直径的比值(圆周率π)，约等于3.1415926
1. Math.SQRT1_2 属性 -- 返回0.5的平方根，或2的平方根除1，约等于0.707
1. Math.SQRT2 属性 -- 返回2的平方根，约等于1.414

