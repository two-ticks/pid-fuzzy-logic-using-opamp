PID Controller ( Proportional Integral Derivative Controller)
* PID Control is a feedback mechanism used in a Control System
* For PID Controller the actuating signal consists of proportional error signal added with derivative and integral of the error signal
* Therefore, actuating signal of PID Control is 
   e(t) = e(t) + Td de(t)/dt + Ki(integration)e(t) dt 
   E(t) = E(s)[ 1 + sTd + Ki / s]
* Used as a mechanical devices and in PLC 
* Proportional derivative and integral parameters can be expressed as Kp, Kd,Ki
* PID control combines advantages of proportional, derivatives and integral control acions 
* It does not perform well in case of optimal control 
* Disadvantages feedback path.
* Linear & Derivative part is noise sensitive
* P       Amplifier         Vo = (RP2/RP1).Verr
  I       Integrator        Vo = (1/RI-CI).(integration)Verr dt
  D       Differentiator    Vo = RD.CD.dVerr/dt
* It is most widely used controller in industry
                                                BLOCK DIAGRAM
* Gc(s) = Kp + sKd + Ki/s 
  G(s) = wn^2(s^2 + sKd + Ki)/ {s^2(s+2Ewn)}
* Poles at origin increases type and reduces ess(steady state error)
* One Zero nullify the effect of pole at origin on stability,While other zero increases the stability of System
------------------------------------------------------------------------------------------------------------------------------------------------
                                            Op Amp PID Controller 