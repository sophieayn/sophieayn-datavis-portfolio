| [home page](https://sophieayn.github.io/sophieayn-datavis-portfolio/) | [data viz examples](dataviz-examples.md) | [critique by design](critique-by-design.md) | [final project I](final-project-part-one.md) | [final project II](final-project-part-two.md) | [final project III](final-project-part-three.md) |

# World Happiness, Health, and Perceptions Visualization Critique, Re-make, and Critique
The following documents my progress critiquing and re-working, to a marginal success, a data visualization published by the World Happiness Report. 

## Step one: the visualization

I retrieved the following visualization from [The World Happiness Report](https://www.worldhappiness.report/ed/2024/happiness-of-the-younger-the-older-and-those-in-between/#ranking-of-happiness-2021-2023)

<div class='tableauPlaceholder' id='viz1775074905520' style='position: relative'><noscript><a href='https:&#47;&#47;www.worldhappiness.report&#47;'><img alt='World Happiness Report 2024Figure 2.1: Country Rankings by Life Evaluations in 2021-2023 _________NotesTabs 1 &amp; 2: The 95% confidence interval is shown in the grey-shaded area at the end of each life evaluation bar.Tab 2: The sub-bars have no impact on the total score reported for each country. Instead, they are a way of explaining the implications of the model estimated in Table 2.1. The few countries that have empty bars do not have sufficient information for the calculation of portions explained by individual factors. These countries still have their overall scores, though, which are based entirely on survey responses, and are independent of our efforts to explore the underlying support factors of happiness. ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;TZ&#47;TZKQZY98W&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='path' value='shared&#47;TZKQZY98W' /> <param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;TZ&#47;TZKQZY98W&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='tabs' value='no' /><param name='language' value='en-US' /></object></div>         
<script type='text/javascript'>               
  var divElement = document.getElementById('viz1775074905520');      
  var vizElement = divElement.getElementsByTagName('object')[0];           
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';   
  var scriptElement = document.createElement('script');                  
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);       
</script>

Initially, I selected this design as I was interested in the subject material of country happiness. This was my first introduction to the World Happiness Report as an organization; I was interested in seeing what data they had and how I could rework their displays of such data. This particular visualization drew me in due to its aesthetically pleasing nature. The chart, due to its rainbow theme, made me happy to look at, which ran well with the organization's theme and purpose. However, as I continued to look at this visualization, I realized it was not displaying what I had first believed it to be. This drew me in, and was the ultimate reason as to why I selected this visualization. 


## Step two: the critique

This critique is based on Stephen Few's Data Visualization Effectiveness Profile, which can be found [here](http://www.perceptualedge.com/articles/visual_business_intelligence/data_visualization_effectiveness_profile.pdf)

The critique is split into the following sections: usefulness, completeness, perceptibility, truthfulness, intuitiveness, aesthetics, and engagement. 

### Usefulness - Score 5/10

This chart is relatively useful. The World Happiness Report was developed so that countries may learn more about world happiness and direct public policy to increase their own happiness. This visualization allows readers to compare countries' happiness level, see each country's individual happiness level, and develop some intuition on other factors regarding country's populations' perceptions. However, due to other factors which will be discussed shortly, the usefullness of this chart is stunted. 

### Completeness - Score 6/10

This chart is not complete. While there is good information included, the visualization does not stand on its own when confronted with questions. Some included variables are confusing, or seemingly contradictory to the title of the graphic. Further reading and context is required to understand the visualization. 

### Perceptibility - Score 7/10
This chart is relatively clear and easy to look at for a quick overview. The chart is sorted by descending total happiness score, which makes the visual easier to look at, and allows readers to pick up important information, such as the most and least happy countries, easily. There are graph lines which separate each country's bar, name label, and sum happiness score. This makes it easy to look at each country individually. 
The perceptibility ends after this point. As this is a split bar chart, it is difficult to compare factor sizes to each other, as each factor beyond the one hugging the y-axis has a different origin point. Furthermore, some factors are confusing without the attached article, such as "Dystopia + residual", "Log GDP per capita", and "Perceptions of corruption." The first two do not make sense to an average reader: what are "residual" and "Log GDP"? The third does not make sense in this format, in which the visualization appears to demonstrate that each factor adds up to a country's total happiness. This point ties into the enxt criteria: truthfulness. 

### Truthfulness - Score 2/10
This chart does not seem truthful, either. While the chart appears to show factors which build up into a country's total happiness, upon reading the chart's notes, one finds that the "sub-bars have no impact on the total score reported for each country." This is a problem. Additionally, supplemental information to understand what certain values, like "Dystopia + residual", is hard to find. This visualization type is interesting, but without proper context and information, the current format is less than truthful. 

### Intuitiveness - Score 4/10
Without the truthfulness of the graph, reader's intuition of the chart leads them astray; the chart is not intuitive. However, readers can understand some basic trends from the chart as-is. It is easy to understand happiness between countries, and which aspects the authors believe to explain happiness. However, more context is needed for the intuition of this chart to increase.  

### Aesthetics - Score 8/10
This visualization is very aesthetic due to the selected colors and order of colors. The entire chart is a long list of rainbows, which ties in with the subject matter of happiness. However, readers have to continuously look to the key to understand what each color means. The high number of colors can distract and exhaust readers' attention, as well. 

### Engagement - Score 8/10
This chart is relatively engaging; this may be due to the topic choice which is salient for every person. People care about their own happiness, and their home country, so they are interested to see how their country may compare to others. 

### Critique Conclusion + Data Explanation

With my first look at this chart, I assumed each variable added up to a country' happiness score. The subtitle for the chart is "Explained by six factors," which furthered this assumtion. This is not what the graphic shows. This is the main shortcoming of the visualizaion. With its current set-up and variable labels, the visualization is not entirely truthful, intutitive, or complete. 

This chart shows the overall happiness score of each country. It also shows 6 different variables which the creators of the report believe explain happiness: Perceptions of corruption, generosity, freedom to make life choices, healthy life expectancy, social support, and log GDP per capita. Each of these variables were collected either through binary survey questions, or through accessible data (for GDP and life expectancy). The dystopia variable is part of the report's methodology and serves as a baseline, or ground 0, for each country. The visualization does not explain this data well. Even upon reading the report, I still have trouble fully understanding some of these variables - this is a problem. 


## Step three: Sketch a solution

I sketched a few solutions for this visualization. The main lesson from this exercise was the difficulty in being able to display this information effectively. The information is separated by country; each country needs to be visible and distinct. There are several variables with differing scales; these also need to be displayed in a means which readers can easily understand. 

### Sketch 1: Looking at one variable at a time

<img width="1466" height="333" alt="First Attempt" src="https://github.com/user-attachments/assets/ddd36380-b966-4117-b725-283f96dfce6f" />

This was an attempt to see how one variable, measured with the y-axis, would look, with each country on the x-axis. The idea was that this would allow for easy comparison between countries. The end result was less than ideal. Adding more variables to this would lead to a messy, uninterpretable visualization. 

### Sketch 2: Maybe the information just needs a table. 
<img width="558" height="1855" alt="Country Happiness" src="https://github.com/user-attachments/assets/7d29400f-046e-48a0-b766-1529cf6c0b1f" />

This was an attempt to make the information as simple and effective as possible. By converting the data into a table, I remove a lot of the cognitive load in trying to decipher the visualization. If this data visualization is purposed for policy makers to see their country's performance in comparison to others, the easiest way to achieve this is to simply provide the information. I tried to use a color gradient to make countries with the highest happiness scores the most vibrant shade of green, with less happy countries having less vibrant shades of green. 


## Step four: Test the solution

With testing my solution, I simply showed the second graphic to a team of people and allowed them to have an open discussion regarding it. After their thoughts, we worked together to discuss potential ways forward. I synthesize the comments, critiques, and advice below. 

Results: 
### Commment 1: What do the numbers mean? 
The small group could not decipher what the values for each variable meant. While they could see from the key that the 'happiness score' went from 0 to 10, they questioned what the other values meant. 

### Comment 2: Order
One member brought up how they continued to look for ascending or descending order in each column. The table is ordered in descending order based on the happiness score. This looks fine for this variable, but left this group member tired upon looking for trends in the other variables. 

### Comment 3: Intuition
This ties in with the previous comments. The group spoke on how they could not understand intuitively what the values each meant. Did a score of 0.142 for 'generosity' mean Finland has low generosity, or high generosity, or that 14.2% of citizens perceive the country to be generous? Why are some variables seemingly on a 0-1 scale, while happiness is on a 0-10 scale, and the values of social support seem to vary from 1.2-1.5? Ultimatley, displaying the raw values made this sketch less useful than the original, as there was no intuition behind their meaning. 

### Synthesis - What to incorporate
This discussion and feedback left me with a few takeaways. 

Color did not come up in the discussion; it did not seem to play a large role in how people intook the information. Potentially, this information does not need color for effective display. 

The numbers confuse readers; the information may be better suited in a score or ranking system. Many people know that a score of A is better than a score of C; this may make a table more intuitive than comparing 0.708 and 0.638 in terms of 'healthy life expectancy.'

Order is also confusing in this format due to the number of variables. Potentially, a final result should incorporate a filter, several pages, or groupings, rather than an overarching descending order. 


## Step five: build the solution

### Creating the ranking system

I wanted to convert each variable into a ranking system from A through F. All missing information would be included as N/A. 

First, I looked through the original report until I understood that for each variable, higher was better. This was counterintutitve for the variable 'Perceptions of Corruption.' 

Second, I put the values for each variable into an online quintile calculator. I performed this for each variable to create each variable's criteria for being scored. I used the quintiles for each variable rather than a fixed value so as to have a score which compares to global values. I used the following [Quintile Calculator](https://statscalculator.com/quintile?base=0.546%0D%0A0.548%0D%0A0.182%0D%0A0.524%0D%0A0.193%0D%0A0.372%0D%0A0.484%0D%0A0.432%0D%0A0.498%0D%0A0.323%0D%0A0.480%0D%0A0.123%0D%0A0.172%0D%0A0.305%0D%0A0.368%0D%0A0.311%0D%0A0.418%0D%0A0.068%0D%0A0.116%0D%0A0.351%0D%0A0.131%0D%0A0.258%0D%0A0.169%0D%0A0.368%0D%0A0.127%0D%0A0.220%0D%0A0.281%0D%0A0.188%0D%0A0.073%0D%0A0.575%0D%0A0.202%0D%0A0.006%0D%0A0.253%0D%0A0.401%0D%0A0.175%0D%0A0.177%0D%0A0.101%0D%0A0.075%0D%0A0.043%0D%0A0.125%0D%0A0.074%0D%0A0.078%0D%0A0.251%0D%0A0.142%0D%0A0.058%0D%0A0.078%0D%0A0.215%0D%0A0.080%0D%0A0.120%0D%0A0.049%0D%0A0.219%0D%0A0.158%0D%0A0.136%0D%0A0.160%0D%0A0.035%0D%0A0.067%0D%0A0.065%0D%0A0.024%0D%0A0.119%0D%0A0.164%0D%0A0.081%0D%0A%0D%0A0.043%0D%0A0.093%0D%0A0.000%0D%0A0.204%0D%0A0.028%0D%0A0.029%0D%0A0.196%0D%0A0.118%0D%0A0.044%0D%0A0.121%0D%0A0.061%0D%0A0.078%0D%0A0.030%0D%0A0.132%0D%0A0.055%0D%0A0.059%0D%0A0.086%0D%0A0.055%0D%0A0.006%0D%0A0.173%0D%0A0.034%0D%0A0.015%0D%0A0.200%0D%0A0.402%0D%0A0.049%0D%0A%0D%0A0.138%0D%0A0.196%0D%0A0.174%0D%0A0.048%0D%0A0.115%0D%0A0.167%0D%0A0.100%0D%0A0.164%0D%0A0.107%0D%0A0.115%0D%0A0.069%0D%0A0.123%0D%0A0.199%0D%0A0.019%0D%0A%0D%0A0.060%0D%0A0.025%0D%0A0.061%0D%0A0.082%0D%0A0.074%0D%0A0.147%0D%0A0.179%0D%0A0.198%0D%0A0.048%0D%0A0.113%0D%0A0.069%0D%0A0.018%0D%0A0.252%0D%0A0.054%0D%0A0.174%0D%0A0.071%0D%0A0.028%0D%0A0.075%0D%0A0.090%0D%0A0.123%0D%0A0.156%0D%0A0.189%0D%0A0.122%0D%0A0.259%0D%0A0.031%0D%0A0.167%0D%0A0.101%0D%0A0.257%0D%0A0.160%0D%0A0.113%0D%0A0.109%0D%0A0.116%0D%0A0.136%0D%0A0.082%0D%0A0.131%0D%0A0.072%0D%0A0.053%0D%0A0.085%0D%0A0.029%0D%0A0.088).

### Creating an easy-to-read table

I decided to maintain the table visualization to display the information. I adjusted my previous iteration's problem with intution through incorporating the aforementioned ranking system, as well as by grouping each country by its happiness rank. Each country within each rank of happiness (or, all rank 'A' countries, all rank 'B' countries, and so on) would then be displayed together. Each other variable remained unordered, so as not to distract readers with trying to make sense of an order. Additionally, I kept only variables which dealt with health and perceptions, excluding the log GDP and baseline disparity variables. The included variables had the least amount of confusion during my user interviews, meaning the visualization maintains the most intuitive items. The disparity variable specifically was to act as a baseline value for the original report's calculations; this variable would not make sense in a ranking setting. Additionally, as this visualization should serve as a tool for policy makers and interested parties to evaluate a country's performance in happiness, perceptions, and health, the title should allow readers to create their own judgements on the trends and takeaways they see. As a result, a fairly vague title was selected. 

With these items in mind, I created the following visualization. 

<img width="520" height="3151" alt="Final vs 1" src="https://github.com/user-attachments/assets/e0571661-2db3-497d-a312-6161815e0725" />

### Fighting with the System

As a new Tableau user, there are many aspects to this system I am unfamiliar with. During this step, I created many versions of an essentially same data visualization previously shown in an attempt to adjust the display to my desire. Bottom line, the program won in this case. 

The outcome I desired was for each rank's cell to be colored-in or outlined with its corresponding color. Each would mirror the Happiness Rank's legend and color scheme.

<img width="70" height="76" alt="legend" src="https://github.com/user-attachments/assets/c0a64b44-1c0d-4205-85db-c0af29ccd025" />

As can be seen in the previous visualization, I did not achieve this. Rather, I had a final column which the program created which displayed a color indicator for the country's happiness score as an overall "success" indicator. This final column, while somewhat useful in its ability to display some form of color, was generated by Tableau and could not be removed from the graphic. If the color indicator was removed, this column populated with 'Abc' to indicate that the graphic was unfinished. 

I followed several different tutorials in an attempt to figure out this issue. However, most tutorials appear to have solutions to color-code cells when dealing with measures, but not dimensions. As I had converted my numerical values into text strings, I no longer was working with the same type of data as the tutorials I found. As I did not end up using any of these tutorials, I am not including them to this page. 

While the additional column, which I could not find how to remove, was helpful in providing color, I found that it distracted from the main point of the graphic. Readers may search for a header for this column to understand what it means. Its placement would pull attention toward the right of the visual, rather than the title and headers which better explain the graphic.

As a result, with support from class faculty, I turned the opacity of these colors to 0 and minimized the width of the column to essentially remove it. This resulted in my final visualization. Note: The legend runs alphabetically, though Tableau public is occasionally pushing 'A' down a few spaces. Reloading appears to reorder the legend. 

<div class='tableauPlaceholder' id='viz1775099053389' style='position: relative'><noscript><a href='#'><img alt='World Happiness, Health, and Perceptions, by Country ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Wo&#47;WorldHappinessHealthandPerceptionsbyCountry&#47;WorldHappinessHealthandPerceptionsbyCountry&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='WorldHappinessHealthandPerceptionsbyCountry&#47;WorldHappinessHealthandPerceptionsbyCountry' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Wo&#47;WorldHappinessHealthandPerceptionsbyCountry&#47;WorldHappinessHealthandPerceptionsbyCountry&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>         
<script type='text/javascript'>         
  var divElement = document.getElementById('viz1775099053389');  
  var vizElement = divElement.getElementsByTagName('object')[0];        
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';      
  var scriptElement = document.createElement('script');          
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);              
</script>

