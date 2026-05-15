// Arduino_Projects

#include <LiquidCrystal.h>

// RS, E, D4, D5, D6, D7
LiquidCrystal lcd(12, 11, 5, 4, 3, 2);

void setup() {
  lcd.begin(16, 2);

  // First line
  lcd.setCursor(0, 0);
  lcd.print("Luna");

  // Second line
  lcd.setCursor(0, 1);
  lcd.print("Irinjalakuda");
}

void loop() {
}
