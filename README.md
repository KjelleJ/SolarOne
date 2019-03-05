# SolarOne
SolarOne - an Android-app - calculates and shows solar data for any place on earth
<span lang="EN-US">©GubboIT  2012-2014</span>

Note: To see some screenshots of SolarOne check the png-files.

# <span lang="EN-US">SolarOne 1.4</span>

**<span lang="EN-US">SolarOne</span>** <span lang="EN-US">calculates and shows solar data for any place on earth. The solar data is stored in a local database on your device. There are 5 predefined places – one for each part of the world but you can add places of your own (see **Add Place** below). The main window shows all places as balloon icons on a world map. Selected places are red balloons and the rest are yellow balloons. Tap on a balloon to see some info and to select or deselect the place. The menu item **Places** shows a list of all places and if they are selected or not. You can also select or deselect using **Places**. On all “map windows” you can use a **Map** or **Satellite** view. Map view is default.</span>

## <span lang="EN-US">Add Place</span>

<span lang="EN-US">A place of your own can be added in this way (it is assumed that **Auto** is checked):</span>

<span lang="EN-US" style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;"></span> </span><span lang="EN-US">Enter the name of the place so Google Maps understands it. Could be “Kuala Lumpur” or “Ferme Park Road 200, London”.</span>

<span lang="EN-US" style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;"></span> </span><span lang="EN-US">Touch **Get Values** and verify that you are on the right place on the map. Otherwise go back and provide more or other info in the name field. Tap on the map in the exact location of interest.</span>

<span lang="EN-US" style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;"></span> </span><span lang="EN-US">Touch **OK**. Latitude, longitude, timezone, and DST values are now set.</span>

<span lang="EN-US" style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;"></span> </span><span lang="EN-US">Go back to the name field and make it shorter if it is long.</span>

<span lang="EN-US" style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;"></span> </span><span lang="EN-US">If the values seem to be reasonable touch **Save** and the solar data for this place are calculated and put into the database.</span>

<span lang="EN-US">You can also enter values manually. This can be useful if you want to define a place without name. Uncheck **Auto** and you can set values manually or get the values step by step.</span>

<span lang="EN-US">If **Daylight Saving Time (DST)** is checked DST will be added to the time of sunrise and sunset if DST is applicable. When you touched **Get Values** (or **Get Time Zone)** the values of **DST Start**, **DST End**, and **DST Offset** are set. For most places those values are correct but DST is a tricky business – the rules can be changed with short notice. If the values do not seem to be correct you can set the values using the **Change** buttons (**Auto** must be unchecked). If **Daylight Saving Time (DST)** is checked ***** will be added after the name of the place. This is true even if the place never applies DST.</span>

## <span lang="EN-US">Delete Place</span>

<span lang="EN-US">Select one or more places and touch **Delete Place**. The places are removed from the database.</span>

## <span lang="EN-US">Graph</span>

<span lang="EN-US">To graph solar data select one or two places and touch **Graph**. If you want to compare solar data you can select two places.</span>

<span lang="EN-US">From the menu you can select the graphs **Rise & Set**, **Max Elevation**, or **Length of Day**:</span>

<span lang="EN-US" style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;"></span> </span>**<span lang="EN-US">Rise & Set</span>** <span lang="EN-US">shows the time of sunrise and sunset for each day during the year.</span>

<span lang="EN-US" style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;"></span> </span>**<span lang="EN-US">Max Elevation</span>** <span lang="EN-US">shows the maximum elevation in degrees for each day during the year: 90 degrees means that the sun is in zenith and 0 that it does not rise.</span>

<span lang="EN-US" style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;"></span> </span>**<span lang="EN-US">Length of Day</span>** <span lang="EN-US">shows the time between sunrise and sunset for each day during the year.</span>

<span lang="EN-US">Tap on the month line to the left to see the solar data at different dates. Use the **+** and **–** buttons to adjust.</span>

## <span lang="EN-US">Solar Sector</span>

<span lang="EN-US">The solar sector from a point can be described as the directions in which you can see the sun from sunrise to sunset. To view the solar sector: Select a place and touch **Solar Sector**. Google Maps is displayed for the place and the solar sector is marked. How the sun seems to move in the sky (clockwise in the north or counter-clockwise in the south) is indicated by the red arrow. Tap on the month line to see the solar sector at different dates. Use the **+** and **–** buttons to adjust. Use the **Info** button to see solar data.</span>

