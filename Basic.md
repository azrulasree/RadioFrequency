# RadioFrequency (RF)
Radio frequency Signal - Oscillation

![image](https://user-images.githubusercontent.com/83261924/212222648-fd40ec7d-a83d-441c-be3c-36fa75c2b23f.png)

Frequency (f) -Hertz
Number of cycle happen per second = Hertz(Hz)

## RF Spectrum
![image](https://user-images.githubusercontent.com/83261924/212222839-92757af6-f509-4971-85d9-a88b457eb32d.png)

2.4Ghz
5Ghz

XmTR - Transmitter --> gives out radio f
RCVR - Receriver --> receive radio f
186K miles per second(mps)
300M mps --> speed of light

Attenuation - Obstruction affect signal

![image](https://user-images.githubusercontent.com/83261924/212223231-00a6603f-2d7c-43d2-a40f-8a9a8fafb70b.png)

* building
* mountains
* etc

## λ - wavelength (meters)
λ - length of each frequency

![image](https://user-images.githubusercontent.com/83261924/212385649-a43ad4ea-aaea-4660-970f-50a14b0744e2.png)

> inverse relationship between wavelength and frequency
```High frequency = low wavelength```

## RF Characteristics
* Attenuation - signal become slow as travel.
* Amplitude - height of signal  --> higher mean more power
* Phase: 
In-Phase = similar frequency --> additive signal strength
Out-Phase = different frequency --> reduces signal strength

![image](https://user-images.githubusercontent.com/83261924/212386662-c8c00419-eea6-4ba1-8578-478b385e1cdb.png)

## RF Behavior
Propagation = how signal travel accross medium

* Absorption = signal loss as pass through objects
* Reflection = signal bounch off object that are larger than its λ --> create multipath = phase

![image](https://user-images.githubusercontent.com/83261924/212502381-667dc28a-4d4e-4ba8-8284-8a95a7a3c951.png)
* Scattering = signal bounch off object that are smaller than its λ= like disco ball
* Refraction = direction changes when go to difference density.

![image](https://user-images.githubusercontent.com/83261924/212502451-244adead-8221-432f-aa3a-b2063cde085c.png)
* Diffraction = how data travel around the object

![image](https://user-images.githubusercontent.com/83261924/212502467-cfdb7fd7-015a-4a76-89c5-7c586bc42b28.png)
* 2.4GHz coverage better than 5GHz (lower f better )
* Free Space Path Loss(FSPL)
Free Range Comms. 
> signal double in distance = 75% loss strength

## Multipath
* Delay Spread
cause by reflection. delay in nanosec = cause out-phase.

![image](https://user-images.githubusercontent.com/83261924/212502919-e67e7649-d877-4b4d-afe4-a2b5cb91244d.png)

signal 180 --> nulling
 
 Data corruption
 signal arrive -> RCVR -> modulation technique -> convert signal to bit
 out-phase signal come --> convert different bit -> cause ISI 
 > Inter-Symbol Interference (ISI) cause data corruption
 CRC is required.(file transfer, ect)
 CRC neglected in VIOP
 
 ### how to deal with multipath
 antenna diversity (multiple antenna) --> receive only good signal. intelligence choice of signal.
Reduce power. if signal use 50w. dont use 100w.
MIMO - Multiple Input Multiple Output
Maximum Ratio Combining (MRC) = combine signal strength for better signal.

## RF Gain and VSWR
active --> amplifier (AmP)
passive --> antenna. focusing signal on 1 side of antenna

> Spectrum Analyzer = wireless site surver, troubleshoot

### Voltage Standing Wave Ration (VSWR)
cause back pressure

![image](https://user-images.githubusercontent.com/83261924/212503216-8254414a-131e-4286-803e-b57d76d951c5.png)
![image](https://user-images.githubusercontent.com/83261924/212503226-63ed0ba4-a88f-41e1-8229-7bb658a461e7.png)

impedence --> Ohm, Ω
> Impedance matching. all material have same impedance.50Ω

Ratio between: highest : lowest

![image](https://user-images.githubusercontent.com/83261924/212503294-0cd8c3f2-3123-4820-878c-ee022bfe9019.png)

Better impedence to have best VSWR
 
### Return Loss
return loss = difference between power sent and replected back
> Higher % return loss. the better




 




