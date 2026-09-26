const int RED    = 10;
const int YELLOW = 9;
const int GREEN  = 8;

void setup() {
  pinMode(RED, OUTPUT);
  pinMode(YELLOW, OUTPUT);
  pinMode(GREEN, OUTPUT);

}
void setLights(bool r, bool y, bool g) {
  digitalWrite(RED, r);
  digitalWrite(YELLOW, y);
  digitalWrite(GREEN, g);
}
void loop() {
  setLights(1, 0, 0);   // red only
  delay(5000);

  setLights(0, 1, 0);   // yellow
  delay(1500);

  setLights(0, 0, 1);   // green only
  delay(5000);

  //setLights(0, 1, 0);   // yellow only
  //delay(2000);

}
