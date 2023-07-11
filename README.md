int LED=12;
int PIR=13;
void setup()
{
  pinMode(13, INPUT);
  pinMode(12, OUTPUT);
}

void loop()
{
  digitalWrite(12, LOW);
  int read=digitalRead(13);
  if(read == HIGH)
  {
    digitalWrite(12,HIGH);
    delay(1000); 
  }
  delay(1000); 

![image](https://github.com/saddamsssssssss/PIR_sensor_with_led/assets/139205268/6dcff83b-c2b2-4fb9-9465-14fc2464d0e9)