<span lang="EN-US">Touch</span><span class="apple-converted-space"><span lang="EN-US" style="font-size:11.5pt;
line-height:115%;color:black"> </span></span>**<span lang="EN-US" style="font-size:11.5pt;line-height:115%;color:black">Animate</span>**<span class="apple-converted-space"><span lang="EN-US" style="font-size:11.5pt;
line-height:115%;color:black">(in menu)</span> </span><span lang="EN-US" style="font-size:11.5pt;line-height:115%;color:black">and the solar sector is shown for the 5</span><sup><span lang="EN-US" style="color:black">th</span></sup><span lang="EN-US" style="font-size:11.5pt;line-height:115%;color:black">, 15</span><sup><span lang="EN-US" style="color:black">th</span></sup><span lang="EN-US" style="font-size:11.5pt;line-height:115%;color:black">, and 25</span><sup><span lang="EN-US" style="color:black">th</span></sup><span class="apple-converted-space"><span lang="EN-US" style="font-size:11.5pt;
line-height:115%;color:black"> </span></span><span lang="EN-US" style="font-size:11.5pt;line-height:115%;color:black">of each month of the year.</span>

<span lang="EN-US">Azimuth at sunrise is defined as the angle counted clockwise from true north along the horizon to the place where the sun rises.</span>

## <span lang="EN-US">Daylight Saving</span>

<span lang="EN-US">All time is local time with or without daylight saving depending on if **Daylight Saving Time (DST)** is checked in **Add Place**. If **Daylight Saving Time (DST)** was checked ***** is appended to the name of the place.</span>

## <span lang="EN-US">Accuracy</span>

<span lang="EN-US">The solar data is less accurate far to the north or south and especially when the sun is very low. The solar data assumes a free horizon and you normally don’t have a free horizon: There are mountains, buildings, forests…</span>

## <span lang="EN-US">Acknowledgments</span>

<span lang="EN-US">Sunrise, sunset and length of day data is calculated using the Java classes from</span> [<span lang="EN-US">http://www.jstott.me.uk/jsuntimes/</span>](http://www.jstott.me.uk/jsuntimes/)<span lang="EN-US">. The calculations of max elevation and azimuth at sunrise and sunset were added to the Java classes. All formulas are from NOAA ([http://www.noaa.gov](http://www.noaa.gov/)). See</span> <span class="apple-converted-space"><span lang="EN-US" style="font-size:11.5pt;
line-height:115%;color:black"> </span></span>[<span lang="EN-US" style="font-size:11.5pt;line-height:115%;color:purple">NOAA Solar Calculator</span>](http://www.esrl.noaa.gov/gmd/grad/solcalc/)<span class="apple-converted-space"><span lang="EN-US" style="font-size:11.5pt;
line-height:115%;color:black"> </span></span> <span lang="EN-US">for definitions.</span>

<span lang="EN-US">Time zone info is taken from Google Time Zone API .</span>

**<span lang="EN-US">DST Start</span>** <span lang="EN-US">and **DST End** are computed using [Joda Time](http://joda-time.sourceforge.net/). **Joda Time** is licensed under the</span> [<span lang="EN-US">Apache License</span>](http://www.apache.org/licenses/LICENSE-2.0) <span lang="EN-US">.</span>

<span lang="EN-US" style="font-size:8.0pt;font-family:&quot;Courier New&quot;">Copyright 2013 GubboIT</span>

<span lang="EN-US" style="font-size:8.0pt;font-family:&quot;Courier New&quot;"> </span>

<span lang="EN-US" style="font-size:8.0pt;font-family:&quot;Courier New&quot;">Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at</span>

<span lang="EN-US" style="font-size:8.0pt;font-family:&quot;Courier New&quot;"> </span>

<span lang="EN-US" style="font-size:8.0pt;font-family:&quot;Courier New&quot;">http://www.apache.org/licenses/LICENSE-2.0</span>

<span lang="EN-US" style="font-size:8.0pt;font-family:&quot;Courier New&quot;"> </span>

<span lang="EN-US" style="font-size:8.0pt;font-family:&quot;Courier New&quot;">Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.</span>

 
 
