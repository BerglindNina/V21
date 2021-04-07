# Verkefni 4 - Mótorar (7%) - DRÖG

Búðu til í **private** Github Repository vefsíðu (Verkefni 4) í Wiki sem inniheldur eftirfarandi:

- Svör við spurningum.
- Tengla á myndbönd af verklegum verkefnum.
  - Mundu að láta nafnið þitt og dagsetningu koma fram í myndbandinu.
- Tengla á kóðaskrár sem þú notar í verklegum verkefnum.

## 4.1. Rafþéttar (e. capasitors) (1%)

1. Kynntu þér rafþétta (e. capasitors):
   - [Circuit Playground: C is for Capacitor (myndband, 7 mín.)](https://learn.adafruit.com/circuit-playground-c-is-for-capacitor/video)
   - [Capacitors](https://www.instructables.com/lesson/Capacitors-2/)
1. Hver er munurinn á rafhlöðu og rafþétti?
  
## 4.2. Transistorar (1%)

1. Kynntu þér [Transistora](https://www.instructables.com/lesson/Transistors/).
1. Svaraðu eftirfarandi spurningum:
    1. Hvað gerir transistor?
    1. Hver er munurinn á NPN og PNP transistorum?

## 4.3. DC Motors (2%)

1. Fylgdu [Lesson 13. DC Motors](https://learn.adafruit.com/adafruit-arduino-lesson-13-dc-motors) og settu upp á Breadboard:
2. Svaraðu eftirfarandi spurningum:
    1. Afhverju þurfum við að nota PWM pinna til að stýra DC mótor?
    2. Afhverju þurfum við að nota viðnám, transistor og diode með DC mótor?
    3. Hvernig er stýrimótor (e. servo motor) ólíkur hefðbundnum DC mótor?

## 4.4. H-Bridge (1%)

1. Lestu þér til um [L293D H-Bridge](https://maker.pro/custom/projects/all-you-need-to-know-about-l293d).
1. Svaraðu eftirfarandi spurningum:
    1. Hvað er hægt að gera með L293D?
    1. Hver er munurinn á L293 or L293D?
  
## 4.5. DC motor reversing (2%)

1. Fylgdu [Lesson 15. DC Motor Reversing](https://learn.adafruit.com/adafruit-arduino-lesson-15-dc-motor-reversing) og settu upp á Breadboard.
1. Svaraðu eftirfarandi spurningum:
    1. Útskýrðu virkni eftirfarandi falls:

        ```cpp
        void setMotor(int speed, boolean reverse) {
            analogWrite(enablePin, speed);
            digitalWrite(in1Pin, !reverse);
            digitalWrite(in2Pin, reverse);
        }
        ```
    1. L293D er með tvo +V pinna (8 and 16), útskýrðu þá.

Ítarefni: [Tveir DC mótorar: speed and spinning direction of a DC motor](https://lastminuteengineers.com/l293d-dc-motor-arduino-tutorial/)