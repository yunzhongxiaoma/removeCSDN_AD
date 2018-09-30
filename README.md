# removeCSDN_AD
去除csdn上的百度推广广告，因为总是吸引我的注意力，让我心烦，所以想去掉  
(并没有经过多台电脑测试，目前就自己能用)  
1.打开chome扩展程序  
2.把test.user.js拖到扩展程序  
3.刷新网页  

代码  
var child=document.getElementById("cpro_u2734133");  
child.parentNode.removeChild(child);
