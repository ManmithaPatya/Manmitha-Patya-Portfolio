# Critique by Design (Data Visualization Exercise 2 and  Critique Assignment 2)
For the completion of this assignment, I followed **five** key steps as listed below. Each step has been elaborated upon in the subsequent sections. 
- [Step one: Find a data visualization with data that can be used](https://manmithapatya.github.io/ManmithaPatya-Portfolio/CritiqueByDesign.html#2.1-Step-one:-Find-a-data-visualization-with-data-that-can-be-used)
- [Step two: Critique the visualization](https://manmithapatya.github.io/ManmithaPatya-Portfolio/CritiqueByDesign.html#2.2-Step-two:-Critique-the-visualization)
- [Step three: Wireframe a solution](https://manmithapatya.github.io/ManmithaPatya-Portfolio/CritiqueByDesign.html#2.3-Step-three:-Wireframe-a-solution)
- [Step four: Test the solution](https://manmithapatya.github.io/ManmithaPatya-Portfolio/CritiqueByDesign.html#2.4-Step-four:-Test-the-solution)
- [Step five: Build your solution](https://manmithapatya.github.io/ManmithaPatya-Portfolio/CritiqueByDesign.html#2.5-Step-five:-Build-your-solution)
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
Perceptibility is measured based on the ease with the information and the graphic can be assimilated by the viewer. This is measured on a scale from Unclear and difficult to Clear and easy. In this graphic, the presence of a color scheme for various buckets of data on the lower left corner and the presence of a scale on the lower right hand corner makes it difficult to keep up with the main representation. Once has to move back and forth from the legends to the main graphic which reduces Perceptibility. The repeated use of '$' and 'K' is also redundant. 

**Truthfulness**
Truthfulness talks about the accuracy and the validity of the data. It is measured on a scale from Inaccurate and/or invalid to Accurate and valid. The date here is represented on sub-segments of sections of a pie. This means that the areas of each subsection will not be the same. Hence, the representation on the graphic is not accurately related to the amount of wage that is being represented. In addition to this, we can see on the lower right hand corner that each sub-segment represents increments of $10,000. However, the last sub-segment represents the data in an increment of $20,000. This makes me question the accuracy of the representation and the justice it does to the actual data. 

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
## 2.5 Step five: Build your solution
