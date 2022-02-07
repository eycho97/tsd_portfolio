# Assignment 3 - Critique By Design

In this assignment, I searched for a visualization that could use improvment and critiqued it.
Then, I created some sketches to start the improvement process and tested the sketches to receive constructive feedback.

### Step 1: Find a Data Visualization
For this assignment, I found a visualization on batting averages for different cities in the 2019 Cricket World Cup.
The visualization captured my eye because of the unique representation of data through city monuments. The source of the visuaization can be found on this [website](https://runrepeat.com/your-city-cricket-world-cup-rankings)

![Cities with Best Batting Average](batting_avg.png)

### Step 2: Critique the Data Visualization

|Criteria|Score|Discussion|
|--------|-----|----------|
|Usefulness|6|After reading the text, and looking through the numbers, people will start to make sense of the visualization. I can see it being useful to those that are curious.|
|Completeness|3|Without the context of the article, it’s easy to mistake this for baseball looking at the title. People might not know what runs means|
|Perceptibility|1|The method of representing the data (city landscapes) have nothing to do with the data itself. It is actually misleading as the city with the highest average (Sydney) has a smaller landscape than others.|
|Truthfulness|4|The numbers themselves may be truthful, but the way the data is represented goes against the data.|
|Intuitiveness|3|Only once you see the numbers for runs and average is it easy to interpret. The text can give some context, but doesn’t make it easier to understand the visualization.|
|Aesthetics|5|The aesthetics themselves are acceptable, and the city landscapes are a creative way to represent the data. However, it distracts from the actual value of the data and if people are unfamiliar with the landscapes, they won’t make the connection to the city.|
|Engagement|5|After looking at the visualization, the audience might want to learn more about different cities and their batting averages. However, it wouldn’t inspire people to share the visualization.|

#### Overall Observations
When I first saw the visualization, I was hooked by the choice of visual representation of the data. However, within a few seconds I was disenchanted and frustrated by how the representation doesn’t align with the numbers. Sydney is supposed to be the city leading in batting average, but the landscape representing it is the smallest among the other cities shown.

I think the visualization uses decent color contrast between the text and background. The text family and font is consistent throughout. The colors are also very eye-catching and hooks the reader in.

Most of the visualization doesn’t work. The data being represented by city landscapes adds no value to better understanding the data at a glance, and is even misleading. The text is interesting for context, but I feel that it belongs in the article and distracts from the visualization itself.

I would change the visualization type to something that can actually represent the data and make it comparable. I would give different weights to the representations of the runs and averages, since the batting averages is the main data point to be discussed. I would also try to minimize the text in the visualization, as the discussion of specific players is interesting, but not integral to understanding the visualization.

#### Primary Audience
The primary audience for the visualization is for those following the Cricket World Cup. This audience might grasp the data more easily than the average person, but I believe it would still be confusing for the particular audience. No matter how knowledgable you are in Cricket, the fact that the visual elements misleads the viewer in the value of the batting averages means that it will be ineffective. 

#### Method Evaluation
I think that this method was a good way to evaluate the data visualization across many criteria. The critique method used by assignment 1 helped me grow my intuition in what to look for in a data visualization and different aspects that were immediately visible to me. However, Few’s method allows us to better analyze the visualization across specified criteria. Some missing elements include use of color, typography and other “physical” aspects of the visualization. However, it seems the evaluation of these elements are ingrained into certain criteria such as perceptibility, completeness, and intuitiveness.  


### Step 3: Wireframe a Solution

![Sketch1](a3sketch1.jpg)

![Sketch2](a3sketch2.jpg)

### Step 4: Test the Solution

### Step 5: Build Your Solution

#### Flourish Version

#### Cricket Statisctics: Batting Average Might Not be the Best Measure for Success
Sydney leads all cities with a 45.37% batting average, but Colombo and Harare have more total runs.
<div class="flourish-embed flourish-chart" data-src="visualisation/8626999"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

#### Tableau Version
<div class='tableauPlaceholder' id='viz1644207205147' style='position: relative'><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='CricketBattingAvg&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>
<script type='text/javascript'>
  var divElement = document.getElementById('viz1644207205147');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';
  vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>
