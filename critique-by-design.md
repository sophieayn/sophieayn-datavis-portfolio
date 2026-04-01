| [home page](https://sophieayn-datavis-portfolio.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Title
The following documents my progress critiquing and re-working, to a marginal success, a data visualization published by the World Happiness Report. 

_For each step below, you should document your progress as you move forward.  In terms of tone, think of the writeup as though you're keeping journal of your step-by-step process.   You should include a any insights you gained from the critique method, and what it led you to think about when considering the redesign.  You should talk about how you moved next to the sketches, and any insights you gleaned from your user feedback.  Document what you changed based on the user feedback in your redesign.  Finally, talk about what your redesigned data visualization shows, why you selected the data visualization you did, and what you attempted to show or do differently._

_You can include screenshots, sketches or other artifacts with your narrative to help tell the story of how you moved through the process.  Again, make sure to avoid including any personally identifying information about your interviewees (don't list full names, etc.).  While this template serves as a guide, make sure to reference the assignment writeup on Canvas for the official guidance.  This template does not include all guidance mentioned on the assignment page._

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
_Don't forget to complete the Google Form found on the assignment page.  You can summarize your thoughts here._
This critique is based on Stephen Few's Data Visualization Effectiveness Profile, which can be found [here](http://www.perceptualedge.com/articles/visual_business_intelligence/data_visualization_effectiveness_profile.pdf)

The critique is split into the following sections: usefulness, completeness, perceptibility, truthfulness, intuitiveness, aesthetics, and engagement. 

### Usefulness - Score 5/10
#### 
This chart is relatively useful. The World Happiness Report was developed so that countries may learn more about world happiness and direct public policy to increase their own happiness. This visualization allows readers to compare countries' happiness level, see each country's individual happiness level, and develop some intuition on other factors regarding country's populations' perceptions. However, due to other factors which will be discussed shortly, the usefullness of this chart is stunted. 

### Completeness - Score 6/10

This chart is not complete. 

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

## Step three: Sketch a solution

I sketched a few solutions for this visualization. The main lesson from this exercise was the difficulty in being able to display this information effectively. The information is separated by country; each country needs to be visible and distinct. There are several variables with differing scales; these also need to be displayed in a means which readers can easily understand. 



## Step four: Test the solution

_Before you conduct your interviews, prepare a simple script.  Use this as a guide and as a way to take notes as you go forward. Come up with your own list of questions you want to ask for the selected visualization. Keep the questions broad so you can get the most value out of your feedback. Then, document answers to your questions here._

Questions to ask (modify these for your own interviews): 

- Can you tell me what you think this is?

- Can you describe to me what this is telling you?

- Is there anything you find surprising or confusing?

- Who do you think is the intended audience for this?

- Is there anything you would change or do differently?

Results: 

_Don't identify or share personally identifiable information (PII) about the people you spoke to._


| Question | Interview 1 | Interview 2 |
|----------|-------------|-------------|
|          |             |             |
|          |             |             |
|          |             |             |

Synthesis: 

_What patterns in the feedback emerge?  What did you learn from the feedback?  Based on this feedback, come up with what design changes you think might make the most sense in your final redesign._

## Step five: build the solution

_Include and describe your final solution here. It's also a good idea to summarize your thoughts on the process overall. When you're done with the assignment, this page should all the items mentioned in the assignment page on Canvas(a link or screenshot of the original data visualization, documentation explaining your process, a summary of your wireframes and user feedback, your final, redesigned data visualization, etc.)._

## References
_List any references you used here._

## AI acknowledgements
_If you used AI to help you complete this assignment (within the parameters of the instruction and course guidelines), detail your use of AI for this assignment here._

