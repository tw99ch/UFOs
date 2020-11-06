# UFOs
## Overview of Project
The purpose of this project is to build an interactive HTML webpage with JavaScript function which allows user to find the UFOs sightings data based on date, city, state, country or shape.

## Results:
After entering to the webpage of UFO Sightings, there is a brief introduction of the webpage and give the user the option to enter their own search.


![](/images/UFOs_webpage.png)

After scrolling down the page, the user can see 5 different filters, including date, city, state, country and shape. The user can choose to enter any info into the search box then the webpage will automatically generate the updated UFOs sighting data on the left. For example, if user wants to see the UFOs sighting in California, the user has to enter "ca" in the state search box. After entering the search data, the webpage will generate the updated table with only sightings in California. 

![](/images/UFOs_filtered.png)

Multiple filters can be entered if the user wants to look up specific sightings data.


![](/images/UFOs_filtered_multiple.png)


## Summary:
The drawbacks of this design is web user would not know which info they can enter, and they might enter info with no result. On the other hand, web user may enter invalid info for the search because of the format is not recognized by JavaScript. Therefore, I have two recommendations to improve the webpage:
1. We can design a dropdown menu that contains all the info for the search box. It is easier for the user to select the info from the list instead of thinking an entry which might not work.
2. We can design a function to let JavaScript read any format entered by user. For example, when searching for Canada, if we entered upper case "CA", JavaScript will return with no result. Therefore, we can design a function to transform the info entered into a system readable format to bring better user experience for the search.
