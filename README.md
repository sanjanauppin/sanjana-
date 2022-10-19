# sanjana-
/to read the status of an LDR for a set point value 200 if, reading exceeds 200 turn on an LED connected to digital 13, else turn off/
void setup()
{
pinMode(A5,INPUT);
pinMode(13,OUTPUT);
}
void loop()
{
int x=(anlogRead(A5);
if (x>200)
digitalWrite(13,HIGH);
else
(digitalWrite(13,LOW);
}
