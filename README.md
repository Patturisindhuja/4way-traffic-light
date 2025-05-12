g# 4way-traffic-light
int NR=2;
int NY=3;
int NG=4;
int SR=5;
int SY=6;
int SG=7;
int ER=8;
int EY=9;
int EG=10;
int WR=11;
int WY=12;
int WG=13;
void setup(){
pinMode(2, OUTPUT);
pinMode(3, OUTPUT);
pinMode(4, OUTPUT);
pinMode(5, OUTPUT);
pinMode(6, OUTPUT);
pinMode(7, OUTPUT);
pinMode(8, OUTPUT);
pinMode(9, OUTPUT);
pinMode(10, OUTPUT);
pinMode(11, OUTPUT);
pinMode(12, OUTPUT);
pinMode(13, OUTPUT);
}
void loop(){
digitalWrite(2, LOW); //North//
digitalWrite(4, HIGH);
delay(5000);
digitalWrite(4, LOW);
digitalWrite(3, HIGH);
delay(2000);
digitalWrite(3, LOW);
digitalWrite(2, HIGH);
digitalWrite(5, LOW);//south//
digitalWrite(7, HIGH);
delay(5000);
digitalWrite(7, LOW);
digitalWrite(6, HIGH);
delay(2000);
digitalWrite(6, LOW);
digitalWrite(5, HIGH);
digitalWrite(8, LOW);//East//
digitalWrite(10, HIGH);
delay(5000);
digitalWrite(10, LOW);
digitalWrite(9, HIGH);
delay(2000);
digitalWrite(9, LOW);
digitalWrite(8, HIGH);
digitalWrite(11, LOW);//West//
digitalWrite(13, HIGH);
delay(5000);
digitalWrite(13, LOW);
digitalWrite(12, HIGH);
delay(2000);
digital Write(12, LOW) 
digitalWrite(11, HIGH);
}