## Final Thoughts
The purpose of this visualization is to be a tool for policy makers to quickly evaluate their country's happiness, health, and perceptions in comparison to other countries. I believe this visualization achieves this job. In comparison to the original graphic, this visualization does not take excessive cognition to understand included variables or convert the presented information into an intuitive understanding. This chart does not indicate that the variables sum into the happiness score to the extent of the original graphic. 

However, I believe improved future iterations of this visualization would incorporate color for a more aesthetically pleasing experience with the data. Additionally, color could be incorporated in two ways to improve intuition and comparison. First, each cell could be colored based on its corresponding variable's rank using the previously included color scheme. Second, each row, or country, could be colored based on its overall performance with each variable. For example, countries with all "A" rankings could be shaded in or outlined with the mentioned green shade. Countries with 2-3 "B" or "C" scores could do the same with the mentioned yellow shade, and so on. 

Other iterations could include different pages for each happiness score to reduce the length of the visualization. These, rather than a table, could rely solely on the color scheme and be displayed in a map format. 

Ultimately, my end result is a more effective visualization, but there are many means to improve it further. 


## References, all previously linked
[The World Happiness Report](https://www.worldhappiness.report/ed/2024/happiness-of-the-younger-the-older-and-those-in-between/#ranking-of-happiness-2021-2023)
[Stephen Few's Data Visualization Effectiveness Profile](http://www.perceptualedge.com/articles/visual_business_intelligence/data_visualization_effectiveness_profile.pdf)
[Quintile Calculator](https://statscalculator.com/quintile?base=0.546%0D%0A0.548%0D%0A0.182%0D%0A0.524%0D%0A0.193%0D%0A0.372%0D%0A0.484%0D%0A0.432%0D%0A0.498%0D%0A0.323%0D%0A0.480%0D%0A0.123%0D%0A0.172%0D%0A0.305%0D%0A0.368%0D%0A0.311%0D%0A0.418%0D%0A0.068%0D%0A0.116%0D%0A0.351%0D%0A0.131%0D%0A0.258%0D%0A0.169%0D%0A0.368%0D%0A0.127%0D%0A0.220%0D%0A0.281%0D%0A0.188%0D%0A0.073%0D%0A0.575%0D%0A0.202%0D%0A0.006%0D%0A0.253%0D%0A0.401%0D%0A0.175%0D%0A0.177%0D%0A0.101%0D%0A0.075%0D%0A0.043%0D%0A0.125%0D%0A0.074%0D%0A0.078%0D%0A0.251%0D%0A0.142%0D%0A0.058%0D%0A0.078%0D%0A0.215%0D%0A0.080%0D%0A0.120%0D%0A0.049%0D%0A0.219%0D%0A0.158%0D%0A0.136%0D%0A0.160%0D%0A0.035%0D%0A0.067%0D%0A0.065%0D%0A0.024%0D%0A0.119%0D%0A0.164%0D%0A0.081%0D%0A%0D%0A0.043%0D%0A0.093%0D%0A0.000%0D%0A0.204%0D%0A0.028%0D%0A0.029%0D%0A0.196%0D%0A0.118%0D%0A0.044%0D%0A0.121%0D%0A0.061%0D%0A0.078%0D%0A0.030%0D%0A0.132%0D%0A0.055%0D%0A0.059%0D%0A0.086%0D%0A0.055%0D%0A0.006%0D%0A0.173%0D%0A0.034%0D%0A0.015%0D%0A0.200%0D%0A0.402%0D%0A0.049%0D%0A%0D%0A0.138%0D%0A0.196%0D%0A0.174%0D%0A0.048%0D%0A0.115%0D%0A0.167%0D%0A0.100%0D%0A0.164%0D%0A0.107%0D%0A0.115%0D%0A0.069%0D%0A0.123%0D%0A0.199%0D%0A0.019%0D%0A%0D%0A0.060%0D%0A0.025%0D%0A0.061%0D%0A0.082%0D%0A0.074%0D%0A0.147%0D%0A0.179%0D%0A0.198%0D%0A0.048%0D%0A0.113%0D%0A0.069%0D%0A0.018%0D%0A0.252%0D%0A0.054%0D%0A0.174%0D%0A0.071%0D%0A0.028%0D%0A0.075%0D%0A0.090%0D%0A0.123%0D%0A0.156%0D%0A0.189%0D%0A0.122%0D%0A0.259%0D%0A0.031%0D%0A0.167%0D%0A0.101%0D%0A0.257%0D%0A0.160%0D%0A0.113%0D%0A0.109%0D%0A0.116%0D%0A0.136%0D%0A0.082%0D%0A0.131%0D%0A0.072%0D%0A0.053%0D%0A0.085%0D%0A0.029%0D%0A0.088)


## AI acknowledgements
I asked Claude AI a few questions regarding how to use tableau to color my visualization in the way I wanted, after prevoius attempts at visualizations did not work. The answer the platform provided did not work, either, and was not used. 

