# Global Terrorism with Bayesian Inference

In this repo, I will be looking at Global Terrorism data from the Global Terrorism Database. This project was to look at everything from a Bayesian perspective. There were three sections to this project, EDA, Bayesian Inference, and Predicting Bombings/Explosions for 1993. 

### Data
- The Global Terrorism Database includes attacks from 1970 to 2016 with a possible 135 variables about each. This does not include data for the year 1993. If you wish the read more about this data the codebook is [here](http://start.umd.edu/gtd/downloads/Codebook.pdf). Please note if you clone this notebook to unzip the data before running the notebook. 

### Part One
- This first part of this project was doing some EDA to explore the data is relevant to part 2 and 3. This included a couple of graphs made in Tableau to help visualize the data. These visualizations gave me an idea for part 2 and a baseline for part 3. Please be patinate with the Tableau visualizations as they are running through Tableau Public and might have a little delay as you interact with them.
- As of right now the Tbaleau visualizations are not working in the Jupyter notebook. Please view them on my [Tableau Profile](https://public.tableau.com/profile/cbjohnson30#!/).

<div class='tableauPlaceholder' id='viz1524848362560' style='position: relative'><noscript><a href='#'><img alt='Attacks Around the World - 1,980 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Wo&#47;WorldTerror-T_S&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='path' value='views&#47;WorldTerror-T_S&#47;Sheet1?:embed=y&amp;:display_count=y' /> <param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Wo&#47;WorldTerror-T_S&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1524848362560');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>

### Part Two
- The second part of this project was to create a Bayesian Inference on a section of the data of your choosing. I chose to look at armed assaults deaths in the United States and Western Europe. My prior was all armed assaults in North America and Western Europe. 
- My biggest take away from this was Western Europe had a larger range in fatalities in armed assaults. The means for the two regions were very similar while Western Europe's standard deviation was larger by 3.3 fatalities. 

### Part Three
- The third part of this project was to predict the number of bombings and explosions for the year 1993. My approach to this to try and predict the number of bombings and explosions by region then add them together to get a total for the world. I also only use data from 1983 to 2003 to try to get a more accurate picture of what was going on in a time frame that I was trying to predict. 
- Please note my P.S. in the notebook and feel free to reach out with any suggestions or answers. 
