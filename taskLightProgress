#define LED_PIN 5
#define POTENTIOMETER_PIN A2

void setup()
{
  pinMode(LED_PIN, OUTPUT);
}

void loop()
{
  int potentiometerValue = analogRead(POTENTIOMETER_PIN);
  int brightness = map(potentiometerValue, 0, 1023, 0, 255);
  analogWrite(LED_PIN, brightness);
  Serial.println(potentiometerValue);
  delay(100);
}
