---
type: ProjectLayout
title: OAR - ROBOT MOTOR
colors: colors-a
date: '2021-10-15'
client: Awesome client
description: 'THIS IS THE BASIC CODING OF MY ROBOT, CONTROLLING THE MOTOR OF THE ROBOT'
---
# ROBOMOTOR CODE AS PER ME

```
import machine
import utime
```

```
class RMC():
def 
```

```
    self.lmf = machine.Pin(18,machine.Pin.OUT)
    self.lmr= machine.Pin(19,machine.Pin.OUT)

    self.rme = machine.Pin(25,machine.Pin.OUT)
    self.rme.on()
    self.rmf = machine.Pin(22,machine.Pin.OUT)
    self.rmr= machine.Pin(23,machine.Pin.OUT)
            
def fwd(self):
    print("FORWARD")
    self.rmf.on()
    self.lmf.on()
    self.rmr.off()
    self.lmr.off()

def bwd(self):
    print("REVERSE")
    self.rmr.on()
    self.lmr.on()
    self.rmf.off()
    self.lmf.off()
    
def r(self):
    print("RIGHT")
    self.rmf.off()
    self.lmf.on()
    self.rmr.off()
    self.lmr.off()
    
def l(self):
    print("LEFT")
    self.rmf.on()
    self.lmf.off()
    self.rmr.off()
    lmr.off()

def dr(self):
    print("RIGHT DRIFT")
    self.rmf.off()
    self.lmf.on()
    self.rmr.on()
    self.lmr.off()
    
def dl(self):
    print("LEFT DRIFT")
    self.rmf.on()
    self.lmf.off()
    self.rmr.off()
    self.lmr.on()
    
def of(self):
    print("OFF")
    self.rmf.off()
    self.lmf.off()
    self.rmr.off()
    self.lmr.off()
    
POWERED BY 
```

