題目1:
void setup() {
  // put your setup code here, to run once:
  pinMode(2,INPUT);
  pinMode(3,OUTPUT);
  digitalWrite(3,HIGH);
  
}

void loop() {
 
if(digitalRead)(2==0);
  digitalWrite(3,LOW);
}

![image](https://github.com/EN-PEN/led-use-butten/blob/master/IMG20200922144210.jpg)

題目2：
int A=0;
void setup() {
  // put your setup code here, to run once:
  pinMode(2,INPUT);
  pinMode(3,OUTPUT);
  digitalWrite(3,HIGH);
  
}

void loop() {
 

if(digitalRead(2) == 0);
{
   while(digitalRead(2) == 0);
   A = (A+1)%2;
   
}
switch(A)
{case 1:
 {digitalWrite(3,LOW);}
 case 0:
  {digitalWrite(3,HIGH);}
}                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        
}
![image]()
