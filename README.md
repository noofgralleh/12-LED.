# 12-LED.
int leds[] = {2,3,4,5,6,7,8,9,10,11,12,13}; // الأرجل الموصلة بالليدات

void setup() {
  for (int i=0; i<12; i++) {
    pinMode(leds[i], OUTPUT);  // تعريف الأرجل كمخارج
  }
}

void loop() {
  for (int i=0; i<12; i++) {
    digitalWrite(leds[i], HIGH); // تشغيل كل الليدات
  }
  delay(1000)
}
