impedance-matching-calculator
=============================
- [Maximum power transfer theorem - Wikipedia](https://en.wikipedia.org/wiki/Maximum_power_transfer_theorem)
- [Maximum Power Transfer and Impedance Matching | Ultimate Electronics Book](https://ultimateelectronicsbook.com/maximum-power-transfer-and-impedance-matching/)
- [**Maximum Power Transfer Theorem - YouTube**](https://www.youtube.com/watch?v=U85eA3-suiQ)
    - need Partial Derivative
    - [Difference Between Partial and Total Derivative - YouTube](https://www.youtube.com/watch?v=Kp7sSp5Kn7o)
    - [多元微积分 - 维基百科，自由的百科全书](https://zh.wikipedia.org/wiki/%E5%A4%9A%E5%85%83%E5%BE%AE%E7%A7%AF%E5%88%86)
- [**Impedance Matching - YouTube**](https://www.youtube.com/watch?v=5p0v7ZU0WcA)
- [Impedance Matching Speaker Cabinets | Too Afraid To Ask - YouTube](https://www.youtube.com/watch?v=pFhClJDeNYk)
- [MESA/Boogie Speaker Impedance Matching and Hook-up ~ Part 1 | MESA/Boogie®](https://legacy.mesaboogie.com/amplitudes/2013/June/mesaboogie-speaker-impedance-matching-and-hook-up-part-1.html)
- [RF Man - Impedance Matching in an RF Amplifier using Conventional RF Transformers and a NanoVNA - YouTube](https://www.youtube.com/watch?v=T-TefkqituE)
- PCB impedance matching (**avoid signal reflection**)
    - [新手入门高速PCB？先搞清楚什么是阻抗匹配。 - YouTube](https://www.youtube.com/watch?v=DSLn3SpjZ3o)
    - [高频PCB和普通PCB有什么区别？ - YouTube](https://www.youtube.com/watch?v=gROftNikYyQ&t=188s)
    - [做个实验告诉你高速PCB为什么要阻抗匹配 - YouTube](https://www.youtube.com/watch?v=sECqiDgvnDU)
    - [Transmission line - Wikipedia](https://en.wikipedia.org/wiki/Transmission_line)
    - [Antenna Design Tools | AEM Antennas](https://aemantennas.com/antenna-design-tools/)
    - [CGI-Wcalc](https://wcalc.sourceforge.net/cgi-wcalc.html)
    - [NFC - NXP Community](https://community.nxp.com/t5/NFC/bd-p/nfc)
        - [NFC天線設計好幫手 - Antenna Design Tool - 大大通(繁體站)](https://www.wpgdadatong.com/blog/detail/75167)
### Notes
- Psource = Vsource * Icircuit
    - Psource = Vsource^2 / (Rth + Rload)
        - (Rth + Rload) increase = less Psource = not efficient
        - (Rth + Rload) decrease = more Icircuit = overcurrent = excessive generation of heat, and the risk of fire or damage to equipment
            - Since Rth is a constant value (labelled impedance on the case of guitar cabinet), Rload should not be smaller than expected
                - real life scenero: blow up a guitar cabinet                
        - Rth = Rload = matched impedance = get the most from Psource
- > 模擬是行50 ohm 而數碼則行75 ohm

### ChatGPT
> In transistor audio amplifier circuits, it is generally recommended to
> match the output impedance of the amplifier to the load impedance (the
> loudspeaker impedance) for maximum power transfer. However, this does
> not necessarily mean that the load resistance should be large.
> 
> The choice of loudspeaker impedance, such as 4 ohms, is based on
> several factors including efficiency, power handling capabilities, and
> market demand. Lower impedance loudspeakers (such as 4 ohms) can draw
> more current from the amplifier, which allows for higher power output.
> This is desirable for applications where high sound levels are
> required, such as in professional audio or home theater systems.
> 
> Additionally, the impedance of a loudspeaker is not purely resistive.
> It typically includes inductive and capacitive components as well,
> which can affect the overall impedance curve. Amplifiers are designed
> to handle these varying impedance loads within their specified range.
> 
> It's worth noting that the output stage of a transistor audio
> amplifier is often designed to provide a low output impedance to match
> the load impedance. This helps to minimize signal loss and distortion.
> Impedance matching techniques, such as output transformers or
> impedance matching networks, can be used to optimize the power
> transfer between the amplifier and the loudspeaker.
> 
> In summary, while it is important to consider impedance matching for
> optimal power transfer, the choice of loudspeaker impedance is
> determined by various factors, and lower impedance loudspeakers like 4
> ohms are commonly used for their power-handling capabilities and
> efficiency.



> The specific voltage level of line level can vary slightly depending
> on the region and specific application, but it is generally around
> 0.316 to 2 volts root mean square (Vrms). 
> 
>  loudspeaker get more power by gettting more current instead of
> voltage (p = vi) because voltage from audio signal cannot be larger

### Tutorials
- [Transistor Impedance Matching - YouTube](https://www.youtube.com/watch?v=0XYMilJxYns&lc=Ugz7-7AksrAA1VJTuBN4AaABAg.ABa-E8CHATeABbDO8flHeH)
- [Why it's so important to know the input and output impedance of a circuit (for max voltage transfer) - YouTube](https://www.youtube.com/watch?v=2HKnARziLzk)
