# AnanasBoard
AnanasBoard is Designed for Stepper Closeloop Control.

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/">
<img alt="知识共享许可协议" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />本作品采用<a rel="license" href="http://creativecommons.org/licenses/by/4.0/">知识共享署名 4.0 国际许可协议</a>进行许可。

如果你认为我做的这些对你来说是有价值的, 并鼓励我进行更多开源和免费的开发. 那你可以资助我, 就算是一杯咖啡...

If you find my work useful and you want to encourage the development of more free resources, you can do it by donating...


<a rel="donate1" href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=8GQHVZ7YR8NZE">
<img alt="PalpayDonate" style="border-width:0" src="https://github.com/Dark-Guan/AnanasBoard/blob/master/donate-with-paypal.png" /></a>

<a rel="donate2" href="https://raw.githubusercontent.com/Dark-Guan/AnanasBoard/master/apcazu6ntbjy04py09.png">
<img alt="Alipay" style="border-width:0"  src="https://github.com/Dark-Guan/AnanasBoard/blob/master/donate-with-alipay.png" /></a>



##feature

1. AMS5600 and Quadrature Encoder Supported  
2. Intelligent Tuning of the Motor Current  
3. Up to 30Khz Pulse Input Supported  
4. Up to 60Khz Stepper Driver PWM with Trapezoid Acceleration  
5. Internal PID Speed Controller  

##driver
1. A4988 and Drv8825 supported.
2. PWM DA function supported.With the  Tale:
    *PWM frequence needs to be up to 10Khz*

| IC| divider resistance | Capacitance | 5V| 3.3V
| ---------------- | ---------------- | ---------------- | ---------------- | ---------------- 
| A4988 | 10KOhm | 0.1uf | 4.7KOhm | 10KOhm
| drv8825 | 10KOhm | 0.1uf | 3.3KOhm | 2.7KOhm

circuit: voltage division circuit with a Capacitance(0.1uf)  
More Info : _[A4988](http://www.allegromicro.com/~/media/Files/Datasheets/A4988-Datasheet.ashx?la=zh-CN) and [Drv8825](http://www.ti.com/lit/ds/symlink/drv8825.pdf)datasheet_.  

# Eagle

Eagle 7.2 Used

# SoftWare

https://github.com/Dark-Guan/Ananas

https://github.com/Dark-Guan/Ananas/tree/master/binary



