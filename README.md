# Mice Tumor Pharmaceutical Study
<div>
    <h2>Intro</h2>
    <p>For this analysis I looked at the results from a study on the effects of different drug regimens and their effects on
    tumor volume.</p>
    </p>
    <h3 align="center">Data</h3>
    <p>I had two data sets, one of the mouse metadata and the other of the test results. These two were combined and cleaned
    to give us the base dataframe. From which, I analyzed the effects on 248 different mice.</p>
    <p align="center">
        <img class="img-mar" width="628" alt="Combined Dataframe"
        src="https://user-images.githubusercontent.com/64094170/123457048-86a7be80-d5b1-11eb-9cf9-a34b0e6b2076.PNG">
    </p>
    <p>
    It is to be noted that these two drug regimens also had the largest number of mice tested.
    There were slighlty more males (51%) to female (49%) mice in the study.
    </p>
</div>
<div>
    <p align="center">
        <img width="377" alt="Male and Female distribution"
        src="https://user-images.githubusercontent.com/64094170/123458932-9cb67e80-d5b3-11eb-94d8-4d140056dc66.PNG">
    </p>
</div>
<div>
    <h2>Findings and Visualizations(matplotlib)</h2>
    <h3 align="center">Summary Statistics</h3>
    <p>
        From my initial summary statistics on the mean and median tumor volume, the two with the smallest mean volume were
        Capomulin (40.68) and Ramicane (40.22). Indicating they may be the most effective at reducitng the size of the
        tumor. It is to be noted that these two drug regimens also had the largest number of mice tested.
    </p>
    <img width="589" alt="summary statistics"
        src="https://user-images.githubusercontent.com/64094170/123459076-cec7e080-d5b3-11eb-9f2e-1c97025f7af9.PNG">
    <hr>
</div>
<div>
    <h3 align="center">Outliers</h3>
     <p>
        We then decided to investigate four of the drug regimen's final tumor volumes for outliers- Capomulin, Ramicane,
        Infubinol, and Ceftamin. Mouse c326 was the only outlier and she was treated with Infubinol. We can see her marked
        in the box and whisker plot in red.
    </p>
    <img width="500" alt="boxplots"
        src="https://user-images.githubusercontent.com/64094170/123467312-5d415f80-d5be-11eb-851a-33569ba6939a.PNG">
    <hr>
</div>
<div>
    <h3 align="center">Mouse s185</h3>
    <p>
        We then looked at the Capomulin treatment of mouse s185. We see over the time of the treatment the tumor reduced in
        volume by almost half. The evidence keeps pointing to Capomulin as an effective drug in reducing tumor volume.
    </p>
    <img width="550" alt="line and scatter"
        src="https://user-images.githubusercontent.com/64094170/123467588-a98c9f80-d5be-11eb-9c88-0f71e963b77d.PNG">
    <hr>
</div>
<div>
    <h3 align="center">Correlation and Further Testing</h3>
    <p>
        From a scatter plot of the average weight and average tumor volume of mice treated with Capomulin, we started to see
        a correlation. We tested the correlation between average mouse weight and average tumor size in mice treated with
        capomulin and found it to be 0.84. This is a pretty strong positive correlation and could mean that what we thought
        was effectiveness in reducing tumor volume was actually a lower average weight of the mice for each drug
        regimen
    </p>
    <p>
        To more effectively assess this data I would suggest checking the average weight of mice in each drug regimen. I
        would also suggest to assess the change in tumor size from the beginning of treatment to the end as a percentage of
        the starting volume. I would test the average age against the tumor volume to see if it is more effective in younger
        or older mice. Assessing the different demographics of the mice tested and each demographic trait's correlation to
        the change in the tumor size from beginning to end. However the dataset is limited to less than 250 mice per drug,
        so some of these demographics may not have enough data to test.
    </p>
    <img width="550" alt="correlation and regression"
        src="https://user-images.githubusercontent.com/64094170/123469666-56681c00-d5c1-11eb-93e7-5b23262965f0.PNG">
</div>
