## A Narrative visualization project for DV416 

Visit: https://github.com/chiku21/dv416final.git

### ABOUT THE VISUALIZATION
This narrative visualization uses the Interactive Slideshow approach to take you through a visual journey of the housing market from Jan 2010 to July 2021 in the Greater Seattle Metro area.


### The Dataset
The Median Home Sale Price and Inventory datasets were acquired from Zillow, July 2021. The raw data was originally curated using Microsoft Excel application to narrow the datasets with data pertaining to a specific region from Jan 2010 to July 2021.

### Scenes
A consistent and cohesive template was built using CSS layout and FullPage.js to set up the scenes for this visual story. Scene transition follows an intuitive approach of sliding up and down via mouse wheel, touch or key-up/down. Slide navigator, along with tool-tip located at the right side of each slide provides a good navigation visual cue. It also acts as a trigger allowing readers to jump to a specific slide. 

### Annotations
Annotations were used to show the high and low points of median home price and inventory on the respective home price and inventory charts. These     call-outs were to effectively paint a concise picture of the market landscape for the last decade in the Seattle Metro area. 

### Tooltips & Visual Aids
Readers can hover over the line on the line charts to bring up the data-label tooltip to inspect the home price and inventory for a specific timeframe.
Axes of all line charts were clearly labeled.  Each data point in the bubble chart were clearly labeled with tooltip showing the current median home price for the specific city upon hovering over the bubble.
 
### Parameters
City location served as the main parameter for the Current Median Home Price bubble chart to allow readers inpect the current median home price based  the directionality of cities with respect to Seattle Proper.The Seattle metro area includes 3 most populous counties covering cities in the Seattle-Bellevue-Everett and Tacoma divisions. These cities are located to the East, North and South of Seattle. Readers are able to use the City Location selector to highlight the cities in the bubble chart to furture inspect their respective median home price. Both set of line charts also provide two respective parameters: home price vs YoY and Inventory vs YoY to allow readers to switch the relevant charts. 

### Triggers
As noted above, buttons were used on both set of line charts to trigger the display  of a proper chart (home price vs YoY and Inventory vs YoY).  The City Locator selector serves as the mechanism to trigger the highlights of cities based on the selected direction. Data tooltips appear upon mouse over event on all the charts.
The slide navigator also serves as the trigger allowing readers to jump to a specific slide.

Note: For the YoY Inventory file, as the values are present until July 1st 2021, it has been extrapolated to reflect till the year end. 

References:
## https://www.zillow.com/research/data/
## https://unsplash.com/s/photos/seattle
## https://www.w3schools.com/
## https://d3js.org/
