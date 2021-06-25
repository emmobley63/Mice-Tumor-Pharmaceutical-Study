# matplotlib-challenge

For this analysis we looked at the results from a study on the effects of different drug regimens and their effects on tumorvolume.

We were given two data sets, one of the mouse metadata and the other of the test results. These two were combined to give us our base dataframe. From which, we analyzed the effects on 248 different mice.

From our initial summary statistics on the mean and median tumor volume, the two with the smallest mean volume were Capomulin (40.68) and Ramicane (40.22). Indicating they may be the most effective at reducitng the size of the tumor. It is to be noted that these two drug regimens also had the largest number of mice tested.
There were slighlty more males (51%) to female (49%) mice in the study.

We then decided to investigate four of the drug regimen's final tumor volumes for outliers- Capomulin, Ramicane, Infubinol, and Ceftamin. Mouse c326 was the only outlier and she was treated with Infubinol. We can see her marked in the box and whisker plot in red.

We then looked at the Capomulin treatment of mouse s185. We see over the time of the treatment the tumor reduced in volume by almost half. The evidence keeps pointing to Capomulin as an effective drug in reducing tumor volume.

From a scatter plot of the average weight and average tumor volume of mice treated with Capomulin, we started to see a correlation. We tested the correlation between average mouse weight and average tumor size in mice treated with capomulin and found it to be 0.84. This is a pretty strong positive correlation and could mean that what we thought was effectiveness in reducing tumor volume was actually a lower average weight of the mice for each drug regimen.

To more effectively assess this data I would suggest checking the average weight of mice in each drug regimen. I would also suggest to assess the change in tumor size from the beginning of treatment to the end as a percentage of the starting volume. I would test the average age against the tumor volume to see if it is more effective in younger or older mice. Assessing the different demographics of the mice tested and each demographic trait's correlation to the change in the tumor size from beginning to end. 

However the dataset is limited to less than 250 mice per drug, so some of these demographics may not have enough data to test.
