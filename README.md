# Visualization of Probability of Losses of Prosper Lending

## Summary

Key message of the visualization are that 
 - the Prosper Rating is proven as a better risk indicator for losses compared to the Prosper Score for lending at Prosper and 
 - Loans rated A or AA provide a good risk mitigation. 

I tried to used Dimple for an understandable and interactive display of the dataset. Please have a look to investigate the data yourself and let me know if the message comes across.

## Design 

After several cleaning steps the dataset contains 27.627 closed loans with either occurred losses or without. The share of losses is printed on the y-scale using Dimple. There are many data points the chart and rates change especially for the Prosper Score. This is why there are many overlaps and finding the right display was a challenge. Receiving Feedback was helpful at this stage. 

Design steps 
 - The initial line chart delivered not the expected clarity and feedback was accordingly (not understandable, what a mess…). 
 - As a first iteration a step iteration was used to limit the overlap of lines. The result looked good (Feedback: like artwork) but the message was lost in the nice graph as the lines were difficult to recognize, especially between the data points. 
 - The second iteration used a cardinal iteration with is smoothed compared to the initial line chart but it showed some inconsistencies but not the data points. 
 - Data points were added as 3rd iteration using an additional bubble chart and used the monotone iteration instead of the cardinal iteration which avoided inconsistencies and still provides some smoothing. The feedback for this final version was very good. 

## Feedback 

See enclosed file https://github.com/dico11/prosper/blob/master/feedback_visualization.pdf

## Resources 

Documentation of Dimple at
 - http://dimplejs.org/
 
Course contant and included link to
 - http://christopheviau.com/d3_tutorial/
 
Data visualization block resources such as 
 - http://bl.ocks.org/jonahwilliams/2f16643b999ada7b1909
 - http://bl.ocks.org/hpaas001/raw/8dcfabc85486a643bea8ead69e5a26e3/



