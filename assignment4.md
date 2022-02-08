# Assignment 4: Admissions Prices

## Terrible, No Good, Very Bad Graphs

I began this assignment with the following charts:
![Screenshot (329)](https://user-images.githubusercontent.com/98050576/152919641-7d1a3797-830a-4655-9e46-d259e00c84fd.png)
![Screenshot (334)](https://user-images.githubusercontent.com/98050576/152919666-eb693a58-9901-4d6b-84a7-2db7facb6004.png)
![Screenshot (335)](https://user-images.githubusercontent.com/98050576/152919671-09c5d9ce-32ad-424a-8d0b-e043003a08d6.png)
![Screenshot (332)](https://user-images.githubusercontent.com/98050576/152919685-73a382c1-d22d-4427-ab49-a434b8745e85.png)
![Screenshot (333)](https://user-images.githubusercontent.com/98050576/152919700-233792c6-d6a6-4eba-8d91-05e1507224c3.png)

These came from a report that was looking at prices that the average consumer spent on entertainment. This report was found in the National Archive of Data on Arts & Culture.

I chose these particular data sets because I thought they could tell a better story if they were merged together, to really be able to see the trends over time. I thought the usefulness was a six because it requires the researcher to click through all the different tables to be able to really see anything, as well as having a completely different type of data for the fifth graph.

I gave it a 7 for completeness because "per family unit" on one of the graphs needed to be explained in the following text, and the percentiles were confusing until I read about them.

Perceptability was a 4, because I'm not sure why the five years were broken up, and why the two sections were being compared at all. I had to study the data for a few days to figure out tha the two sections that were being compared was live events and events that could be done at someone'e leisure. 

Truthfulness I gave a 9. This is because of the context of the graphs and that it was pure data. The creators of the report wasn't really trying to sway anyone with the graphs, just trying to showcase some data in a visual way. I did not give it a 10 for the simple reason that the bars are not proportional.

I gave a 5 for intuitiveness, because of the same reasons for perceptability. There were labels and elements in the graph that had to be looked up and needed context for. I found myself thinking "why?" a lot when looking at these graphs. 

Aesthetically, it wasn't great. I gave all of them together an average of 4, mostly for lack of consistency. For these being in a singular report, the color schemes change from year to year, the labels change (some have dollar signs above the bars while others don't), and then the fifth one is comparaing something completely different than the rest of them. In addition, they all had some sort of graphic behind them, and it took away focus overall. 

Enagagement I gave a 2 mostly because the only reason I wanted to learn more was so I could actually understand what the graph was telling me.

## Some Redesigns to Save the Day

My first initial thought on a redesign was a type of line chart, that ended up looking like this. 
![20220206_162440](https://user-images.githubusercontent.com/98050576/152923391-8f6e79dd-c250-43a9-a2c2-3d63094fc950.jpg)

I wasn't in love with this design. It didn't exactly do the things I had hoped it would, and it felt it feel flat in a lot ways. Since I was unsure where to go from here (I had had my mind set on a line graph from the beginning) I went and checked out [The Data Viz Project](/https://datavizproject.com/) to find some kind of inspiration. 

That's when I saw this kind of chart.

![Screenshot (336)](https://user-images.githubusercontent.com/98050576/152923868-4ec63c75-0d90-41c7-a9ab-4d38c0162fb8.png)
It reminded me a lot of the box and whisker plots we learn about in alegebra, and I thought I would give it a try with this dataset, since it does show a range of prices per year.
Here is the first sketch I made with this new design in mind. 

![20220206_162449](https://user-images.githubusercontent.com/98050576/152923999-248ce8da-fb69-4039-a07a-4fc59bc24c5c.jpg)

I definitely liked this one a lot better, but I went ahead and included both when I interviewed the next set of people.

# The Interviews

Interview One: mid-twenties, non-binary, museum operations manager

Image One
- First glance was a little confusing, but after reading the labels was able to figure out the graph.
- Had to reference the legend a few times to understand which line was which
- Asked: Why is the data separated that way? (meaning the two different lines)
- Asked: What is the definition of a “family unit”
- Liked the title 

Image Two
- Loved this type of graph
- Suggested finding a more concise title
- Liked the range that the graph shows, “makes it easier to see where the lowest and highest points are and how they actually compare to the average”
- Loved that the “family unit” is defined and likes the “pop-up” that will be eventually added in Flourish
- Wouldn’t change anything besides the title


Interview Two: late twenties, male, Broadway producer

Image One
- A lot to take in at first
- Really need to study all the labels before being able to understand the graph
- Repeating areas in title and in x-axis
	- Can add in “per family” in title
	- Add $ to the x-axis
	- Change “family unit” to “household”
- Not sure if it’s the best way to show it
	- Possibly stacked bar chart? 

Image Two
- People need to know how to read a box chart first
- Looks like its for researchers
- Can read this one really well
- Text can still be cleaned up more
- Can just put $ sign in x-axis
- Potentially change the color scheme


Interview Three: mid-twenties, gender fluid, film director

Image One
- Can comprehend the graph
- Y-axis has too information
- What is the family unit description?
- Never seen this type of graph
- Audience is people who make prices for arts events

Image Two
- This graph looks better than the last one
- Surprised by the data, not by the presentation of it
- Really clear
- Would like to see the actual range

After hearing from these three people, I took their feedback into consideration and came up with this sketch.

![20220208_002146](https://user-images.githubusercontent.com/98050576/152924484-14f015ae-34d4-45b8-9c20-bf2b6e282cc7.jpg)

# Let's Get Digital

This was actually the most difficult and frustrating portion of the entire project for me. Even though I could articulate what I wanted on paper, I was limited to my knowledge and the capabilities of Flourish and Tableau. I spent some time trying to figure it out myself, and even asked our TA Anna to hold office hours before class to help me out. When she also came up short on how to get more than one data set per year, I decided to change courses again. 
The closest I came to getting what I had originally envisioned was in Tableau. This was that outcome:
<div class='tableauPlaceholder' id='viz1644298968451' style='position: relative'><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Assignment4_Graph&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1644298968451');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';
  vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

However, it still wasn't quite right. This orientation was difficult to make comparisions with, and that took out a major piece of why I wanted to highlight both data sets. 

Unfortunately, I decided to go with a much simpler option, with a different narrative. This graph was made in Flourish, and has only one data set. However, it utilizes the pop-up boxes to show the data points, the graph is a box plot to show the range per year, and it accomlished the goal of putting the years all together. 

<div class="flourish-embed flourish-scatter" data-src="visualisation/8626972"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

This vizualization also made the idea clear on what the graph was about, and the labels are easy to understand. The color palette is consistent and clean, with high contrast. 

[Back to Main Page](/portfolio.md)
