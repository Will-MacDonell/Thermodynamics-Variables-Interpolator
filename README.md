# Thermodynamics-Variables-Interpolator
This MATLAB function uses input file water.cgi.txt - ref. National Institute of Standards and Technology [NIST], 2020 (https://webbook.nist.gov/chemistry/fluid/).   

The function uses NIST Data to interpolate Thermodynamic Variables at an inputted temperature - Either single Temp value or Temperature Vector. 

If a Temperature Vector (i.e. [T1, T2]) is inputted, the function will find the thermodynamic variables at T1 and T2 as well as the average value (actual average from an interpolated date, not a linear average) of the thermodynamic variable between the two temperatures.   

INPUT = Temparature [Celcius] - Either T or [T1,T2] 

OUTPUT = Table of Thermodynamic Variables [TemperatureC Pressureatm Densitykgm3  Volumem3kg Internal EnergykJkg EnthalpykJk EntropyJgK CvJgK CpJgK  Sound Spdms JouleThomsonFatm ViscosityPas ThermCondWmK] &amp;&amp; A plot showing thermodynamic variables with Temperature, Labelled with the identified variables at specified temperatures.  

Created by Will MacDonell (https://github.com/Will-MacDonell)
