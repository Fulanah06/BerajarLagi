# BerajarLagi
Modul Sensor LDR
--
#include "DHT.h"
#define DHTPIN 5
#define DHTTYPE DHT22

DHT dht(DHTPIN, DHTTYPE);

void setup() {
  // put your setup code here, to run once:
  Serial.begin(9600);
  Serial.println(F("DHT22 test!"));

  dht.begin();

}

void loop() {
  // put your main code here, to run repeatedly:
  float h = dht.readHumidity(); //pembacaan kelembaban dalam %
  float t = dht.readTemperature(); //pembacaan suhu dala celcius
  float f = dht.readTemperature(true); //pembacaan suhu dalam Fahrenheit

  if(isnan(h) || isnan(t) || isnan(f)){
    Serial.println(F("Gaga membaca dari DHT sensor!"));
    return;
  }

  Serial.print(F("Humadity: "));
  Serial.print(h);
  Serial.print(F("% Temperature: "));
  Serial.print(t);
  Serial.print(F("°C "));
  Serial.print(f);
  Serial.println(" °F");
}
