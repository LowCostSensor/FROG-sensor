For any information, please contact riccardogaetano.cirrone@unipa.it

This FROG sensor measures chlorophyll-a fluorescence and turbidity in water using LEDs and a photodiode. It converts light intensity readings into concentration values (ppb) or relative fluorescence signals, logs data locally to an SD card for offline storage, can upload measurements to ThingSpeak over Wi-Fi for remote monitoring. The device runs automatic measurements at regular intervals.

Monitoring and maintaining functioning freshwater habitats is increasingly challenging, despite the widespread implementation of European and international freshwater quality monitoring frameworks. With the complexities of climate change, there is a need for data with higher spatial and temporal resolution. In this context, citizen science initiatives have emerged as a valuable complement to official monitoring programs. These initiatives are particularly important in small river basins and remote rural areas, where data from environmental agencies is often sparse or unavailable. However, concerns regarding the reliability and consistency of citizen-generated data persist, highlighting the need for novel technological solutions capable of improving the quality of in situ measurements collected by volunteers.

We present a low-cost fluorometer for field measurements of phytoplankton biomass, through the measurement of chlorophyll-a, featuring a multivariate turbidity correction algorithm and automated online data upload. This open-source device aims to advance monitoring by integrating cutting-edge optical sensing with IoT connectivity and citizen science.
The sensor is integrated in a 3D-printed case and comprises an optical system with two light sources: an 820 nm LED for turbidity measurements and a 430 nm SMD LED for chlorophyll-a excitation, coupled with a long-pass optical filter. The voltage signal from the photodiode is acquired via a 16-bit analog-to-digital converter and transmitted to a microcomputer (Raspberry Pi Zero 2 W), which powers and controls the system.
Laboratory and field evaluations demonstrated that the sensor delivers accurate and reproducible measurements, achieving higher resolution and precision than measurements without turbidity correction. For ease of replication, the 3D enclosure CAD model, software, and user guidelines are openly accessible online.

We welcome collaborations and contributions from researchers, developers, and citizen science groups.

## Build Your Own FROG
We can support the assembly of FROG sensors for research or educational purposes. Users only need to cover component and shipping costs.
