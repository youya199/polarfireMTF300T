# Problems Log 
## 12092023
1. software install  
Describe: cannot synthesize because lack of VCRUNTIME140_1.dll
![image](https://github.com/youya199/polarfireMTF300T/assets/94166804/8d890313-a775-4e20-913d-e0bfa622e30b)  
Solve: download and install c++ Redistribution on [official website](https://learn.microsoft.com/de-DE/cpp/windows/latest-supported-vc-redist?view=msvc-170#visual-studio-2015-2017-2019-and-2022). Make sure to download the right version which corresponds to your PC  

## 15092023  
1. board debugging  
Describe: for the 4 LEDs, I intend to make the fourth LED blink, but it turns out the first LED blinks.  
Solve: in Libero, the order of signal starts from right bit, i.e. the LSB is the 0th bit and the MSB the last bit. E.g. for signal a = "0001", a[0] is '1'.

## 18092023  
1. VHDL coding
Describe: by state machine, if separate the state driving part and assigning part, please dont use internal signal! otherwise it would cause one clock delay!  
![image](https://github.com/youya199/polarfireMTF300T/assets/94166804/a53db33f-6fa8-4423-9fb2-5bcdf4e94279)

