# Matching table

Many of these questions, and more can be generated automatically.  See the table below.

![](assets/images/badyearvssatellite.png)

![](assets/images/genetematchingtable.png)

In the matching table, you can see how much any data source matched another by looking at the rows and columns.  
For example, to see the computer's ratio of number of farmer bad years that were flagged by the combined severity metric, look at the 
look at the combined_severity column, and the is_bad_year row.  Since there were 8 farmer bad years, 
and 4 of them had the red combined_severity bar in them, that is 0.50 of the time.

In insurance, this might reflect the number of droughts a farmer had experienced that had a payout.

But what if we wanted to check the ratio of combined severity years that farmers said were bad, 
you would look at the is_bad_year column and the combined_severity_row.   There were 20 red bars 
representing combined severity years--many of them are really tiny. You need to squint to see the small ones. 
A way to tell is that any year that has a circle has no severity of any type, and combined severity is triggered 
when any of the options are triggered.  Four of these years are in farmer bad years, that is 4/18 or 0.20. 

Those are years that the insurance would have had a payout, and the farmer would have wanted the payout.  
Its very interesting that nearly all of the "missed" payouts, that do not occur in farmer bad years are very small.
That means that it might be possible to set a higher threshold for payouts to eliminate those, 
and have an insurance that is more acccurate.  That is something that commonly (but not universally) happens in index insurance, 
where small payouts are less accurate than big payouts.

Because it is hard to eyeball everything, and we might be working in hundreds or thousands of places, 
its obviously valuable to have the computer calcuate some things for us. 
**The computer cannot make all the decisions for us because some of the decisions are difficult trade offs 
between options that only humans would be able to choose**.  

**Spoiler alert**: Even an expert who does not ping the farmers during the design process could make harmful choices.  

Lets play the role of that expert!

<div id="slide-config" 
     data-type="simple" 
     data-next="../slideyouself/">
</div>


