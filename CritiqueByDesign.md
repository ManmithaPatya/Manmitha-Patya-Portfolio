# Critique by Design (Data Visualization Exercise 2 and  Critique Assignment 2)
## check2
For the completion of this assignment, I followed **five** key steps as listed below. Each step has been elaborated upon in the subsequent sections. 
- [Step one: Find a data visualization with data that can be used](# 2.1-Step-one:-Find-a-data-visualization-with-data-that-can-be-used)
- [Step two: Critique the visualization](# 2.2-Step-two:-Critique-the-visualization)
- [Step three: Wireframe a solution](# 2.3-Step-three:-Wireframe-a-solution)
- [Step four: Test the solution](# 2.4-Step-four:-Test-the-solution)
- [Step five: Build your solution](# 2.5-Step-five:-Build-your-solution)

## 2.1 Step one: Find a data visualization with data that can be used
The Visualization I chose for this assignment shows the wage gap between the male and the female genders across twenty industries in the United states. The visualization and the accompanying data can be viewed [here](https://howmuch.net/articles/men-vs-women-comparing-income-by-industry). 

The visualization represents the data as of 2019. However, based on the article, it would be beneficial to have either a benchmark value of comparison or view of historical data so that important trends can be observed. 

This visualization can be improved on the fronts of accessibility and understandability so that it can bring more visibility to the important discussed of wage gap based on gender. 

The data can be found either on the page of the visualization or can be found on the website of the [US Census Bureau](https://data.census.gov/cedsci/table?q=S2413&tid=ACSST1Y2019.S2413&hidePreview=true).

The following is the visualization:
<img src="https://cdn.howmuch.net/articles/men-vs-women-comparing-income-by-industry-5134.jpg">

## 2.2 Step two: Critique the visualization
While the visualization is interesting in it's choice of graphic, it is inconvenient to some extent. The presence of a scale for various buckets of earning combined with sub-segments in combination with the wages and the industry makes it difficult to efficiently draw timely conclusions. 

In order to critique this visualization, I chose to use the 'Data Visualization Effectiveness Profile'. Here, I will evaluate it across seven criteria: *Usefulness, Completeness, Perceptibility, Truthfulness, Intuitiveness, Aesthetics and Engagement*. 

**Usefulness**
Usefulness is determined based in the needs of the audience and is measured on a scale from Useless to Very useful. It is very important to understand the wage gap that exists between genders and hence, it is important to represent this information in a way in which everyone can understand it. However, in this visual, it would have been useful to show the number of people in the market separated by gender. This will then start a conversation about causes that drive wage gap based on the industry. The visual is focused on civilian Employed Population who are 16+ years of age. The plot does not differentiate between those who are full-time employees and those who are part-time employees. We should also consider the fact that a few of the participants are student who are working part-time. Maternity can be a cause for women to be out of the job market for a while which can skew data. Hence, adding some more relevant information would have increased the usefulness of the visual.  

**Completeness**
Completeness is determined based on the extent to which information represented helps produce the right amount of understanding. It is measured on a scale from No relevant data to all relevant data. The visualization here provides no information about the number of people in a particular industry even though it's a focal point of the article and the data set. It would be useful to also provide some information about full-time and part-time employees. The use of a spherical graphic is a good way of ensuring that visually, the gender gap between and women is not missed.   

**Perceptibility**
Perceptibility is measured based on the ease with which the information and the graphic can be assimilated by the viewer. This is measured on a scale from Unclear and difficult to Clear and easy. In this graphic, the presence of a color scheme for various buckets of data on the lower left corner and the presence of a scale on the lower right hand corner makes it difficult to keep up with the main representation. Once has to move back and forth from the legends to the main graphic which reduces Perceptibility. The repeated use of '$' and 'K' is also redundant. 

**Truthfulness**
Truthfulness talks about the accuracy and the validity of the data. It is measured on a scale from Inaccurate and/or invalid to Accurate and valid. The date here is represented on sub-segments of sections of a pie. This means that the areas of each subsection will not be the same. Hence, the representation on the graphic is not accurately related to the amount of wage that is being represented. In addition to this, we can see on the lower right hand corner that each sub-segment represents increments of $10,000. However, the last sub-segment intends to represent the data in an increment of $20,000. However, we can see that it goes from $80K to $10K, i.e, overall, the range of the wages is represented on a segment going from $10K to $10K. This makes me question the accuracy of the representation and the justice it does to the actual data. 

**Intuitiveness**
Intuitiveness talks about the degree to which the visualization is familiar and easy to understand. It is represented on a scale from Unfamiliar; difficult to understand to Familiar; easy to understand. Based on conventions of data representations, those viewing the graphic might overlook the non-uniformity in the sub-segment size and the scale. This can lead to wrong intuitiveness and thus wrong conclusions. 

**Aesthetics**
Aesthetics range from Ugly to Pleasing to the eye to Beautiful. The use of color here (Blue for men and Pink for women) is in-line with general use. However, the use of gradients of blue and pink can be confusing.

**Engagement**
Engagement is focused on overall quality. It ranges from Distracts from data to Neutral to Draws one into the data. In this visualization, the additional footers and the two legends serve as distractions from the graphic. The graphic itself leaves us with a few unanswered questions. Emphasis should also be on one industry vs other industries or national median wage vs the wage within an industry. The graphic tries to provide too much information while at the same time not providing much. 

## 2.3 Step three: Wireframe a solution
I used [figma](https://www.figma.com/files/recent?fuid=1072321393156381394) in order to think through my redesign of the above plot. Since my data has 20 categories (the industries) and three data series (the median wage of men, the median wage of women and the median wage across the population), I decided to use a combination of bar plot and line plot. The bar plots will be grouped by the wage of men and women for each industry and the line plot will hold the value of the median wage of the overall population.

My wireframe generated on figma can be viewed below (for 2019 data):

<iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="800" height="450" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Ffile%2FQu4xRqgLiZ5vgAsriBdFpN%2FUntitled%3Fnode-id%3D0%253A1" allowfullscreen></iframe>
## 2.4 Step four: Test the solution
In order to test the solution, I showed the wired frame to three individuals (a Heinz student, a Tepper student and a student at Mellon College).
### Can you tell me what you think this is?
1. "It is the representation of the median wage by gender and industry."
2. "It is wages across those industries and is shown by gender and showcases the disparity in pay."

### Can you describe to me what this is telling you?
1. "When I see the wireframe, I get the idea of how you want to represent the data visualization and you have explained how each part is going to show some aspect of the data. In terms of insight, I get that in general, the median wage of men is higher than the median wage of women and since you have represented a sample of 3 industries, I would flag that."
2. "It is showing the disparity, but I don't understand the black curve. There is a general trend I can identify that woman are paid less"

### Is there anything you find surprising or confusing?
1. "At first glance, I was unsure what the black curve is but once I read the associated test, I understood what it represents."
2. "I don't understand the black curve and the usage of industries of the x-axis is not clear to me"

### Is there anything else you would expect to see so that the takeaways are clearer to you?
1. "I would like to know what country this is based on."
2. "I would try representing the x-axis by a number of those employed in a particular industry instead of having a categorical label"

### Who do you think is the intended audience for this?
1. "People looking for proof of wage inequality based on gender, and economists."
2. "Law makers and those in academia and policy makers."

### Is there anything you would change or do differently?
1. "I would probably provide a few examples of industries."
2. "I don't understand the filter and would make sure even the bars are the same thickness in the wireframe so that nothing is misinterpreted."

## 2.5 Step five: Build your solution
The exercise of critiquing the visualization helped me immensely when it came to deconstructing it. It helped me gauge what worked and enhanced it while also figuring out those aspects of it which need to be reconsidered. What I learnt is that fancy visualizations don't often work. They can be cluttered and can at times complicate data which can easily be represented by simple graphs with no ambiguity. 

This assignment aligned my thoughts not just in visual presentation but also in terms of how correct data representation is key. (I had to do quite a bit of data cleaning and data aggregation of over 5 years of data to make this work!)

In order to get the data ready, I did the following:
- Removed the subcategorization of the industries so that each industry is stand-alone and is not grouped under any other category
- Renamed all the industries to keep them consistent and to ensure that all of them fit in the visual
- Removed unwanted data such as 'error margin'
- Reordered the industries so that they are in ascending order of name
- Shifted the category 'Other Services' to the end to follow good visualization practice

In this first visual, I worked off my wireframe to build a visualization using the 'Combo: Lines & columns (grouped)' as my graphic as choice. The bars represent the series data- median wage of women and the median wage of men. The line representation is used for the overall median wage of the population. The x-axis contains each of the twenty industries. I represented the median wage is dollars only on the y-axis so that it is not repeated multiple times. I tested the colors used against the most common color blindness [here](https://www.color-blindness.com/coblis-color-blindness-simulator/) to ensure that they were color blind friendly.

The visualization is as follows:

<div class="flourish-embed flourish-chart" data-src="visualisation/8629282"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

In my critique section, I mentioned the importance of historical data and how it can help enhance the visual. Keeping that in mind, I found data for years 2015 through 2019 on the US Census website and aggregated them into one single dataset. I then proceeded to clean the data following the steps mentioned before.

Once the data was cleaned, I represented the data using 'Bar chart (grouped)' visualization via 'Grid of Charts'. Here, I split the grids according to gender and we can now see a side-by-side view of the changes in wage through the years for the two genders across industries. As in the previously developed visual, wage ($) is represented only once on the x-axis so that it is not repeated multiple times and the industries are arranged in alphabetical order with 'Other Services' at the end.

Using the control, we can either hit play to look at the changes through the years or we can look at the difference in wages in any particular year.

The visualization is as follows (Hit Play and look at the trends!):

<div class="flourish-embed flourish-chart" data-src="visualisation/8628881"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

## Further Development
In this section, I would like to discuss additions I would have liked to make to the two plots I developed so that they are more informative without being cluttered. They would have been possible if I has access to specific data which I was unable to find. The reason I did not make this data for the visualization is that I used real-world data and I did not want to use that with a mix of made-up data.  

The first addition I would have liked to make is to add a filter to the plots to also visualize the median wages as divided between part-time and full-time employees. It will be very interesting to see how the data skew (if any) shifts in that case.  

The second enhancement I would like to see is to my second plot where, in addition to seeing the trends through the years, I would also like to see represented on the graphic the percentage by which men earn more than women. This was already calculated by me in the dataset. However, due to the limitations of flourish, I was unable to incorporate it without changing the individual x-axis which would not constitute the principles of good visualization practices.
