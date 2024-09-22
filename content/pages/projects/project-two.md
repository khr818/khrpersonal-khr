---
type: ProjectLayout
title: OAR - ULTRASONIC SENSOR
colors: colors-a
date: '2024-09-22'
client: K HARSHAN RAGHAV
description: ''
---
THE ULTRASONIC CODING

```
import machine
import utime
class sonic():
     def__init__(self):
          self.trig = machine.Pin(13,machine.Pin.OUT)
          self.echo = machine.Pin(14,machine.Pin.IN,machine.Pin.PULL_DOWN)

     def dista(self):
          self.trig.off()
          utime.sleep_us(2)
          self.trig.on()
          utime.off_us(10)
          self.trig.off()

          while self.echo.value() == 0:
               st = utime.ticks_us()
          while self.echo.value() == 1:
               rt = utime.ticks_us()

          dr = rt - st
          dist = 0.0343*dr
          obj = dist/2
```

