#tinatin kopadze
##contact
-Email: [tiko.kopadze777@gmail.com](mailto:tiko.kopadze777@gmail.com)
-Linkedin: [tinatin kopadze](https://www.linkedin.com/in/%E1%83%97%E1%83%98%E1%83%9C%E1%83%90%E1%83%97%E1%83%98%E1%83%9C-%E1%83%99%E1%83%9D%E1%83%9E%E1%83%90%E1%83%AB%E1%83%94-93428a113/)   
-Tel: 571733234
-Facebook: [tiko kopadze](https://www.facebook.com/profile.php?id=100001954727912)
##summary:
*Meticulous web developer with over 2 years of front end experience and passion for responsive website design and a firm believer in the mobile-first approach. W3C certified. Implemented new responsive website approach which increased mobile traffic by 20%.*
##skills:
-Microsoft office
-JavaScript
-Html
-Css
##code example: 
    ` // Constants
var RADIUS = 20;
var DELAY = 40;
var count = 0 ; 
var i = 0;
function start(){
   setTimer(draw, DELAY);
}
function draw(){
       if(count%2 == 0 ){
       var color = Color.red;
   }else{
     var color = Color.black;
}
    var centerX = RADIUS + 2*RADIUS * count;
    var centerY = RADIUS +2*RADIUS*i  ;
    var radius = RADIUS ;
    drawCircle( radius, color, centerX, centerY);
    count++; 
     if (count == getWidth()/2/RADIUS){
         i++;
         count=0;
     }
}
function row(centery){
    
     if(count%2 == 0 ){
       var color = Color.red;
   }else{
     var color = Color.black;
}
    var centerX = RADIUS + 2*RADIUS * count;
    var centerY = centery +2*centery*i  ;
    var radius = RADIUS ;
    drawCircle( radius, color, centerX, centerY);
    count++;
}

function drawCircle(radius, color, x, y){
    var circle = new Circle(radius);
    circle.setColor(color);
    circle.setPosition(x, y);
    add(circle);
} `
##experience:
-bitcamp stage 1 
-bitcamp stage 2
##education:
-2013-2019:Tsmu-Medical Doctor
-2020-present: Evex Hospitals-Endocrinology Residency
##English:B2