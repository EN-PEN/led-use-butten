題目1:
void setup() {<br>
  // put your setup code here, to run once:<br>
  pinMode(2,INPUT);<br>
  pinMode(3,OUTPUT);<br>
  digitalWrite(3,HIGH);<br>
  
}<br>

void loop() {<br>
 
if(digitalRead)(2==0);<br>
  digitalWrite(3,LOW);<br>
}<br>

![image](https://github.com/EN-PEN/led-use-butten/blob/master/IMG20200922144210.jpg)

題目2：
int A=0;
void setup() {<br>
  // put your setup code here, to run once:<br><br>
  pinMode(2,INPUT);<br>
  pinMode(3,OUTPUT);<br>
  digitalWrite(3,HIGH);<br>
  
}<br>

void loop() {<br>
 

if(digitalRead(2) == 0);<br>
{<br>
   while(digitalRead(2) == 0);<br>
   A = (A+1)%2;<br>
   
}<br>
switch(A)<br>
{case 1:<br>
 {digitalWrite(3,LOW);}<br>
 case 0:<br>
  {digitalWrite(3,HIGH);}<br>
}<br>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        
}<br>
![image](https://github.com/EN-PEN/led-use-butten/blob/master/IMG20200922144623.jpg)
