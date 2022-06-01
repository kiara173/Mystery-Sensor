# Biegesensor 4.5" 
---

![](https://www.distrelec.at/Web/WebShopImages/landscape_large/6-/01/Sparkfun-SEN-08606-30152836-01.jpg)

---

 Der Biegesensor ermöglicht es, Verbiegungen zu erkennen und deren Ausmaß zu bestimmen. Es handelt sich um eine schmale Leiste mit 11 cm Länge und 6,3 mm Breite. Wird der Fühler des Sensors gebogen (Aufrollbewegung mit den Metallplättchen nach außen), ändert sich der elektrische Widerstand (kΩ) zwischen den Anschlusspins. Durch eine Widerstandsmessung kann folglich auf die Biegung des Fühlers geschlossen werden.

Der Sensor besitzt am Ende ein weiches Verbindungsteil mit zwei Lötsteckern. Das Maß an Flexibilität des Sensors kann mithilfe eines Arduino-Boards gemessen werden. Da ein Arduino nicht direkt eine Widerstandsänderung messen kann, wird hier eine Messverstärkerschaltung benötigt. Eine Möglichkeit bietet hierfür ein sogenannter Spannungsteiler, bei dem der Sensor in Reihe mit einem zweiten Widerstand zwischen Versorgungsspannung und Masse gelegt wird. Der Arduino kann schließlich die Widerstandsänderung als Spannungsänderung über einen analogen Pin erfassen.

Der Flexsensor darf nur im aktiven Bereich gebogen werden. Wird er allzu oft an der Basis verbogen, so könnte das Gerät Schaden nehmen.

Man könnte einen Sensorhandschuh für die Steuerung von Videospielen oder als interaktives Musikinstrument entwickeln. Hier kann die Beugung der Finger erfasst werden. Oder man könnt einen Sevomotor verbinden. Ein Servo ist ein kleines Gerät, das eine Abtriebswelle hat. Sie können kleine Servomotoren direkt an einen Arduino anschließen und die Wellenposition sehr genau steuern, indem dem Servo ein codiertes Signal gesendet wird. In der Praxis werden Servomotoren verwendet, um die Position von Objekten zu steuern, Objekte zu drehen, Beine, Arme oder Hände von Robotern zu bewegen oder Sensoren mit hoher Präzision bewegen zu können. 


## Mit Arduino verbinden 
---
![](https://cdn.sparkfun.com/r/600-600/assets/learn_tutorials/3/1/0/Arduino_circuit_09_02-01.png) ![](https://cdn.sparkfun.com/r/600-600/assets/learn_tutorials/3/1/0/SIK_Arduino_Uno_exp_09_01.jpg)
---

Der Sensor wird über einen Widerstand (kΩ richtet sich nach der maximalen Widerstandes der möglichen Biegung) mit dem Arduino verbunden. (5V) Die Verbindung zwischen Sensor und Widerstand ist mit dem Analog In Pin A0 des Arduinos verbunden. Zudem folgt eine Verbindung des anderen Pins des Sensors mit dem Ground des Arduinos.


### Quelle :
https://www.generationrobots.com/de/401948-biegesensor-22.html
https://learn.sparkfun.com/tutorials/flex-sensor-hookup-guide
https://www.makeyourschool.de/material/biegesensor/
https://www.exp-tech.de/blog/arduino-tutorial-servo