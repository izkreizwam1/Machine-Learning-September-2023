# Machine-Learning-September-2023
Project for Soft uni
you can find all details in "Mental Prediction.ipynb"
<b>The first part of teh project can be found here [https://github.com/izkreizwam1/Data-Science---Project-2023](https://github.com/izkreizwam1/Data-Science---Project-2023) <b>

# Mental health in the Tech industry - Prediction
   ### by Tomislav Vasilev

This project is continuation of my previous project "Mental health in the Tech industry". I want to work on the Dataset i had previously created and expand its scope. <br>
## Abstract

We will have the assumption that the participants in each year were part of different and independent sets of participants and there is no overlapping between them.<br>
The dataset used for the initial training has been pre-processed in my previous Project "Mental health in the Tech industry". From there we know our dataset is relatively balanced and we should treat it as a balanced problem.<br>


In this project we will:<br>
1. Try to create a predictive model that is able to determine if an individual has looked for help based on the environment and conditions of his work (or at least how the individual perceives and picture this environment through the questions asked). We will experiment with a couple of different approaches<br>
1.1. If our model manages to give a proper prediction result. We can focus on the False Positive results, as those might be people who need help but have not yet addressed it.<br>
2. we will create a pipeline<br>
3. we will get new data for the year 2017 and:<br>
    3.1. train our model on 2014/2016 and test it on 2017<br>
    3.2. apply continues training on our model with 2017 and test it on 2017 using Incremental training<br>


we will observe the results and if it is possible to add additional feature from external datasets to improve our model.

