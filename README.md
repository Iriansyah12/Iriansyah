
<html>

<head><title>Hai</title>

<!-- Created By Ryan -->

<script>alert ('HAI!!')


alert ('SELAMAT ULANG TAHUN JULIKE')</script>

<script language="JavaScript"> 

 

function tb5_makeArray(n){

 this.length = n;

 return this.length;

}

 

tb5_messages = new tb5_makeArray(7);

tb5_messages[6] = "happy birtday";

tb5_rptType = 'infinite';

tb5_rptNbr = 20;

tb5_speed = 30;

tb5_delay = 2000;

var tb5_counter=2;

var tb5_currMsg=0;

var tb5_stsmsg="";

function tb5_shuffle(arr){

var k;

for (i=0; i<arr.length; i++){

 k = Math.round(Math.random() * (arr.length - i - 1)) + i;

 temp = arr[i];arr[i]=arr[k];arr[k]=temp;

}

return arr;

}

tb5_arr = new tb5_makeArray(tb5_messages[tb5_currMsg].length);

tb5_sts = new tb5_makeArray(tb5_messages[tb5_currMsg].length);

for (var i=0; i<tb5_messages[tb5_currMsg].length; i++){

 tb5_arr[i] = i;

 tb5_sts[i] = "_";

}

tb5_arr = tb5_shuffle(tb5_arr);

function tb5_init(n){

var k;

if (n == tb5_arr.length){

 if (tb5_currMsg == tb5_messages.length-1){

 if ((tb5_rptType == 'finite') && (tb5_counter==tb5_rptNbr)){

 clearTimeout(tb5_timerID);

 return;

 }

 tb5_counter++;

 tb5_currMsg=0;

 }

 else{

 tb5_currMsg++;

 }

 n=0;

 tb5_arr = new tb5_makeArray(tb5_messages[tb5_currMsg].length);

 tb5_sts = new tb5_makeArray(tb5_messages[tb5_currMsg].length);

 for (var i=0; i<tb5_messages[tb5_currMsg].length; i++){

 tb5_arr[i] = i;

 tb5_sts[i] = "_";

 }

 tb5_arr = tb5_shuffle(tb5_arr);

 tb5_sp=tb5_delay;

}

else{

 tb5_sp=tb5_speed;

 k = tb5_arr[n];

 tb5_sts[k] = tb5_messages[tb5_currMsg].charAt(k);

 tb5_stsmsg = "";

 for (var i=0; i<tb5_sts.length; i++)

 tb5_stsmsg += tb5_sts[i];

 document.title = tb5_stsmsg;

 n++;

 }

 tb5_timerID = setTimeout("tb5_init("+n+")", tb5_sp);

}

function tb5_randomizetitle(){

 tb5_init(0);

}

tb5_randomizetitle();

 

</script>

</br><center><img src="juli1.jpg"alt="Lolykuu" width="30% atau xpx" height="50% atau ypx"/></a> 

</head>

<body BGCOLOR="black">

<center><center>

<br><font size="6"><font color="red" face="courier new">Created by:RYAN</font>

<br><br><!-- Created By SYL -->

<font size="5"><font color="white" face="courier new">Mungkin sa tra bisa memberikan kado yang istimewa,</font>

<br><font size="5"><font color="white" face="courier new">Selamat ulang tahun!</font>

<br><font size="5"><font color="white" face="courier new">Semoga ko senantiasa diberi kemudahan oleh tuhan dalam menjalani setiap urusan dan selalu menjadi pribadi yang lebih baik dari sebelumnya</font>

<br><font size="5"><font color="white" face="courier new">tolong di jawab ucapan terima kasihnya di bawah ini hehe</font>

<br><a href="https://api.whatsapp.com/send?phone=6282398101387&text=Ya%20aku%20Mau%20Terima"><input type="button" value="Yes" onclick="alert('happy birtday');" style="font size="5"></a><><><><a href="https://api.whatsapp.com/send?phone=6282398101387&text=Maaf%20Aku%20NggaBisa%20Terima">

<br><br><br><hr color="red"><!-- Created By SYL -->

<font size="4"><font color="white" face="courier new">("Thanks:")</font>

</body>

<style type="text/css">

