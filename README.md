# CODIGO-PROGRAMACAO
tinkercad update<BR>
const int btn1 = 0;<BR>
const int btn2 = 1;<BR>
const int btn3 = 2;<BR>
<BR>
int cond = 0;<BR>
int cond1 = 0;<BR>
int cond2 = 0;<BR>
<BR><BR>
void setup()<BR>
{<BR>
  pinMode(13, OUTPUT);<BR>
  pinMode(12, OUTPUT);<BR>
  pinMode(11, OUTPUT);<BR>
  pinMode(10, OUTPUT);<BR>
  pinMode(btn1, INPUT);<BR>
  <BR>
}<BR>
<BR>
void loop()<BR>
{<BR>
  <BR>
  cond  = digitalRead(btn1);<BR>
  cond1  = digitalRead(btn2);<BR>
  cond2  = digitalRead(btn3);<BR>
  <BR>
  if(cond == HIGH ) {  <BR>
  <BR>
  digitalWrite(13, HIGH);<BR>
  digitalWrite(12, HIGH);<BR>
  digitalWrite(11, LOW);<BR>
  digitalWrite(10, LOW);<BR>
  delay(300);<BR>
  digitalWrite(13, LOW);<BR>
  digitalWrite(12, LOW);<BR>
  digitalWrite(11, LOW);<BR>
  digitalWrite(10, LOW);<BR>
  delay(300);<BR>
    <BR>
  }<BR>
  <BR>
  if(cond == LOW ) {  <BR>
  <BR>
  digitalWrite(13, LOW);<BR>
  digitalWrite(12, LOW);<BR>
  digitalWrite(11, LOW);<BR>
  digitalWrite(10, LOW);<BR>
  delay(100);<BR>
    <BR>
  }<BR>

  <BR>
  if(cond1 == HIGH ) {  <BR>
  <BR>
  digitalWrite(13, LOW);<BR>
  digitalWrite(12, LOW);<BR>
  digitalWrite(11, HIGH);<BR>
  digitalWrite(10, HIGH);<BR>
  delay(300);<BR>
  digitalWrite(13, LOW);<BR>
  digitalWrite(12, LOW);<BR>
  digitalWrite(11, LOW);<BR>
  digitalWrite(10, LOW);<BR>
  delay(300);  <BR>
  }<BR>
  <BR>
  if(cond1 == LOW ) {  <BR>
  <BR>
  digitalWrite(13, LOW);<BR>
  digitalWrite(12, LOW);<BR>
  digitalWrite(11, LOW);<BR>
  digitalWrite(10, LOW);<BR>
  delay(100);<BR>
    <BR>
  }<BR>
  <BR>
  
  if(cond2 == HIGH ) {  <BR>
  <BR>
  digitalWrite(13, HIGH);<BR>
  digitalWrite(12, HIGH);<BR>
  digitalWrite(11, HIGH);<BR>
  digitalWrite(10, HIGH);<BR>
  delay(300);<BR>
  digitalWrite(13, LOW);<BR>
  digitalWrite(12, LOW);<BR>
  digitalWrite(11, LOW);<BR>
  digitalWrite(10, LOW);<BR>
  delay(300);  <BR>
  }<BR>
  <BR>
  if(cond2 == LOW ) {  <BR>
  <BR>
  digitalWrite(13, LOW);<BR>
  digitalWrite(12, LOW);<BR>
  digitalWrite(11, LOW);<BR>
  digitalWrite(10, LOW);<BR>
  delay(100);<BR>
    <BR>
  }<BR>
  <BR>
  <BR>
     <BR>
}<BR>
