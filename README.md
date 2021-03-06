Caleb Taing

3/14/2020

Final Project - Hydrophone

The goal for this project involves obtaining raw data from OOI Broadband hydrophone packages from nodes Oregon Shelf, and Offshore. Part 1 analyzes noise levels by plotting frequency (Hz) vs power spectral density (dB) at locations specified as cases for project 2, specifically at timeframes where certain parameters are present. Part 2 analyzes noise levels from Airgun, Marine Mammal, and Earthquake/Volcano noise. Likewise, frequency (Hz) vs power spectral density (dB) are analyzed; as well, a spectogram of Time (s) vs Frequency (Hz) as a color coded heat map. 

## Part 1: Four time periods within 2 different node locations
### Oregon Shelf Surface Mooring *Cases* 
Case 1: Rain and Wind (absent): **2 March 2018**
> ![f1](https://github.com/calebkt/BME_450_Hydrophone/blob/master/Hydrophone_images/f1.PNG)

Case 2: No Rain and Wind: **21 December 2018**
> ![f2](https://github.com/calebkt/BME_450_Hydrophone/blob/master/Hydrophone_images/f2.PNG)

Case 3: Rain and no Wind: **25 May 2018**
> ![f3](https://github.com/calebkt/BME_450_Hydrophone/blob/master/Hydrophone_images/f3.PNG)

Case 4: Rain and Wind: **7 March 2018**
> ![f4](https://github.com/calebkt/BME_450_Hydrophone/blob/master/Hydrophone_images/f4.PNG)

### Oregon Offshore Mooring *Cases*
Case 1: Rain and Wind (absent): **9 April 2018**
> ![f5](https://github.com/calebkt/BME_450_Hydrophone/blob/master/Hydrophone_images/f5.PNG)

Case 2: No Rain and Wind: **26 September 2018**
> ![f6](https://github.com/calebkt/BME_450_Hydrophone/blob/master/Hydrophone_images/f6.PNG)

Case 3: Rain and no Wind: **4 September 2018**
> ![f7](https://github.com/calebkt/BME_450_Hydrophone/blob/master/Hydrophone_images/f7.PNG)

Case 4: Rain and Wind: **12 December 2018**
> ![f8](https://github.com/calebkt/BME_450_Hydrophone/blob/master/Hydrophone_images/f8.PNG)

### PART 1 - Questions
1.1) What is the effect of wind and rain on underwater noise? Explain any behavior you observe in your result.
>> According to my data, case 3, where there is rain and no wind has the highest PSD at lower frequencies regarding Figure 7. However, at the higher frequences for Figure 7, the PSD drops the lowest. This serves to be a trend throughout the pieces; as frequency is low, PSD will be high, while high frequency yields a lower PSD. In Figure 4, which represents both rain and wind being present, the average PSD is the lowest. 

1.2) Which one has the highest impact? Rain or wind?
>> The highest impact upon PSD compares specifically case 2 and case 3. In these cases, Oregon Shelf has an extremely small difference comparing Figure 2, and Figure 3 where whether wind or rain are absent, the graphs are very similar. Comparing case 2 and case 3 however for Oregon Offshore, rain has a greater effect. Regarding Figure 6 and Figure 7, at lower frequencies, initially, Figure 7 yields a higher PSD. 

1.3) What are the main reasons for observing different spectral levels in Oregon shelf compared to Oregon offshore?
>> As Oregon Shelf is shallow, and closer to the surface, spectral levels are higher for Oregon Shelf then Oregon Offshore. From this, Oregon shelf yields less attenuation losses compared to Oregon Offshore based on different depth and general locations. 

## PART 2: Spectral Data for Airgun, Marine Mammals, and Earthquake   and Comparison
Prior spectral data, this Wenz Curve will be utilized in order to properly compare the bandwidths.
> ![WC](https://github.com/calebkt/BME_450_Hydrophone/blob/master/Hydrophone_images/WC.png)

**Airgun - 1 August, 2019 - 07:45 (30 sec period)**
> ![f9](https://github.com/calebkt/BME_450_Hydrophone/blob/master/Hydrophone_images/f9.PNG)
Airgun spectral data ranges from 0 to 2500 Hz. Looking very closely, the second signal at 24 seconds expresses this. According to the Wenz Curve, ship and industrial activity ranges from 10 to 10,000 Hz making this case consistent. Lower frequencies are utilized in order not to interfere with marine life, as well as ship based navigation.

**Marine Mammals - 6 October, 2017 - 19:55 (10 sec period)**
> ![f10](https://github.com/calebkt/BME_450_Hydrophone/blob/master/Hydrophone_images/f10.PNG)
Expressed here, marine mammal vocalizations range from 500 to 4500 Hz. According to the Wenz Curve, biologics range from 8 to 100,000+ H; an enormous range. This satisfies this condition appropriately; according to seaworld.org, humpback whales, have vocalization frequencies ranging from 20 to 8000 Hz which satisfies this condition. 

**Earthquake - 25 April, 2019 - 06:35 (20 sec period)**
> ![f11](https://github.com/calebkt/BME_450_Hydrophone/blob/master/Hydrophone_images/f11.PNG)
According to Figure 11, earthquake frequency ranges from 0 to 36 Hz. This will satisfy the conditions expressed by the Wenz Curve; as earthquakes and explosions range from 0 to 100 Hz. Likewise, comparing spectral levels, yellow yields 120 (dB) which matches the Wenz Curve's spectral level at a frequency of 5 for the blue dashed line. 