body, a:hover {cursor: url(http://cur.cursors-4u.net/cursors/cur-9/cur862.ani), url(http://cur.cursors-4u.net/cursors/cur-9/cur862.png), progress !important; 

</style>







<style type="text/css">



#outerCircleText {



font-style: courier new;

font-weight: bold;

font-family: 'comic sans ms', verdana, arial;

color: white;



position: absolute;top: 0;left: 0;z-index: 3000;cursor: default;}

#outerCircleText div {position: relative;}

#outerCircleText div div {position: absolute;top: 0;left: 0;text-align: center;}



</style>

<script type="text/javascript">





;(function(){





var msg = " HBD ";



var size = 15;





var circleY = 0.75; var circleX = 2;



var letter_spacing = 4;



var diameter = 10;





var rotation = 0.2;



var speed = 0.3;







if (!window.addEventListener && !window.attachEvent || !document.createElement) return;



msg = msg.split('');

var n = msg.length - 1, a = Math.round(size * diameter * 0.208333), currStep = 20,

ymouse = a * circleY + 20, xmouse = a * circleX + 20, y = [], x = [], Y = [], X = [],

o = document.createElement('div'), oi = document.createElement('div'),

b = document.compatMode && document.compatMode != "BackCompat"? document.documentElement : document.body,



mouse = function(e){

 e = e || window.event;

 ymouse = !isNaN(e.pageY)? e.pageY : e.clientY; // y-position

 xmouse = !isNaN(e.pageX)? e.pageX : e.clientX; // x-position

},



makecircle = function(){ // rotation/positioning

 if(init.nopy){

  o.style.top = (b || document.body).scrollTop + 'px';

  o.style.left = (b || document.body).scrollLeft + 'px';

 };

 currStep -= rotation;

 for (var d, i = n; i > -1; --i){ // makes the circle

  d = document.getElementById('iemsg' + i).style;

  d.top = Math.round(y[i] + a * Math.sin((currStep + i) / letter_spacing) * circleY - 15) + 'px';

  d.left = Math.round(x[i] + a * Math.cos((currStep + i) / letter_spacing) * circleX) + 'px';

 };

},



drag = function(){ // makes the resistance

 y[0] = Y[0] += (ymouse - Y[0]) * speed;

 x[0] = X[0] += (xmouse - 20 - X[0]) * speed;

 for (var i = n; i > 0; --i){

  y[i] = Y[i] += (y[i-1] - Y[i]) * speed;

  x[i] = X[i] += (x[i-1] - X[i]) * speed;

 };

 makecircle();

},



init = function(){ 

 if(!isNaN(window.pageYOffset)){

  ymouse += window.pageYOffset;

  xmouse += window.pageXOffset;

 } else init.nopy = true;

 for (var d, i = n; i > -1; --i){

  d = document.createElement('div'); d.id = 'iemsg' + i;

  d.style.height = d.style.width = a + 'px';

  d.appendChild(document.createTextNode(msg[i]));

  oi.appendChild(d); y[i] = x[i] = Y[i] = X[i] = 0;

 };

 o.appendChild(oi); document.body.appendChild(o);

 setInterval(drag, 25);

},



ascroll = function(){

 ymouse += window.pageYOffset;

 xmouse += window.pageXOffset;

 window.removeEventListener('scroll', ascroll, false);

};



o.id = 'outerCircleText'; o.style.fontSize = size + 'px';



if (window.addEventListener){

 window.addEventListener('load', init, false);



 document.addEventListener('mouseover', mouse, false);

 document.addEventListener('mousemove', mouse, false);

  if (/Apple/.test(navigator.vendor))

   window.addEventListener('scroll', ascroll, false);

}

else if (window.attachEvent){

 window.attachEvent('onload', init);

 document.attachEvent('onmousemove', mouse);

};



})();



</script>

<!-- copyright@2k21 by SYL --> <!-- Tolong jangan hapus copyright nya yah :v tolong hargai karya saya SYL -->

<iframe width="0%" height="0" scrolling="no" frameborder="no" allow="autoplay" src="https://soundcloud.com/user442216899/jamrud-selamat-ulang-tahun?utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing"></iframe>

</html>
