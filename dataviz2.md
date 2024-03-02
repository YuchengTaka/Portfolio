| [home page](https://yuchengtaka.github.io/Portfolio/) | [visualizing debt](dataviz2.md) | [critique by design](Assignment34.md) | [final project I](Final_Project_Yucheng.md) | [final project II](Final_Project_Part2_Yucheng.md) | [final project III](Final_Project_Part3_Yucheng.md) |

# Data Visualization 2
Here is my data visualization assignment!
Here is the link to the main portfolio: https://yuchengtaka.github.io/Portfolio/
# Visualization Part 1 (Government Debit bar chart)
This is the link to the dataset: https://data.oecd.org/sharebox/?id=7krr&title=General%20government%20debt%2C%20Total%2C%20%25%20of%20GDP%2C%202019
<iframe src="https://data.oecd.org/chart/7krr" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/7krr" target="_blank">OECD Chart: General government debt, Total, % of GDP, 2019</a></iframe>

# Visualization Part 2 (Heat Map)
This is the data visualization heat map made from Tableau. The data was downloaded from: https://data.oecd.org/gga/general-government-debt.htm

<div class='tableauPlaceholder' id='viz1706580634848' style='position: relative'><noscript><a href='#'><img alt='debtGDP ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;20&#47;2019debtGDP&#47;debtGDP&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='2019debtGDP&#47;debtGDP' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;20&#47;2019debtGDP&#47;debtGDP&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>            
<script type='text/javascript'>                    
 var divElement = document.getElementById('viz1706580634848');                    
 var vizElement = divElement.getElementsByTagName('object')[0];                    
 vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
 var scriptElement = document.createElement('script');                    
 scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
 vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

# Part 3 (Box-whisker Plot)

Introduction: I chose a box-whisker plot to visualize all countries' debt-to-GDP ratios based on years. The plot provides a five-number summary which is the minimum, first quartile, median, third quartile, and maximum, and there are outliers as well which have relatively extreme ratios. I chose it because it could  display the distribution of the debt-to-GDP ratio over the years. It could easily show outliers under extreme debt situations. The global distribution of debt-to-GDP is sorted into sections. It offers the trend of the global debt situation which is crucial for economic analysis. The color scheme I chose is dark green to light green for the middle 50% of the data, I think the main point of color for this plot is better visual experience and data separation between quartiles. The green is easy to watch and navigate. The color change also align with the lower ratio the better, dark green represents a deeper positivity as well. 

<div class='tableauPlaceholder' id='viz1706583972792' style='position: relative'><noscript><a href='#'><img alt='BOX ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Pa&#47;Part3DebtGDP&#47;BOX&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Part3DebtGDP&#47;BOX' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Pa&#47;Part3DebtGDP&#47;BOX&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
 var divElement = document.getElementById('viz1706583972792');                    
 var vizElement = divElement.getElementsByTagName('object')[0];                    
 vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
 var scriptElement = document.createElement('script');                    
 scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
 vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

# Discussion 
In this assignment, we investigate three different data visualization methods on the debt-to-GDP ratio. In this discussion, I would individually comment on each of the methods, and compare them in how well they deliver information. 
The first data visualization was a Government Debit Bar chart, the data is retrieved from this link: https://data.oecd.org/sharebox/?id=7krr&title=General%20government%20debt%2C%20Total%2C%20%25%20of%20GDP%2C%202019

I chose the year 2019, the x-axis is countries, and the y-axis is the ratio in %. The countries are sorted from lowest ratio to highest ratio. The bar chart gives a clear comparison between each nation's debt-to-GDP ratio. The black average bar is obvious to read and serves as a standard for specific comparison with other countries' grey bars. This data only shows one-dimensional information about the actual value of a country's debt to GDP situation.  

The second data visualization is the heat map of debt-to-GDP ratios based on year and location. The dataset is from this link:https://data.oecd.org/gga/general-government-debt.htm

The heatmap has a reversed color of orange-blue diverging, with blue corresponding to the lowest ratio and orange corresponding to the largest ratio. This color setting is ideal for blue is often connected with positivity and orange connected with warnings and negativity. In this scenario, the debt-to-GDP ratio is ideal if it is lower. A low ratio suggests stability and a strong capacity for a government to pay back debts without incurring financial hardship. On the other hand, a high ratio might indicate potential difficulties in meeting debt obligations and could affect a country's borrowing costs and economic stability, which is common in a lot of slowing economies. Thus, the orange is warning for high ratios, and the blue is showing alright for low ratios. 

The third data visualization I chose is the box-whisker plot. The source of data is the same as the previous heat map. The x-axis is the year and the y-axis is the value of the debt-to-GDP ratio. The box extrally layered the data with its five points, minimum, first quartile, median, third quartile, and maximum. Thus in this case, one could find which category the nation of your interest is in and have an idea of how well that country is doing in a debt situation that year. The box-whisker plot provides a distribution of these ratios. By examining the median line within each box, you can identify trends in the central tendency of debt-to-GDP ratios over time. One could observe the fluctuation in global debt-to-GDP ratios. It allows for quick comparison between different years to see how debt levels relative to GDP have changed. The outliers are also showing extreme situations that need investigation, it could be an economic stress and boom, which could promote future case study at these outlying nations. 

This data bar chart only shows one-dimensional information about the actual value of a country's debt to GDP situation, while the heat map offers the information of changing in a country's debt situation over the years and also provides an indication of the seriousness of debt problem with the help of the blue and orange color scheme. The box-whisker plot provide global trend on the debt situation and provide straightforward comparison on how debt situation changes overtime. 
