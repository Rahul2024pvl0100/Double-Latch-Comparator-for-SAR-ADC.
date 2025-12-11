Implementation of High-Speed Two-Stage Dynamic Comparator for SAR ADC

Sept 2025 – Oct 2025

This project focuses on designing a high-speed and low-power dynamic comparator for use in Successive Approximation Register (SAR) Analog-to-Digital Converters. 
Comparators are extremely important in SAR ADCs because they decide each bit during the conversion process. If the comparator is fast and accurate, the overall ADC works better. 
The goal of this project was to develop a comparator that can operate at very high frequencies while consuming very little energy and producing low noise.

The design uses a two-stage structure. The first stage is a StrongARM latch, which is a popular dynamic comparator used in many ADCs because it consumes no static power and can make decisions very quickly. 
To improve its performance even more, dynamic biasing was added to the StrongARM latch. This technique increases speed by allowing faster switching and also helps reduce unnecessary power loss.

The second stage helps clean and strengthen the output signal so that the final decision is stable and suitable for digital circuits inside the ADC.

The design was simulated at a supply voltage of 1.8 V, and the results show excellent performance. The comparator achieved a very high operating frequency of 1.024 GHz, meaning it can support fast ADCs.
The clock-to-Q delay was only 90.26 ps, showing how quickly it can make a decision. The input-referred noise was measured to be 5.23 μV, which means the comparator can distinguish very small input differences. 
It also consumed only 52.48 fJ of energy per comparison, making it highly power-efficient. The calculated Figure of Merit (FoM) of 2.18 (fJ·ps·10⁵)⁻¹ further confirms its suitability for high-performance SAR ADC applications.

Overall, this project successfully demonstrates a fast, low-noise, and energy-efficient comparator design for modern mixed-signal systems.
