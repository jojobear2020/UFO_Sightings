# UFO_Sightings

To access actual site, please click on the link below:

https://jojobear2020.github.io/UFO_Sightings/



## Project Overview ##

The purpose of the project was to demonstrate the use of JavaScript to create an interactive website that would allow to 
filter page/given dataset based on the user entry. The dataset we used is a sample set of UFO sightings in the U.S. for the first two weeks of January 2010.


## Results ##

Initially we created a dynamic table that was working as intended; however, there was only one option to sort the data – by the date. To provide a more in-depth analysis of UFO sightings we updated filter search to allow users to filter for multiple criteria at the same time. 

* In addition to the date we added table filters for the city, state, country, and shape. 


  ![filter_search_options](https://github.com/jojobear2020/UFO_Sightings/blob/main/static/images/filter_search_options.PNG)


* As a hint how to enter information, we provided placeholders in each category.

`input type="text" placeholder="roswell" id="city" class="form-control"`


* Once search request is entered in at least one field, we just need to click `enter`and search results by that criteria will show up.

  ![search_by_state_or](https://github.com/jojobear2020/UFO_Sightings/blob/main/static/images/filter_search_state_or.PNG)


## Summary ##
Searching the data using interactive website is way more fun and definitely more eye-pleasing in that sense that just shifting through a regular database.  At the same time, it has its drawbacks. One of the main ones is inability to save results and actual absence on the Search button.


## Recommendations ##

1.	Add option to download search results to xlsx, scv or pdf file. 
2.	Add back "Search" button as making users press the `enter` button may be a bit confusing to some. Having actual Search button makes website easier to use.
3.  Add "Reset" button in addition to "Search".
3.	Add some visual or audio effects. I added audio control panel to add some fun aspect, but having videos or audio sounds when we press a button, would be a nice touch.
4.	Having more data than just two weeks (maybe a year?).
