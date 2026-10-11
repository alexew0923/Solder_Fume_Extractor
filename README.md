# Solder Fume Extractor
This repository contains information on how to build your own custom solder fume extractor.

<img src="https://github.com/alexew0923/Solder_Fume_Extractor/blob/main/Assets/fume_extractor.jpg" width=50% height=50%>

# Materials
*Note: * The products listed here are not affiliated with me any kind and I only bought these after searching which to buy.
| Product  | Price |
| ------------- | ------------- |
| [iPower 4 Inch 100 CFM (cubic feet per minute) Inline Duct Booster Fan](https://a.co/d/0aFPhZU8) | $29.99 |
| [iPower 4 Inch 8 Feet Duct](https://a.co/d/0cc4P8BJ) | $15.19  |
| [Jafanda JF180 Original Replacement Filters](https://www.jafanda.com/en-ca/products/jafanda-jf180-original-replacement-filters) | $44.00 |
| 3D printed housing for the filter. (stl file located in the repository) | 377 g * $0.06/g = $22.62
| **Total** | **$111.80** |

# Why I Chose to Build My Own
The reason behind why I did not buy a solder fume extractor online is because the ones online are easily over $50 and there were not much information on how to buy a good one. Upon research, I discovered that the best way is just to vent the air completely out the window. That is why I initially only had the inline duct fan and the duct pipe to carry the solder fume outdoor.

However, I felt like blowing the solder fume without filtering it would harm the neighbors. Many solder fume extractors sold on the internet uses carbon filters, but I find them unreliable as I can easily see through the filter and the carbon powder on them are too little. I wanted to find a filter that can capture both particulate matter and volatile organic compounds (VOC). While the filter I selected might not be the best, Jafanda filter has both HEPA filter, which captures the particulate matter, and activated carbon filter, which captures the VOCs. If you would like to use another filter, I recommend one with both HEPA and activated carbon filter. You can edit the 3D model as you wish.

# Results
I conducted three tests, one with the fume extractor on the left, top, and without the air filter. I used the air quality monitor in my previous [repository](https://github.com/alexew0923/Air_Quality_Monitor) and I placed it in front of the fan for the half fan and next to the workbench for the remaining time. Attached chart is the recommend particulate matter mass concentration.

<img src="https://github.com/alexew0923/Air_Quality_Monitor/blob/main/PM_Standard.jpeg" width=50% height=50%>
Credit: ATMO https://atmotube.com/blog/particulate-matter-pm-levels-and-aqi

## Test 1
<img src="https://github.com/alexew0923/Solder_Fume_Extractor/blob/main/Assets/air_filter_on_left" width=50% height=50%>
<img src="https://github.com/alexew0923/Solder_Fume_Extractor/blob/main/Assets/setup_left.jpg" width=50% height=50%>
As seen in the graph, the particulate matter mass concentration stayed in the safe level. However, I noticed the fan was too weak to suck all the fume and I could constantly smell the escaping fumes.

## Test 2
<img src="https://github.com/alexew0923/Solder_Fume_Extractor/blob/main/Assets/air_filter_on_top" width=50% height=50%>
<img src="https://github.com/alexew0923/Solder_Fume_Extractor/blob/main/Assets/setup_top.jpg" width=50% height=50%>
This time, I changed the position of the air filter to above the workbench as fumes rise in the air. I hoped the result would improve, but it was about the same. The issue with weak duct fan persisted and the solder fumes often did not pass the filter and went around it.

## Test 3
<img src="https://github.com/alexew0923/Solder_Fume_Extractor/blob/main/Assets/no_air_filter" width=50% height=50%>
I was not expecting the result to be this different, but not having the air filter increased the mass concentration of various size of particulate matter by over 40 times when applying solder to the soldering iron. Looking at this, I really understand the reason why having fume extractor is important for others and my health.

# Conclusion
While I am using lead-free solder and thought it would be enough, I realized how a solder fume extractor can improve my health. It would be a best practice to vent the solder fume outside, but if it is not feasible, an air filter can come in handy. Some limitations are that the air filter I used is a bit too large for the size of my work table and even though the fan is rated as 100 CFM, I was not satisfied with how strong it can suck the solder fumes. The air filter blocks air flow and I might consider how attaching the air filter behind the fan affects its inhaling power.
