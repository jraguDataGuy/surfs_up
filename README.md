# Surfs Up - Analysis Temperature by Location to Determine Feasability of New Business Endeavours
## Overivew
Prior to operning a Surf/Ice Cream shop in Oahu, we have been asked by entrepreneur W. Avy to assess temperatures on the island to determine feasability of a year-round shop. Ultimately, our goal is to review the weather in the heat of Summer and Winter to make sure the conditions will help this business 'catch a wave'

## Results of June and December
**June Reults**

![Image of June Results](https://github.com/jraguDataGuy/surfs_up/blob/main/Resources/June%20Temps.png)

**December Results**

![Image of Dec Results](https://github.com/jraguDataGuy/surfs_up/blob/main/Resources/December%20Temps.png)

- As expected, mean temperature is higher in June.
- We have more data points to analyze for June over December, giving as very minimal more confidence in the results
- As expected, the low temperature in December gets to 56. Compared to other climates this is not insufferable, but not ideal for surfing paired with ice cream
- Temperature highs are a very nice 83 and 85 degrees. This is nearly perfect weather for our business

## Summary and Additional Thoughts
Ultimately, it is hard to argue against opening a Surf/Ice Cream shop in Oahu. People all over the world come to Hawaii to enjoy the weather. However, our data is quite broad and could use some more narrowing down to bring some more certainty in our decision making process:
- We do have Precipitation data included in our measurement table. I would feel more comfortable comparing the precipitation levels in the months before making a final decision. Rain would dampen the spirits of surfers.
- We could expand our analysis to get an idea of how December and June compare to all of the data. We would need to run a querie not limiting the data to months to get a snapshop of the typical Oahu weather. 
- To select a specific location, I would want to querie by the station locations to ensure our spots include the best surfing conditions, ie are close to the water.
- Our data does have some items that are not available in our SQLite file. As a non-surfer, I would only make the assumption Oahu is an ideal place to surf. To ensure that, I would want data on what ideal surfing conditions are, and ensure we select a prime spot for our shop.
