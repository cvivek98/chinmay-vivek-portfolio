| [home page](https://cvivek98.github.io/chinmay-vivek-portfolio/) | [visualizing debt](visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Step one: choose a data visualization from MakeoverMonday
I picked the following image from MakeOverMonday repository. I picked this chart because the content in the chart is of personal interest to me and several people I know. Most students are on a tight budget and cannot spend exorbitant amounts on high protein foods. It was also interesting because most of the food items they showed on the chart are food items that I consume on a regular basis. Hence, I was able to relate better to the content of the chart and also learn how much the cost varies between them so I can make more pocket friendly decisions. Also, as soon as I saw the shorter bars having larger colorie values and the logos not clear, I knew there are ways to make this visualization more impactful. 

Source: https://lifehacker.com/the-cheapest-ways-to-get-your-protein-right-now-1850001760
        https://www.thebodybuildingdietitians.com/blog/how-cost-effective-is-your-high-protein-diet
   
![image](https://github.com/cvivek98/chinmay-vivek-portfolio/assets/143840786/b4d14238-a121-4ad4-b1ac-851e785dc4e2)


# Step two: critique the data visualization

What visualization are you ranking?  Provide the title and web-accessible URL.
https://www.thebodybuildingdietitians.com/blog/how-cost-effective-is-your-high-protein-diet
_The Cheapest Ways to Get Your Protein_


**Usefulness**.  Is it useful for the intended audience?  Does it communicate valuable information? 1-10
8
It is pretty useful for the intended audience which could be fitness enthusiasts, nutritionists, dieticians etc. It is common knowledge that healthy food is not budget friendly and the chart helps understand which sources of protein are more pocket friendly compared to others. The visualization does a good job in conveying this useful information but there are pieces of information on the chart which are harder to comprehend and add to clutter, hence I did not rate it any higher than a 8/10.

**Completeness**.  Does the visualization have everything necessary to make it understandable? 1-10
9
The visualization has everything the viewer needs to understand the chart. For instance, the title gives enough context to understand what the viz is about and the axis titles help understand the variables. It is a fairly straightforward bar chart and does not have much cognitive overload for the viewers. 

**Perceptibility**.  Can the reader understand the information with minimal effort? Is the visualization type appropriate?  Does it use illogical comparisons? 1-10
6
It is very easy to understand the bar chart and the associated cost information it tries to display. However, the calorie data label added to the bars make it difficult to read because taller bars have smaller calorie count compared to other shorter bars. There could have been a better way to visualize the calorie information making it easier to perceive. 

**Truthfulness**.  Is the visualization accurate, reliable and valid?  Is it representing what it says it is, and in the most complete and truthful manner? Does it misrepresent the data or make comparisons that aren't correct? 1-10
7
The visualization definitely represents what it intends to do, which is showing which source of protein costs the least per 30 grams of protein. It doesn’t misinterpret the data but it doesn’t showcase the whole picture. For example, even though Whey Protein is the second cheapest protein choice as it costs less, its cost per package is extremely high so the user is paying a higher price upfront.

**Intuitiveness**. Is it easy to understand and clearly communicate the information?  If unfamiliar, does it include easy to understand instructions on how to interpret it? 1-10
7
The bar chart is easy to understand with the price value as the height of the bars. However, when we look at the calorie information, it gets confusing because some taller bars have lower calorie count than other shorter bars. This makes the bar less intuitive.

**Aesthetics**.  Is it interesting / enjoyable to look at?  Is it a good example of what a beautiful data visualization might look like?  Is it somewhere in the middle - pleasing but otherwise not distracting to look at? 1-10
7
The bar chart in itself is interesting to look at. However, some of the aesthetic elements that the designer added failed to come through to the viewer. For example, the icons added on top of the bars are supposed to add aesthetic value and context but they are difficult to read and forces the viewer to squint / zoom in. 

**Engagement**.  Does it lead the audience to learn more about the topic?  Does it inspire the audience to talk about the data or share it with others? 1-10
8
The chart gives some information about the cost and protein intake which would be of interest to the primary audience of this visualization. However, it does not give a complete picture of the food intake because there are several other variables like fat, sugar, carbohydrate intake in these food items that can affect the food choices. I do agree that just looking at the cheapest protein options was new information to me and made me want to talk about it to my friends who would find this information useful.   

**Describe your overall observations about the data visualization here.  What stood out to you?  What did you find worked really well?  What didn't?  What, if anything, would you do differently?**
The simplicity of a bar chart clearly telling me which are the cheaper options and which are the more expensive ones worked really well. It took me almost no time to understand the context of the chart and get to this conclusion. I felt like adding the pictures on top of each bar was a good idea but did not quite work well because most of those images were hard to read. I would try to incorporate the calorie info better into the viz and also include other information like cost per package of each item because essentially that is the price the user pays upfront. Also, with respect to the color choice of the bars, since the value we are measuring is the cost (in $), I would rather use a green color because that usually resonates with money better than blue. 

**Who is the primary audience for this tool?  Do you think this visualization is effective for reaching that audience?  Why or why not?**
Nutritionists, Dieticians and fitness enthusiasts are some prospective viewers for this visualization. The visualization is effective for this audience because it is a very simple visualization and the audience is fairly educated to grasp the key elements of this visualization. However, this audience would like to have some other additional information like total package price, calorie count and other information like fat, sugar content etc before making the conclusion that a certain food item is the cheapest source of protein and recommending it.

**Final thoughts: how successful what this method at evaluating the data visualization you selected? Are there measures you feel are missing or not being captured here?  What would you change?  Provide 1-2 recommendations (color, type of visualization, layout, etc.)**
I feel like this method is definitely very comprehensive in its approach to cover all aspects of the visualization. I had to spend a lot of time trying to dig into the details of the graph and think about finer things which I might have skipped over without the structure that this method provides. However, I felt like there was some overlap between the different metrics it tried to capture like Perceptibility and Intuitiveness. I found that much of the points around these metrics were the same and having two separate metrics did not provide any additional value. I would have liked if the method also captured details on color and chart type choices. This is because I often spend a good chunk of my designing time trying to figure out the best choices for these and they lay the foundation of the visualization. 


# Step three: sketch out a solution

Following up on the critique, I made the necessary changes in my redesign directly in Tableau. Firstly, I changed the title to give the viewers the key insight directly instead of having them fish for it. Also, I changed the color of the bars to green in order to resonate more with the values which are in USD. I also changed the order of the sort to go ascending instead of descending so that the cheapest options show up first on the left. Usually, viewers read from left to right so this would draw their attention to the cheapest options first which is where our highlight is. Even the title complements the same and makes it simpler of the viewer to reach the key insight faster. Additionally, I introduced a new variable which is 'price per package' so that the viewers know that eventhough some of these food items sound more economical when we look at 'cost per 20g of protein', it is not quite the case because they would have to buy in intervals of package units which can increase upfront costs. I felt that either of these variables alone do not do justice to the entire picture and both of them in conjunction provide a more holistic picture. 

Note: When I started looking into the raw data to figure out ways to improve the visualisation, I realized that the raw data they provided is not exactly the same they used for the chart. There were a few differences which made it harder to replicate it exactly. 
Some of the differences were:
- The cost was given per 20 grams of protein instead of per 30 grams
- Some of the food items were similar but not exactly the same e.g. Firm Tofu vs Extra Firm Tofu (the numbers will vary a bit)
- The calorie information was not provided in the raw data but since this was something I was meaning to address in my critique, I fetched the calorie information from external sources 
(United States Department of Agriculture (USDA) National Nutrient Database for Standard Reference: https://fdc.nal.usda.gov/
Self Nutrition Data: https://www.self.com/)
I also had to clean up some of the cost data as some entries were in cents while others in Dollars. I cleaned this up directly in Excel before refreshing the Data Source in Tableau.

<img width="1128" alt="image" src="https://github.com/cvivek98/chinmay-vivek-portfolio/assets/143840786/d2b08202-78d3-436f-b5ff-5ca4581a441c">


# Step four: Test the solution

I tested my redesign to 3 students, trying to keep the respondent group as diverse as possible, and these were there thoughts:

**Student 1 (Male, Late 20s):**
•⁠  ⁠**Can you tell me what you think this is?**
Comparing products prices which give the same protein content.

•⁠  ⁠**Can you describe to me what this is telling you?**
How can I opt for an efficient priced product meeting my daily requirement of protein.

•⁠  ⁠**Is there anything you find surprising or confusing?**
The first chart is easy to comprehend. I believe you must tweak chart's title since you are mentioning calories as well. If not it is an extra information in the chart, which is completely fine.

•⁠  ⁠**Who do you think is the intended audience for this?**
For health enthusiasts who might be on restricted budget like students. I believe this will help me make a better choice to get the proteins without hurting my pocket.

•⁠  ⁠**Is there anything you would change or do differently?**
The second graph is difficult to comprehend. I can't figure out the labels at the top of the bars and also what the orange circle represents. Could be because I am tired.

**Student 2 (Male, Late 30s):**

•⁠ **Initial thoughts:**
Overall, the viz looks really good! I really like the design.

•⁠ **What worked?**
I like the viz (chart type selections) and the color selection. 

•⁠ **What can be improved?**
Include the legend for the orange dots.
There are groups / categories that I can see. For e.g. dairy products, non vegetarian meat etc. I would like to see them grouped together in some way. It doesn't have to change the sort order but I maybe every category gets a color of its own? Some way to categorise it would be great.


**Student 3 (Female, Mid 20s):**

•⁠ **What worked?**
I liked the clear bar graph widths. The professor mentioned how sometimes they are too narrow or wide. These look perfect.
I like the idea of including costs per package as it gives more context for a buyer.
It is also very clear to see which items cost more overall / package wise. 

•⁠ **What didn't work?**
The title is long. Maybe add a note to move some of the things out of the title?

•⁠ **What questions came up?**
I understand that the package costs are included now for a reason but is it really a fair comparison? Because every food item has different quantities based on packaging like milk is in gallons but cheese is number of slices etc. So I am not sure if it is the most accurate representation.

In conclusion, these were some of the key feedback points I received:
- The title is better now but slightly longer
- The viz type and color selection works well
- Need to add legend for the orange dots (price per package)
- Need to explore ways to group some of the food items together (like dairy, meat etc.)
- If possible, find a better way to compare as package quantity would be different for each item


# Step five: Build your solution

For the final version of the solution, I made the follwoing changes:
- Reduced the word count of the title such that it conveys the same information in a more ocncise manner
- Added a legend for the dots that represent package value (I had to add the image and corresponding text as floating items on the dashboard)
- Added 'Vegan' and 'Vegetarian' filters to the dashboard for the user to drill deeper as needed
- Grouped the Dairy, Meat etc items together and color coded them (I had to group these items together by creating a calculated field that buckets these items together and I added the calculated field to the colors mark)
- Removed the tick marks from all axes to reduce cluttering
- Change font color for all labels and titles to make it easier to read
- I decided to remove the calorie information from the chart as it felt like forcing additional information into the view. Instead, I added it to the tooltip so it is stored as additional informaiton if the user want to view it

<div class='tableauPlaceholder' id='viz1707265693304' style='position: relative'><noscript><a href='#'><img alt='Protein Sources Cost &lt;$10 per package but Milk and Chicken Breast Give the Highest Value ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;TS&#47;TSWD34&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='TSWD34&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;TS&#47;TSWD34&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                <script type='text/javascript'>                    
        var divElement = document.getElementById('viz1707265693304');                    
        var vizElement = divElement.getElementsByTagName('object')[0];                    
        vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
        var scriptElement = document.createElement('script');                    
        scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>
