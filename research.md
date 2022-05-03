---
layout:page
title: Research
excerpt: "Research"
---

__1. Detecting slow slip event from seafloor pressure data using machine learning__ ([here](https://github.com/bing-he/SSE_detection_using_machine_learning) for code and details)

Slow slip event is a special tectonic signal with strong energy compared to a Magnitude of 6 earthquakes but releases energy gently that people can not feel. This signal represents the release of tectonic stress between earthquakes, and thus, their existence indicates a lower likelihood of future large earthquakes and tsunamis. However, it is challenging to detect such signals because standard measuring instruments do not work underwater, and considerable ocean noise makes the detection hard. This work trained a machine learning model, which can quickly and accurately detect the signals in continuous seafloor pressure data.

__2. Detecting tremors from ocean bottom seismic data__ ([here](https://github.com/bing-he/Tremor_detection) for code and details)

Tremor is characterized by emergent and persistent microseism and is usually accompanied with slow slip events. Hours- to weeks-long tremors are easy to identify by visual and envelope correlation methods. However, isolated short-duration tremors can be challenging to distinguish from the earthquake and ambient noise signals, especially for noisy ocean bottom seismic data. This work incorporated the previous tremor detection methods and performed a transparent workflow to automatically detect tremors in ocean bottom seismic data, significantly reducing false detections from earthquakes, T-phases, and noise. 

__3. (Collabration) Separation of seismic signal using machine learning methods__ ([here](https://github.com/yinjiuxun/WaveDecompNet) for code and details)

A seismogram is a record of how the ground moves and usually contains a rich mix of seismic signals. The transient signals capture the seismic process, and it is essential to understand the earthquake mechanisms. The ambient noise field is helpful in correlation seismology to extract spatial and temporal variations in the earth's structure. This work developed a multi-task encoder-decoder network named WaveDecompNet to directly separate transient signals from ambient signals in the time domain. (Collabrate with seismologists from Harward University).

__4. (Collaration) Removing the contributions from ocean water in seafloor pressure data__ ([Paper](https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2020JB020065?casa_token=pm7yaa0JfL8AAAAA%3AN08nZQ5zYyyHFUU_PJWF3w8OX_8L2WynfDoox1YTn4kTTR2n9PQowsDSsobhubJXpA4ZTAkzgt7wA-Y) for details)

Seafloor pressure measurement is commonly used to measure the vertical seafloor deformations on submarine volcanoes and offshore subduction zones. Because of the complex ocean waves and unavoidable instrumental drifts, it is hard to separate the geodetic and oceanographic contributions from the seafloor pressure data. This work utilizes the deep currents measurements and the theory of geostrophic balance to learn the oceanographic contributions, and it demonstrates that the optimal interpolation method performs better than complex empirical orthogonal function in reducing ocean noise. (Collabrate with physical oceanographers). 

__5. Building a 3D subduction zone model using CUBIT__

   __Simulating the spontaneous earthquakes using PYLITH in 3D model__ ([Paper1] https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2019JB017541 [Paper2] https://www.sciencedirect.com/science/article/abs/pii/S0012821X19303000?via%3Dihub )

(My Master's work) The largest earthquakes often occur on the shallow plate interface in subduction zones, usually accompanied with devastating ground shakings and tsunamis. For example, during the 2004 Sumatra Mw 9.3 earthquake and 2011 Tohoku-Oki Mw 9.0 earthquake, strong ground shakings and huge tsunamic waves caused large fatalities and property losses. Rupture prediction and hazard assessment in subduction zones are highly needed for society. We conduct dynamic rupture simulations in Nicoya Peninsula, Costa Rica. The simulated result shows a high coherence with geodetic observations in final slip, moment rate and rupture speed. The simulated rupture scenarios have great significance to help the rupture prediction and hazard assessments.
