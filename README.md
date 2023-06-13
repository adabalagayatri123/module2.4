# module2.4
&lt;!DOCTYPE html&gt;
&lt;html&gt;
&lt;head&gt;
&lt;/head&gt;
&lt;body style = &quot;text-align: center; font-size: 20px;&quot;&gt;
&lt;h1&gt; Online seats reservation &lt;/h1&gt;
Enter the number of seats: &lt;input id = &quot;number&quot;&gt;
&lt;br&gt;&lt;br&gt;
&lt;button onclick = &quot;m()&quot;&gt;Pay only&lt;/button&gt;
&lt;p id = &quot;res&quot;&gt;&lt;/p&gt;
&lt;script&gt;
function ticket(num)
{
actual=num*150;
discount=(actual/10); afterdisc=actual-discount; return afterdisc
}
function m()
{
var num = document.getElementById(&quot;number&quot;).value;
var f = ticket(num);
document.getElementById(&quot;res&quot;).innerHTML=&quot;The total price is &quot; + num + &quot;
is: &quot; + f ;
}
&lt;/script&gt;
&lt;/body&gt;
&lt;/html&gt;
{
document.write(&quot;Bookings are not Allowed&quot;);
}
else
{

if (n==3)
{
t1=150-(150*(3/100));
t2=150-(150*(5/100));
t3=150-(150*(7/100));
tcost=t1+t2+t3;
document.write(&quot;For 3 tickets,you need to pay :&quot;,tcost,&quot;instead of &quot;,(150*3),&quot;with

discounts&quot;);
}
else if (n==4)
{
t1=150-(150*(3/100));
t2=150-(150*(5/100));
t3=150-(150*(7/100));
t4=150-(150*(9/100));
tcost=t1+t2+t3+t4;
document.write(&quot;For 4 tickets,you need to pay :&quot;,tcost,&quot;instead of &quot;,(150*4),&quot;with
t2=150-(150*(5/100));
t3=150-(150*(7/100));
t4=150-(150*(9/100));
t5=150-(150*(11/100));
tcost=t1+t2+t3+t4+t5;
document.write(&quot;For 5 tickets,you need to pay :&quot;,tcost,&quot;instead of &quot;,(150*5),&quot;with

discounts&quot;);
}
}
&lt;/script&gt;
&lt;/body&gt;
&lt;/html&gt;
OUTPUT:
discounts&quot;);
}
else
{
t1=150-(150*(3/100));
t2=150-(150*(5/100));
t3=150-(150*(7/100));
t4=150-(150*(9/100));
t5=150-(150*(11/100));
tcost=t1+t2+t3+t4+t5;
document.write(&quot;For 5 tickets,you need to pay :&quot;,tcost,&quot;instead of &quot;,(150*5),&quot;with

discounts&quot;);
}
}
&lt;/script&gt;
&lt;/body&gt;
&lt;/html&gt;
